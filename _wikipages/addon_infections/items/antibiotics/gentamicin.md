---
layout: contentpage
title: Gentamicin
category: items
addon: infections
subcategory: antibiotics
permalink: /items/nt_infections/gentamicin/
inline_image: /images/addon_infections/items/gentamicin.png

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
      - header: "Medical Fabricator Requirements (Output: 3x)"
        items:
            - "{{MEDICAL}} 40"
            - "{{CARBON}} (1x)"
            - "{{BROAD_SPECTRUM_ANTIBIOTICS}} (1x)"
            - "{{SEA_YEAST_SHROOM}} (1x)"

      - header: "Deconstructor Yield"
        items:
            - "Has no deconstructor outputs."

  - title: Store
    sections:
      - items:
          - "Base Price: 90 Marks"
          - "Buyable at Merchant: Medical"

blocks:
  - type: description
    header: "Description:"
    order: 1
    text: |
     An aminoglycoside antibiotic that is very effective against gram-negative bacteria. Efficacy is offset by its high kidney toxicity.

     **Effective Against:**
     - {{PSEUDOMONAS_INFECTION}} (95% effective)
     - {{PROVOBACTER_INFECTION}} (95% effective)
     - {{AEROGANELLA_INFECTION}} (95% effective)
     - {{STAPHYLOCOCCAL_INFECTION}} (10% effective)
     - {{MRSA_INFECTION}} (10% effective)

  - type: application_success
    header: "Application Success:"
    order: 2
    text: |
     - \+50% Gentamicin
     - \+25% {{KIDNEY_DAMAGE}}
     - \+5% {{LIVER_DAMAGE}}

  - type: application_failure
    header: "Application Failure:"
    order: 3
    text: |
     - \+5% {{KIDNEY_DAMAGE}}
---