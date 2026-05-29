---
layout: contentpage
title: Tonic Liquid
addon: pharmacy
subcategory: active_ingredients_(positive)
permalink: /items/pharmacy/tonic_liquid/
inline_image: /images/non-neurotrauma/resources/tonic_liquid.png

infobox:
  - title: Labels
    sections:
      - items:
          - Item
          - Pharmacy Expansion

  - title: Statistics
    sections:
      - items:
          - "Skill Required: {{MEDICAL}} 0"
          - "Maximum inventory stack: 8"

  - title: Crafting
    sections:
      - header: "Medical Fabricator Requirements (Output: 2x)"
        items:
            - "{{MEDICAL}} 30"
            - "{{CALCIUM}} (3x)"
            - "{{ZINC}} (3x)"
            - "{{POTASSIUM}} (3x)"

      - header: "Deconstructor Yield"
        items:
            - "{{CALCIUM}} (1x)"
            - "{{ZINC}} (1x)"
            - "{{POTASSIUM}} (1x)"


  - title: Store
    sections:
      - items:
          - "Base Price: 75 Marks"
          - "Buyable at Outposts: All"
          - "Buyable at Merchant: Nightclub"
          - "Sold in Vending Machines"

blocks:
  - type: description
    header: "Description:"
    order: 1
    text: |
     #### - Type: "Active Ingredient"
     #### - Skill Required: {{MEDICAL}} 0
     <br>
     An active pill ingredient made from {{TONIC_LIQUID}}; has positive effects. Affliction is applied instantly. 

  - type: effects
    header: "Crafting Success:"
    order: 2
    text: |
     - 25% Slow metabolism (150/600 max, 100-200% buff duration), -1/s
---