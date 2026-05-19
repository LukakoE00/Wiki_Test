---
layout: contentpage
title: Bone Damage
category: afflictions
subcategory: bones
permalink: /afflictions/bones/bone_damage/
image: /images/svg/bones.svg
inline_image: /images/afflictions/bones/bone_damage.png

blocks:
  - type: description
    header: "Description:"
    order: 1
    text: |
     Bone damage is not lethal, and can usually be ignored as long as it has not progressed to {{BONE_DEATH}} .
  
  - type: caused_by
    header: "Caused By:"
    order: 2
    text: |
     - {{KIDNEY_DAMAGE}} (72% or more, point at which it outpaces natural regeneration)
     - {{RADIATION_SICKNESS}} (31% or more, point at which it outpaces natural regeneration)
     - {{SEPSIS}} (50% or more, point at which it outpaces natural regeneration)
     - {{HYPOXEMIA}} (will neutralize natural regeneration completely at 100%)
  
  - type: effects
    header: "Effects:"
    order: 3
    text: |
     - {{BONE_DEATH}} (at 90% or more)
  
  - type: treatments
    header: "Treatments:"
    order: 4
    text: |
     - Time
     - {{OSTEOSYNTHETIC_SURGERY}}
---