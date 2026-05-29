---
layout: contentpage
title: Antibiotic Glue
category: items
subcategory: consumables
permalink: /items/consumables/antibiotic_glue
image: /images/svg/anybodypart.svg
inline_image: /images/base_neurotrauma/items/consumables/antibiotic_glue.png

infobox:
  - title: Labels
    sections:
      - items:
          - Item
          - Niche

  - title: Statistics
    sections:
      - items:
          - "Skill Required: {{MEDICAL}} 55"
          - "Maximum inventory stack: 8"

  - title: Crafting
    sections:
      - header: "Medical Fabricator Requirements (Output: 4x)"
        items:
            - "{{MEDICAL}} 48"
            - "{{BROAD_SPECTRUM_ANTIBIOTICS}} (2x)" 
            - "{{STABILOZINE}} (1x)"
            - "{{ELASTIN}} (1x)"

      - header: "Deconstructor Yield"
        items:
            - "- Has no deconstructor outputs."

  - title: Store
    sections:
      - items:
          - "Minimum Difficulty: 25%"
          - "Base Price: 80 Marks"
          - "Buyable at Outposts: Habitation, Colony"
          - "Buyable at Merchant: Medical"

blocks:
  - type: description
    header: "Description:"
    order: 1
    text: |
     #### Medical Skill Check: 55

     A glue used to quickly seal bleeding wounds and treat {{BURNS}} on a single limb. Also treats {{INFECTED_WOUNDS}}.

  - type: application_success
    header: "Application Success:"
    order: 2
    text: |
     - \-60% {{BLEEDING}}.
     - \-15% {{BURNS}}.
     - \-100% {{INFECTED_WOUNDS}}.

  - type: application_failure
    header: "Application Failure:"
    order: 3
    text: |
     - \-40% {{BLEEDING}}.
     - \-10% {{BURNS}}.
     - \-100% {{INFECTED_WOUNDS}}.
     - 50% chance to cause {{HEART_ATTACK}} if {{BLEEDING}}.
---