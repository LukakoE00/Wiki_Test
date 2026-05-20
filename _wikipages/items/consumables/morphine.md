---
layout: contentpage
title: Morphine
category: items
subcategory: consumables
permalink: /items/consumables/morphine
image: /images/svg/anybodypart.svg
inline_image: /images/items/consumables/morphine.png

blocks:
  - type: description
    header: "Description:"
    order: 1
    text: |
     #### Medical Skill Check: 30

     A moderately powerful opiate used to induce {{ANALGESIA}}.

     To prevent exploits, morphine cannot be shot as a projectile, such as out of a {{SYRINGE_GUN}}.

  - type: application_success
    header: "Application Success:"
    order: 2
    text: |

     - \+50% {{ANALGESIA}}
     - \+10% [Opiate Addiction](https://barotraumagame.com/wiki/Opiate_Addiction)
     - \+10% {{OPIATE_OVERDOSE}}
     - \-30% {{OPIATE_WITHDRAWAL}}

     #### While >30% drunk changes to:

     - \+100% {{ANALGESIA}}
     - \+10% [Opiate Addiction](https://barotraumagame.com/wiki/Opiate_Addiction)
     - \+20% {{OPIATE_OVERDOSE}}
     - \-30% {{OPIATE_WITHDRAWAL}}

  - type: application_failure
    header: "Application Failure:"
    order: 3
    text: |

     - \+30% {{ANALGESIA}}
     - \+25% [Opiate Addiction](https://barotraumagame.com/wiki/Opiate_Addiction)
     - \+20% {{OPIATE_OVERDOSE}}
     - \-30% {{OPIATE_WITHDRAWAL}}

     #### While >30% drunk changes to:

     - \+60% {{ANALGESIA}}
     - \+25% [Opiate Addiction](https://barotraumagame.com/wiki/Opiate_Addiction)
     - \+40% {{OPIATE_OVERDOSE}}
     - \-30% {{OPIATE_WITHDRAWAL}}

---