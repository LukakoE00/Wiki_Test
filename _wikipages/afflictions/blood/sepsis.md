---
layout: contentpage
title: Sepsis
category: afflictions
subcategory: blood
permalink: /afflictions/blood/sepsis/
image: /images/svg/blood.svg
inline_image: /images/afflictions/blood/sepsis.png

blocks:
  - type: description
    header: "Description:"
    order: 1
    text: |
     Sepsis is a dangerous affliction caused by letting {{INFECTED_WOUNDS}} fester. Sepsis is rather easy to spot, as only one other affliction in the game will give you {{FEVER}}.
  
  - type: caused_by
    header: "Caused By:"
    order: 2
    text: |
     - Failing {{AZATHIOPRINE}} skill check
     - {{BLOOD_PACKS}} who's donor had sepsis
     - {{GANGRENE}} (15% or more)
     - {{FOREIGN_BODIES}} (20% or more)
     - {{INFECTED_WOUNDS}} (50% or more)
     - {{DIALYSIS_FILTER}}(0.1% chance per second)
     - {{TOXIN_FILTER}} (0.1% chance per second)
  
  - type: effects
    header: "Effects:"
    order: 3
    text: |
     - {{LIVER_DAMAGE}} (3% or more, point at which it outpaces natural regeneration)
     - {{HEART_DAMAGE}} (at 3% or more, point at which it outpaces natural regeneration)
     - {{LUNG_DAMAGE}} (at 3% or more, point at which it outpaces natural regeneration)
     - {{GANGRENE}} (at 5% or more)
     - {{FEVER}} (at 5% or more)
     - {{KIDNEY_DAMAGE}} (at 6% or more, point at which it outpaces natural regeneration, 3% if one kidney is dead)
     - {{HYPERVENTILATION}} (at 15% or more)
     - {{INCREASED_HEARTRATE}} (at 20% or more)
     - {{NEUROTRAUMA}} (at 25% or more, point at which it outpaces natural regeneration)
     - {{CONFUSION}} (at 40% or more)
     - {{BONE_DAMAGE}} (at 50% or more, point at which it outpaces natural regeneration)
  
  - type: treatments
    header: "Treatments:"
    order: 4
    text: |
     - {{BROAD_SPECTRUM_ANTIBIOTICS}}
---