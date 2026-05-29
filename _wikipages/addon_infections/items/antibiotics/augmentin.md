---
layout: contentpage
title: Augmentin
category: items
addon: infections
subcategory: antibiotics
permalink: /items/nt_infections/augmentin/
inline_image: /images/addon_infections/items/augmentin.png

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
            - "{{MEDICAL}} 30"
            - "{{POTASSIUM}} (1x)"
            - "{{BROAD_SPECTRUM_ANTIBIOTICS}} (1x)"

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
     An aminopenicillin combination drug of amoxicillin and clavulanic acid. Effective against most beta-lactamase producing bacteria.

     **Effective Against:**
     - {{STREPTOCOCCAL_INFECTION}} (93.8% effective)
     - {{STAPHYLOCOCCAL_INFECTION}} (90% effective)
     - {{PROVOBACTER_INFECTION}} (60% effective)
     - {{AEROGANELLA_INFECTION}} (25% effective)

  - type: application_success
    header: "Application Success:"
    order: 2
    text: |
     - \+50% Augmentin
     - \+15% {{KIDNEY_DAMAGE}}
     - \+10% {{LIVER_DAMAGE}}
     - \+20% {{METHICILLIN_RESISTANCE_RISK}}

  - type: application_failure
    header: "Application Failure:"
    order: 3
    text: |
     - \+5% {{LIVER_DAMAGE}}
     - \+30% {{METHICILLIN_RESISTANCE_RISK}}
---