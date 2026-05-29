---
layout: contentpage
title: Sampler tool
category: items
addon: infections
subcategory: tools
permalink: /items/nt_infections/sampler_tool/
inline_image: /images/addon_infections/items/sampler_tool.png

infobox:
  - title: Labels
    sections:
      - items:
          - Item
          - Infections Expansion

  - title: Statistics
    sections:
      - items:
          - "Skill Required: None"
          - "Maximum inventory stack: 1"

  - title: Crafting
    sections:
      - header: "Medical Fabricator Requirements (Output: 1x)"
        items:
            - "{{MEDICAL}} 40"
            - "{{HEMATOLOGY_ANALYZER}} (1x)"
            - "{{FPGA_CIRCUIT}} (1x)"

      - header: "Deconstructor Yield"
        items:
            - "{{PLASTIC}} (1x)"
            - "{{FPGA_CIRCUIT}} (1x)"

  - title: Store
    sections:
      - items:
          - "Base Price: 250 Marks"
          - "Buyable at Merchant: Medical"

blocks:
  - type: description
    header: "Description:"
    order: 1
    text: |
     Used for collecting suspected infected samples and blood work relating to pathogens. It is essential for diagnosing infections.

     Requires a {{CULTURE_TUBE}} for bacterial samples or a {{VIRAL_TRANSPORT_MEDIUM}} for viral samples. Using the tool without a sample loaded will give a reading of bacteria in the blood, which can be used to diagnose the pathogen responsible for {{PNEUMONIA}}.

  - type: usage
    header: "Usage:"
    order: 2
    text: |
     Insert a tube or medium into the tool and use it on a patient's limb in the health interface. The tool follows a specific precedence for collection:
     1. **Pus Sample:** Taken if the limb has {{PURULENT_DRAINAGE}} or an {{ABSCESS}}.
     2. **Tissue Sample:** Taken if the limb has {{RETRACTED_SKIN}}.
     3. **Blood Sample:** Taken if no pus or tissue is available.
---