---
layout: contentpage
title: Neurotrauma
category: afflictions
subcategory: head_brain
permalink: /afflictions/head-brain/neurotrauma/
image: /images/svg/brain.svg
inline_image: /images/afflictions/head-brain/neurotrauma.png

blocks:
  - type: description
    header: "Description:"
    order: 1
    text: |
     Neurotrauma is one of the only things that can deal direct damage to your health. Neurotrauma is extremely dangerous and can build up very quickly, and upon reaching 200%, will instantly kill the player. The brain will heal at a rate of 0.1% per second, assuming that the {{CONFIGURATION_MENU}} is unchanged and nothing is damaging it.
  
  - type: caused_by
    header: "Caused By:"
    order: 2
    text: |
     - {{STROKE}}
     - {{LIVER_DAMAGE}} (80% or more, point at which it outpaces natural regeneration)
     - {{KIDNEY_DAMAGE}} (cancels out natural kidney regeneration at 100%)
     - {{SEPSIS}} (25% or more, point at which it outpaces natural regeneration)
     - {{HYPOXEMIA}} (10% or more, point at which it outpaces natural regeneration)
     - Using a {{TOURNIQUET}}  on the head
     - {{METHAMPHETAMINE}}
     - {{HYPERZINE}}
     - {{TRAUMATIC_SHOCK}} (equal to strength divided by 100 per second, 10% or more is the point at which it outpaces natural regeneration)
     - {{CYANIDE_POISONING}}  (70% or more)
     - {{OPEN_WOUNDS}}, chance when inflicted on head

     Additionally, {{SKULL_FRACTURES}} prevent the natural regeneration of neurotrauma. The gain or loss rate of neurotrauma depends on the affliction strengths of all its causes combined. The rate, including most common causes, can be calculated using the [Neurotrauma Gain Calculator](https://www.desmos.com/calculator/coqgws42wb) created by @‌arceronth.
  
  - type: effects
    header: "Effects:"
    order: 3
    text: |
     - Direct damage to vitality
     - Instant death (at 200%)
     - {{RESPIRATORY_ARREST}} (at 100% or more)
     - {{UNCONSCIOUSNESS}} (at 100% or more)
  
  - type: treatments
    header: "Treatments:"
    order: 4
    text: |
     - Treating the causes
     - {{MANNITOL}}
---