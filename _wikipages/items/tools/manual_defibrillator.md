---
layout: contentpage
title: Manual Defibrillator
category: items
subcategory: tools
permalink: /items/tools/manual_defibrillator
image: /images/svg/anybodypart.svg
inline_image: /images/items/tools/manual_defibrillator.png

blocks:
  - type: description
    header: "Description:"
    order: 1
    text: |
     An item used to correct the heartbeat of a patient. When used on a patient and charged with batteries, the defibrillator has a chance to either reset {{FIBRILLATION}}, cause {{CARDIAC_ARREST}}, or cure cardiac arrest. Using any defibrillator on a human will stun them for one second.

     The chance for these is depicted in the graph below, with cyan being the chance to reset fibrillation, pink being the chance to cause cardiac arrest and orange being the chance to cure it. The X axis is medical skill and the Y axis is the chance to do something (with 1 being 100%).

     At medical skill below 80, the {{AUTOMATED_EXTERNAL_DEFIBRILLATOR_AED}} has better chances in all regards. At 100 medical skill, the manual defibrillator is superior. Manual defibrillator becomes perfectly safe, and is guaranteed to cure cardiac arrest and fibrillation.

     !{{GRAPH_PNG}}
---