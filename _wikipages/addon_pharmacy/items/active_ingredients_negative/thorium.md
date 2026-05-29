---
layout: contentpage
title: Thorium
addon: pharmacy
subcategory: active_ingredients_(negative)
permalink: /items/pharmacy/thorium/
inline_image: /images/non-neurotrauma/resources/thorium.png
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
          - "Base Price: 125 Marks"
          - "Buyable at Outposts: Mining"

blocks:
  - type: description
    header: "Description:"
    order: 1
    text: |
     #### - Type: "Active Ingredient"
     #### - Skill Required: {{MEDICAL}} 0
     <br>
     An active pill ingredient made from {{THORIUM}}; has negative effects.

  - type: effects
    header: "Crafting Success:"
    order: 2
    text: |
     - +30 {{RADIATION_SICKNESS}}
---