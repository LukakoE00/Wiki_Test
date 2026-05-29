---
layout: contentpage
title: Adrenaline
category: items
subcategory: consumables
permalink: /items/consumables/adrenaline
image: /images/svg/anybodypart.svg
inline_image: /images/base_neurotrauma/items/consumables/adrenaline.png

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
      - header: "Medical Fabricator Requirements"
        items:
            - "Cannot be fabricated."

      - header: "Deconstructor Yield"
        items:
            - "Has no deconstructor outputs."

  - title: Store
    sections:
      - items:
          - "Base Price: 60 Marks"
          - "Buyable at Outposts: Research, Military"
          - "Buyable at Merchant: Medical"

blocks:
  - type: description
    header: "Description:"
    addon: vanilla
    order: 1
    text: |
     Adrenaline is mainly used in the treatment of {{CARDIAC_ARREST}}, but has numerous other effects. Each adrenaline lasts 55 seconds.

  - type: effects
    header: "Effects:"
    addon: vanilla
    order: 2
    text: |
     - +8% [Adrenaline Rush](https://barotraumagame.com/wiki/Adrenaline_Rush) (does not keep patient conscious below 0 vitality)
     - +30% Blood Pressure
     - {{ANALGESIA}}, up to 4.5%
     - {{INCREASED_HEARTRATE}}
     - {{HYPERVENTILATION}}
     - +20% Melee Damage
     - Halves {{FIBRILLATION}} gain speed
     - Halves the potency of slowing effects (such as from {{PLASTER_CAST}})
     - Prevents {{DISLOCATIONS}} from locking hands or slowing the character
     - Prevents {{FRACTURES}} from locking hands or slowing the character. Causes bleeding if the character uses weapons held in the respective fractured arms. Causes bleeding over time if the character has fractured legs.

# ------------------------------------------ NT PHARMACY INGREDIENT -------------------------------------------

  - type: description
    header: "Description:"
    addon: pharmacy
    order: 1
    text: |
      #### - Type: "Active Ingredient"
      #### - Skill Required: {{MEDICAL}} 0
      <br>
      An active pill ingredient; has positive effects.

  - type: effects
    header: "Crafting Success:"
    addon: pharmacy
    order: 2
    text: |
      - Slows down onset of {{CARDIAC_ARREST}}
      - Reduces impact of Slowing effects
      - Causes {{HYPERVENTILATION}} and {{INCREASED_HEARTRATE}}
      - Increases Melee damage
---