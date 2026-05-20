---
layout: contentpage
title: Surgical Drill
category: items
subcategory: tools
permalink: /items/tools/surgical_drill
image: /images/svg/anybodypart.svg
inline_image: /images/items/tools/surgical_drill.png

blocks:
  - type: description
    header: "Description:"
    order: 1
    text: |
     #### Medical Skill Check: 45

     The fifth step in {{OSTEOSYNTHETIC_SURGERY}}. The surgical drill will **not** work without 100% {{RETRACTED_SKIN}}.

     This item is not directly craftable. To obtain it from a fabricator, the player must craft the “Surgery toolbox (kit)”.

  - type: application_success
    header: "Application Success:"
    order: 2
    text: |

     Successfully using the surgical drill will give the patient {{DRILLED_BONES}} on the limb the tool was used on.

  - type: application_failure
    header: "Application Failure:"
    order: 3
    text: |

     - \+12% {{BURNS}}
     - \+10% {{INTERNAL_WOUNDS}}

---