---
layout: contentpage
title: Health Scanner
category: items
subcategory: tools
permalink: /items/tools/health_scanner
image: /images/svg/anybodypart.svg
inline_image: /images/base_neurotrauma/items/tools/health_scanner.png

infobox:
  - title: Labels
    sections:
      - items:
          - Item
          - Essential

  - title: Statistics
    sections:
      - items:
          - "Skill Required: {{MEDICAL}} 40"
          - "Maximum inventory stack: 1"

  - title: Crafting
    sections:
      - header: "Fabricator Requirements (Output: 1x)"
        items:
            - "{{MEDICAL}} 40"
            - "{{FPGA_CIRCUIT}} (1x)"
            - "{{ALUMINIUM}} (1x)"

      - header: "Deconstructor Yield"
        items:
            - "{{ALUMINIUM}} (1x)"

  - title: Store
    sections:
      - items:
          - "Base Price: 150 Marks"
          - "Buyable at Outpost: Colony"
          - "Buyable at Merchant: Research, Military, Medical"

blocks:
  - type: description
    header: "Description:"
    order: 1
    text: |
     An item which is extremely important for diagnosis. Upon use and charged with batteries, you will get the readout of all afflictions visible to the health scanner, and the patient you're scanning will gain 0.5% {{RADIATION_SICKNESS}} per second, and you (the person scanning) will gain 0.3% per second. Additionally, one can scan themselves and others by using the health scanner in the interface like a treatment, as you would a bandage. This gives 1% radiation sickness, and also allows you to scan individual limbs to find things such as {{FOREIGN_BODIES}}.

---