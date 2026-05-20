---
layout: contentpage
title: Surgical Saw
category: items
subcategory: tools
permalink: /items/tools/surgical_saw
image: /images/svg/anybodypart.svg
inline_image: /images/items/tools/surgical_saw.png

blocks:
  - type: description
    header: "Description:"
    order: 1
    text: |
     #### Medical Skill Check: 45

     The fifth step in {{AMPUTATION_SURGERY}}. The surgical saw will **not** work without 100% {{RETRACTED_SKIN}}.

     This item is not directly craftable. To obtain it from a fabricator, the player must craft the “Surgery toolbox (kit)”.

  - type: application_success
    header: "Application Success:"
    order: 2
    text: |

     - Successfully using the surgical saw will give the patient {{SAWED_BONES}} on the limb the tool was used on.

  - type: application_failure
    header: "Application Failure:"
    order: 3
    text: |

     - \+15% {{BLEEDING}}
     - \+6% {{INTERNAL_WOUNDS}}
     - \+4% {{OPEN_WOUNDS}}

---