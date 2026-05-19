---
layout: contentpage
title: Lung Damage
category: afflictions
subcategory: lungs
permalink: /afflictions/lungs/lung_damage/
image: /images/svg/lungs.svg
inline_image: /images/afflictions/lungs/lung_damage.png

blocks:
  - type: description
    header: "Description:"
    order: 1
    text: |
     Lung damage is not lethal, as long as it is below 100%. The lungs will heal at a rate of 0.01% per second, assuming that the config is unchanged, nothing is damaging them and they're below 100% damage.
  
  - type: caused_by
    header: "Caused By:"
    order: 2
    text: |
     - {{BROAD_SPECTRUM_ANTIBIOTICS}}
     - {{LIQUID_OXYGENITE}}
     - Using an {{AMBUBAG}} containing welding/incendium fuel or paint
     - Smoking
     - {{HEMOTRANSFUSION_SHOCK}} (between 0-70%)
     - {{RADIATION_SICKNESS}} (28% or more, point at which it outpaces natural regeneration)
     - {{SEPSIS}} (3% or more, point at which it outpaces natural regeneration)
     - {{HYPOXEMIA}} (4% or more, point at which it outpaces natural regeneration)
     - {{INTERNAL_WOUNDS}}
     - {{OPEN_WOUNDS}}
  
  - type: effects
    header: "Effects:"
    order: 3
    text: |
     - {{COUGH}} (at 50% or more)
     - {{SHORTNESS_OF_BREATH}} (at 45% or more)
     - {{RESPIRATORY_ARREST}} (at 100%)
  
  - type: treatments
    header: "Treatments:"
    order: 4
    text: |
     - Time
     - {{THIAMINE}}
     - {{ORGAN_TRANSPLANT_SURGERY}}
---