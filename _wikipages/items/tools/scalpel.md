---
layout: contentpage
title: Scalpel
category: items
subcategory: tools
permalink: /items/tools/hemostat
image: /images/svg/anybodypart.svg
inline_image: /images/items/tools/scalpel.png

blocks:
  - type: description
    header: "Description:"
    order: 1
    text: |
     #### Medical Skill Check: 30

     The second step in **all** surgical procedures. The scalpel will **not** work without {{ANALGESIA}} or {{UNCONSCIOUSNESS}}.

     This item is not directly craftable. To obtain it from a fabricator, the player must craft the “Surgery toolbox (kit)”.

  - type: application_success
    header: "Application Success:"
    order: 2
    text: |

     - Gives {{SURGERY_INCISION}} on the limb the tool was used on, and will remove any {{PLASTER_CAST}} or {{BANDAGED}}.

  - type: application_failure
    header: "Application Failured:"
    order: 3
    text: |

     - \+15% {{BLEEDING}}
     - \+10% {{OPEN_WOUNDS}}

---