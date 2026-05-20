---
layout: contentpage
title: Tourniquet
category: items
subcategory: consumables
permalink: /items/consumables/tourniquet
image: /images/svg/anybodypart.svg
inline_image: /images/items/consumables/tourniquet.png

blocks:
  - type: description
    header: "Description:"
    order: 1
    text: |
     #### Medical Skill Check: 30

     An item used to restrict the blood flow to prevent {{BLOOD_LOSS}} from {{ARTERIAL_BLEEDING}}. Tourniquets can be removed using {{TRAUMA_SHEARS}}, and are also removed after {{OPEN_CLOSE_SURGERY}}. Using a tourniquet on the head will give the victim 15% {{48_NEUROTRAUMA}} , 200% oxygen low, and will not clamp carotid arterial bleeding.

  - type: application_success
    header: "Application Success:"
    order: 2
    text: |

     - Prevents {{BLOOD_LOSS}} caused by {{ARTERIAL_BLEEDING}}, and slowly treats {{BLEEDING}}, but will cause {{GANGRENE}} if kept on for too long.

  - type: application_failure
    header: "Application Failure:"
    order: 3
    text: |

     - \+6% {{INTERNAL_WOUNDS}}
     Does not consume the tourniquet.

---