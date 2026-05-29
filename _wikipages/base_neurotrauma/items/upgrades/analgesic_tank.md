---
layout: contentpage
title: Analgesic Tank
category: items
subcategory: upgrades
permalink: /items/upgrades/analgesic_tank
image: /images/svg/anybodypart.svg
inline_image: /images/base_neurotrauma/items/upgrades/analgesic_tank.png

infobox:
  - title: Labels
    sections:
      - items:
          - Item
          - Important

  - title: Statistics
    sections:
      - items:
          - "Skill Required: None"
          - "Maximum inventory stack: 1"

  - title: Crafting
    sections:
      - header: "Medical Fabricator Requirements (Output: 1x)"
        items:
            - "{{MEDICAL}} 40"
            - "{{MECHANICAL}} 20"
            - "{{ALUMINIUM}} (2x)"
            - "{{MORPHINE}} (2x)"

      - header: "Deconstructor Yield"
        items:
            - "{{ALUMINIUM}} (1x)"

  - title: Store
    sections:
      - items:
          - "Base Price: 270 Marks"
          - "Buyable at Outposts: Habitation, Colony"
          - "Buyable at Merchant: Medical"

blocks:
  - type: description
    header: "Description:"
    order: 1
    text: |
     A tank of analgesics which can be used in the {{SURGERY_TABLE}} or {{AMBUBAG}}. It can be bought or crafted, and refilled. It can receive quality, increasing its maximum condition by 5% per level.

     When used in a Surgery Table, provides up to 14% {{ANALGESIA}} to the patient **laying** on the table, and its condition reduces by 0.7% per second.

     When used in an Ambubag, condition reduces by 25%, and provides:
     - \+56% {{ANALGESIA}}
     - \+40%{{OPIATE_ADDICTION}}
     - \+30% {{OPIATE_OVERDOSE}}
     - \-75% {{WITHDRAWAL}}

     #### If the patient is more than 30% {{DRUNK}}, instead provides:
     - \+106% {{ANALGESIA}}
     - \+40%{{OPIATE_ADDICTION}}
     - \+60% {{OPIATE_OVERDOSE}}
     - \-75% {{WITHDRAWAL}}
---