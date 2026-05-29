---
layout: contentpage
title: Bandages
category: items
subcategory: consumables
permalink: /items/consumables/bandages
image: /images/svg/anybodypart.svg
inline_image: /images/base_neurotrauma/items/consumables/bandages.png

infobox:
  - title: Labels
    sections:
      - items:
          - Item
          - First Aid
          - Important

  - title: Statistics
    sections:
      - items:
          - "Skill Required: {{MEDICAL}} 10"
          - "Maximum inventory stack: 8"

  - title: Crafting
    sections:
      - header: "Medical Fabricator Requirements (Output: 3x)"
        items:
            - "{{MEDICAL}} 5"
            - "{{ORGANIC_FIBER}} (1x)"

      - header: "Deconstructor Yield"
        items:
            - "Has no deconstructor outputs."

  - title: Store
    sections:
      - items:
          - "Base Price: 30 Marks"
          - "Buyable at Outposts: All"
          - "Buyable at Merchant: Medical"

blocks:
  - type: description
    header: "Description:"
    order: 1
    text: |
     #### Medical Skill Check: 10

     Bandages are used for covering wounds to prevent {{INFECTED_WOUNDS}} . Bandages can also stabilize {{DISLOCATIONS}}, preventing internal damage as well as stabilizing {{FRACTURES}} to prevent {{INTERNAL_WOUNDS}}, {{PNEUMOTHORAX}} and {{NEUROTRAUMA}} for both {{RIB_FRACTURES}} and {{SKULL_FRACTURES}} respectively.

  - type: application_success
    header: "Application Success:"
    order: 2
    text: |
     - \+50% {{BANDAGED}}
     - \-24% {{BLEEDING}}

  - type: application_failure
    header: "Application Failure:"
    order: 3
    text: |
     - \+36% {{BANDAGED}}
     - \-18% {{BLEEDING}}

---