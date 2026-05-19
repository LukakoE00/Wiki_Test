---
layout: contentpage
title: Blood Loss
category: afflictions
subcategory: blood
permalink: /afflictions/blood/blood_loss/
image: /images/svg/blood.svg
inline_image: /images/afflictions/blood/blood_loss.png

blocks:
  - type: description
    header: "Description:"
    order: 1
    text: |
     While blood loss can be extremely resource-intensive to cure if it's severe enough, when it's at or below 30%, it can usually be ignored.
  
  - type: caused_by
    header: "Caused By:"
    order: 2
    text: |
     - {{INTERNAL_BLEEDING}}
     - Using an {{EMPTY_BLOOD_PACK}}
     - {{BLEEDING}}
     - {{ARTERIAL_BLEEDING}} (doesn’t give more than 99.5% blood loss)
     - {{AORTIC_RUPTURE}}
     - {{SURGERY_INCISION}} (unless they have {{CLAMPED_BLEEDING}})
     - {{HEMATOLOGY_ANALYZER}}
     - {{HEMOTRANSFUSION_SHOCK}} (between 0-70%)
  
  - type: effects
    header: "Effects:"
    order: 3
    text: |
     - {{HYPOTENSION}} (scales depending on how much blood loss)
     - {{HYPOXEMIA}} (at 40% or more)
     - {{INCREASED_HEARTRATE}} (at 40% or more)
     - {{PALE_SKIN}} (at 40% or more)
     - {{HEADACHE}} (at 50% or more)
     - {{WEAKNESS}} (at 60% or more)
  
  - type: treatments
    header: "Treatments:"
    order: 4
    text: |
     - Giving {{BLOOD_PACKS}}
     - {{DEUSIZINE}}
     - Time
     - {{COMBAT_STIMULANT}}
---