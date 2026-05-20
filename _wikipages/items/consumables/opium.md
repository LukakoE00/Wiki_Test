---
layout: contentpage
title: Opium
category: items
subcategory: consumables
permalink: /items/consumables/opium
image: /images/svg/anybodypart.svg
inline_image: /images/items/consumables/opium.png

blocks:
  - type: description
    header: "Description:"
    order: 1
    text: |
     #### Medical Skill Check: 15

     A weak opiate used to induce {{ANALGESIA}}.

  - type: application_success
    header: "Application Success:"
    order: 2
    text: |

     - \+20% {{ANALGESIA}}
     - \+5% [Opiate Addiction](https://barotraumagame.com/wiki/Opiate_Addiction)
     - \+8.75% {{OPIATE_OVERDOSE}}
     - \-15% {{OPIATE_WITHDRAWAL}}

     #### While >30% drunk changes to:

     - \+40% {{ANALGESIA}}
     - \+5% [Opiate Addiction](https://barotraumagame.com/wiki/Opiate_Addiction)
     - \+18.75% {{OPIATE_OVERDOSE}}
     - \-15% {{OPIATE_WITHDRAWAL}}

  - type: application_failure
    header: "Application Failure:"
    order: 3
    text: |

     - \+10% {{ANALGESIA}}
     - \+20% [Opiate Addiction](https://barotraumagame.com/wiki/Opiate_Addiction)
     - \+15% {{OPIATE_OVERDOSE}}
     - \-15% {{OPIATE_WITHDRAWAL}}

     #### While >30% drunk changes to:

     - \+20% {{ANALGESIA}}
     - \+20% [Opiate Addiction](https://barotraumagame.com/wiki/Opiate_Addiction)
     - \+30% {{OPIATE_OVERDOSE}}
     - \-15% {{OPIATE_WITHDRAWAL}}
---