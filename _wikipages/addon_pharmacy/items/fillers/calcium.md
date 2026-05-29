---
layout: contentpage
title: Calcium
addon: pharmacy
subcategory: fillers
permalink: /items/pharmacy/calcium/
inline_image: /images/non-neurotrauma/resources/calcium.png

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
          - "Base Price: 31 Marks"
          - "Buyable at Outposts: Mining"

blocks:
  - type: description
    header: "Description:"
    order: 1
    text: |
     #### - Type: "Filler"
     #### - Skill Required: {{MEDICAL}} 25
     <br>
     A pill filler using {{CALCIUM}}.

     <br>
     Can be obtained by deconstructing an {{ARM_TRANSPLANT}} or {{LEG_TRANSPLANT}}, in addition to basegame sources.

  - type: effects
    header: "Crafting Success:"
    order: 2
    text: |
     - Multiplies yield by 3x
     - Multiplies potency by 0.35x

  - type: effects
    header: "Crafting Failure:"
    order: 3
    text: |
     - Multiplies yield by 3x
     - Multiplies potency by 0.2x
---