---
layout: contentpage
title: Naloxone
category: items
subcategory: consumables
permalink: /items/consumables/naloxone
image: /images/svg/anybodypart.svg
inline_image: /images/items/consumables/naloxone.png

blocks:
  - type: description
    header: "Description:"
    order: 1
    text: |
     #### Medical Skill Check: 39

     Naloxone is used to treat the effects of opiates.

  - type: application_success
    header: "Application Success:"
    order: 2
    text: |

     - \-60% {{OPIATE_WITHDRAWAL}}
     - \-60% {{OPIATE_OVERDOSE}}
     - \-60% [Opiate Addiction](https://barotraumagame.com/wiki/Opiate_Addiction)
     - \-60% {{ANALGESIA}}
     - \-60% Opioids

  - type: application_failure
    header: "Application Failure:"
    order: 3
    text: |

     - \-30% {{OPIATE_WITHDRAWAL}}
     - \-30% {{OPIATE_OVERDOSE}}
     - \-30% [Opiate Addiction](https://barotraumagame.com/wiki/Opiate_Addiction)
     - \-60% {{ANALGESIA}}
     - \-60% Opioids
     - \+15% {{COMA}} (50% chance)
---