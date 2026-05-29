---
layout: contentpage
title: Hydrocortisone
category: items
addon: infections
subcategory: consumables
permalink: /items/nt_infections/hydrocortisone/
inline_image: /images/addon_infections/items/hydrocortisone.png

infobox:
  - title: Labels
    sections:
      - items:
          - Item
          - Infections Expansion

  - title: Statistics
    sections:
      - items:
          - "Skill Required: {{MEDICAL}} 30"
          - "Maximum inventory stack: 8"

  - title: Crafting
    sections:
      - header: "Medical Fabricator Requirements (Output: 2x)"
        items:
            - "{{MEDICAL}} 20"
            - "{{ADRENALINE_GLAND}} (1x)"
            - "{{CARBON}} (1x)"

      - header: "Deconstructor Yield"
        items:
            - "Has no deconstructor outputs."

  - title: Store
    sections:
      - items:
          - "Base Price: 40 Marks"
          - "Buyable at Merchant: Medical"

blocks:
  - type: description
    header: "Description:"
    order: 1
    text: |
     A corticosteroid used to suppress the immune system. Can be used to reduce Sepsis gain. 

  - type: application_success
    header: "Application Success:"
    order: 2
    text: |
     - \+60% Corticosteroids
     - Lowers {{IMMUNITY}} down to 80%

  - type: application_failure
    header: "Application Failure:"
    order: 3
    text: |
     - \+40% Corticosteroids
     - Lowers {{IMMUNITY}} down to 80%
---