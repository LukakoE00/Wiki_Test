---
layout: contentpage
title: Paralyzant
addon: pharmacy
subcategory: active_ingredients_(negative)
permalink: /items/pharmacy/paralyzant/
inline_image: /images/non-neurotrauma/resources/paralyzant.png
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
            - "{{MEDICAL}} 40"
            - "{{CHLORAL_HYDRATE}} (2x)"
            - "{{PARALYXIS}} (1x)"

      - header: "Deconstructor Yield"
        items:
            - "{{CHLORINE}} (1x)"
            - "{{PARALYXIS}} (1x)"

  - title: Store
    sections:
      - items:
          - "Base Price: 380 Marks"
          - "Buyable at Outposts: Colony, Research, Military"

blocks:
  - type: description
    header: "Description:"
    order: 1
    text: |
     #### - Type: "Active Ingredient"
     #### - Skill Required: {{MEDICAL}} 0
     <br>
     An active pill ingredient made from {{PARALYZANT}}; has negative effects.

  - type: effects
    header: "Crafting Success:"
    order: 2
    text: |
     - Instant poisoning on use, side effects ramp up with affliction strength
     - +1 {{PARALYSIS}} (1/100 max, -50% to 100% movement speed & visual effects depending on affliction strength, {{UNCONSCIOUSNESS}} at 99-100 {{PARALYSIS}}), +1/second
---