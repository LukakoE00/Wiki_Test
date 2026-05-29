---
layout: contentpage
title: Poop
addon: pharmacy
subcategory: active_ingredients_(negative)
permalink: /items/pharmacy/poop/
inline_image: /images/non-neurotrauma/resources/poop.png
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
            - "{{CARBON}} (1x)"

  - title: Store
    sections:
      - items:
          - "Not sold."
          
blocks:
  - type: description
    header: "Description:"
    order: 1
    text: |
     #### - Type: "Active Ingredient"
     #### - Skill Required: {{MEDICAL}} 0
     <br>
     An active pill ingredient made from {{POOP}}; has negative effects.

  - type: effects
    header: "Crafting Success:"
    order: 2
    text: |
     - Instant {{SEPSIS}} on use, effects ramp up with affliction strength as per regular {{SEPSIS}}
     - +1 {{SEPSIS}} (1/100 max, +0.5  {{SEPSIS}}/second)
---