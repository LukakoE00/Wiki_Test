---
layout: contentpage
title: Calyxanide
addon: pharmacy
subcategory: active_ingredients_(positive)
permalink: /items/pharmacy/calyxanide/
inline_image: /images/non-neurotrauma/resources/calyxanide.png

infobox:
  - title: Labels
    sections:
      - items:
          - Item
          - Pharmacy Expansion

  - title: Statistics
    sections:
      - items:
          - "Skill Required: {{MEDICAL}} 38"
          - "Maximum inventory stack: 8"

  - title: Crafting
    sections:
      - header: "Medical Fabricator Requirements"
        items:
            - "{{MEDICAL}} 22"
            - "{{CALYX_EXTRACT}}"
            - "{{BROAD_SPECTRUM_ANTIBIOTICS}} (1x)"
            - "{{STABILOZINE}} (3x)"

      - header: "Deconstructor Yield"
        items:
            - "{{BROAD_SPECTRUM_ANTIBIOTICS}} (1x)"
            - "{{STABILOZINE}} (1x)"

  - title: Store
    sections:
      - items:
          - "Base Price: 510 Marks"
          - "Buyable at Outposts: All"
          - "Buyable at Merchant: Medical, Husk"

blocks:
  - type: description
    header: "Description:"
    order: 1
    text: |
     #### - Type: "Active Ingredient"
     #### - Skill Required: {{MEDICAL}} 38
     <br>
     An active pill ingredient made from {{CALYXANIDE}}; has positive effects.

  - type: effects
    header: "Crafting Success:"
    order: 2
    text: |
     - -50% {{HUSK_INFECTION}}

  - type: effects
    header: "Crafting Failure:"
    order: 3
    text: |
     - -30% {{HUSK_INFECTION}}
---