---
layout: contentpage
title: Naloxone
category: items
subcategory: consumables
permalink: /items/consumables/naloxone
image: /images/svg/anybodypart.svg
inline_image: /images/items/consumables/naloxone.png

blocks:
  - type: description
    header: "Description:"
    order: 1
    text: |
     ### Medical skill check: 39

     Naloxone is used to treat the effects of opiates.

     ### Application success:

     \-60% Opiate {{WITHDRAWAL}}
     \-60% {{OPIATE_OVERDOSE}}
     \-60% Opiate addiction
     \-60% {{ANALGESIA}}
     \-60% {{OPIOIDS}}

     ### Application failure:

     \-30% Opiate {{WITHDRAWAL}}
     \-30% {{OPIATE_OVERDOSE}}
     \-30% Opiate addiction
     \-60% {{ANALGESIA}}
     \-60% {{OPIOIDS}}
     \+15% {{COMA}} (50% chance)
---