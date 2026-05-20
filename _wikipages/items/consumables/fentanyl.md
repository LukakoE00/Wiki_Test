---
layout: contentpage
title: Fentanyl
category: items
subcategory: consumables
permalink: /items/consumables/fentanyl
image: /images/svg/anybodypart.svg
inline_image: /images/items/consumables/fentanyl.png

blocks:
  - type: description
    header: "Description:"
    order: 1
    text: |
     ### Medical Skill Check: 72

     A powerful opiate used to induce {{ANALGESIA}}.

     To prevent exploits, fentanyl cannot be shot as a projectile, such as out of a {{SYRINGE_GUN}}.

  - type: application_success
    header: "Application Success:"
    order: 2
    text: |

     - \+75% {{ANALGESIA}}
     - \+15% [Opiate Addiction](https://barotraumagame.com/wiki/Opiate_Addiction)
     - \+22.5% {{OPIATE_OVERDOSE}}
     - \-100%{{OPIATE_WITHDRAWAL}}

     #### While >30% drunk changes to:

     - \+150% {{ANALGESIA}}
     - \+15% [Opiate Addiction](https://barotraumagame.com/wiki/Opiate_Addiction)
     - \+37.5% {{OPIATE_OVERDOSE}}
     - \-100% {{OPIATE_WITHDRAWAL}}

  - type: application_failure
    header: "Application Failure:"
    order: 3
    text: |

     - \+50% {{ANALGESIA}}
     - \+40% [Opiate Addiction](https://barotraumagame.com/wiki/Opiate_Addiction)
     - \+30% {{OPIATE_OVERDOSE}}
     - \-100% {{OPIATE_WITHDRAWAL}}

     #### While >30% drunk changes to:

     - \+100% {{ANALGESIA}}
     - \+40% [Opiate Addiction](https://barotraumagame.com/wiki/Opiate_Addiction)
     - \+60% {{OPIATE_OVERDOSE}}
     - \-100% {{OPIATE_WITHDRAWAL}}

---