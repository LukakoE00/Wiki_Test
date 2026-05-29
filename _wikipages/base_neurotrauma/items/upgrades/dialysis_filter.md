---
layout: contentpage
title: Dialysis Filter
category: items
subcategory: upgrades
permalink: /items/upgrades/dialysis_filter
image: /images/svg/anybodypart.svg
inline_image: /images/base_neurotrauma/items/upgrades/dialysis_filter.png

infobox:
  - title: Labels
    sections:
      - items:
          - Item
          - Important

  - title: Statistics
    sections:
      - items:
          - "Skill Required: None"
          - "Maximum inventory stack: 1"

  - title: Crafting
    sections:
      - header: "Medical Fabricator Requirements (Output: 1x)"
        items:
            - "{{MEDICAL}} 60"
            - "{{MECHANICAL}} 40"
            - "{{ALUMINIUM}} (2x)"
            - "{{FPGA_CIRCUIT}} (2x)"
            - "{{ORGANIC_FIBER}} (2x)"
            - "{{SODIUM}} (2x)"
            - "{{CALCIUM}} (1x)"

      - header: "Deconstructor Yield"
        items:
            - "{{ALUMINIUM}} (1x)"

  - title: Store
    sections:
      - items:
          - "Base Price: 420 Marks"
          - "Buyable at Outposts: Habitation, Colony"
          - "Buyable at Merchant: Medical"

blocks:
  - type: description
    header: "Description:"
    order: 1
    text: |
     A filter which can be placed in the {{SURGERY_TABLE}} to reduce the patient’s {{ACIDOSIS}} or {{ALKALOSIS}}. It can be crafted, but cannot be bought. It can receive quality, increasing its maximum condition by 5% per level.

     If the patient **lays** on the table with an installed dialysis filter and has either {{ACIDOSIS}} or {{ALKALOSIS}}, these afflictions will be reduced by 0.8/s, the condition of the filter will drop by 1/s, and there is a 0.1% chance per second for the patient to receive {{SEPSIS}}. The condition of the filter will not drop and there is no chance of sepsis if the patient does not have acidosis or alkalosis.

---