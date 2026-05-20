---
layout: contentpage
title: Toxin Filter
category: items
subcategory: upgrades
permalink: /items/upgrades/toxin_filter
image: /images/svg/anybodypart.svg
inline_image: /images/items/upgrades/toxin_filter.png

blocks:
  - type: description
    header: "Description:"
    order: 1
    text: |
     A filter which can be placed in the {{SURGERY_TABLE}} to treat the patient’s poisons.

     Only {{POISON_AFFLICTION_TYPE}} "smartCard-inline") added by vanilla are valid for the toxin filter. For the patient **laying** on the table, the filter reduces each poison at a unique rate depending on its strength. Multiple poisons can be filtered at once. For each poison being filtered, the condition of the filter reduces by 0.8/s, and there is a 0.1% chance per second for the patient to receive {{SEPSIS}}. These effects do not occur if the patient is not poisoned.

     #### {{MORBUSINE_POISONING}}

     - \-1.8%/s, 0-50% affliction strength
     - \-2.3%/s, 50-100% strength

     #### {{CYANIDE_POISONING}}

     - \-2.8/s, 0-30% strength
     - \-5.5/s, 30-100% strength

     #### {{SUFFORIN_POISONING}}

     - \-1/s, 0-50% strength
     - \-1.8/s, 50-100% strength

     #### {{DELIRIUMINE}}

     - \-1.6/s, 0-50% strength
     - \-2.3%, 50-100% strength

---