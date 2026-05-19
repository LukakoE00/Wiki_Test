---
layout: contentpage
title: Radiation Sickness
category: afflictions
subcategory: torso
permalink: /afflictions/torso/radiation_sickness/
image: /images/svg/torso.svg
inline_image: /images/afflictions/torso/radiation_sickness.png

blocks:
  - type: description
    header: "Description:"
    order: 1
    text: |
     Low levels of radiation sickness are easily treatable, but if radiation sickness gets high enough, it will quickly begin killing the organs. Lungs will take more damage from radiation than other organs. Radiation sickness will appear on the health scanner at 25% and above.

     ---

  - type: caused_by
    header: "Caused By:"
    order: 2
    text: |
     - {{HEALTH_SCANNER}} (0.5% per second to person getting scanned, 0.3% per second to person scanning, 1% if used as a treatment, as you would a bandage)
     - {{RADIOTOXIN}}
     - Nuclear explosions
     - Being near a {{VOLATILE_FULGURIUM_FUEL_ROD}}
     - Swallowing Plutonium.
  
  - type: effects
    header: "Effects:"
    order: 3
    text: |
     - {{LIVER_DAMAGE}} (at 29% or more, point at which it outpaces natural regeneration)
     - {{HEART_DAMAGE}} (at 29% or more, point at which it outpaces natural regeneration)
     - {{KIDNEY_DAMAGE}} (at 33% or more, point at which it outpaces natural regeneration, 29% if one kidney is dead)
     - {{LUNG_DAMAGE}} (at 28% or more, point at which it outpaces natural regeneration)
     - {{BONE_DAMAGE}} (at 31% or more, point at which it outpaces natural regeneration)
     - {{NAUSEA}} (at 80% or more)
     - {{SEIZURE}} (at 50% or more)
  
  - type: treatments
    header: "Treatments:"
    order: 4
    text: |
     - {{ANTIRAD}}
---