---
layout: contentpage
title: Antibiotic Ointment
category: items
subcategory: consumables
permalink: /items/consumables/antibiotic_ointment
image: /images/svg/anybodypart.svg
inline_image: /images/base_neurotrauma/items/consumables/antibiotic_ointment.png

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
          - "Skill Required: {{MEDICAL}} 55"
          - "Maximum inventory stack: 8"

  - title: Crafting
    sections:
      - header: "Medical Fabricator Requirements (Output: 4x)"
        items:
            - "{{MEDICAL}} 10"
            - "{{STABILOZINE}} (1x)"
            - "{{BROAD_SPECTRUM_ANTIBIOTICS}} (1x)"

      - header: "Deconstructor Yield"
        items:
            - "Has no deconstructor outputs."

  - title: Store
    sections:
      - items:
          - "Base Price: 40 Marks"
          - "Buyable at Outposts: Habitation, Colony"
          - "Buyable at Merchant: Medical"

blocks:
  - type: description
    header: "Description:"
    order: 1
    text: |
     Antibiotic ointment is an item used to treat {{INFECTED_WOUNDS}} and prevent them for some time.

     It can be crafted at a medical fabricator or bought from a medical merchant.

  - type: application_success
    header: "Application Success:"
    order: 2
    text: |
     - \-72% {{INFECTED_WOUNDS}}
     - \+120% {{OINTMENTED}}
     - \-12% {{BURNS}}

  - type: application_failure
    header: "Application Failure:"
    order: 3
    text: |
     - \-24% {{INFECTED_WOUNDS}}
     - \+60% {{OINTMENTED}}
     - \-7.2% {{BURNS}}

---