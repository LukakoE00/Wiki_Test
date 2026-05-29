---
layout: contentpage
title: Trauma Shears
category: items
subcategory: tools
permalink: /items/tools/trauma_shears
image: /images/svg/anybodypart.svg
inline_image: /images/base_neurotrauma/items/tools/trauma_shears.png

infobox:
  - title: Labels
    sections:
      - items:
          - Item
          - Surgery
          - Essential

  - title: Statistics
    sections:
      - items:
          - "Skill Required: {{MEDICAL}} 10"
          - "Maximum inventory stack: 1"
          
  - title: Crafting
    sections:
      - header: "Medical Fabricator Requirements"
        items:
            - "{{MEDICAL}} 25"
            - "{{STEEL_BAR}} (1x)"

      - header: "Deconstructor Yield"
        items:
            - "Has no deconstructor outputs."

  - title: Store
    sections:
      - items:
          - "Base Price: 50 Marks"
          - "Buyable at Outpost: Habitation, Colony"
          - "Buyable at Merchant: Medical"

blocks:
  - type: description
    header: "Description:"
    order: 1
    text: |

     A pair of scissors used to remove {{PLASTER_CAST}} and {{BANDAGED}}.

     It can be crafted at a medical fabricator or purchased from a merchant.

  - type: application_success
    header: "Application Success:"
    order: 2
    text: |

     - Removes {{PLASTER_CAST}} , {{BANDAGED}} , and {{TRIAGE_CARD}} on the used limb.

  - type: application_failure
    header: "Application Failure:"
    order: 3
    text: |

     - \+15% {{BLEEDING}}
     - \+10% {{OPEN_WOUNDS}}

---