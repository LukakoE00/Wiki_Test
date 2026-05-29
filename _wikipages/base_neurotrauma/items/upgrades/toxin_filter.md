---
layout: contentpage
title: Toxin Filter
category: items
subcategory: upgrades
permalink: /items/upgrades/toxin_filter
image: /images/svg/anybodypart.svg
inline_image: /images/base_neurotrauma/items/upgrades/toxin_filter.png

infobox:
  - title: Labels
    sections:
      - items:
          - Item
          - Niche

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
            - "{{MECHANICAL}} 40"
            - "{{ALUMINIUM}} (2x)"
            - "{{FPGA_CIRCUIT}} (2x)"
            - "{{ORGANIC_FIBER}} (2x)"
            - "{{SODIUM}} (2x)"
            - "{{STABILOZINE}} (2x)"

      - header: "Deconstructor Yield"
        items:
            - "{{ALUMINIUM}} (1x)"

  - title: Store
    sections:
      - items:
          - "Base Price: 485 Marks"
          - "Buyable at Outposts: Habitation, Colony"
          - "Buyable at Merchant: Medical"

blocks:
  - type: description
    header: "Description:"
    order: 1
    text: |
     A filter which can be placed in the {{SURGERY_TABLE}} to treat the patient’s poisons.

     Only [Poisons](https://barotraumagame.com/wiki/Poison_(Affliction_Type)) added by vanilla are valid for the toxin filter. For the patient **laying** on the table, the filter reduces each poison at a unique rate depending on its strength. Multiple poisons can be filtered at once. For each poison being filtered, the condition of the filter reduces by 0.8/s, and there is a 0.1% chance per second for the patient to receive {{SEPSIS}}. These effects do not occur if the patient is not poisoned.
     <br><br>
     #### {{MORBUSINE_POISONING}}
     - \-1.8%/s, 0-50% affliction strength
     - \-2.3%/s, 50-100% strength
     <br><br>
     #### {{CYANIDE_POISONING}}
     - \-2.8/s, 0-30% strength
     - \-5.5/s, 30-100% strength
     <br><br>
     #### {{SUFFORIN_POISONING}}
     - \-1/s, 0-50% strength
     - \-1.8/s, 50-100% strength
     <br><br>
     #### {{DELIRIUMINE_POISONING}}
     - \-1.6/s, 0-50% strength
     - \-2.3%, 50-100% strength

---