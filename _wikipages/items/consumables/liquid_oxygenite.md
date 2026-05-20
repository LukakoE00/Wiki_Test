---
layout: contentpage
title: Liquid Oxygenite
category: items
subcategory: consumables
permalink: /items/consumables/liquid_oxygenite
image: /images/svg/anybodypart.svg
inline_image: /images/items/consumables/liquid_oxygenite.png

blocks:
  - type: description
    header: "Description:"
    order: 1
    text: |
     #### Medical Skill Check: 72

     A liquified alien material used to inject oxygen directly into the bloodstream, treating {{HYPOXEMIA}}.

  - type: application_success
    header: "Application Success:"
    order: 2
    text: |

     All effects occur over 30 seconds:

     - \-3000% {{HYPOXEMIA}}
     - \+6% {{VANILLA_ORGAN_DAMAGE}}
     - \+6% {{LUNG_DAMAGE}}
     - \+6% {{LIVER_DAMAGE}}
     - \+6% {{HEART_DAMAGE}}
     - \+6% {{KIDNEY_DAMAGE}}
     Effectively, Liquid Oxygenite will make the user immune to hypoxemia during the 30 seconds.

  - type: application_success
    header: "Application Failure:"
    order: 3
    text: |

     All effects occur over 20 seconds:
     - \-200% {{HYPOXEMIA}}
     - \+10% {{VANILLA_ORGAN_DAMAGE}}
     - \+10% {{LUNG_DAMAGE}}
     - \+10% {{LIVER_DAMAGE}}
     - \+10% {{HEART_DAMAGE}}
     - \+10% {{KIDNEY_DAMAGE}}
---