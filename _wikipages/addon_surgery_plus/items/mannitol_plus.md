---
layout: contentpage
title: Mannitol Plus
addon: surgery_plus
subcategory: items
permalink: /items/surgery_plus/mannitol_plus
# image: /images/svg/anybodypart.svg
inline_image: /images/addon_surgery_plus/items/mannitol_plus.png

addons:
  - id: surgery_plus
    label: Surgery Plus

  - id: pharmacy
    label: NT Pharmacy Ingredient

infobox:
  - title: Labels
    sections:
      - items:
          - Item
          - Niche
          - Surgery Plus Expansion

  - title: Statistics
    sections:
      - items:
          - "Skill Required: {{MEDICAL}} 70"
          - "Maximum inventory stack: 8"

  - title: Crafting
    sections:
      - header: "Medical Fabricator Requirements"
        items:
            - "Mannitol Maniac Talent (Surgeon)"
            - "{{MEDICAL}} 80"
            - "{{SURGERY}} 80"
            - "{{MANNITOL}} (1x)"
            - "{{ADRENALINE}} (1x)"
            - "{{LIQUID_OXYGENITE}} (1x)"
            - "{{STABILOZINE}} (1x)"

      - header: "Deconstructor Yield"
        items:
            - "{{MANNITOL}} (1x)"
            - "{{ADRENALINE}} (1x)"

  - title: Store
    sections:
      - items:
          - "Cannot be bought"

blocks:
  - type: description
    header: "Description:"
    addon: surgery_plus
    order: 1
    text: |
     Mannitol Plus is a talent item, meaning it requires a talent to craft. Upon being administered, it will treat 30% {{NEUROTRAUMA}} over the course of 10 seconds even if the patient is unstable and apply the {{MANNITOL}} affliction without causing organ damage.

# ------------------------------------------ NT PHARMACY INGREDIENT -------------------------------------------

  - type: description
    header: "Description:"
    addon: pharmacy
    order: 1
    text: |
      #### - Type: "Active Ingredient"
      #### - Skill Required: {{MEDICAL}} 60
      <br>
      An active pill ingredient made from {{MANNITOL_PLUS}}; has positive effects. Directly cures a small amount of {{NEUROTRAUMA}} and applies {{MANNITOL}} affliction.

  - type: effects
    header: "Crafting Success:"
    addon: pharmacy
    order: 2
    text: |
      - +30% {{MANNITOL}} (60% strength of a regular Mannitol)
      - -10% {{NEUROTRAUMA}}

  - type: effects
    header: "Crafting Failure:"
    addon: pharmacy
    order: 3
    text: |
      - +15% {{MANNITOL}} (30% strength of a regular Mannitol)
      - -5% {{NEUROTRAUMA}}
---