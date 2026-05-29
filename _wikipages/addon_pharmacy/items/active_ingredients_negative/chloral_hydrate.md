---
layout: contentpage
title: Chloral hydrate
addon: pharmacy
subcategory: active_ingredients_(negative)
permalink: /items/pharmacy/chloral_hydrate/
inline_image: /images/non-neurotrauma/resources/chloral_hydrate.png
infobox:
  - title: Labels
    sections:
      - items:
          - Item
          - Pharmacy Expansion
  - title: Statistics
    sections:
      - items:
          - "Skill Required: {{MEDICAL}} 30"
          - "Maximum inventory stack: 8"
  - title: Crafting
    sections:
      - header: "Medical Fabricator Requirements"
        items:
            - "{{MEDICAL}} 50"
            - "{{CHLORINE}} (2x)"
            - "{{ETHANOL}} (1x)"

      - header: "Deconstructor Yield"
        items:
            - "{{CHLORINE}} (1x)"
            - "{{ETHANOL}} (1x)"

  - title: Store
    sections:
      - items:
          - "Base Price: 100 Marks"
          - "Buyable at Outposts: Colony, Research, Military"

blocks:
  - type: description
    header: "Description:"
    order: 1
    text: |
     #### - Type: "Active Ingredient"
     #### - Skill Required: {{MEDICAL}} 0
     <br>
     An active pill ingredient made from {{CHLORAL_HYDRATE}}; has negative effects.
     
  - type: effects
    header: "Crafting Success:"
    order: 2
    text: |
     - +15% incremental {{STUN}} (15/100 max, -20% to -70% movement speed at 0 to 90, stunned & +3 nausea/sec at 90 to 100), -5/second at 0 to 90, -1/second at 90 to 100
---