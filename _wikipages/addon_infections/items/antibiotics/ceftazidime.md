---
layout: contentpage
title: Ceftazidime
category: items
addon: infections
subcategory: antibiotics
permalink: /items/nt_infections/ceftazidime/
inline_image: /images/addon_infections/items/ceftazidime.png

infobox:
  - title: Labels
    sections:
      - items:
          - Item
          - Infections Expansion

  - title: Statistics
    sections:
      - items:
          - "Skill Required: Medical 30"
          - "Maximum inventory stack: 8"

  - title: Crafting
    sections:
      - header: "Medical Fabricator Requirements (Output: 3x)"
        items:
            - "{{MEDICAL}} 30"
            - "{{CARBON}} (1x)"
            - "{{SLIME_BACTERIA}} (1x)"

      - header: "Deconstructor Yield"
        items:
            - "Has no deconstructor outputs."

  - title: Store
    sections:
      - items:
          - "Base Price: 65 Marks"
          - "Buyable at Merchant: Medical"

blocks:
  - type: description
    header: "Description:"
    order: 1
    text: |
     A third-generation cephalosporin antibiotic primarily useful against gram-negative bacterial strains.

     **Effective Against:**
     - {{PSEUDOMONAS_INFECTION}} (87.5% effective)
     - {{PROVOBACTER_INFECTION}} (80% effective)
     - {{AEROGANELLA_INFECTION}} (75% effective)
     - {{STREPTOCOCCAL_INFECTION}} (20% effective)

  - type: application_success
    header: "Application Success:"
    order: 2
    text: |
     - \+50% Ceftazidime
     - \+15% {{KIDNEY_DAMAGE}}
     - \+7.5% {{LIVER_DAMAGE}}

  - type: application_failure
    header: "Application Failure:"
    order: 3
    text: |
     - \+5% {{KIDNEY_DAMAGE}}
---