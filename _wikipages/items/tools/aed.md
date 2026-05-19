---
layout: contentpage
title: AED
category: items
subcategory: tools
permalink: /items/tools/aed
image: /images/svg/anybodypart.svg
inline_image: /images/items/tools/aed.png

blocks:
  - type: description
    header: "Description:"
    order: 1
    text: |
     An item used to correct the heartbeat of a patient. When used on a patient and charged with batteries, the aed has a chance to either reset {{FIBRILLATION}}, or cure {{CARDIAC_ARREST}}.

     The chance for these is depicted in this graph, with cyan being the chance to reset fibrillation, pink being the chance to cause cardiac arrest and orange being the chance to cure it. The X axis is medical skill and the Y axis is the chance to do something (with 1 being 100%).

     At medical skill below 80, the {{MANUAL_DEFIBRILLATOR}} is worse in all regards. At 100 medical skill, the manual defibrillator is better in all regards.

     !{{GRAPH2_PNG}}
---