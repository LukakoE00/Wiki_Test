---
layout: contentpage
title: Needle
category: items
subcategory: consumables
permalink: /items/consumables/needle
image: /images/svg/anybodypart.svg
inline_image: /images/items/consumables/needle.png

blocks:
  - type: description
    header: "Description:"
    order: 1
    text: |
     #### Medical Skill Check: 20

     A consumable needle that reduces the strength of {{PNEUMOTHORAX}} to 15% and {{CARDIAC_TAMPONADE}} to 5%, but does not treat them. If the patient does not have pneumothorax, the needle will give them {{PNEUMOTHORAX}} instead.

  - type: application_success
    header: "Application Success:"
    order: 2
    text: |

     - Reduces {{PNEUMOTHORAX}} to 15% over time
     - Reduces {{CARDIAC_TAMPONADE}} to 5% over time

     Effects persist until the Needle affliction wears off.

  - type: application_failure
    header: "Application Failure:"
    order: 3
    text: |

     - \+10% {{VANILLA_ORGAN_DAMAGE}}
     - \+10% {{BLEEDING}}

---