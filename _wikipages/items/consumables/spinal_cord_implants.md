---
layout: contentpage
title: Spinal Cord Implants
category: items
subcategory: consumables
permalink: /items/consumables/spinal_cord_implants
image: /images/svg/anybodypart.svg
inline_image: /images/items/consumables/spinal_cord_implants.png

blocks:
  - type: description
    header: "Description:"
    order: 1
    text: |
     #### Medical Skill Check: 45

     Implants used for treating {{SPINAL_CORD_INJURY}}. The implants will **not** work without 50% or higher {{RETRACTED_SKIN}}.

  - type: application_success
    header: "Application Success:"
    order: 2
    text: |

     - \-100% {{SPINAL_CORD_INJURY}}

     If the patient’s neck fracture is untreated, the spine will become injured again.

  - type: application_failure
    header: "Application Failure:"
    order: 3
    text: |

     - \+5% {{BLEEDING}}
     - \+5% {{INTERNAL_WOUNDS}}

---