---
layout: contentpage
title: Anesthesia
category: afflictions
subcategory: torso
permalink: /afflictions/torso/anesthesia/
image: /images/svg/torso.svg
inline_image: /images/afflictions/torso/anesthesia.png

blocks:
  - type: description
    header: "Description:"
    order: 1
    text: |
     Anesthesia is an affliction that prevents traumatic shock during surgery, and unlike {{ANALGESIA}}, doesn't require a {{SURGERY_TABLE}} to perform safe surgery. Anesthesia will immediately wear off upon reaching 100% strength. Anesthesia will also slow your character down by 50%.
  
  - type: caused_by
    header: "Caused By:"
    order: 2
    text: |
     - {{PROPOFOL}}
  
  - type: effects
    header: "Effects:"
    order: 3
    text: |
     - {{HYPOVENTILATION}} (at 40% or more)
     - {{UNCONSCIOUSNESS}} (at 15% or more)
     - {{ANALGESIA}} (doesn't give more than 5% analgesia)
     - 50% slower movement speed
     - Possible sideeffects include:
       - {{HYPOTENSION}}
       - {{CONFUSION}}
       - {{BLURRED_VISION}}
       - {{FEVER}}
       - {{FIBRILLATION}}
       - {{SEIZURE}}
       - {{VOMITING_BLOOD}}
       - Psychosis
  
  - type: treatments
    header: "Treatments:"
    order: 4
    text: |
     - {{ANAPARALYZANT}}
     - Time
---