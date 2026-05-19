---
layout: contentpage
title: Heart Damage
category: afflictions
subcategory: heart
permalink: /afflictions/heart/heart_damage/
image: /images/svg/heart.svg
inline_image: /images/afflictions/heart/heart_damage.png

blocks:
  - type: description
    header: "Description:"
    order: 1
    text: |
     Heart damage is not lethal, as long as it is below 100%. The heart will heal at a rate of 0.01% per second, assuming that the config is unchanged, nothing is damaging it and it's below 100% damage.

  - type: caused_by
    header: "Caused By:"
    order: 2
    text: |
     - {{HEART_ATTACK}}
     - {{BROAD_SPECTRUM_ANTIBIOTICS}}
     - {{LIQUID_OXYGENITE}}
     - {{HEMOTRANSFUSION_SHOCK}} (between 0-70%)
     - {{MANNITOL}}
     - {{RADIATION_SICKNESS}} (29% or more, point at which it outpaces natural regeneration)
     - {{SEPSIS}} (3% or more, point at which it outpaces natural regeneration)
     - {{HYPOXEMIA}} (4% or more, point at which it outpaces natural regeneration)
     - {{INTERNAL_WOUNDS}}
     - {{OPEN_WOUNDS}}
     - {{SUFFORIN_POISONING}} (75% or more)
  
  - type: effects
    header: "Effects:"
    order: 3
    text: |
     - {{COUGH}} (at 50% or more)
     - {{SHORTNESS_OF_BREATH}} (at 80% or more)
     - {{LEG_SWELLING}} (at 80% or more)
     - {{CARDIAC_ARREST}} (at 100%)
  
  - type: treatments
    header: "Treatments:"
    order: 4
    text: |
     - Time
     - {{THIAMINE}}
     - {{ORGAN_TRANSPLANT_SURGERY}}

---