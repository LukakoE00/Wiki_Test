---
layout: contentpage
title: Diving Knife
category: items
subcategory: tools
permalink: /items/tools/diving_knife
image: /images/svg/anybodypart.svg
inline_image: /images/base_neurotrauma/items/tools/diving_knife.png

infobox:
  - title: Labels
    sections:
      - items:
          - Item

  - title: Statistics
    sections:
      - items:
          - "Skill Required: {{MEDICAL}} 30"
          - "Maximum inventory stack: 1"

  - title: Crafting
    sections:
      - header: "Fabricator Requirements (Output: 1x)"
        items:
            - "{{WEAPONS}} 30"
            - "{{IRON}} (2x)"

      - header: "Deconstructor Yield"
        items:
            - "{{IRON}} (1x)"

  - title: Store
    sections:
      - items:
          - "Base Price: 29 Marks"
          - "Buyable at Outposts: All"
          - "Buyable at Merchant: Military, Armory"

blocks:
  - type: description
    header: "Description:"
    order: 1
    text: |

     In addition to the normal uses of a knife, they can be used to remove {{BANDAGES}}.

  - type: application_success
    header: "Application Success:"
    order: 2
    text: |

     - Removes {{BANDAGED}} on the limb the knife was used on.

  - type: application_failure
    header: "Application Failure:"
    order: 3
    text: |

     - \+15% {{BLEEDING}}
     - \+10% {{OPEN_WOUNDS}}
---