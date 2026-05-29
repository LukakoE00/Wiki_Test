---
layout: contentpage
title: Saline
category: items
subcategory: consumables
permalink: /items/consumables/saline
image: /images/svg/anybodypart.svg
inline_image: /images/base_neurotrauma/items/consumables/saline.png

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
          - First Aid
          - Important

  - title: Statistics
    sections:
      - items:
          - "Skill Required: {{MEDICAL}} 10"
          - "Maximum inventory stack: 8"

  - title: Crafting
    sections:
      - header: "Medical Fabricator Requirements (Output: 2x)"
        items:
            - "{{MEDICAL}} 5"
            - "{{SODIUM}} (1x)"
            - "{{CHLORINE}} (2x)"

      - header: "Deconstructor Yield"
        items:
            - "Has no deconstructor outputs."

  - title: Store
    sections:
      - items:
          - "Base Price: 50 Marks"
          - "Buyable at Outposts: All"
          - "Buyable at Merchant: Medical"

blocks:
  - type: description
    header: "Description:"
    addon: vanilla
    order: 1
    text: |
     An isotonic solution used to replace lost fluids, or to treat {{ALKALOSIS}}.

  - type: application_success
    header: "Application Success:"
    addon: vanilla
    order: 2
    text: |

     - \+30% Blood Pressure
     - \+0.07% {{ACIDOSIS}} per second

     Effects last for 200 seconds.

  - type: application_failure
    header: "Application Failure:"
    addon: vanilla
    order: 3
    text: |

     - \+30% Blood Pressure
     - \+0.07% {{ACIDOSIS}} per second

     Effects last for 120 seconds.

# ------------------------------------------ NT PHARMACY INGREDIENT -------------------------------------------

  - type: description
    header: "Description:"
    addon: pharmacy
    order: 1
    text: |
      #### - Type: "Base"
      #### - Skill Required: {{MEDICAL}} 10
      <br>
      A pill base using {{RINGERS_SOLUTION}} or Saline. The most accessible base, but provides only a single capacity slot and slightly reduces potency.

  - type: effects
    header: "Crafting Success:"
    addon: pharmacy
    order: 2
    text: |
      - Increases capacity to 1
      - Multiplies potency by 0.9x


  - type: effects
    header: "Crafting Failure:"
    addon: pharmacy
    order: 3
    text: |
      - Increases capacity to 1
      - Multiplies potency by 0.7x
---