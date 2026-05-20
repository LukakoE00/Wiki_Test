---
layout: contentpage
title: Traumatic Shock
category: afflictions
subcategory: surgery
permalink: /afflictions/surgery-afflictions/traumatic_shock/
image: /images/svg/surgery.svg
inline_image: /images/afflictions/surgery/traumatic_shock.png

blocks:
  - type: description
    header: "Description:"
    order: 1
    text: |
     Traumatic shock can rapidly become fatal, and should your patient acquire this at any point, it is likely to be unintended. Traumatic shock will decrease in strength 4x as fast provided the victim is under the effects of {{ANESTHESIA}}, or has {{ANALGESIA}} while being near a {{SURGERY_TABLE}}.

     If a character has {{RETRACTED_SKIN}} and the round ends (such as on docking to a station), the character will gain 5 minutes of traumatic shock immunity on the next round.

  - type: caused_by
    header: "Caused By:"
    order: 2
    text: |
     - Performing unsafe surgery:
       - {{SURGERY_INCISION}} without {{ANALGESIA}}
       - Any other surgical step after {{CLAMPED_BLEEDING}}  without sedation, such as being near a {{SURGERY_TABLE}} or having {{ANESTHESIA}}.
     - Using {{TWEEZERS}}  through gunshot wounds or deep tissue injuries (causes minor shock unless overused)
  
  - type: effects
    header: "Effects:"
    order: 3
    text: |
     - {{HYPOTENSION}}  (and lots of it)
     - {{CARDIAC_ARREST}}  (at 40% or more)
     - {{RESPIRATORY_ARREST}}  (at 30% or more)
     - {{NEUROTRAUMA}}  (equal to strength divided by 100 per second, 10% or more is the point at which it outpaces natural regeneration)
     - [Psychosis](barotraumagame.com/wiki/Psychosis) (equal to strength divided by 100 per second)
  
  - type: treatments
    header: "Treatments:"
    order: 4
    text: |
     - Terminating the surgery and waiting
     - Bringing into proximity of a {{SURGERY_TABLE}} and making sure the patient is sedated
  
  - type: prevention
    header: "Prevention:"
    order: 5
    text: |
     - Making sure that the surgery is safe before proceeding beyond the {{RETRACTED_SKIN}} step
     - Making sure {{ANALGESIA}} or other forms of sedation don’t run out in the middle of surgery
---