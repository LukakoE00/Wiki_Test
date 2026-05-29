---
layout: contentpage
title: Antiseptic Sprayer
category: items
subcategory: tools
permalink: /items/tools/antiseptic_sprayer
image: /images/svg/anybodypart.svg
inline_image: /images/base_neurotrauma/items/tools/antiseptic_sprayer.png

infobox:
  - title: Labels
    sections:
      - items:
          - Item
          - First Aid
          - Niche
          - Toggleable

  - title: Statistics
    sections:
      - items:
          - "Skill Required: {{MEDICAL}} 40"
          - "Maximum inventory stack: 1"

  - title: Crafting
    sections:
      - header: "Fabricator Requirements (Output: 1x)"
        items:
            - "{{PLASTIC}} (1x)"

      - header: "Deconstructor Yield"
        items:
            - "Has no deconstructor outputs."

  - title: Store
    sections:
      - items:
          - "Base Price: 75 Marks"
          - "Buyable at Merchant: Medical"

blocks:
  - type: description
    header: "Description:"
    order: 1
    text: |
     #### This item is only usable in-game if enabled via the {{CONFIGURATION_MENU}} under 'Item Availability'.

     A sprayer which sprays {{ANTISEPTIC}} onto {{INFECTED_WOUNDS}}. Using the antiseptic sprayer with antiseptic in it will treat 100% infected wounds, give 20% {{OINTMENTED}} and use up 10% of the antiseptic.

---