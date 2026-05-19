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
     ### Medical skill check: 10

     Antibiotic ointment is an item used to treat {{INFECTED_WOUNDS}} and prevent them for some time.

     It can be crafted at a medical fabricator or bought from a medical merchant.

     ### Application successful:

     \-72% {{INFECTED_WOUNDS}}
     \+120% {{OINTMENTED}}
     \-12% {{BURNS}}

     ### Application failure:

     \-24% {{INFECTED_WOUNDS}}
     \+60% {{OINTMENTED}}
     \-7.2% {{BURNS}}

---