---
layout: contentpage
title: Lead
addon: pharmacy
subcategory: active_ingredients_(negative)
permalink: /items/pharmacy/lead/
inline_image: /images/non-neurotrauma/resources/lead.png
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
          - "Base Price: 18 Marks"
          - "Buyable at Outposts: All"

blocks:
  - type: description
    header: "Description:"
    order: 1
    text: |
     #### - Type: "Active Ingredient"
     #### - Skill Required: {{MEDICAL}} 0
     <br>
     An active pill ingredient made from {{LEAD}}; has negative effects.
     
  - type: effects
    header: "Crafting Success:"
    order: 2
    text: |
     - +20% {{NEUROTRAUMA}}
---