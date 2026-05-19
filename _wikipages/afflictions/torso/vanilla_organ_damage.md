---
layout: contentpage
title: Vanilla Organ Damage
category: afflictions
subcategory: torso
permalink: /afflictions/torso/vanilla_organ_damage/
image: /images/svg/torso.svg
inline_image: /images/afflictions/torso/vanilla_organ_damage.png

blocks:
  - type: description
    header: "Description:"
    order: 1
    text: |
     A side effect of some medicines. Additional organ damage is caused by failing the medical skill check of those medicines.

     In Neurotrauma, it is not considered a form of damage and cannot be treated by sources which treat damage.
  
  - type: caused_by
    header: "Caused By:"
    order: 2
    text: |
     - {{ALIEN_BLOOD}} +3.75 or 7.5%
     - {{BROAD_SPECTRUM_ANTIBIOTICS}} +20 or 12% over antibiotics duration
     - {{CHLORAL_HYDRATE}} +2.5%
     - {{LIQUID_OXYGENITE}} +6 or 10%
     - {{MANNITOL}} +5 or 10%
     - {{METHAMPHETAMINE}} +15 or 30%
     - {{SUFFORIN_POISONING}} (at 75% or more)
     - {{INTERNAL_WOUNDS}}
     - {{OPEN_WOUNDS}}
  
  - type: treatments
    header: "Treatments:"
    order: 3
    text: |
     - Time
     - {{DEUSIZINE}}
     - {{ORGAN_TRANSPLANT_SURGERY}} will heal some vanilla organ damage with fresh organs
     - {{THIAMINE}}
---