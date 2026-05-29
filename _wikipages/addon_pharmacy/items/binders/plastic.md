---
layout: contentpage
title: Plastic
addon: pharmacy
subcategory: binders
permalink: /items/pharmacy/plastic/
inline_image: /images/non-neurotrauma/resources/plastic.png

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
      - header: "Fabricator Requirements"
        items:
            - "{{MECHANICAL}} 20"
            - "{{CARBON}} (1x)"
            - "{{SILICON}} (2x)"

      - header: "Deconstructor Yield"
        items:
            - "{{CARBON}} (%)"
            - "{{SILICON}} (%)"

  - title: Store
    sections:
      - items:
          - "Base Price: 45 Marks"
          - "Buyable at Outposts: All"
    
blocks:
  - type: description
    header: "Description:"
    order: 1
    text: |
     #### - Type: "Binder"
     #### - Skill Required: {{MEDICAL}} 50
     <br>
     A pill binder using {{PLASTIC}}.


  - type: effects
    header: "Crafting Success:"
    order: 2
    text: |
     - Multiplies potency by 1.6x
     - Halves the output yield

  - type: effects
    header: "Crafting Failure:"
    order: 3
    text: |
     - Halves the output yield
---