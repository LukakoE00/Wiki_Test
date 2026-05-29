---
layout: contentpage
title: Sodium Nitroprusside
category: items
subcategory: consumables
permalink: /items/consumables/sodium_nitroprusside
image: /images/svg/anybodypart.svg
inline_image: /images/base_neurotrauma/items/consumables/sodium_nitroprusside.png

infobox:
  - title: Labels
    sections:
      - items:
          - Item
          - Niche
          - Toggleable

  - title: Statistics
    sections:
      - items:
          - "Skill Required: {{MEDICAL}} 10"
          - "Maximum inventory stack: 8"

  - title: Crafting
    sections:
      - header: "Medical Fabricator Requirements (Output: 3x)"
        items:
            - "{{MEDICAL}} 30"
            - "{{SODIUM}} (1x)"
            - "{{NITROGLYCERIN}} (1x)"

      - header: "Deconstructor Yield"
        items:
            - "Has no deconstructor outputs."

  - title: Store
    sections:
      - items:
          - "Base Price: 100 Marks"
          - "Buyable at Merchant: Medical"

blocks:
  - type: description
    header: "Description:"
    order: 1
    text: |
     #### This item is only usable in-game if enabled via the {{CONFIGURATION_MENU}} under 'Item Availability'.

     A medication to reduce blood pressure. While this drug is active, {{FIBRILLATION}} caused by {{HYPOTENSION}} will be reduced. Identical effect and affliction to {{NITROGLYCERIN}}.

  - type: application_success
    header: "Application Success:"
    order: 2
    text: |

     - \-45% Blood Pressure

     Effects last for 200 seconds.

  - type: application_failure
    header: "Application Failure:"
    order: 3
    text: |

     - \-45% Blood Pressure

     Effects last for 120 seconds.

---