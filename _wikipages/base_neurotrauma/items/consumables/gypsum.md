---
layout: contentpage
title: Gypsum
category: items
subcategory: consumables
permalink: /items/consumables/gypsum
image: /images/svg/anybodypart.svg
inline_image: /images/base_neurotrauma/items/consumables/gypsum.png

infobox:
  - title: Labels
    sections:
      - items:
          - Item
          - Very Important

  - title: Statistics
    sections:
      - items:
          - "Skill Required: {{MEDICAL}} 40"
          - "Maximum inventory stack: 4"

  - title: Crafting
    sections:
      - header: "Medical Fabricator Requirements (Output: 1x)"
        items:
            - "{{MEDICAL}} 15"
            - "{{CALCIUM}} (1x)"

      - header: "Deconstructor Yield"
        items:
            - "Has no deconstructor outputs."

  - title: Store
    sections:
      - items:
          - "Base Price: 50 Marks"
          - "Buyable at Outposts: Habitation, Colony"
          - "Buyable at Merchant: Medical"

blocks:
  - type: description
    header: "Description:"
    order: 1
    text: |
     A fine powder that when used in conjunction with {{BANDAGED}}, will encase a limb in a {{PLASTER_CAST}}, in order to heal {{FRACTURES}}. Gypsum will not work if you have not used {{BANDAGES}}  or {{PLASTISEAL}} beforehand, and **will do nothing for skull, rib and neck fractures.**

     For each plaster cast applied to the player, they will get a 20% movement speed debuff. Plaster casts can be removed with {{TRAUMA_SHEARS}}.

  - type: application_success
    header: "Application Success:"
    order: 2
    text: |

     - Turns {{BANDAGED}} into {{PLASTER_CAST}}, which will slowly heal arm and leg fractures encased in it.

  - type: application_failure
    header: "Application Failure:"
    order: 3
    text: |

     - Deletes the gypsum and does nothing.
---