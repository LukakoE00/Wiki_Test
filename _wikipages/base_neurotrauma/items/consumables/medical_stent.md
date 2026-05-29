---
layout: contentpage
title: Medical Stent
category: items
subcategory: consumables
permalink: /items/consumables/medical_stent
image: /images/svg/anybodypart.svg
inline_image: /images/base_neurotrauma/items/consumables/medical_stent.png

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

     The fourth step in {{AORTIC_RUPTURE_SURGERY}}. The stent will **not** work if you have not used the {{ENDOVASCULAR_BALLOON}} beforehand. Using the medical stent will cure {{AORTIC_RUPTURE}}, and also remove the Endovascular Balloon from the patient.

---