---
layout: contentpage
title: Scalpel
category: items
subcategory: tools
permalink: /items/tools/hemostat
image: /images/svg/anybodypart.svg
inline_image: /images/base_neurotrauma/items/tools/scalpel.png

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
     The second step in **all** surgical procedures. The scalpel will **not** work without {{ANALGESIA}} or {{UNCONSCIOUSNESS}}.

     This item is not directly craftable. To obtain it from a fabricator, the player must craft the “Surgery toolbox (kit)”.

  - type: application_success
    header: "Application Success:"
    order: 2
    text: |

     - Gives {{SURGERY_INCISION}} on the limb the tool was used on, and will remove any {{PLASTER_CAST}} or {{BANDAGED}}.

  - type: application_failure
    header: "Application Failured:"
    order: 3
    text: |

     - \+15% {{BLEEDING}}
     - \+10% {{OPEN_WOUNDS}}

---