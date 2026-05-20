---
layout: contentpage
title: Mannitol
category: items
subcategory: consumables
permalink: /items/consumables/mannitol
image: /images/svg/anybodypart.svg
inline_image: /images/items/consumables/mannitol.png

blocks:
  - type: description
    header: "Description:"
    order: 1
    text: |
     #### Medical Skill Check: 60

     Mannitol is a medication used to treat {{NEUROTRAUMA}} and halve its gain. In return, it causes various organ damage. For Mannitol to treat {{NEUROTRAUMA}}, Blood Pressure must be greater than 70% and {{HYPOXEMIA}} must be less than 30%

  - type: application_success
    header: "Application Success:"
    order: 2
    text: |

     - \+50% Mannitol (treats up to 100% {{NEUROTRAUMA}})
     - \+5% {{VANILLA_ORGAN_DAMAGE}}
     - \+10% {{HEART_DAMAGE}}
     - \+10% {{KIDNEY_DAMAGE}}

  - type: application_failure
    header: "Application Failure:"
    order: 3
    text: |

     - \+30% Mannitol (treats up to 60% {{NEUROTRAUMA}})
     - \+10% {{VANILLA_ORGAN_DAMAGE}}
     - \+20% {{HEART_DAMAGE}}
     - \+20% {{KIDNEY_DAMAGE}}

     Effects occur over 10 seconds.

---