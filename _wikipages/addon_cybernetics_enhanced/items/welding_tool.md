---
layout: contentpage
title: Welding Tool
addon: cybernetics_enhanced
subcategory: items
permalink: /items/cybernetics_enhanced/welding_tool
# image: /images/svg/anybodypart.svg
inline_image: /images/addon_cybernetics_enhanced/items/welding_tool.png

infobox:
  - title: Labels
    sections:
      - items:
          - Item
          - Equipment

  - title: Statistics
    sections:
      - items:
          - "Skill Required: {{MECHANICAL}} 50"
          - "Maximum inventory stack: 1"
          - "Requires Welding Fuel"

  - title: Crafting
    sections:
      - header: "Fabricator Requirements (Output: 1x)"
        items:
            - "{{MECHANICAL}} 30"
            - "{{STEEL}} (2x)"
            - "{{PLASTIC}} (2x)"

      - header: "Deconstructor Yield"
        items:
            - "{{STEEL}} (1x)"
            - "{{PLASTIC}} (1x)"

  - title: Store
    sections:
      - items:
          - "Base Price: 150 Marks"
          - "Buyable at Outposts: All"
          - "Buyable at Merchant: Engineering"

blocks:
  - type: description
    header: "Description:"
    order: 1
    text: |
     Used to repair {{BENT_METAL}} on Cyberlimbs.

  - type: application_success
    header: "Application Success:"
    order: 2
    text: |

     - \-20% {{BENT_METAL}}

  - type: application_failure
    header: "Application Failure:"
    order: 3
    text: |

     - \-5% {{BENT_METAL}}

---