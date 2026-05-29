---
layout: contentpage
title: Antirad
addon: pharmacy
subcategory: active_ingredients_(positive)
permalink: /items/pharmacy/antirad/
inline_image: /images/non-neurotrauma/resources/antirad.png

infobox:
  - title: Labels
    sections:
      - items:
          - Item
          - Pharmacy Expansion

  - title: Statistics
    sections:
      - items:
          - "Skill Required: {{MEDICAL}} 25"
          - "Maximum inventory stack: 8"

  - title: Crafting
    sections:
      - header: "Medical Fabricator Requirements"
        items:
            - "{{MEDICAL}} 35"
            - "{{RADIOTOXIN}} (1x)"
            - "{{STABILOZINE}} (1x)"

      - header: "Deconstructor Yield"
        items:
            - "{{STABILOZINE}} (1x)"

  - title: Store
    sections:
      - items:
          - "Base Price: 125 Marks"
          - "Minimum Level Difficulty: 11%"
          - "Buyable at Outposts: All"
          - "Buyable at Merchant: Medical"

blocks:
  - type: description
    header: "Description:"
    order: 1
    text: |
     #### - Type: "Active Ingredient"
     #### - Skill Required: {{MEDICAL}} 0
     <br>
     An active pill ingredient made from {{ANTIRAD}}; has positive effects.

  - type: effects
    header: "Crafting Success:"
    order: 2
    text: |
     - -50% {{RADIATION_SICKNESS}}
---