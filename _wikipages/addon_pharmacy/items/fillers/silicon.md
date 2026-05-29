---
layout: contentpage
title: Silicon
addon: pharmacy
subcategory: fillers
permalink: /items/pharmacy/silicon/
inline_image: /images/non-neurotrauma/resources/silicon.png

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
          - "Base Price: 17 Marks"
          - "Buyable at Outposts: Mining"

blocks:
  - type: description
    header: "Description:"
    order: 1
    text: |
     #### - Type: "Filler"
     #### - Skill Required: {{MEDICAL}} 25
     <br>
     A pill filler using {{SILICON}}.
     <br>
     Gives you twice the amount of pills, at half the strength. Will additionally change the sprite to Tablets.

  - type: effects
    header: "Crafting Success:"
    order: 2
    text: |
     - Multiplies yield by 2x
     - Multiplies potency by 0.5x

  - type: effects
    header: "Crafting Failure:"
    order: 3
    text: |
     - Multiplies yield by 2x
     - Multiplies potency by 0.35x
---