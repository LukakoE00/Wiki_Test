---
layout: contentpage
title: Alien Blood
category: items
subcategory: consumables
permalink: /items/consumables/alien_blood
image: /images/svg/anybodypart.svg
inline_image: /images/base_neurotrauma/items/consumables/alien_blood.png

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
          - First Aid

  - title: Statistics
    sections:
      - items:
          - "Skill Required: Medical 55"
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
          - "Base Price: 100 Marks"
          - "Buyable at Outposts: Research"

blocks:
  - type: description
    header: "Description:"
    addon: vanilla
    order: 1
    text: |
     Using Alien Blood in place of regular blood is extremely dangerous and should only be used in dire situations.

  - type: application_success
    header: "Application Success:"
    addon: vanilla
    order: 2
    text: |
     - \-20% {{BLOOD_LOSS}}
     - \+60% {{PSYCHOSIS}}
     - \+100% {{HEMOTRANSFUSION_SHOCK}}

  - type: application_failure
    header: "Application Failure:"
    addon: vanilla
    order: 3
    text: |
     - \-20% {{BLOOD_LOSS}}
     - \+60% {{PSYCHOSIS}}
     - \+100% {{HEMOTRANSFUSION_SHOCK}}

# ------------------------------------------ NT PHARMACY INGREDIENT -------------------------------------------

  - type: description
    header: "Description:"
    addon: pharmacy
    order: 1
    text: |
      #### - Type: "Base"
      #### - Skill Required: {{MEDICAL}} 60
      <br>
      A pill base using Alien Blood. Provides the highest capacity and potency multiplier of all bases, at the cost of adding psychosis on use.

  - type: effects
    header: "Crafting Success:"
    addon: pharmacy
    order: 2
    text: |
      - Increases capacity to 3
      - Multiplies potency by 1.2x
      - +5 psychosis


  - type: effects
    header: "Crafting Failure:"
    addon: pharmacy
    order: 3
    text: |
      - Increases capacity to 3
      - Multiplies potency by 0.8x
      - +10 psychosis
---