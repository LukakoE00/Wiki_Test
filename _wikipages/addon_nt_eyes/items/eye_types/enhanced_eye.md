---
layout: contentpage
title: Enhanced Eye
addon: nt_eyes
subcategory: eye_types
permalink: /items/nt_eyes/enhanced_eye/
inline_image: /images/addon_nt_eyes/items/enhanced_eye.png
infobox:
  - title: Labels
    sections:
      - items:
          - Item
          - Eyes Expansion

  - title: Applicable Lenses
    sections:
      - items:
          - "{{ELECTRICAL_LENSES}}"
          - "{{THERMAL_LENSES}}"
          - "{{MEDICAL_LENSES}}"
          - "{{NIGHT_VISION_LENSES}}"

  - title: Crafting
    sections:
      - header: "Medical Fabricator Requirements (Output 1x)"
        items:
            - "{{MEDICAL}} 50"
            - "{{MECHANICAL}} 35"
            - "{{HUMAN_EYE}} (1x)"
            - "{{FPGA_CIRCUIT}} (1x)"
            - "{{PLASTIC}} (1x)"

      - header: "Deconstructor Yield"
        items:
            - "{{CARBON}} (1x)"
            - "{{SILICON}} (1x)"

  - title: Store
    sections:
      - items:
          - "Base Price: 500 Marks"
          - "Minimum level difficulty: 20%"
          - "Buyable at Outposts: Research"
          - "Buyable at Merchant: Medical"


blocks:
  - type: description
    header: "Description:"
    order: 1
    text: |
     - Human eyes enhanced with electrical circuits and plastic.
     
     - Cyber lenses can be applied with {{LENS_APPLICATION_SURGERY}}.

  - type: effects
    header: "Effects:"
    order: 2
    text: |
     - Vision.
     
     - Cyber lens usage.
     
     - Better damage resistance.
---
