---
layout: contentpage
title: Trauma Shears
category: items
subcategory: tools
permalink: /items/tools/trauma_shears
image: /images/svg/anybodypart.svg
inline_image: /images/items/tools/trauma_shears.png

blocks:
  - type: description
    header: "Description:"
    order: 1
    text: |
     #### Medical Skill Check: 10

     A pair of scissors used to remove {{PLASTER_CAST}} and {{BANDAGED}}.

     It can be crafted at a medical fabricator or purchased from a merchant.

  - type: application_success
    header: "Application Success:"
    order: 2
    text: |

     - Removes {{PLASTER_CAST}} , {{BANDAGED}} , and {{TRIAGE_CARD}} on the used limb.

  - type: application_failure
    header: "Application Failure:"
    order: 3
    text: |

     - \+15% {{BLEEDING}}
     - \+10% {{OPEN_WOUNDS}}

---