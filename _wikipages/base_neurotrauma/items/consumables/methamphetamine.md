---
layout: contentpage
title: Methamphetamine
category: items
subcategory: consumables
permalink: /items/consumables/methamphetamine
image: /images/svg/anybodypart.svg
inline_image: /images/base_neurotrauma/items/consumables/methamphetamine.png

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
      - header: "Medical Fabricator Requirements (Output: 1x)"
        items:
            - "{{MEDICAL}} 30"
            - "{{PHOSPHORUS}} (1x)"
            - "{{CHLORINE}} (2x)"
            - "{{CARBON}} (2x)"

      - header: "Deconstructor Yield"
        items:
            - "{{PHOSPHORUS}} (1x)"
            - "{{CHLORINE}} (1x)"
            - "{{CARBON}} (1x)"

  - title: Store
    sections:
      - items:
          - "Base Price: 50 Marks"
          - "Buyable at Outposts: Colony, Research"
          - "Buyable at Merchant: Military"

blocks:
  - type: description
    header: "Description:"
    addon: vanilla
    order: 1
    text: |
     A stimulant.

  - type: application_success
    header: "Application Success:"
    addon: vanilla
    order: 2
    text: |
     - \+70% {{HYPERACTIVITY}}
     - \+15% {{VANILLA_ORGAN_DAMAGE}}
     - \+15% {{NEUROTRAUMA}}
     - \+15% {{CHEMICAL_ADDICTION}}
     - \+30% {{PSYCHOSIS}}
     - \-22.5% {{STUN}}
     - \-90% {{CHEMICAL_WITHDRAWAL}}

  - type: application_failure
    header: "Application Failure:"
    addon: vanilla
    order: 3
    text: |
     - \+50% {{HYPERACTIVITY}}
     - \+30% {{VANILLA_ORGAN_DAMAGE}}
     - \+30% {{NEUROTRAUMA}}
     - \+30% {{CHEMICAL_ADDICTION}}
     - \+45% {{PSYCHOSIS}}
     - \-22.5% {{STUN}}
     - \-90% {{CHEMICAL_WITHDRAWAL}}

     {{HYPERACTIVITY}} occurs instantly, while the other effects occur over 30 seconds.

# ------------------------------------------ NT PHARMACY INGREDIENT -------------------------------------------

  - type: description
    header: "Description:"
    addon: pharmacy
    order: 1
    text: |
      #### - Type: "Active Ingredient"
      #### - Skill Required: {{MEDICAL}} 35
      <br>
      An active pill ingredient made from {{METHAMPHETAMINE}}; has positive effects.

  - type: effects
    header: "Crafting Success:"
    addon: pharmacy
    order: 2
    text: |
      - +35% {{HYPERACTIVITY}} (210/600 max, 0-35% movement speed, 0-30% swimming speed, 0-35% melee attack speed), -1/s
      - +7 Organ damage
      - +7 {{NEUROTRAUMA}}
      - +15 {{PSYCHOSIS}}
      - +7 {{CHEMICAL_ADDICTION}}
      - -45 {{WITHDRAWAL}}

  - type: effects
    header: "Crafting Failure:"
    addon: pharmacy
    order: 3
    text: |
      - +25% {{HYPERACTIVITY}} (150/600 max, 0-35% movement speed, 0-30% swimming speed, 0-35% melee attack speed), -1/s
      - +15 Organ damage
      - +15 {{NEUROTRAUMA}}
      - +22 {{PSYCHOSIS}}
      - +15 {{CHEMICAL_ADDICTION}}
      - -45 {{WITHDRAWAL}}
---