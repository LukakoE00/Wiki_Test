---
layout: contentpage
title: Screwdriver
addon: cybernetics_enhanced
subcategory: items
permalink: /items/cybernetics_enhanced/screwdriver
# image: /images/svg/anybodypart.svg
inline_image: /images/addon_cybernetics_enhanced/items/screwdriver.png

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
          - "Skill Required: {{MECHANICAL}} 40"
          - "Maximum inventory stack: 1"

  - title: Crafting
    sections:
      - header: "Fabricator Requirements (Output: 1x)"
        items:
            - "{{MECHANICAL}} 20"
            - "{{IRON}} (2x)"

      - header: "Deconstructor Yield"
        items:
            - "{{IRON}} (1x)"

  - title: Store
    sections:
      - items:
          - "Base Price: 10 Marks"
          - "Buyable at Outposts: All"
          - "Buyable at Merchant: Engineering"

blocks:
  - type: description
    header: "Description:"
    order: 1
    text: |
     Used to repair {{LOOSE_SCREWS}} on Cyberlimbs.

  - type: application_success
    header: "Application Success:"
    order: 2
    text: |

     - \-20% {{LOOSE_SCREWS}}

  - type: application_failure
    header: "Application Failure:"
    order: 3
    text: |

     - \-5% {{LOOSE_SCREWS}}

---