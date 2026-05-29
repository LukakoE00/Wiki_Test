---
layout: contentpage
title: Sutures
category: items
subcategory: consumables
permalink: /items/consumables/sutures
image: /images/svg/anybodypart.svg
inline_image: /images/base_neurotrauma/items/consumables/sutures.png

infobox:
  - title: Labels
    sections:
      - items:
          - Item
          - First Aid
          - Essential

  - title: Statistics
    sections:
      - items:
          - "Skill Required: {{MEDICAL}} 30"
          - "Maximum inventory stack: 48"

  - title: Crafting
    sections:
      - header: "Medical Fabricator Requirements (Output: 16x)"
        items:
            - "{{MEDICAL}} 25"
            - "{{ALUMINIUM}} (1x)"
            - "{{ORGANIC_FIBER}} (2x)"

      - header: "Deconstructor Yield"
        items:
            - "Has no deconstructor outputs."

  - title: Store
    sections:
      - items:
          - "Base Price: 9 Marks"
          - "Buyable at Outposts: Habitation, Colony"
          - "Buyable at Merchant: Medical"

blocks:
  - type: description
    header: "Description:"
    order: 1
    text: |
     The final step in **all** surgical procedures. Also very useful for curing most {{OPEN_WOUNDS}} & {{BLEEDING}}.

  - type: application_success
    header: "Application Success:"
    order: 2
    text: |

     - \-20% {{OPEN_WOUNDS}} (except Blunt Force Trauma)
     - \-40% {{BLEEDING}}

     Removes all surgery related afflictions (denoted with hexagonal icons)

  - type: application_failure
    header: "Application Failure:"
    order: 3
    text: |

     - \+6% {{INTERNAL_WOUNDS}}

---