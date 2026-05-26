---
layout: contentpage
title: Mannitol
category: items
subcategory: consumables
permalink: /items/consumables/mannitol
image: /images/svg/anybodypart.svg
inline_image: //images/base_neurotrauma/items/consumables/mannitol.png

addons:
  - id: vanilla
    label: Base Neurotrauma

  - id: pharmacy
    label: NT Pharmacy Ingredient


infobox:
  - title: Labels
    sections:
      - items:
          - Item
          - Important

  - title: Statistics
    sections:
      - items:
          - "Skill Required: {{MEDICAL}} 60"
          - "Maximum inventory stack: 8"

  - title: Crafting
    sections:
      - header: "Medical Fabricator Requirements (Output: 1x)"
        items:
            - "{{MEDICAL}} 80"
            - "{{ADRENALINE}} (1x)"
            - "{{ETHANOL}} (1x)"
            - "{{LIQUID_OXYGENITE}} (1x)"
            - "{{STABILOZINE}} (1x)"

      - header: "Deconstructor Yield"
        items:
            - "{{ADRENALINE}} (1x)"
            - "{{LIQUID_OXYGENITE}} (1x)"

  - title: Store
    sections:
      - items:
          - "Base Price: 300 marks"
          - "Buyable at Merchant: Medical"

blocks:
  - type: description
    header: "Description:"
    addon: vanilla
    order: 1
    text: |
     Mannitol is a medication used to treat {{NEUROTRAUMA}} and halve its gain. In return, it causes various organ damage. For Mannitol to treat {{NEUROTRAUMA}}, Blood Pressure must be greater than 70% and {{HYPOXEMIA}} must be less than 30%

  - type: application_success
    header: "Application Success:"
    addon: vanilla
    order: 2
    text: |

     - \+50% Mannitol (treats up to 100% {{NEUROTRAUMA}})
     - \+5% {{VANILLA_ORGAN_DAMAGE}}
     - \+10% {{HEART_DAMAGE}}
     - \+10% {{KIDNEY_DAMAGE}}

  - type: application_failure
    header: "Application Failure:"
    addon: vanilla
    order: 3
    text: |

     - \+30% Mannitol (treats up to 60% {{NEUROTRAUMA}})
     - \+10% {{VANILLA_ORGAN_DAMAGE}}
     - \+20% {{HEART_DAMAGE}}
     - \+20% {{KIDNEY_DAMAGE}}

     Effects occur over 10 seconds.

# ------------------------------------------ NT PHARMACY INGREDIENT -------------------------------------------

  - type: description
    header: "Description:"
    addon: pharmacy
    order: 1
    text: |
      #### - Type: "Binder"
      #### - Skill Required: {{MEDICAL}} 60
      <br>
      In pill form, Mannitol does not cause organ damage like it does for the base item.

  - type: effects
    header: "Crafting Success:"
    addon: pharmacy
    order: 2
    text: |
      - Multiplies output yield by 2x
      - Adds 10% Mannitol affliction (1/5th a normal Mannitol) to all created pills


  - type: effects
    header: "Crafting Failure:"
    addon: pharmacy
    order: 3
    text: |
      - Multiplies output yield by 2x
      - Adds 5% Mannitol affliction (1/10th a normal Mannitol) to all created pills
---