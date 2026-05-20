---
layout: contentpage
title: Alien Blood
category: items
subcategory: consumables
permalink: /items/consumables/alien_blood
image: /images/svg/anybodypart.svg
inline_image: /images/items/consumables/alien_blood.png

blocks:
  - type: description
    header: "Description:"
    order: 1
    text: |
     #### Medical Skill Check: 40

     Using Alien Blood in place of regular blood is extremely dangerous and should only be used in dire situations.

  - type: application_success
    header: "Application Success:"
    order: 2
    text: |
     - \-20% {{BLOOD_LOSS}}
     - \+60% [Psychosis](https://barotraumagame.com/wiki/Psychosis)
     - \+100% {{HEMOTRANSFUSION_SHOCK}}

  - type: application_failure
    header: "Application Failure:"
    order: 3
    text: |
     - \-20% {{BLOOD_LOSS}}
     - \+60% [Psychosis](https://barotraumagame.com/wiki/Psychosis)
     - \+100% {{HEMOTRANSFUSION_SHOCK}}
---