---
layout: contentpage
title: FPGA Circuit
addon: cybernetics_enhanced
subcategory: items
permalink: /items/cybernetics_enhanced/fpga_circuit
# image: /images/svg/anybodypart.svg
inline_image: /images/addon_cybernetics_enhanced/items/fpga_circuit.png

infobox:
  - title: Labels
    sections:
      - items:
          - Item
          - Niche
          - Cybernetics Expansion

  - title: Statistics
    sections:
      - items:
          - "Skill Required: {{ELECTRICAL}} 40"
          - "Maximum inventory stack: 8"

  - title: Crafting
    sections:
      - header: "Fabricator Requirements (Output: 1x)"
        items:
            - "{{ELECTRICAL}} 15"
            - "{{PLASTIC}} (1x)"
            - "{{COPPER}} (2x)"
            - "{{TIN}} (1x)"

      - header: "Deconstructor Yield"
        items:
            - "{{COPPER}} (1x)"

  - title: Store
    sections:
      - items:
          - "Base Price: 80 Marks"
          - "Buyable at Outposts: Habitation, Research, Military, Mine"
          - "Buyable at Merchant: Engineering"

blocks:
  - type: description
    header: "Description:"
    order: 1
    text: |
     Used to repair {{DAMAGED_ELECTRONICS}} on Cyberlimbs.

  - type: application_success
    header: "Application Success:"
    order: 2
    text: |

     - \-50% {{DAMAGED_ELECTRONICS}}

  - type: application_failure
    header: "Application Failure:"
    order: 3
    text: |

     - \-20% {{DAMAGED_ELECTRONICS}}

---