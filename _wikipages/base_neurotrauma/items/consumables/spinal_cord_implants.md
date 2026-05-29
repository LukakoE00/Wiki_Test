---
layout: contentpage
title: Spinal Cord Implants
category: items
subcategory: consumables
permalink: /items/consumables/spinal_cord_implants
image: /images/svg/anybodypart.svg
inline_image: /images/base_neurotrauma/items/consumables/spinal_cord_implants.png

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
            - "{{MEDICAL}} 70"
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
     Implants used for treating {{SPINAL_CORD_INJURY}}. The implants will **not** work without 50% or higher {{RETRACTED_SKIN}}.

  - type: application_success
    header: "Application Success:"
    order: 2
    text: |

     - \-100% {{SPINAL_CORD_INJURY}}

     If the patient’s neck fracture is untreated, the spine will become injured again.

  - type: application_failure
    header: "Application Failure:"
    order: 3
    text: |

     - \+5% {{BLEEDING}}
     - \+5% {{INTERNAL_WOUNDS}}

---