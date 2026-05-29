---
layout: contentpage
title: Viral transport medium
category: items
addon: infections
subcategory: tools
permalink: /items/nt_infections/viral_transport_medium/
inline_image: /images/addon_infections/items/viral_transport_medium.png

infobox:
  - title: Labels
    sections:
      - items:
          - Item
          - Infections Expansion

  - title: Statistics
    sections:
      - items:
          - "Maximum inventory stack: 8"

  - title: Crafting
    sections:
      - header: "Medical Fabricator Requirements (Output: 4x)"
        items:
            - "{{MEDICAL}} 20"
            - "{{PLASTIC}} (1x)"
            - "{{SALINE}} (1x)"
            - "{{PHOSPHORUS}} (1x)"
            - "{{ALIEN_BLOOD}} (1x)"

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
     A sample medium for collecting viruses. Used in conjunction with the {{SAMPLER_TOOL}}.

     Place inside of a {{SAMPLE_ANALYZER}} to be analyzed immediately. Unlike bacterial samples, these can be analyzed without incubation. Confirmed viral samples can be used to craft viral {{VACCINE}} variants.
---