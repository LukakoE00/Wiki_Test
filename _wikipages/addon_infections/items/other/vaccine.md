---
layout: contentpage
title: Vaccines
category: items
addon: infections
subcategory: consumables
permalink: /items/nt_infections/vaccines/
inline_image: /images/addon_infections/items/vaccine.png

infobox:
  - title: Labels
    sections:
      - items:
          - Item
          - Infections Expansion

  - title: Statistics
    sections:
      - items:
          - "Skill Required: Medical 50-60"
          - "Maximum inventory stack: 8"

  - title: Crafting
    sections:
      - header: "Medical Fabricator Requirements (Output: 2x)"
        items:
            - "{{MEDICAL}} 50 or 60"
            - "Confirmed Sample (1x or 3x)"
            - "{{ANAPARALYZANT}} or {{TONIC_LIQUID}} (1x)"
            - "{{SALINE}} (1x)"

  - title: Store
    sections:
      - items:
          - "Base Price: 250-350 Marks"
          - "Buyable at Merchant: Medical"

blocks:
  - type: description
    header: "Description:"
    order: 1
    text: |
     A vaccine against a certain pathogen and strain. Staph vaccines work for both {{STAPHYLOCOCCAL_INFECTION}} and {{MRSA_INFECTION}}. Works by decreasing the severity of an infection by up to 50%.

     <br>
     Will last roughly ~5.7 hours.
---