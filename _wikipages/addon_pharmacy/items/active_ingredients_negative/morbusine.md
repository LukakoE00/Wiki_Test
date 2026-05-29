---
layout: contentpage
title: Morbusine
addon: pharmacy
subcategory: active_ingredients_(negative)
permalink: /items/pharmacy/morbusine/
inline_image: /images/non-neurotrauma/resources/morbusine.png
infobox:
  - title: Labels
    sections:
      - items:
          - Item
          - Pharmacy Expansion

  - title: Statistics
    sections:
      - items:
          - "Skill Required: {{MEDICAL}} 50"
          - "Maximum inventory stack: 8"
  - title: Crafting
    sections:
      - header: "Medical Fabricator Requirements"
        items:
            - "{{MEDICAL}} 58"
            - "{{CHLORINE}} (2x)"
            - "{{CALCIUM}} (2x)"
            - "{{SULPHURIC_ACID}} (1x)"

      - header: "Deconstructor Yield"
        items:
            - "{{CHLORINE}} (1x)"
            - "{{CALCIUM}} (1x)"
            - "{{SULPHURIC_ACID}} (1x)"

  - title: Store
    sections:
      - items:
          - "Base Price: 250 Marks"
          - "Buyable at Outposts: Colony, Research, Military"
          - "Buyable at Merchant: Husk (50+ Reputation)"

blocks:
  - type: description
    header: "Description:"
    order: 1
    text: |
     #### - Type: "Active Ingredient"
     #### - Skill Required: {{MEDICAL}} 0
     <br>
     An active pill ingredient made from {{MORBUSINE}}; has negative effects.

  - type: effects
    header: "Crafting Success:"
    order: 2
    text: |
     - Instant poisoning on use, side effects ramp up with affliction strength
     - +1 {{MORBUSINE_POISONING}} (1/100 max, -20% movement speed, +7 to +15 oxygen low & -0 to -0.5 vitality/second depending on affliction strength), +1 poisoning/second
---