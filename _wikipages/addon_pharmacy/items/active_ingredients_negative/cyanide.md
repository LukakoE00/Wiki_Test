---
layout: contentpage
title: Cyanide
addon: pharmacy
subcategory: active_ingredients_(negative)
permalink: /items/pharmacy/cyanide/
inline_image: /images/non-neurotrauma/resources/cyanide.png
infobox:
  - title: Labels
    sections:
      - items:
          - Item
          - Pharmacy Expansion
  - title: Statistics
    sections:
      - items:
          - "Skill Required: {{MEDICAL}} 60"
          - "Maximum inventory stack: 8"
  - title: Crafting
    sections:
      - header: "Medical Fabricator Requirements"
        items:
            - "{{MEDICAL}} 64"
            - "{{SODIUM}} (3x)"
            - "{{CHLORAL_HYDRATE}} (1x)"

      - header: "Deconstructor Yield"
        items:
            - "{{SODIUM}} (2x)"
            - "{{CHLORAL_HYDRATE}} (1x)"

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
     An active pill ingredient made from {{CYANIDE}}; has negative effects.

  - type: effects
    header: "Crafting Success:"
    order: 2
    text: |
     - Instant poisoning on use, side effects ramp up with affliction strength
     - +1 {{CYANIDE_POISONING}} (1/200 max, -20% to -90% movement speed & -0 to -2 vitality/second depending on affliction strength), +1 to +0.5 poisoning/second depending on affliction strength
---