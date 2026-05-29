---
layout: contentpage
title: Fentanyl
category: items
subcategory: consumables
permalink: /items/consumables/fentanyl
image: /images/svg/anybodypart.svg
inline_image: /images/base_neurotrauma/items/consumables/fentanyl.png

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
          - Niche

  - title: Statistics
    sections:
      - items:
          - "Skill Required: {{MEDICAL}} 72"
          - "Maximum inventory stack: 8"

  - title: Crafting
    sections:
      - header: "Medical Fabricator Requirements (Output: 1x)"
        items:
            - "{{MEDICAL}} 50"
            - "{{OPIUM}} (1x)"
            - "{{ADRENALINE}} (1x)"
            - "{{ETHANOL}} (1x)"

      - header: "Deconstructor Yield"
        items:
            - "{{OPIUM}} (1x)"
            - "{{ADRENALINE}} (1x)"

  - title: Store
    sections:
      - items:
          - "Base Price: 190 Marks"
          - "Buyable at Merchant: Medical"

blocks:
  - type: description
    header: "Description:"
    addon: vanilla
    order: 1
    text: |
     A powerful opiate used to induce {{ANALGESIA}}.

     To prevent exploits, fentanyl *cannot* be shot as a projectile, such as out of a Syringe Gun.

  - type: application_success
    header: "Application Success:"
    addon: vanilla
    order: 2
    text: |
     - \+75% {{ANALGESIA}}
     - \+15% {{OPIATE_ADDICTION}}
     - \+22.5% {{OPIATE_OVERDOSE}}
     - \-100%{{OPIATE_WITHDRAWAL}}

     <br>
     #### While >30% drunk changes to:
     - \+150% {{ANALGESIA}}
     - \+15% {{OPIATE_ADDICTION}}
     - \+37.5% {{OPIATE_OVERDOSE}}
     - \-100% {{OPIATE_WITHDRAWAL}}

  - type: application_failure
    header: "Application Failure:"
    addon: vanilla
    order: 3
    text: |
     - \+50% {{ANALGESIA}}
     - \+40% {{OPIATE_ADDICTION}}
     - \+30% {{OPIATE_OVERDOSE}}
     - \-100% {{OPIATE_WITHDRAWAL}}

     <br>
     #### While >30% drunk changes to:
     - \+100% {{ANALGESIA}}
     - \+40% {{OPIATE_ADDICTION}}
     - \+60% {{OPIATE_OVERDOSE}}
     - \-100% {{OPIATE_WITHDRAWAL}}

# ------------------------------------------ NT PHARMACY INGREDIENT -------------------------------------------

  - type: description
    header: "Description:"
    addon: pharmacy
    order: 1
    text: |
      #### - Type: "Active Ingredient"
      #### - Skill Required: {{MEDICAL}} 45
      <br>
      An active pill ingredient made from {{FENTANYL}}; has positive effects.

  - type: effects
    header: "Crafting Success:"
    addon: pharmacy
    order: 2
    text: |
      - +37.5% {{ANALGESIA}}
      - +7.5% {{OPIATE_ADDICTION}}
      - +11.25% {{OPIATE_OVERDOSE}}
      - -50% {{WITHDRAWAL}}

  - type: effects
    header: "Crafting Failure:"
    addon: pharmacy
    order: 3
    text: |
      - +25% {{ANALGESIA}}
      - +20% {{OPIATE_ADDICTION}}
      - +15% {{OPIATE_OVERDOSE}}
      - -50% {{WITHDRAWAL}}
---