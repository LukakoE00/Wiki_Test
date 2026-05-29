---
layout: contentpage
title: Skin Retractors
category: items
subcategory: tools
permalink: /items/tools/skin_retractors
image: /images/svg/anybodypart.svg
inline_image: /images/base_neurotrauma/items/tools/skin_retractors.png

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
          - "Skill Required: {{MEDICAL}} 30"
          - "Maximum inventory stack: 1"
          
  - title: Crafting
    sections:
      - header: "Medical Fabricator Requirements"
        items:
            - "Cannot be fabricated standalone."

      - header: "Deconstructor Yield"
        items:
            - "Has no deconstructor outputs."

  - title: Store
    sections:
      - items:
          - "Base Price: 35 Marks"
          - "Buyable at Merchant: Medical"

blocks:
  - type: description
    header: "Description:"
    order: 1
    text: |
     The fourth step in most surgical procedures. The retractors will **not** work without 100% {{CLAMPED_BLEEDING}}.

     This item is not directly craftable. To obtain it from a fabricator, the player must craft the “Surgery toolbox (kit)”.

  - type: application_success
    header: "Application Success:"
    order: 2
    text: |

     - Gives the patient {{RETRACTED_SKIN}} on the limb the tool was used on.

  - type: application_failure
    header: "Application Failure:"
    order: 2
    text: |

     - \+10% {{INTERNAL_WOUNDS}}

---