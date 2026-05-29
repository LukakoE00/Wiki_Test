---
layout: contentpage
title: Streptokinase
category: items
subcategory: consumables
permalink: /items/consumables/streptokinase
image: /images/svg/anybodypart.svg
inline_image: /images/base_neurotrauma/items/consumables/streptokinase.png

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
          - "Skill Required: None"
          - "Maximum inventory stack: 8"

  - title: Crafting
    sections:
      - header: "Medical Fabricator Requirements (Output: 2x)"
        items:
            - "{{MEDICAL}} 40"
            - "{{SLIME_BACTERIA}} (1x)"
            - "{{STABILOZINE}} (1x)"

      - header: "Deconstructor Yield"
        items:
            - "{{STABILOZINE}} (1x)"

  - title: Store
    sections:
      - items:
          - "Base Price: 120 Marks"
          - "Buyable at Merchant: Medical"

blocks:
  - type: description
    header: "Description:"
    addon: vanilla
    order: 1
    text: |
     A blood thinner. Using Streptokinase will prevent natural {{BLEEDING}} regeneration and increases the chance of getting a {{STROKE}} if the patient has more than 150% {{HYPERTENSION}}.

  - type: effects
    header: "Effects:"
    addon: vanilla
    order: 2
    text: |
     - Fully treats {{HEART_ATTACK}} and {{HEMOTRANSFUSION_SHOCK}}

# ------------------------------------------ NT PHARMACY INGREDIENT -------------------------------------------

  - type: description
    header: "Description:"
    addon: pharmacy
    order: 1
    text: |
      #### - Type: "Active Ingredient"
      #### - Skill Required: {{MEDICAL}} 0
      <br>
      An active pill ingredient made from {{STREPTOKINASE}}; has positive effects.

  - type: effects
    header: "Crafting Success:"
    addon: pharmacy
    order: 2
    text: |
      - -20% {{HEART_ATTACK}}
      - -50% {{HEMOTRANSFUSION_SHOCK}}
      - +25% {{STREPTOKINASE}} (helps cure heart attack, makes stroke worse)
---