---
layout: contentpage
title: Sufforin
addon: pharmacy
subcategory: active_ingredients_(negative)
permalink: /items/pharmacy/sufforin/
inline_image: /images/non-neurotrauma/resources/sufforin.png
infobox:
  - title: Labels
    sections:
      - items:
          - Item
          - Pharmacy Expansion

  - title: Statistics
    sections:
      - items:
          - "Skill Required: {{MEDICAL}} 40"
          - "Maximum inventory stack: 8"

  - title: Crafting
    sections:
      - header: "Medical Fabricator Requirements"
        items:
            - "{{MEDICAL}} 60"
            - "{{SULPHURIC_ACID}} (1x)"
            - "{{POTASSIUM}} (1x)"

      - header: "Deconstructor Yield"
        items:
            - "{{SULPHURIC_ACID}} (1x)"

  - title: Store
    sections:
      - items:
          - "Base Price: 100 Marks"
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
     An active pill ingredient made from {{SUFFORIN}}; has negative effects.

  - type: effects
    header: "Crafting Success:"
    order: 2
    text: |
     - Instant poisoning on use, side effects ramp up with affliction strength
     - +1 {{SUFFORIN_POISONING}} (1/200 max, visual effects & -0 to -2 vitality/second depending on affliction strength), +2 to +0.5 poisoning/second depending on affliction strength
---