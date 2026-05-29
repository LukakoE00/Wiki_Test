---
layout: contentpage
title: Osteosynthesis Implants
category: items
subcategory: consumables
permalink: /items/consumables/osteosynthesis_implants
image: /images/svg/anybodypart.svg
inline_image: /images/base_neurotrauma/items/consumables/osteosynthesis_implants.png

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
          - "Skill Required: {{MEDICAL}} 45"
          - "Maximum inventory stack: 1"

  - title: Crafting
    sections:
      - header: "Medical Fabricator Requirements (Output: 1x)"
        items:
            - "{{MEDICAL}} 35"
            - "{{MECHANICAL}} 20"
            - "{{TITANIUM_ALUMINIUM_ALLOY}} (1x)"
            - "{{LIQUID_OXYGENITE}} (1x)"
            - "{{CALCIUM}} (1x)"

      - header: "Deconstructor Yield"
        items:
            - "Has no deconstructor outputs."

  - title: Store
    sections:
      - items:
          - "Base Price: 350 Marks"
          - "Buyable at Merchant: Medical"

blocks:
  - type: description
    header: "Description:"
    order: 1
    text: |
     The sixth step in {{OSTEOSYNTHETIC_SURGERY}}. The implants will **not** work without 100% {{DRILLED_BONES}}.

  - type: application_success
    header: "Application Success:"
    order: 2
    text: |

     Cures all fractures on the limb the implants were used on, and uses up 25% of the implants.

  - type: application_failure
    header: "Application Failure:"
    order: 2
    text: |

     - \+5% {{BLEEDING}}
     - \+5% {{INTERNAL_WOUNDS}}

---