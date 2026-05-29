---
layout: contentpage
title: Ringer's Solution
category: items
subcategory: consumables
permalink: /items/consumables/ringers_solution
image: /images/svg/anybodypart.svg
inline_image: /images/base_neurotrauma/items/consumables/ringers_solution.png

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
          - "Skill Required: {{MEDICAL}} 20"
          - "Maximum inventory stack: 8"

  - title: Crafting
    sections:
      - header: "Medical Fabricator Requirements (Output: 1x)"
        items:
            - "{{MEDICAL}} 25"
            - "{{SALINE}} (1x)"
            - "{{POTASSIUM}} (1x)"
            - "{{CARBON}} (1x)"

      - header: "Deconstructor Yield"
        items:
            - "{{SALINE}} (1x)"
            - "{{POTASSIUM}} (1x)"

  - title: Store
    sections:
      - items:
          - "Base Price: 100 Marks"
          - "Buyable at Merchant: Medical"

blocks:
  - type: description
    header: "Description:"
    addon: vanilla
    order: 1
    text: |
     An isotonic solution used to replace lost fluids, or to treat {{ACIDOSIS}}.

  - type: application_success
    header: "Application Success:"
    addon: vanilla
    order: 2
    text: |

     - \+30% Blood Pressure
     - \+0.07% {{ALKALOSIS}} per second

     Lasts for 200 seconds.

  - type: application_failure
    header: "Application Failure:"
    addon: vanilla
    order: 3
    text: |

     - \+30% Blood Pressure
     - \+0.07% {{ALKALOSIS}} per second

     Lasts for 120 seconds.

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