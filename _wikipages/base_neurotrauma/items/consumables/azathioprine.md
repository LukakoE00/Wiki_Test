---
layout: contentpage
title: Azathioprine
category: items
subcategory: consumables
permalink: /items/consumables/azathioprine
image: /images/svg/anybodypart.svg
inline_image: /images/base_neurotrauma/items/consumables/azathioprine.png

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
          - Important
          - Toggleable

  - title: Statistics
    sections:
      - items:
          - "Skill Required: {{MEDICAL}} 10"
          - "Maximum inventory stack: 8"

  - title: Crafting
    sections:
      - header: "Medical Fabricator Requirements (Output: 2x)"
        items:
            - "{{MEDICAL}} 50"
            - "{{ETHANOL}} (1x)"
            - "{{PHOSPHORUS}} (1x)"
            - "{{SULPHURIC_ACID}} (1x)"

      - header: "Deconstructor Yield"
        items:
            - "Has no deconstructor outputs."

  - title: Store
    sections:
      - items:
          - "Base Price: 100 Marks"
          - "Buyable at Merchant: Medical"

blocks:
  - type: description
    header: "Description:"
    addon: vanilla
    order: 1
    text: |
     Azathioprine is an immunosuppressant medication used during {{ORGAN_TRANSPLANT_SURGERY}} if organ rejection is enabled in the {{CONFIGURATION_MENU}}. It will lower Immunity over time, making it safe to place an organ into the body when Immunity is below 10%.

  - type: application_success
    header: "Application Success:"
    addon: vanilla
    order: 2
    text: |
     - Lowers immunity over time

  - type: application_failure
    header: "Application Failure:"
    addon: vanilla
    order: 3
    text: |
     - Lowers immunity over time
     - Causes {{SEPSIS}}

# ------------------------------------------ NT PHARMACY INGREDIENT -------------------------------------------

  - type: description
    header: "Description:"
    addon: pharmacy
    order: 1
    text: |
      #### - Type: "Active Ingredient"
      #### - Skill Required: {{MEDICAL}} 40
      <br>
      An active pill ingredient; has positive effects.

  - type: effects
    header: "Crafting Success:"
    addon: pharmacy
    order: 2
    text: |
      - +25% Immunosuppressant

  - type: effects
    header: "Crafting Failure:"
    addon: pharmacy
    order: 3
    text: |
      - +15% Immunosuppressant
      - 50% chance to cause 1 {{SEPSIS}}
---