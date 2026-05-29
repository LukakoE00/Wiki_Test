---
layout: contentpage
title: Empty Blood Pack
category: items
subcategory: consumables
permalink: /items/consumables/empty_blood_pack
image: /images/svg/anybodypart.svg
inline_image: /images/base_neurotrauma/items/consumables/empty_blood_pack.png

infobox:
  - title: Labels
    sections:
      - items:
          - Item
          - Important

  - title: Statistics
    sections:
      - items:
          - "Skill Required: {{MEDICAL}} 30"
          - "Maximum inventory stack: 8"

  - title: Crafting
    sections:
      - header: "Medical Fabricator Requirements (Output: 4x)"
        items:
            - "{{MEDICAL}} 10"
            - "{{PLASTIC}} (1x)"

      - header: "Deconstructor Yield"
        items:
            - "Has no deconstructor outputs."

  - title: Store
    sections:
      - items:
          - "Base Price: 25 Marks"
          - "Buyable at Merchant: Medical"

blocks:
  - type: description
    header: "Description:"
    order: 1
    text: |
     Empty blood packs are used for acquiring {{BLOOD_PACKS}}. Empty blood packs can only be used on humans with less than 31% {{BLOOD_LOSS}}, otherwise it does nothing.

  - type: application_success
    header: "Application Success:"
    order: 2
    text: |

     - \+30% {{BLOOD_LOSS}}

  - type: application_failure
    header: "Application Failure:"
    order: 3
    text: |

     - \+40% {{BLOOD_LOSS}}

     If the human that the empty blood pack is used on is suffering from either {{ACIDOSIS}}, {{ALKALOSIS}} or {{SEPSIS}}, then those afflictions will also be given to whoever the blood is given to (affliction gained will be the donor's affliction level at time of extraction divided by 5). Using an empty blood pack will multiply the patient’s acidosis or alkalosis by 0.9.

---