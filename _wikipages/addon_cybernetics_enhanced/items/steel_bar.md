---
layout: contentpage
title: Steel Bar
addon: cybernetics_enhanced
subcategory: items
permalink: /items/cybernetics_enhanced/steel_bar
# image: /images/svg/anybodypart.svg
inline_image: /images/addon_cybernetics_enhanced/items/steel_bar.png

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
          - "Skill Required: {{MECHANICAL}} 60"
          - "Maximum inventory stack: 8"

  - title: Crafting
    sections:
      - header: "Fabricator Requirements (Output: 1x)"
        items:
            - "{{MECHANICAL}} 20"
            - "{{CARBON}} (1x)"
            - "{{IRON}} (2x)"

      - header: "Deconstructor Yield"
        items:
            - "{{CARBON}} (1x)"
            - "{{IRON}} (1x)"

  - title: Store
    sections:
      - items:
          - "Base Price: 28 Marks"
          - "Buyable at Outposts: All"

blocks:
  - type: description
    header: "Description:"
    order: 1
    text: |
     Used to repair {{MATERIAL_LOSS}} on Cyberlimbs.

  - type: application_success
    header: "Application Success:"
    order: 2
    text: |

     - \-50% {{MATERIAL_LOSS}}

  - type: application_failure
    header: "Application Failure:"
    order: 3
    text: |

     - \-20% {{MATERIAL_LOSS}}

---