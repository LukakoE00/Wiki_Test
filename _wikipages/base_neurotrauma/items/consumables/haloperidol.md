---
layout: contentpage
title: Haloperidol
category: items
subcategory: consumables
permalink: /items/consumables/haloperidol
image: /images/svg/anybodypart.svg
inline_image: /images/base_neurotrauma/items/consumables/haloperidol.png

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
          - "Skill Required: {{MEDICAL}} 37"
          - "Maximum inventory stack: 8"

  - title: Crafting
    sections:
      - header: "Medical Fabricator Requirements (Output: 1x)"
        items:
            - "{{MEDICAL}} 21"
            - "{{LITHIUM}} (1x)"
            - "{{CARBON}} (2x)"
            - "{{CHLORINE}} (2x)"

      - header: "Deconstructor Yield"
        items:
            - "{{LITHIUM}} (1x)"
            - "{{CARBON}} (1x)"
            - "{{CHLORINE}} (1x)"

  - title: Store
    sections:
      - items:
          - "Base Price: 130 Marks"
          - "Buyable at Outposts: All"
          - "Buyable at Merchant: Medical"

blocks:
  - type: description
    header: "Description:"
    addon: vanilla
    order: 1
    text: |
     An antipsychotic drug also useful in the treatment of alcohol withdrawal.

  - type: application_success
    header: "Application Success:"
    addon: vanilla
    order: 2
    text: |
     - \-100% {{PSYCHOSIS}}
     - \-100% [Hallucinating](https://barotraumagame.com/wiki/Hallucinating)
     - \-100% {{ALCOHOL_WITHDRAWAL}}

  - type: application_failure
    header: "Application Failure:"
    addon: vanilla
    order: 3
    text: |
     - \-25% {{PSYCHOSIS}}
     - \-25% [Hallucinating](https://barotraumagame.com/wiki/Hallucinating)
     - \-25% alcohol {{ALCOHOL_WITHDRAWAL}}

# ------------------------------------------ NT PHARMACY INGREDIENT -------------------------------------------

  - type: description
    header: "Description:"
    addon: pharmacy
    order: 1
    text: |
      #### - Type: "Active Ingredient"
      #### - Skill Required: {{MEDICAL}} 37
      <br>
      An active pill ingredient made from {{HALOPERIDOL}}; has positive effects.

  - type: effects
    header: "Crafting Success:"
    addon: pharmacy
    order: 2
    text: |
      - -50% {{PSYCHOSIS}}
      - -50% [Hallucinating](https://barotraumagame.com/wiki/Hallucinating)
      - -50% {{ALCOHOL_WITHDRAWAL}}

  - type: effects
    header: "Crafting Failure:"
    addon: pharmacy
    order: 3
    text: |
      - -12% {{PSYCHOSIS}}
      - -12% [Hallucinating](https://barotraumagame.com/wiki/Hallucinating)
      - -12% {{ALCOHOL_WITHDRAWAL}}
---