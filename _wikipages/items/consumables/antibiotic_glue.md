---
layout: contentpage
title: Antibiotic Glue
category: items
subcategory: consumables
permalink: /items/consumables/antibiotic_glue
image: /images/svg/anybodypart.svg
inline_image: /images/items/consumables/antibiotic_glue.png

blocks:
  - type: description
    header: "Description:"
    order: 1
    text: |
     #### Medical Skill Check: 55

     A glue used to quickly seal bleeding wounds and treat {{BURNS}} on a single limb. Also treats {{INFECTED_WOUNDS}}.

  - type: application_success
    header: "Application Success:"
    order: 2
    text: |
     - \-60% {{BLEEDING}}.
     - \-15% {{BURNS}}.
     - \-100% {{INFECTED_WOUNDS}}.

  - type: application_failure
    header: "Application Failure:"
    order: 3
    text: |
     - \-40% {{BLEEDING}}.
     - \-10% {{BURNS}}.
     - \-100% {{INFECTED_WOUNDS}}.
     - 50% chance to cause {{HEART_ATTACK}} if {{BLEEDING}}.
---