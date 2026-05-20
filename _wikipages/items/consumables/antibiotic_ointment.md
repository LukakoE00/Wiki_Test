---
layout: contentpage
title: Antibiotic Ointment
category: items
subcategory: consumables
permalink: /items/consumables/antibiotic_ointment
image: /images/svg/anybodypart.svg
inline_image: /images/items/consumables/antibiotic_ointment.png

blocks:
  - type: description
    header: "Description:"
    order: 1
    text: |
     #### Medical Skill Check: 10

     Antibiotic ointment is an item used to treat {{INFECTED_WOUNDS}} and prevent them for some time.

     It can be crafted at a medical fabricator or bought from a medical merchant.

  - type: application_success
    header: "Application Success:"
    order: 2
    text: |
     - \-72% {{INFECTED_WOUNDS}}
     - \+120% {{OINTMENTED}}
     - \-12% {{BURNS}}

  - type: application_failure
    header: "Application Failure:"
    order: 3
    text: |
     - \-24% {{INFECTED_WOUNDS}}
     - \+60% {{OINTMENTED}}
     - \-7.2% {{BURNS}}

---