---
layout: contentpage
title: Culture tube
category: items
addon: infections
subcategory: tools
permalink: /items/nt_infections/culture_tube/
inline_image: /images/addon_infections/items/culture_tube.png

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
            - "{{ELASTIN}} (1x)"
            - "{{STABILOZINE}} (1x)"

      - header: "Deconstructor Yield"
        items:
            - "Has no deconstructor outputs."

  - title: Store
    sections:
      - items:
          - "Base Price: 20 Marks"
          - "Buyable at Merchant: Medical"

blocks:
  - type: description
    header: "Description:"
    order: 1
    text: |
     A sample medium for collecting bacteria. 

     After collecting a sample using the {{SAMPLER_TOOL}}, place the unknown sample inside a {{SAMPLE_ANALYZER}} to get a confirmed sample. Confirmed samples are used to craft items like Vaccines or Weaponized Bacteria. You can duplicate samples with a clean culture tube and a confirmed sample.
---