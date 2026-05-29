---
layout: contentpage
title: Carbon
addon: pharmacy
subcategory: active_ingredients_(positive)
permalink: /items/pharmacy/carbon/
inline_image: /images/non-neurotrauma/resources/carbon.png

infobox:
  - title: Labels
    sections:
      - items:
          - Item
          - Pharmacy Expansion

  - title: Statistics
    sections:
      - items:
          - "Maximum inventory stack: 8"

  - title: Crafting
    sections:
      - header: "Medical Fabricator Requirements"
        items:
            - "Cannot be fabricated."

      - header: "Deconstructor Yield"
        items:
            - "Has no deconstructor outputs."

  - title: Store
    sections:
      - items:
          - "Base Price: 10 Marks"
          - "Buyable at Outposts: Mining"

blocks:
  - type: description
    header: "Description:"
    order: 1
    text: |
     #### - Type: "Active Ingredient"
     #### - Skill Required: {{MEDICAL}} 0
     <br>
     An active pill ingredient made from {{CARBON}}; has positive effects.

  - type: effects
    header: "Crafting Success:"
    order: 2
    text: |
     - -7% All poisons
     - -7% {{DRUNK}}
     - -7% {{PARALYSIS}}
     - -15% {{RADIATION_SICKNESS}}
---