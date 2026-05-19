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
     ### Medical skill check: 20

     A consumable needle that reduces the strength of {{PNEUMOTHORAX}} to 15% and {{CARDIAC_TAMPONADE}} to 5%, but does not treat them. If the patient does not have pneumothorax, the needle will give them pneumothorax instead.

     ### Application success:

     - Reduces {{PNEUMOTHORAX}} to 15% over time
     - Reduces {{CARDIAC_TAMPONADE}} to 5% over time

     Effects persist until the Needle affliction wears off.

     ### Application failure:

     \+10% {{VANILLA_ORGAN_DAMAGE}}
     \+10% {{BLEEDING}}

---