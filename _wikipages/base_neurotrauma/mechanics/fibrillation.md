---
layout: contentpage
title: Fibrillation
category: gamemechanics
subcategory: base_mechanics
permalink: /mechanics/fibrillation
inline_image: /images/base_neurotrauma/mechanics/fibrillation.png

blocks:
  - type: description
    header: "Description:"
    order: 1
    text: |
     Fibrillation will start off as increased heartrate which will slowly increase. Once increase heartrate reaches 100%, the victim will enter fibrillation, and symptoms will start.
  
  - type: caused_by
    header: "Caused By:"
    order: 2
    text: |
     - {{AORTIC_RUPTURE}}
     - {{ACIDOSIS}}
     - {{HYPOTENSION}}
     - {{HYPOXEMIA}}
     - {{ANESTHESIA}}
  
  - type: effects
    header: "Effects:"
    order: 3
    text: |
     - {{CARDIAC_ARREST}} (at 20% or more)
     - {{HYPOTENSION}} (at 100%)
  
  - type: treatments
    header: "Treatments:"
    order: 4
    text: |
     - Treating the causes
     - {{ADRENALINE}} (slows down fibrillation)
     - {{MANUAL_DEFIBRILLATOR}} or {{AED}}
---