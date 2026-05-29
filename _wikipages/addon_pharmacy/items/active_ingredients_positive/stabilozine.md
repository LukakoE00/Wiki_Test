---
layout: contentpage
title: Stabilozine
addon: pharmacy
subcategory: active_ingredients_(positive)
permalink: /items/pharmacy/stabilozine/
inline_image: /images/non-neurotrauma/resources/stabilozine.png

infobox:
  - title: Labels
    sections:
      - items:
          - Item
          - Pharmacy Expansion

  - title: Statistics
    sections:
      - items:
          - "Skill Required: {{MEDICAL}} 25"
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
          - "Base Price: 40 Marks"
          - "Buyable at Outposts: Habitation, Research"
          - "Buyable at Merchants: Medical"

blocks:
  - type: description
    header: "Description:"
    order: 1
    text: |
     #### - Type: "Active Ingredient"
     #### - Skill Required: {{MEDICAL}} 0
     <br>
     An active pill ingredient made from {{STABILOZINE}}; has positive effects.

  - type: effects
    header: "Crafting Success:"
    order: 2
    text: |
     - -15% Drunk
     - -15% to all poisons
     - -15% {{OPIATE_WITHDRAWAL}}
     - -15% {{CHEMICAL_WITHDRAWAL}}
     - -15% {{ALCOHOL_WITHDRAWAL}}
     - -15% {{RADIATION_SICKNESS}}
     - -15% {{PARALYSIS}}
---