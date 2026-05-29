---
layout: contentpage
title: Pressure Stabilizer
addon: pharmacy
subcategory: active_ingredients_(positive)
permalink: /items/pharmacy/pressure_stabilizer/
inline_image: /images/non-neurotrauma/resources/pressure_stabilizer.png

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
      - header: "Medical Fabricator Requirements"
        items:
            - "No Pressure Talent (Medical Doctor)"
            - "{{LIQUID_OXYGENITE}} (2x)"
            - "{{STABILOZINE}} (2x)"

      - header: "Deconstructor Yield"
        items:
            - "{{LIQUID_OXYGENITE}} (1x)"

  - title: Store
    sections:
      - items:
          - "Not sold"

blocks:
  - type: description
    header: "Description:"
    order: 1
    text: |
     #### - Type: "Active Ingredient"
     #### - Skill Required: {{MEDICAL}} 35
     <br>
     An active pill ingredient made from {{PRESSURE_STABILIZER}}; has positive effects.

  - type: effects
    header: "Crafting Success:"
    order: 2
    text: |
     - +50% {{PRESSURE_STABILIZED}} (500/1000 max, 100% oxygen low resistance, -0.5 oxygen low per second, pressure immunity), -1/s

  - type: effects
    header: "Crafting Failure:"
    order: 3
    text: |
     - +25% {{PRESSURE_STABILIZED}} (250/1000 max, 100% oxygen low resistance, -0.5 oxygen low per second, pressure immunity), -1/s
---