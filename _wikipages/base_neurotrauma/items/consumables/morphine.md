---
layout: contentpage
title: Morphine
category: items
subcategory: consumables
permalink: /items/consumables/morphine
image: /images/svg/anybodypart.svg
inline_image: /images/base_neurotrauma/items/consumables/morphine.png

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
          - "Skill Required: {{MEDICAL}} 50"
          - "Maximum inventory stack: 8"

  - title: Crafting
    sections:
      - header: "Medical Fabricator Requirements (Output: 1x)"
        items:
            - "{{MEDICAL}} 18"
            - "{{OPIUM}} (2x)"

      - header: "Deconstructor Yield"
        items:
            - "{{OPIUM}} (1x)"

  - title: Store
    sections:
      - items:
          - "Base Price: 100 Marks"
          - "Buyable at Outposts: All"
          - "Buyable at Merchant: Medical"

blocks:
  - type: description
    header: "Description:"
    addon: vanilla
    order: 1
    text: |
     A moderately powerful opiate used to induce {{ANALGESIA}}.

     To prevent exploits, morphine *cannot* be shot as a projectile, such as out of a Syringe Gun.

  - type: application_success
    header: "Application Success:"
    addon: vanilla
    order: 2
    text: |
     - \+50% {{ANALGESIA}}
     - \+10% {{OPIATE_ADDICTION}}
     - \+10% {{OPIATE_OVERDOSE}}
     - \-30% {{OPIATE_WITHDRAWAL}}

     <br>
     #### While >30% drunk changes to:
     - \+100% {{ANALGESIA}}
     - \+10% {{OPIATE_ADDICTION}}
     - \+20% {{OPIATE_OVERDOSE}}
     - \-30% {{OPIATE_WITHDRAWAL}}

  - type: application_failure
    header: "Application Failure:"
    addon: vanilla
    order: 3
    text: |
     - \+30% {{ANALGESIA}}
     - \+25% {{OPIATE_ADDICTION}}
     - \+20% {{OPIATE_OVERDOSE}}
     - \-30% {{OPIATE_WITHDRAWAL}}

     <br>
     #### While >30% drunk changes to:
     - \+60% {{ANALGESIA}}
     - \+25% {{OPIATE_ADDICTION}}
     - \+40% {{OPIATE_OVERDOSE}}
     - \-30% {{OPIATE_WITHDRAWAL}}

# ------------------------------------------ NT PHARMACY INGREDIENT -------------------------------------------

  - type: description
    header: "Description:"
    addon: pharmacy
    order: 1
    text: |
      #### - Type: "Active Ingredient"
      #### - Skill Required: {{MEDICAL}} 30
      <br>
      An active pill ingredient made from {{MORPHINE}}; has positive effects.

  - type: effects
    header: "Crafting Success:"
    addon: pharmacy
    order: 2
    text: |
      - +25% {{ANALGESIA}}
      - +5% {{OPIATE_ADDICTION}}
      - +5% {{OPIATE_OVERDOSE}}
      - -15% {{WITHDRAWAL}}

  - type: effects
    header: "Crafting Failure:"
    addon: pharmacy
    order: 3
    text: |
      - +12.5% {{ANALGESIA}}
      - +12.5% {{OPIATE_ADDICTION}}
      - +10% {{OPIATE_OVERDOSE}}
      - -15% {{WITHDRAWAL}}
---