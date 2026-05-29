---
layout: contentpage
title: Dextromethorphan
category: items
addon: infections
subcategory: consumables
permalink: /items/nt_infections/dextromethorphan/
inline_image: /images/addon_infections/items/dextromethorphan.png

infobox:
  - title: Labels
    sections:
      - items:
          - Item
          - Infections Expansion

  - title: Statistics
    sections:
      - items:
          - "Skill Required: {{MEDICAL}} 10"
          - "Maximum inventory stack: 8"

  - title: Crafting
    sections:
      - header: "Medical Fabricator Requirements (Output: 2x)"
        items:
            - "{{MEDICAL}} 20"
            - "{{CARBON}} (1x)"
            - "{{OPIUM}} (1x)"

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
     An antitussive used to suppress a cough. Reduces viral infection symptoms, slowdown, and chance to spread.

  - type: application_success
    header: "Application Success:"
    order: 2
    text: |
     - \+80% Dextromethorphan
     - {{NAUSEA}} (if >80%)
     - {{PSYCHOSIS}} (if >90%)

  - type: application_failure
    header: "Application Failure:"
    order: 3
    text: |
     - \+60% Dextromethorphan
     - {{NAUSEA}} (if >80%)
     - {{PSYCHOSIS}} (if >90%)
---