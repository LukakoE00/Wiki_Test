---
layout: contentpage
title: Zinc supplement
category: items
addon: infections
subcategory: consumables
permalink: /items/nt_infections/zinc_supplement/
inline_image: /images/addon_infections/items/zinc_supplement.png

infobox:
  - title: Labels
    sections:
      - items:
          - Item
          - Infections Expansion

  - title: Statistics
    sections:
      - items:
          - "Skill Required: {{MEDICAL}} 20"
          - "Maximum inventory stack: 8"

  - title: Crafting
    sections:
      - header: "Medical Fabricator Requirements (Output: 2x)"
        items:
            - "{{MEDICAL}} 20"
            - "{{ZINC}} (1x)"
            - "{{CARBON}} (1x)"

      - header: "Deconstructor Yield"
        items:
            - "Has no deconstructor outputs."

  - title: Store
    sections:
      - items:
          - "Base Price: 30 Marks"
          - "Buyable at Merchant: Medical"

blocks:
  - type: description
    header: "Description:"
    order: 1
    text: |
     A supplement useful for viral infections. Acts as treatment for {{INFLUENZA}} and {{COMMON_COLD}}.

     **Effective Against:**
     - {{COMMON_COLD}} (25% effective)
     - {{INFLUENZA}} (20% effective)

  - type: application_success
    header: "Application Success:"
    order: 2
    text: |
     - \+70% Zinc supplement
     - {{NAUSEA}} (if >80%)
     - {{PSYCHOSIS}} (if >90%)

  - type: application_failure
    header: "Application Failure:"
    order: 3
    text: |
     - \+50% Zinc supplement
     - {{NAUSEA}} (if >80%)
     - {{PSYCHOSIS}} (if >90%)
---