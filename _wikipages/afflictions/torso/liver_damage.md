---
layout: contentpage
title: Liver Damage
category: afflictions
subcategory: torso
permalink: /afflictions/torso/liver_damage/
image: /images/svg/torso.svg
inline_image: /images/afflictions/torso/liver_damage.png

blocks:
  - type: description
    header: "Description:"
    order: 1
    text: |
     Liver damage, if progressed to liver failure, is fatal and can cause massive blood loss in the form of {{INTERNAL_BLEEDING}}. The liver will heal at a rate of 0.01% per second, assuming that the config is unchanged, nothing is damaging it and it's below 100% damage.

  - type: caused_by
    header: "Caused By:"
    order: 2
    text: |
     - {{BROAD_SPECTRUM_ANTIBIOTICS}}
     - {{LIQUID_OXYGENITE}}
     - {{HEMOTRANSFUSION_SHOCK}} (between 0-70%)
     - {{RADIATION_SICKNESS}} (29% or more, point at which it outpaces natural regeneration)
     - {{SEPSIS}} (3% or more, point at which it outpaces natural regeneration)
     - {{HYPOXEMIA}} (4% or more, point at which it outpaces natural regeneration)
     - {{DRUNK}} (over 40%)
     - {{SUFFORIN_POISONING}} (75% or more)
     - {{INTERNAL_WOUNDS}}
     - {{OPEN_WOUNDS}}
  
  - type: effects
    header: "Effects:"
    order: 2
    text: |
     - {{LEG_SWELLING}} (at 40% or more)
     - {{INTERNAL_BLEEDING}} (at 100%)
     - {{VOMITING_BLOOD}} (at 100%)
     - {{HYPERTENSION}}
     - {{NEUROTRAUMA}} (at 80% or more, point at which it outpaces natural regeneration)
     - {{ABDOMINAL_DISCOMFORT}} (at 65% or more)
     - {{JAUNDICE}} (at 80% or more)
     - {{BLOATING}} (at 50% or more)
     - Reduced ability to heal bleeding, bleeding will not heal at all at 100% damage
  
  - type: treatments
    header: "Treatments:"
    order: 3
    text: |
     - Time
     - {{THIAMINE}}
     - {{ORGAN_TRANSPLANT_SURGERY}}
---