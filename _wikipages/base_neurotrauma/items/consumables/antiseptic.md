---
layout: contentpage
title: Antiseptic
category: items
subcategory: consumables
permalink: /items/consumables/antiseptic
image: /images/svg/anybodypart.svg
inline_image: /images/base_neurotrauma/items/consumables/antiseptic.png

infobox:
  - title: Labels
    sections:
      - items:
          - Item
          - Niche
          - Toggleable

  - title: Statistics
    sections:
      - items:
          - "Skill Required: None"
          - "Maximum inventory stack: 8"

  - title: Crafting
    sections:
      - header: "Medical Fabricator Requirements (Output: 1x)"
        items:
            - "{{MEDICAL}} 40"
            - "{{CHLORINE}} (1x)"
            - "{{ETHANOL}} (1x)"

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
    order: 1
    text: |
     #### This item is only usable in-game if enabled via the {{CONFIGURATION_MENU}} under 'Item Availability'.

     Antiseptic is an item whose only use is to be loaded into the {{ANTISEPTIC_SPRAYER}}. For each spray of the antiseptic sprayer, 10% condition will be used from the antiseptic.

---