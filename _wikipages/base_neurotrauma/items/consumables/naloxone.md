---
layout: contentpage
title: Naloxone
category: items
subcategory: consumables
permalink: /items/consumables/naloxone
image: /images/svg/anybodypart.svg
inline_image: /images/base_neurotrauma/items/consumables/naloxone.png

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
          - "Skill Required: {{MEDICAL}} 39"
          - "Maximum inventory stack: 8"

  - title: Crafting
    sections:
      - header: "Medical Fabricator Requirements (Output: 1x)"
        items:
            - "{{MEDICAL}} 23"
            - "{{OPIUM}} (1x)"
            - "{{STABILOZINE}} (1x)"

      - header: "Deconstructor Yield"
        items:
            - "{{STABILOZINE}} (1x)"

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
     Naloxone is used to treat the effects of opiates.

  - type: application_success
    header: "Application Success:"
    addon: vanilla
    order: 2
    text: |
     - \-60% {{OPIATE_WITHDRAWAL}}
     - \-60% {{OPIATE_OVERDOSE}}
     - \-60% {{OPIATE_ADDICTION}}
     - \-60% {{ANALGESIA}}
     - \-60% Opioids

  - type: application_failure
    header: "Application Failure:"
    addon: vanilla
    order: 3
    text: |
     - \-30% {{OPIATE_WITHDRAWAL}}
     - \-30% {{OPIATE_OVERDOSE}}
     - \-30% {{OPIATE_ADDICTION}}
     - \-60% {{ANALGESIA}}
     - \-60% Opioids
     - \+15% {{COMA}} (50% chance)

# ------------------------------------------ NT PHARMACY INGREDIENT -------------------------------------------

  - type: description
    header: "Description:"
    addon: pharmacy
    order: 1
    text: |
      #### - Type: "Active Ingredient"
      #### - Skill Required: {{MEDICAL}} 40
      <br>
      An active pill ingredient made from {{NALOXONE}}; has positive effects.

  - type: effects
    header: "Crafting Success:"
    addon: pharmacy
    order: 2
    text: |
      - -30% {{ANALGESIA}}
      - -30% {{OPIATE_OVERDOSE}}
      - -30% {{OPIATE_WITHDRAWAL}}

  - type: effects
    header: "Crafting Failure:"
    addon: pharmacy
    order: 3
    text: |
      - -30% {{ANALGESIA}}
      - -15% {{OPIATE_OVERDOSE}}
      - -15% {{OPIATE_WITHDRAWAL}}
      - 50% Chance of +8 {{COMA}}
---