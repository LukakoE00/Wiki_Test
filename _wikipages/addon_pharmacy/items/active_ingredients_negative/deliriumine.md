---
layout: contentpage
title: Deliriumine
addon: pharmacy
subcategory: active_ingredients_(negative)
permalink: /items/pharmacy/deliriumine/
inline_image: /images/non-neurotrauma/resources/deliriumine.png
infobox:
  - title: Labels
    sections:
      - items:
          - Item
          - Pharmacy Expansion

  - title: Statistics
    sections:
      - items:
          - "Skill Required: {{MEDICAL}} 35"
          - "Maximum inventory stack: 8"
  - title: Crafting
    sections:
      - header: "Medical Fabricator Requirements (Output: 2x)"
        items:
            - "{{MEDICAL}} 50"
            - "{{DEMENTONITE_CLUSTER}}"
            - "{{ETHANOL}}"

      - header: "Deconstructor Yield"
        items:
            - "Has no deconstructor outputs."

  - title: Store
    sections:
      - items:
          - "Base Price: 250 Marks"
          - "Buyable at Outposts: Colony, Research, Military"

blocks:
  - type: description
    header: "Description:"
    order: 1
    text: |
     #### - Type: "Active Ingredient"
     #### - Skill Required: {{MEDICAL}} 0
     <br>
     An active pill ingredient made from {{DELIRIUMINE}}; has negative effects.
     
  - type: effects
    header: "Crafting Success:"
    order: 2
    text: |
     - Instant poisoning on use, side effects ramp up with affliction strength
     - +1 {{DELIRIUMINE_POISONING}} (1/100 max, causes +1 psychosis/second), +1 poisoning/second
---