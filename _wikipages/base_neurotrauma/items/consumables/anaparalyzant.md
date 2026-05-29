---
layout: contentpage
title: Anaparalyzant
category: items
subcategory: consumables
permalink: /items/consumables/anaparalyzant
image: /images/svg/anybodypart.svg
inline_image: /images/base_neurotrauma/items/consumables/anaparalyzant.png

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
          - "Skill Required: {{MEDICAL}} 64"
          - "Maximum inventory stack: 8"

  - title: Crafting
    sections:
      - header: "Medical Fabricator Requirements (Output: 1x)"
        items:
            - "{{MEDICAL}} 24"
            - "{{PARALYZANT}} (1x)" 
            - "{{STABILOZINE}} (1x)"

      - header: "Deconstructor Yield"
        items:
            - "{{STABILOZINE}} (1x)"

  - title: Store
    sections:
      - items:
          - "Minimum Difficulty: 15%"
          - "Base Price: 200 Marks"
          - "Buyable at Outposts: All"
          - "Buyable at Merchant: Medical"

blocks:
  - type: description
    header: "Description:"
    addon: vanilla
    order: 1
    text: |
     Alongside it's original use of providing paralysis resistance and treating paralysis, Anaparalyzant can be used to quickly decrease {{ANESTHESIA}} and wake a patient up much faster.

  - type: application_success
    header: "Application Success:"
    addon: vanilla
    order: 2
    text: |
     - Instantly cures {{ANESTHESIA}}
     - \+800% {{PARALYSIS_RESISTANCE}}.
     - \+5% {{PSYCHOSIS}}

  - type: application_failure
    header: "Application Failure:"
    addon: vanilla
    order: 3
    text: |
     - \-3% {{ANESTHESIA}} per second for 60 seconds.
     - \+6.5% {{PARALYSIS_RESISTANCE}} per second for 60 seconds.
     - \+0.75% {{PSYCHOSIS}} per second for 60 seconds.

# ------------------------------------------ NT PHARMACY INGREDIENT -------------------------------------------

  - type: description
    header: "Description:"
    addon: pharmacy
    order: 1
    text: |
     - Type: "Active Ingredient"
     - Skill Required: {{MEDICAL}} 64
     <br>
     An active pill ingredient made from {{ANAPARALYZANT}}; has positive effects.

    type: effects
    header: "Crafting Success:"
    addon: pharmacy
    order: 2
    text: |
     - +50% {{PARALYSIS_RESISTANCE}} (400/800 max, -5/s)
     - +2.5 {{PSYCHOSIS}}
     - -100% {{ANESTHESIA}} (200/200 max)

    type: effects
    header: "Crafting Failure:"
    addon: pharmacy
    order: 3
    text: |
     - +25% {{PARALYSIS_RESISTANCE}} (200/800 max, -5/s)
     - +20 {{PSYCHOSIS}}
     - -100% {{ANESTHESIA}} (200/200 max)
---