---
layout: contentpage
title: Hypotension
category: afflictions
subcategory: blood
permalink: /afflictions/blood/hypotension/
image: /images/svg/blood.svg
inline_image: /images/afflictions/blood/hypotension.png

blocks:
  - type: description
    header: "Description:"
    order: 1
    text: |
     Hypotension is blood pressure that has dropped below normal levels. Hypotension is lethal if it is severe enough. Lower percentages correspond to lower blood pressure.
  
  - type: caused_by
    header: "Caused By:"
    order: 2
    text: |
     - {{BLOOD_LOSS}} (scales depending on how much blood loss)
     - {{TRAUMATIC_SHOCK}}
     - {{ANESTHESIA}}
     - {{IRREGULAR_HEARTBEAT}}
     - {{NITROGLYCERIN}} (reduces blood pressure by 45%)
     - {{CARDIAC_ARREST}} (sets blood pressure to the minimum)
     - {{CARDIAC_TAMPONADE}} (halves blood pressure)
  
  - type: effects
    header: "Effects:"
    order: 3
    text: |
     - {{FIBRILLATION}}
     - {{CONFUSION}} (at 30% or less)
     - {{PALE_SKIN}} (at 50% or less)
     - {{BLURRED_VISION}} (at 55% or less)
     - {{HEADACHE}} (at 60% or less)
     - {{LIGHTHEADEDNESS}} (at 60% or less)
     - {{HYPOXEMIA}} (at 70% or less)
     - {{HYPERVENTILATION}} (at 80% or less)
  
  - type: treatments
    header: "Treatments:"
    order: 4
    text: |
     - Treating the causes
     - {{BLOOD_PACKS}}
     - {{SALINE}}
     - {{RINGER_S_SOLUTION}}
     - {{AUTOPULSE}}
     - {{ADRENALINE}}
     - {{DEUSIZINE}}
     - CPR
---