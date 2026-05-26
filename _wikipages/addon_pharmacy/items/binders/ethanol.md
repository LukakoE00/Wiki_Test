---
layout: contentpage
title: Ethanol
addon: pharmacy
subcategory: binders
permalink: /items/pharmacy/ethanol/
inline_image: /images/non-neurotrauma/resources/ethanol.png

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
          - "Base Price: 60 marks"
          - "Buyable at Outposts: All"
          - "Buyable at Merchant: Nightclub"
          - "Found in Vending Machines"

blocks:
  - type: description
    header: "Description:"
    order: 1
    text: |
     #### - Type: "Binder"
     #### - Skill Required: {{MEDICAL}} 20
     <br>
     A pill binder using {{ETHANOL}}. A simple, low-skill binder with no side effects on success. The most commonly used binder for general recipes.

     <br>
     Obtained by deconstructing a {{SEA_YEAST_SHROOM}}.

  - type: effects
    header: "Crafting Success:"
    order: 2
    text: |
     - No side-effects

  - type: effects
    header: "Crafting Failure:"
    order: 3
    text: |
     - Gives 5% {{DRUNK}} per pill at default yield (10% divided by the number of pills crafted)
---