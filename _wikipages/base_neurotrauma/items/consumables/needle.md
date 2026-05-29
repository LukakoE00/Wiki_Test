---
layout: contentpage
title: Needle
category: items
subcategory: consumables
permalink: /items/consumables/needle
image: /images/svg/anybodypart.svg
inline_image: /images/base_neurotrauma/items/consumables/needle.png

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
          - "Skill Required: None"
          - "Maximum inventory stack: 16"

  - title: Crafting
    sections:
      - header: "Medical Fabricator Requirements (Output: 2x)"
        items:
            - "{{MEDICAL}} 20"
            - "{{PLASTIC}} (1x)"
            - "{{ALUMINIUM}} (1x)"

      - header: "Deconstructor Yield"
        items:
            - "Has no deconstructor outputs."

  - title: Store
    sections:
      - items:
          - "Base Price: 60 Marks"
          - "Buyable at Merchant: Medical"

blocks:
  - type: description
    header: "Description:"
    order: 1
    text: |
     A consumable needle that reduces the strength of {{PNEUMOTHORAX}} to 15% and {{CARDIAC_TAMPONADE}} to 5%, but does not treat them. If the patient does not have pneumothorax, the needle will give them {{PNEUMOTHORAX}} instead.

  - type: application_success
    header: "Application Success:"
    order: 2
    text: |

     - Reduces {{PNEUMOTHORAX}} to 15% over time
     - Reduces {{CARDIAC_TAMPONADE}} to 5% over time

     Effects persist until the Needle affliction wears off.

  - type: application_failure
    header: "Application Failure:"
    order: 3
    text: |

     - \+10% {{VANILLA_ORGAN_DAMAGE}}
     - \+10% {{BLEEDING}}

---