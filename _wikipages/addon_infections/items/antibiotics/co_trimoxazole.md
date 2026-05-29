---
layout: contentpage
title: Co-trimoxazole
category: items
addon: infections
subcategory: antibiotics
permalink: /items/nt_infections/co_trimoxazole/
inline_image: /images/addon_infections/items/co_trimoxazole.png

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
      - header: "Medical Fabricator Requirements (Output: 3x)"
        items:
            - "{{MEDICAL}} 40"
            - "{{CARBON}} (1x)"
            - "{{SODIUM}} (1x)"
            - "{{SULPHURIC_ACID}} (1x)"

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
     A fixed-dose, combination drug of trimethoprim and sulfamethoxazole.

     **Effective Against:**
     - {{STAPHYLOCOCCAL_INFECTION}} (80% effective)
     - {{MRSA_INFECTION}} (80% effective)
     - {{STREPTOCOCCAL_INFECTION}} (66.7% effective)
     - {{AEROGANELLA_INFECTION}} (60% effective)

  - type: application_success
    header: "Application Success:"
    order: 2
    text: |
     - \+50% Co-trimoxazole
     - \+17.5% {{KIDNEY_DAMAGE}}
     - \+10% {{LIVER_DAMAGE}}

  - type: application_failure
    header: "Application Failure:"
    order: 3
    text: |
     - \+5% {{KIDNEY_DAMAGE}}
---