---
layout: contentpage
title: Primaxin
category: items
addon: infections
subcategory: antibiotics
permalink: /items/nt_infections/primaxin/
inline_image: /images/addon_infections/items/primaxin.png

infobox:
  - title: Labels
    sections:
      - items:
          - Item
          - Infections Expansion

  - title: Statistics
    sections:
      - items:
          - "Skill Required: {{MEDICAL}} 50"
          - "Maximum inventory stack: 8"

  - title: Crafting
    sections:
      - header: "Medical Fabricator Requirements (Output: 2x)"
        items:
            - "{{MEDICAL}} 40"
            - "{{CARBON}} (1x)"
            - "{{SODIUM}} (1x)"
            - "{{SLIME_BACTERIA}} (1x)"

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
     A carbapenem class combination antibiotic of imipenem and cilastatin. Prevents degradation of the antibiotic in the body.

     **Effective Against:**
     - {{PSEUDOMONAS_INFECTION}} (80% effective)
     - {{STREPTOCOCCAL_INFECTION}} (80% effective)
     - {{STAPHYLOCOCCAL_INFECTION}} (75% effective)
     - {{PROVOBACTER_INFECTION}} (66.7% effective)
     - {{AEROGANELLA_INFECTION}} (50% effective)

  - type: application_success
    header: "Application Success:"
    order: 2
    text: |
     - \+50% Primaxin
     - \+17.5% {{KIDNEY_DAMAGE}}
     - \+12.5% {{LIVER_DAMAGE}}
     - \+20% {{METHICILLIN_RESISTANCE_RISK}}

  - type: application_failure
    header: "Application Failure:"
    order: 3
    text: |
     - \+5% {{LIVER_DAMAGE}}
     - \+30% {{METHICILLIN_RESISTANCE_RISK}}
---