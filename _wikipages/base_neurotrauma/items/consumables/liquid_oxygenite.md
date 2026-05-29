---
layout: contentpage
title: Liquid Oxygenite
category: items
subcategory: consumables
permalink: /items/consumables/liquid_oxygenite
image: /images/svg/anybodypart.svg
inline_image: /images/base_neurotrauma/items/consumables/liquid_oxygenite.png

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
          - First Aid
          - Important

  - title: Statistics
    sections:
      - items:
          - "Skill Required: {{MEDICAL}} 50"
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
          - "Base Price: 80 Marks"
          - "Buyable at Merchant: City, Research, Medical"

blocks:
  - type: description
    header: "Description:"
    addon: vanilla
    order: 1
    text: |
     A liquified alien material used to inject oxygen directly into the bloodstream, treating {{HYPOXEMIA}}. It is obtained by deconstructing [Oxygenite Shards](https://barotraumagame.com/wiki/Oxygenite_Shard)

  - type: application_success
    header: "Application Success:"
    addon: vanilla
    order: 2
    text: |
     All effects occur over 30 seconds:

     - \-3000% {{HYPOXEMIA}}
     - \+6% {{VANILLA_ORGAN_DAMAGE}}
     - \+6% {{LUNG_DAMAGE}}
     - \+6% {{LIVER_DAMAGE}}
     - \+6% {{HEART_DAMAGE}}
     - \+6% {{KIDNEY_DAMAGE}}
     <br><br>
     Effectively, Liquid Oxygenite will make the user immune to hypoxemia during the 30 seconds.

  - type: application_success
    header: "Application Failure:"
    addon: vanilla
    order: 3
    text: |
     All effects occur over 20 seconds:
     - \-200% {{HYPOXEMIA}}
     - \+10% {{VANILLA_ORGAN_DAMAGE}}
     - \+10% {{LUNG_DAMAGE}}
     - \+10% {{LIVER_DAMAGE}}
     - \+10% {{HEART_DAMAGE}}
     - \+10% {{KIDNEY_DAMAGE}}

# ------------------------------------------ NT PHARMACY INGREDIENT -------------------------------------------

  - type: description
    header: "Description:"
    addon: pharmacy
    order: 1
    text: |
      #### - Type: "Active Ingredient"
      #### - Skill Required: {{MEDICAL}} 72
      <br>
      An active pill ingredient made from {{LIQUID_OXYGENITE}}; has positive effects.

  - type: effects
    header: "Crafting Success:"
    addon: pharmacy
    order: 2
    text: |
      - +2.5% Organ damage
      - +2.5% {{KIDNEY_DAMAGE}}
      - +2.5% {{HEART_DAMAGE}}
      - +2.5% {{LUNG_DAMAGE}}
      - +2.5% {{LIVER_DAMAGE}}
      - -100% {{HYPOXEMIA}}

  - type: effects
    header: "Crafting Failure:"
    addon: pharmacy
    order: 3
    text: |
      - +2.5% Organ damage
      - +2.5% {{KIDNEY_DAMAGE}}
      - +2.5% {{HEART_DAMAGE}}
      - +2.5% {{LUNG_DAMAGE}}
      - +2.5% {{LIVER_DAMAGE}}
      - -60% {{HYPOXEMIA}}
---