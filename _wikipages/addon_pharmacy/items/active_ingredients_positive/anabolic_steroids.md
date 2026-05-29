---
layout: contentpage
title: Anabolic Steroids
addon: pharmacy
subcategory: active_ingredients_(positive)
permalink: /items/pharmacy/anabolic_steroids/
inline_image: /images/non-neurotrauma/resources/anabolic_steroids.png

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
            - "{{MEDICAL}} 30"
            - "{{TONIC_LIQUID}} (1x)"
            - "{{ADRENALINE}} (3x)"

      - header: "Deconstructor Yield"
        items:
            - "{{TONIC_LIQUID}} (1x)"
            - "{{ADRENALINE}} (2x)"

  - title: Store
    sections:
      - items:
          - "Base Price: 350 Marks"
          - "Buyable at Outposts: Colony, Research, Military"

blocks:
  - type: description
    header: "Description:"
    order: 1
    text: |
     #### - Type: "Active Ingredient"
     #### - Skill Required: {{MEDICAL}} 35
     <br>
      An active pill ingredient made from {{ANABOLIC_STEROIDS}}; has positive effects.

  - type: effects
    header: "Crafting Success:"
    order: 2
    text: |
     - +35% {{VIGOR}} (210/600 max, 0-50% Damage Resistance, 0-35% Melee Damage), -1/s
     - +7 Organ damage
     - +7 {{NEUROTRAUMA}}
     - +15 {{PSYCHOSIS}}
     - +7 {{CHEMICAL_ADDICTION}}
     - -45 {{WITHDRAWAL}}

  - type: effects
    header: "Crafting Failure:"
    order: 3
    text: |
     - +25% Vigor (150/600 max, 0-50% Damage Resistance, 0-35% Melee Damage), -1/s
     - +15 Organ damage
     - +15 {{NEUROTRAUMA}}
     - +22 {{PSYCHOSIS}}
     - +15 {{CHEMICAL_ADDICTION}}
     - -45 {{WITHDRAWAL}}
---