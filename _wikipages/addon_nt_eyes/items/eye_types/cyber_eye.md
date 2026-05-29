---
layout: contentpage
title: Cyber Eye
addon: nt_eyes
subcategory: eye_types
permalink: /items/nt_eyes/cyber_eye/
inline_image: /images/addon_nt_eyes/items/cyber_eye.png
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
            - "{{MEDICAL}} 80"
            - "{{MECHANICAL}} 45"
            - "{{PLASTIC}} (3x)"
            - "{{FPGA_CIRCUIT}} (2x)"
            - "{{FULGURIUM_CHUNK}} (2x)"
            - "{{TITANIUM_ALUMINIUM_ALLOY}} (1x)"

      - header: "Deconstructor Yield"
        items:
            - "{{IRON}} (1x)"
            - "{{COPPER}} (1x)"
            - "{{PLASTIC}} (1x)"

  - title: Store
    sections:
      - items:
          - "Base Price: 1000 Marks"
          - "Minimum level difficulty: 30%"
          - "Buyable at Outposts: Research"

blocks:
  - type: description
    header: "Description:"
    order: 1
    text: |
     - Costly synthetic eyes. Can’t be damaged by bodily afflictions, can’t be naturally healed.
     
     - Can be repaired by Cyber Eye Repair Surgery
     
     - Resistant to water pressure.
     
     - Does not need to be refrigerated.
     
     - Cyber lenses can be applied with {{LENS_APPLICATION_SURGERY}}.

  - type: effects
    header: "Effects:"
    order: 2
    text: |
     - Better vision.
     
     - Lens application.
     
     - High damage resistance.
---
