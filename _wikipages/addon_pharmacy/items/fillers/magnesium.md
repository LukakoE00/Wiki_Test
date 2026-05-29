---
layout: contentpage
title: Magnesium
addon: pharmacy
subcategory: fillers
permalink: /items/pharmacy/silicon/
inline_image: /images/non-neurotrauma/resources/magnesium.png

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
            - "Has no deconstructor outputs."

  - title: Store
    sections:
      - items:
          - "Base Price: 65 Marks"
          - "Buyable at Outposts: All"

blocks:
  - type: description
    header: "Description:"
    order: 1
    text: |
     #### - Type: "Filler"
     #### - Skill Required: {{MEDICAL}} 15
     <br>
     A pill filler using {{MAGNESIUM}}.
     <br>
     Gives you half the amount of pills, at double the strength. Will additionally change the sprite to a Horse Pill.

  - type: effects
    header: "Crafting Success:"
    order: 2
    text: |
     - Multiplies yield by 0.5x
     - Multiplies potency by 2x

  - type: effects
    header: "Crafting Failure:"
    order: 3
    text: |
     - Multiplies yield by 0.5x
     - Multiplies potency by 1.3x
---