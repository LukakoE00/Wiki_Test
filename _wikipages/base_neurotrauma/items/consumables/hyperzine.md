---
layout: contentpage
title: Hyperzine
category: items
subcategory: consumables
permalink: /items/consumables/hyperzine
image: /images/svg/anybodypart.svg
inline_image: /images/base_neurotrauma/items/consumables/hyperzine.png

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
          - "Skill Required: {{MEDICAL}} 50"
          - "Maximum inventory stack: 8"

  - title: Crafting
    sections:
      - header: "Medical Fabricator Requirements (Output: 1x)"
        items:
            - "{{MEDICAL}} 40"
            - "{{METHAMPHETAMINE}} (1x)"
            - "{{ANABOLIC_STEROIDS}} (1x)"

      - header: "Deconstructor Yield"
        items:
            - "{{ANABOLIC_STEROIDS}} (1x)"

  - title: Store
    sections:
      - items:
          - "Base Price: 450 Marks"
          - "Buyable at Merchant: Research, Military"

blocks:
  - type: description
    header: "Description:"
    addon: vanilla
    order: 1
    text: |
     A powerful stimulant.

  - type: application_success
    header: "Application Success:"
    addon: vanilla
    order: 2
    text: |
     - \-12% {{INTERNAL_DAMAGE}}
     - \+18% {{CHEMICAL_ADDICTION}}
     - \+18% {{NEUROTRAUMA}}
     - \+15% {{PSYCHOSIS}}
     - \+400% {{HYPERACTIVITY}}
     - \+400% {{VIGOR}}
     - \-54% {{STUN}}
     - \-90% {{CHEMICAL_WITHDRAWAL}}
     
     <br>
     {{HYPERACTIVITY}} and Vigor are applied instantly, while the other effects are applied over a 60 second duration.

# ------------------------------------------ NT PHARMACY INGREDIENT -------------------------------------------

  - type: description
    header: "Description:"
    addon: pharmacy
    order: 1
    text: |
      #### - Type: "Active Ingredient"
      #### - Skill Required: {{MEDICAL}} 50
      <br>
      An active pill ingredient made from {{HYPERZINE}}; has positive effects.

  - type: effects
    header: "Crafting Success:"
    addon: pharmacy
    order: 2
    text: |
      - +33% {{HYPERACTIVITY}} (200/600 max, 0-35% movement speed, 0-30% swimming speed, 0-35% melee attack speed), -1/s
      - +33% {{VIGOR}} (200/600 max, 0-50% damage resistance, 0-35% melee damage), -1/s
      - +5 Organ damage
      - +5 {{NEUROTRAUMA}}
      - +15 {{PSYCHOSIS}}
      - +10 {{CHEMICAL_ADDICTION}}
      - -45 {{WITHDRAWAL}}

  - type: effects
    header: "Crafting Failure:"
    addon: pharmacy
    order: 3
    text: |
      - +33% {{HYPERACTIVITY}} (200/600 max, 0-35% movement speed, 0-30% swimming speed, 0-35% melee attack speed), -1/s
      - +33% {{VIGOR}} (200/600 max, 0-50% damage resistance, 0-35% melee damage), -1/s
      - +10 Organ damage
      - +10 {{NEUROTRAUMA}}
      - +30 {{PSYCHOSIS}}
      - +10 {{CHEMICAL_ADDICTION}}
      - -45 {{WITHDRAWAL}}
---