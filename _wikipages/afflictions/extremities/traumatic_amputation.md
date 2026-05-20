---
layout: contentpage
title: Traumatic Amputation
category: afflictions
subcategory: extremities
permalink: /afflictions/extremities/traumatic_amputation/
image: /images/svg/extremities.svg
inline_image: /images/afflictions/extremities/traumatic_amputation.png

blocks:
  - type: description
    header: "Description:"
    order: 1
    text: |
     Traumatic amputation is the non-surgical amputation of an extremity. A traumatic amputation will act the exact same as a {{SURGICAL_AMPUTATION}} , besides from the fact that you will acquire {{ARTERIAL_BLEEDING}} upon first getting amputated. A limb must be fractured in order to become traumatically amputated.
  
  - type: caused_by
    header: "Caused By:"
    order: 2
    text: |
     - {{INTERNAL_WOUNDS}}
     - {{OPEN_WOUNDS}}
     - {{OPEN_WOUNDS}}, more than 75% (unique to head amputations)
  
  - type: effects
    header: "Effects:"
    order: 3
    text: |
     ### In all traumatic amputations:

     - {{ARTERIAL_BLEEDING}}
     - {{INTENSE_PAIN}}

     ### In leg amputations:

     - 1 leg amputation will halve speed
     - 2 leg amputations will force you to go prone

     ### In arm amputations:

     - 1 arm amputation will prevent you from using that arm (you cant hold 2-handed items anymore).
     - 2 arm amputations will prevent you from interacting with anything, such as doors, ladders, buttons, etc.

     ### In head amputations:

     - Instant death
  
  - type: treatments
    header: "Treatments:"
    order: 4
    text: |
     - {{AMPUTATION_SURGERY}}
     - Performing {{AMPUTATION_SURGERY}}  (use severed limb before applying {{SUTURES}} )
---