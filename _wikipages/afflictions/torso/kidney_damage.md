---
layout: contentpage
title: Kidney Damage
category: afflictions
subcategory: torso
permalink: /afflictions/torso/kidney_damage/
image: /images/svg/torso.svg
inline_image: /images/afflictions/torso/kidney_damage.png

blocks:
  - type: description
    header: "Description:"
    order: 1
    text: |
     Kidney damage is usually survivable, as even if it has progressed to kidney failure, it will still kill extremely slowly. Kidney damage will not heal below 50% damage if it passes the 50% threshold, as one of the kidneys has died. The kidneys will heal at a rate of 0.01% per second if one kidney is alive, and will heal at a rate of 0.02% per second if both kidneys are alive, assuming that the {{CONFIGURATION_MENU}} is unchanged and nothing is damaging them.

     ---

  - type: caused_by
    header: "Caused By:"
    order: 2
    text: |
     - {{BROAD_SPECTRUM_ANTIBIOTICS}}
     - {{LIQUID_OXYGENITE}}
     - {{HEMOTRANSFUSION_SHOCK}} (between 0-70%)
     - {{MANNITOL}}
     - {{RADIATION_SICKNESS}} (33% or more, point at which it outpaces natural regeneration, 29% if one kidney is dead)
     - {{HYPERTENSION}} (184% or more, point at which it outpaces natural regeneration, 152% if one kidney is dead)
     - {{SEPSIS}} (6% or more, point at which it outpaces natural regeneration, 3% if one kidney is dead)
     - {{HYPOXEMIA}} (8% or more, point at which it outpaces natural regeneration, 4% if one kidney is dead)
     - {{SUFFORIN_POISONING}} (75% or more)
     - {{INTERNAL_WOUNDS}}
     - {{OPEN_WOUNDS}}
  
  - type: effects
    header: "Effects:"
    order: 2
    text: |
     - {{LEG_SWELLING}} (at 60% or more)
     - {{ACIDOSIS}} (at 80% or more)
     - {{HYPERTENSION}}
     - {{BONE_DAMAGE}} (at 72% or more, point at which it outpaces natural regeneration)
     - {{VOMITING}} (at 60% or more)
     - {{NEUROTRAUMA}} (will neutralize natural regeneration completely at 100%)
     - {{NAUSEA}} (at 60% or more)
  
  - type: treatments
    header: "Treatments:"
    order: 3
    text: |
     - Time
     - {{THIAMINE}}
     - {{ORGAN_TRANSPLANT_SURGERY}}
---