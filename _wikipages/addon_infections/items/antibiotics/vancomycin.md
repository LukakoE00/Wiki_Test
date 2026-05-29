---
layout: contentpage
title: Vancomycin
category: items
addon: infections
subcategory: antibiotics
permalink: /items/nt_infections/vancomycin/
inline_image: /images/addon_infections/items/vancomycin.png

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
            - "{{SLIME_BACTERIA}} (1x)"

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
     A glycopeptide antibiotic that is very effective against most gram-positive bacteria. It is the primary defense against MRSA.

     **Effective Against:**
     - {{STAPHYLOCOCCAL_INFECTION}} (98% effective)
     - {{MRSA_INFECTION}} (98% effective)
     - {{STREPTOCOCCAL_INFECTION}} (95% effective)
     - {{AEROGANELLA_INFECTION}} (50% effective)

  - type: application_success
    header: "Application Success:"
    order: 2
    text: |
     - \+50% Vancomycin
     - \+20% {{KIDNEY_DAMAGE}}
     - \+5% {{LIVER_DAMAGE}}

  - type: application_failure
    header: "Application Failure:"
    order: 3
    text: |
     - \+5% {{KIDNEY_DAMAGE}}
---