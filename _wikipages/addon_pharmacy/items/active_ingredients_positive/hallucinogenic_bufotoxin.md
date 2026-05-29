---
layout: contentpage
title: Hallucinogenic Bufotoxin
addon: pharmacy
subcategory: active_ingredients_(positive)
permalink: /items/pharmacy/hallucinogenic_bufotoxin/
inline_image: /images/non-neurotrauma/resources/hallucinogenic_bufotoxin.png

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
            - "{{SALINE}} (1x)"
            - "{{PARALYXIS}} (1x)"

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
     #### - Skill Required: {{MEDICAL}} 30
     <br>
     An active pill ingredient made from {{HALLUCINOGENIC_BUFOTOXIN}}; has positive effects.

  - type: effects
    header: "Crafting Success:"
    order: 2
    text: |
     - -30% {{PARALYSIS}}
     - +10 {{PSYCHOSIS}}

  - type: effects
    header: "Crafting Failure:"
    order: 3
    text: |
     - -15% {{PARALYSIS}}
     - +10 {{PSYCHOSIS}}
---