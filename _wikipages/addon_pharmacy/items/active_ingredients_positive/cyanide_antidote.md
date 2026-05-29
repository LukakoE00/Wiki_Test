---
layout: contentpage
title: Cyanide Antidote
addon: pharmacy
subcategory: active_ingredients_(positive)
permalink: /items/pharmacy/cyanide_antidote/
inline_image: /images/non-neurotrauma/resources/cyanide_antidote.png

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
            - "{{MEDICAL}} 26"
            - "{{CYANIDE}} (1x)"
            - "{{STABILOZINE}} (1x)"

      - header: "Deconstructor Yield"
        items:
            - "{{STABILOZINE}} (1x)"

  - title: Store
    sections:
      - items:
          - "Minimum difficulty: 15%"
          - "Base Price: 350 Marks"
          - "Buyable at Outposts: All"
          - "Buyable at Merchant: Medical, Husk"

blocks:
  - type: description
    header: "Description:"
    order: 1
    text: |
     #### - Type: "Active Ingredient"
     #### - Skill Required: {{MEDICAL}} 0
     <br>
     An active pill ingredient made from {{CYANIDE_ANTIDOTE}}; has positive effects.

  - type: effects
    header: "Crafting Success:"
    order: 2
    text: |
     - -50% {{CYANIDE_POISONING}}
---