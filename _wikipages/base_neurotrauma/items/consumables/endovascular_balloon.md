---
layout: contentpage
title: Endovascular Balloon
category: items
subcategory: consumables
permalink: /items/consumables/endovascular_balloon
image: /images/svg/anybodypart.svg
inline_image: /images/base_neurotrauma/items/consumables/endovascular_balloon.png

infobox:
  - title: Labels
    sections:
      - items:
          - Item
          - Surgery
          - Niche
          - Toggleable

  - title: Statistics
    sections:
      - items:
          - "Skill Required: None"
          - "Maximum inventory stack: 4"

  - title: Crafting
    sections:
      - header: "Medical Fabricator Requirements (Output: 2x)"
        items:
            - "{{MEDICAL}} 25"
            - "{{ORGANIC_FIBER}} (1x)"
            - "{{PLASTIC}} (1x)"
            - "{{RUBBER}} (1x)"

      - header: "Deconstructor Yield"
        items:
            - "Has no deconstructor outputs."

  - title: Store
    sections:
      - items:
          - "Base Price: 80 Marks"
          - "Buyable at Merchant: Medical"

blocks:
  - type: description
    header: "Description:"
    order: 1
    text: |
     #### This item is only usable in-game if 'Hardmode Aortic Rupture' is enabled in the {{CONFIGURATION_MENU}}.

     The third step in {{AORTIC_RUPTURE_SURGERY}}. The balloon will **not** work without 100% {{SURGERY_INCISION}}. Using the balloon will block the aorta, which will prevent {{BLOOD_LOSS}} caused by {{AORTIC_RUPTURE}}, and will treat regular bleeding, but will also cause {{GANGRENE}}.

---