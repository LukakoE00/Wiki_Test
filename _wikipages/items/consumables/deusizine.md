---
layout: contentpage
title: Deusizine
category: items
subcategory: consumables
permalink: /items/consumables/deusizine
image: /images/svg/anybodypart.svg
inline_image: /images/items/consumables/deusizine.png

blocks:
  - type: description
    header: "Description:"
    order: 1
    text: |
     #### Medical Skill Check: 72

     A special drug, treating a variety of life-threatening afflictions over 20 seconds and providing a moderate Vigor buff.

  - type: application_success
    header: "Application Success:"
    order: 2
    text: |
     - \-20% {{INTERNAL_WOUNDS}}
     - \-50% {{BLOOD_LOSS}}
     - \-50% {{BLEEDING}}
     - \-100% {{HYPOXEMIA}}
     - \-20% {{VANILLA_ORGAN_DAMAGE}}
     - \-6% [Stun](https://barotraumagame.com/wiki/Stun)
     - \+4% {{BURNS}}
     - \+40% Blood Pressure
     - \+200% [Vigor](https://barotraumagame.com/wiki/Vigor)

  - type: application_failure
    header: "Application Failure:"
    order: 3
    text: |
     - \-10% {{INTERNAL_WOUNDS}}
     - \-25% {{BLOOD_LOSS}}
     - \-10% {{BLEEDING}}
     - \-40% {{HYPOXEMIA}}
     - \-10% {{VANILLA_ORGAN_DAMAGE}}
     - \+20% {{BURNS}}
     - \+20% Blood Pressure
     - \+200% [Vigor](https://barotraumagame.com/wiki/Vigor)

---