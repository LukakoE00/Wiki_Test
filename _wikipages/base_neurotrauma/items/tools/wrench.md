---
layout: contentpage
title: Wrench
category: items
subcategory: tools
permalink: /items/tools/wrench
image: /images/svg/anybodypart.svg
inline_image: /images/base_neurotrauma/items/tools/wrench.png

infobox:
  - title: Labels
    sections:
      - items:
          - Item
          - Essential

  - title: Statistics
    sections:
      - items:
          - "Skill Required: 60 / 30 (If patient has {{ANALGESIA}})"
          - "Maximum inventory stack: 1"

  - title: Crafting
    sections:
      - header: "Fabricator Requirements (Output: 1x)"
        items:
            - "{{MECHANICAL}} 20"
            - "{{IRON}} (2x)"

      - header: "Deconstructor Yield"
        items:
            - "{{IRON}} (1x)"

  - title: Store
    sections:
      - items:
          - "Base Price: 20 Marks"
          - "Buyable at Outposts: All"
          - "Buyable at Merchant: Engineering"

blocks:
  - type: description
    header: "Description:"
    order: 1
    text: |
     The wrench is used to treat {{DISLOCATIONS}}. To use, drag it onto the dislocated limb in the health interface and use it as a treatment, like you would a bandage. If the limb has no dislocation, the wrench will not do anything.

     The wrench can also be used to remove an {{AUTOPULSE}} or {{BODY_BAG}} from a person, as long as they aren’t {{UNCONSCIOUSNESS}}, by using the wrench on their torso as treatment. The item will be placed in the inventory of the wrench user.

     Other vanilla wrenches are able to perform the same actions, including:

     - Hardened Wrench
     - Dementonite Wrench
     - Multitool
     - Heavy Wrench
     - Murder Mystery Wrench

  - type: application_success
    header: "Application Success:"
    order: 2
    text: |

     - Cures {{DISLOCATIONS}} on that limb

  - type: application_failure
    header: "Application Failure:"
    order: 3
    text: |

     - Causes {{FRACTURES}} on that limb

---