---
layout: contentpage
title: Empty Blood Pack
category: items
subcategory: consumables
permalink: /items/consumables/empty_blood_pack
image: /images/svg/anybodypart.svg
inline_image: /images/items/consumables/empty_blood_pack.png

blocks:
  - type: description
    header: "Description:"
    order: 1
    text: |
     ### Medical skill check: 30

     Empty blood packs are used for acquiring {{BLOOD_PACKS}}. Empty blood packs can only be used on humans with less than 31% {{BLOOD_LOSS}}, otherwise it does nothing.

     ### Application success:

     \+30% {{BLOOD_LOSS}}

     ### Application failure:

     \+40% {{BLOOD_LOSS}}

     If the human that the empty blood pack is used on is suffering from either {{ACIDOSIS}}, {{ALKALOSIS}} or {{SEPSIS}}, then those afflictions will also be given to whoever the blood is given to (affliction gained will be the donor's affliction level at time of extraction divided by 5). Using an empty blood pack will multiply the patient’s acidosis or alkalosis by 0.9.

---