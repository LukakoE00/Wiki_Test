---
layout: contentpage
title: Opium
category: items
subcategory: consumables
permalink: /items/consumables/opium
image: /images/svg/anybodypart.svg
inline_image: /images/base_neurotrauma/items/consumables/opium.png

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
          - Very Important

  - title: Statistics
    sections:
      - items:
          - "Skill Required: {{MEDICAL}} 40"
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
          - "Base Price: 40 Marks"
          - "Buyable at Outposts: Habitation, Colony, Research"
          - "Available in Vending Machines"

blocks:
  - type: description
    header: "Description:"
    addon: vanilla
    order: 1
    text: |
     A weak opiate used to induce {{ANALGESIA}}. Obtained by deconstructing [Aquatic Poppies](https://barotraumagame.com/wiki/Aquatic_Poppy).

  - type: application_success
    header: "Application Success:"
    addon: vanilla
    order: 2
    text: |
     - \+20% {{ANALGESIA}}
     - \+5% {{OPIATE_ADDICTION}}
     - \+8.75% {{OPIATE_OVERDOSE}}
     - \-15% {{OPIATE_WITHDRAWAL}}

     <br>
     #### While >30% drunk changes to:
     - \+40% {{ANALGESIA}}
     - \+5% {{OPIATE_ADDICTION}}
     - \+18.75% {{OPIATE_OVERDOSE}}
     - \-15% {{OPIATE_WITHDRAWAL}}

  - type: application_failure
    header: "Application Failure:"
    addon: vanilla
    order: 3
    text: |
     - \+10% {{ANALGESIA}}
     - \+20% {{OPIATE_ADDICTION}}
     - \+15% {{OPIATE_OVERDOSE}}
     - \-15% {{OPIATE_WITHDRAWAL}}

     <br>
     #### While >30% drunk changes to:
     - \+20% {{ANALGESIA}}
     - \+20% {{OPIATE_ADDICTION}}
     - \+30% {{OPIATE_OVERDOSE}}
     - \-15% {{OPIATE_WITHDRAWAL}}

# ------------------------------------------ NT PHARMACY INGREDIENT -------------------------------------------

  - type: description
    header: "Description:"
    addon: pharmacy
    order: 1
    text: |
      #### - Type: "Active Ingredient"
      #### - Skill Required: {{MEDICAL}} 15
      <br>
      An active pill ingredient made from {{OPIUM}}; has positive effects.

  - type: effects
    header: "Crafting Success:"
    addon: pharmacy
    order: 2
    text: |
      - +10% {{ANALGESIA}}
      - +2.5% {{OPIATE_ADDICTION}}
      - +4.37% {{OPIATE_OVERDOSE}}
      - -7.5% {{WITHDRAWAL}}

  - type: effects
    header: "Crafting Failure:"
    addon: pharmacy
    order: 3
    text: |
      - +5% {{ANALGESIA}}
      - +10% {{OPIATE_ADDICTION}}
      - +7.5% {{OPIATE_OVERDOSE}}
      - -7.5% {{WITHDRAWAL}}
---