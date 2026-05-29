---
layout: contentpage
title: Chlorine
addon: pharmacy
subcategory: fillers
permalink: /items/pharmacy/chlorine/
inline_image: /images/non-neurotrauma/resources/chlorine.png

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
          - "Base Price: 11 Marks"
          - "Buyable at Outposts: Mining"

blocks:
  - type: description
    header: "Description:"
    order: 1
    text: |
     #### - Type: "Filler"
     #### - Skill Required: {{MEDICAL}} 50
     <br>
     A pill filler using {{CHLORINE}}.

  - type: effects
    header: "Crafting Success:"
    order: 2
    text: |
     - Multiplies potency by 1.3x
     - Adds 2 Burn to outputs

  - type: effects
    header: "Crafting Failure:"
    order: 3
    text: |
     - Multiplies potency by 0.7x
     - Adds 8 Burn to outputs
---