---
layout: contentpage
title: Elastin
addon: pharmacy
subcategory: binders
permalink: /items/pharmacy/elastin/
inline_image: /images/non-neurotrauma/resources/elastin.png

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
          - "Base Price: 40 marks"
          - "Buyable at Outposts: Research, Colony"
          - "Buyable at Merchant: Medical"
    
blocks:
  - type: description
    header: "Description:"
    order: 1
    text: |
     #### - Type: "Binder"
     #### - Skill Required: {{MEDICAL}} 40
     <br>
     A pill binder using {{ELASTIN}}. A strong potency multiplier with no effect on yield.

     <br>
     Obtained by deconstructing an {{ELASTIN_PLANT}}.

  - type: effects
    header: "Crafting Success:"
    order: 2
    text: |
     - Multiplies potency by 1.25x

  - type: effects
    header: "Crafting Failure:"
    order: 3
    text: |
     - Multiplies potency by 0.9x
---