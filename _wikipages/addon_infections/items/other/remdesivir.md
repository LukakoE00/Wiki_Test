---
layout: contentpage
title: Remdesivir
category: items
addon: infections
subcategory: consumables
permalink: /items/nt_infections/remdesivir/
inline_image: /images/addon_infections/items/remdesivir.png

infobox:
  - title: Labels
    sections:
      - items:
          - Item
          - Infections Expansion

  - title: Statistics
    sections:
      - items:
          - "Skill Required: {{MEDICAL}} 40"
          - "Maximum inventory stack: 8"

  - title: Crafting
    sections:
      - header: "Medical Fabricator Requirements (Output: 2x)"
        items:
            - "{{MEDICAL}} 40"
            - "{{CARBON}} (1x)"
            - "{{CYANIDE}} (1x)"

      - header: "Deconstructor Yield"
        items:
            - "Has no deconstructor outputs."

  - title: Store
    sections:
      - items:
          - "Base Price: 60 Marks"
          - "Buyable at Merchant: Medical"

blocks:
  - type: description
    header: "Description:"
    order: 1
    text: |
     An antiviral drug used to treat {{EUROPAN_COUGH}}.

     **Effective Against:**
     - {{EUROPAN_COUGH}} (90% effective)

  - type: application_success
    header: "Application Success:"
    order: 2
    text: |
     - \+60% Remdesivir
     - \+15% {{LIVER_DAMAGE}}

  - type: application_failure
    header: "Application Failure:"
    order: 3
    text: |
     - \+5% {{LIVER_DAMAGE}}
---