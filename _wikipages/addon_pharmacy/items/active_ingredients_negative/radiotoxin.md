---
layout: contentpage
title: Radiotoxin
addon: pharmacy
subcategory: active_ingredients_(negative)
permalink: /items/pharmacy/radiotoxin/
inline_image: /images/non-neurotrauma/resources/radiotoxin.png
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
            - "{{MEDICAL}} 56"
            - "{{THORIUM}} (1x)"
            - "{{URANIUM}} (2x)"

      - header: "Deconstructor Yield"
        items:
            - "{{THORIUM}} (1x)"
            - "{{URANIUM}} (1x)"

  - title: Store
    sections:
      - items:
          - "Base Price: 200 Marks"
          - "Buyable at Outposts: Colony, Habitation, Research, Military"

blocks:
  - type: description
    header: "Description:"
    order: 1
    text: |
     #### - Type: "Active Ingredient"
     #### - Skill Required: {{MEDICAL}} 0
     <br>
     An active pill ingredient made from {{RADIOTOXIN}}; has negative effects.

  - type: effects
    header: "Crafting Success:"
    order: 2
    text: |
     - +32 {{RADIATION_SICKNESS}}
---