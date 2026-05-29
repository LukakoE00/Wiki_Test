---
layout: contentpage
title: Sodium
addon: pharmacy
subcategory: fillers
permalink: /items/pharmacy/sodium/
inline_image: /images/non-neurotrauma/resources/sodium.png

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
          - "Base Price: 33 Marks"
          - "Buyable at Outposts: Mining"

blocks:
  - type: description
    header: "Description:"
    order: 1
    text: |
     #### - Type: "Filler"
     #### - Skill Required: {{MEDICAL}} 15
     <br>
     A pill filler using {{SODIUM}}. 
     
     <br>
     Pills made using this filler will **explode** unless combined with {{RINGERS_SOLUTION}} or {{SALINE}} as a Base.

  - type: effects
    header: "Crafting Success:"
    order: 2
    text: |
     - Multiplies potency by 1.2x

  - type: effects
    header: "Crafting Failure:"
    order: 3
    text: |
     - Multiplies potency by 0.8x
---