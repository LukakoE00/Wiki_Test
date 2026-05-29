---
layout: contentpage
title: Unasyn
category: items
addon: infections
subcategory: antibiotics
permalink: /items/nt_infections/unasyn/
inline_image: /images/addon_infections/items/unasyn.png

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
      - header: "Medical Fabricator Requirements (Output: 3x)"
        items:
            - "{{MEDICAL}} 20"
            - "{{SULPHURIC_ACID}} (1x)"
            - "{{BROAD_SPECTRUM_ANTIBIOTICS}} (1x)"

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
     A fixed-dose, aminopenicillin combination antibiotic of ampicillin and beta-lactamase inhibitor sulbactam.

     **Effective Against:**
     - {{STREPTOCOCCAL_INFECTION}} (90% effective)
     - {{STAPHYLOCOCCAL_INFECTION}} (75% effective)
     - {{PROVOBACTER_INFECTION}} (40% effective)
     - {{AEROGANELLA_INFECTION}} (20% effective)

  - type: application_success
    header: "Application Success:"
    order: 2
    text: |
     - \+50% Unasyn
     - \+12.5% {{KIDNEY_DAMAGE}}
     - \+10% {{LIVER_DAMAGE}}
     - \+20% {{METHICILLIN_RESISTANCE_RISK}}

  - type: application_failure
    header: "Application Failure:"
    order: 3
    text: |
     - \+5% {{LIVER_DAMAGE}}
     - \+30% {{METHICILLIN_RESISTANCE_RISK}}
---