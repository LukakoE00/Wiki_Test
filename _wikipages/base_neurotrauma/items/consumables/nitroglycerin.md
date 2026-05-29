---
layout: contentpage
title: Nitroglycerin
category: items
subcategory: consumables
permalink: /items/consumables/nitroglycerin
image: /images/svg/anybodypart.svg
inline_image: /images/base_neurotrauma/items/consumables/nitroglycerin.png

addons:
  - id: vanilla
    label: Base Neurotrauma

  - id: pharmacy
    label: NT Pharmacy Ingredient

infobox:
  - title: Labels
    sections:
      - items:
          - Item
          - Niche

  - title: Statistics
    sections:
      - items:
          - "Skill Required: {{MEDICAL}} 35"
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
          - "Base Price: 150 Marks"
          - "Buyable at Merchant: Military, Armory, Medical"

blocks:
  - type: description
    header: "Description:"
    addon: vanilla
    order: 1
    text: |
     A jar containing a very volatile vasodilator, liable to explode on impact or exposure to heat. While this drug is active, {{FIBRILLATION}} caused by {{HYPOTENSION}} will be reduced.

  - type: application_success
    header: "Application Success:"
    addon: vanilla
    order: 2
    text: |
     - \-45% Blood Pressure

     Effects last for 400 seconds.

  - type: application_failure
    header: "Application Failure:"
    addon: vanilla
    order: 3
    text: |
     - \-45% Blood Pressure

     Effects last for 200 seconds.

# ------------------------------------------ NT PHARMACY INGREDIENT -------------------------------------------

  - type: description
    header: "Description:"
    addon: pharmacy
    order: 1
    text: |
      #### - Type: "Active Ingredient"
      #### - Skill Required: {{MEDICAL}} 0
      <br>
      An active pill ingredient made from {{NITROGLYCERIN}}; has positive effects.

  - type: effects
    header: "Crafting Success:"
    addon: pharmacy
    order: 2
    text: |
      - -100% {{CARDIAC_ARREST}}
      - -50% {{HEART_ATTACK}}
---