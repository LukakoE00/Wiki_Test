---
layout: contentpage
title: Plastiseal
category: items
subcategory: consumables
permalink: /items/consumables/plastiseal
image: /images/svg/anybodypart.svg
inline_image: /images/base_neurotrauma/items/consumables/plastiseal.png

infobox:
  - title: Labels
    sections:
      - items:
          - Item
          - Very Important
          - First Aid

  - title: Statistics
    sections:
      - items:
          - "Skill Required: {{MEDICAL}} 22"
          - "Maximum inventory stack: 8"

  - title: Crafting
    sections:
      - header: "Medical Fabricator Requirements (Output: 3x)"
        items:
            - "{{MEDICAL}} 16"
            - "{{BANDAGES}} (3x)"
            - "{{ELASTIN}} (1x)"

      - header: "Deconstructor Yield"
        items:
            - "Has no deconstructor outputs."

  - title: Store
    sections:
      - items:
          - "Base Price: 50 Marks"
          - "Buyable at Merchant: Medical"

blocks:
  - type: description
    header: "Description:"
    order: 1
    text: |
     An improved version of {{BANDAGED}}, which can more effectively treat wounds.

  - type: application_success
    header: "Application Success:"
    order: 2
    text: |

     - \+100% {{BANDAGED}}
     - \-48% {{BLEEDING}}
     - \-24% {{BURNS}}

  - type: application_failure
    header: "Application Failure:"
    order: 3
    text: |

     - \+50% {{BANDAGED}}
     - \-24% {{BLEEDING}}
     - \-12% {{BURNS}}

     Applying plastiseal will also replace any dirty bandages on the limb the bandage is applied to. Plastiseal can also be used after {{RETRACTED_SKIN}} in order to treat third degree burns.

---