---
layout: contentpage
title: Coma
category: afflictions
subcategory: head_brain
permalink: /afflictions/head-brain/coma/
image: /images/svg/brain.svg
inline_image: /images/afflictions/head-brain/coma.png

blocks:
  - type: description
    header: "Description:"
    order: 1
    text: |
     Coma often happens after suffocating, and usually isn't fatal with proper medical care. The recommended course of action is to strap an autopulse onto the patient if it is severe enough.
  
  - type: caused_by
    header: "Caused By:"
    order: 2
    text: |
     - {{STROKE}}
     - {{CARDIAC_ARREST}}
     - High levels of {{ACIDOSIS}}  (60% or more)
     - {{MORBUSINE_POISONING}} (20% or more)
     - Failing {{NALOXONE}} skill check
  
  - type: effects
    header: "Effects:"
    order: 3
    text: |
     - {{CARDIAC_ARREST}} (at 40% or more)
     - {{UNCONSCIOUSNESS}} (at 15% or more)
  
  - type: treatments
    header: "Treatments:"
    order: 4
    text: |
     - Treating the causes and waiting

     The natural regen rate of a coma will increase from 0.2/s to 0.5/s when the following conditions are met:

     - {{ACIDOSIS}} is below 20%
     - {{ALKALOSIS}} is below 20%
     - {{HEART_DAMAGE}} below 30%
     - {{LUNG_DAMAGE}} below 40%
     - Patient has full oxygen availability (comparable to having {{HYPOXEMIA}} at 0%)
---