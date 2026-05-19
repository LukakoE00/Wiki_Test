---
layout: contentpage
title: Blood Packs
category: items
subcategory: consumables
permalink: /items/consumables/blood_packs
image: /images/svg/anybodypart.svg
inline_image: /images/items/consumables/blood_packs.png

blocks:
  - type: description
    header: "Description:"
    order: 1
    text: |
     Blood packs are acquired from using an {{EMPTY_BLOOD_PACK}} on a human with less than 31% {{BLOOD_LOSS}}. Blood packs must be administered to the correct bloodtype, which is stated in the description of the item.

     ### Compatible blood type application

     \-30% {{BLOOD_LOSS}}
     \+30% blood pressure

     ### Incompatible blood type application

     \-20% {{BLOOD_LOSS}}
     \+30% blood pressure
     \+100% {{HEMOTRANSFUSION_SHOCK}}

     If the human that the blood pack came from was suffering from either {{ACIDOSIS}}, {{ALKALOSIS}}, or {{SEPSIS}}, then those afflictions will be stored in the blood pack (1/10 of the donor’s affliction strength for acidosis or alkalosis). Placing a blood pack in a {{HEMATOLOGY_ANALYZER}} will show if it has any of these afflictions and their strength. Additionally, if a recipient has acidosis or alkalosis, administering neutral blood will multiply it by 0.9, unless they have 0% bloodloss.

---