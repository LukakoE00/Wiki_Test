---
layout: contentpage
title: Drainage
category: items
subcategory: consumables
permalink: /items/consumables/drainage
image: /images/svg/anybodypart.svg
inline_image: /images/base_neurotrauma/items/consumables/drainage.png

infobox:
  - title: Labels
    sections:
      - items:
          - Item
          - Surgery
          - Essential

  - title: Statistics
    sections:
      - items:
          - "Skill Required: {{MEDICAL}} 30"
          - "Maximum inventory stack: 4"

  - title: Crafting
    sections:
      - header: "Medical Fabricator Requirements (Output: 1x)"
        items:
            - "{{MEDICAL}} 25"
            - "{{PLASTIC}} (1x)"

      - header: "Deconstructor Yield"
        items:
            - "Has no deconstructor outputs."

  - title: Store
    sections:
      - items:
          - "Base Price: 70 Marks"
          - "Buyable at Merchant: Medical"

blocks:
  - type: description
    header: "Description:"
    order: 1
    text: |
     Drainage is a one time use item that is used to treat {{PNEUMOTHORAX}} and {{CARDIAC_TAMPONADE}}. It is used after {{RETRACTED_SKIN}}. If the patient does not have pneumothorax or tamponade, the drainage will do nothing and will not be consumed.

---