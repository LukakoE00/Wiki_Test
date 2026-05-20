---
layout: contentpage
title: Immunity
category: gamemechanics
subcategory: base_mechanics
permalink: /mechanics/immunity

blocks:
  - type: description
    header: "Description:"
    order: 1
    text: |
     Immunity helps fight {{INFECTED_WOUNDS}} and increases natural healing. If your immunity is 6% or lower, you can use incompatible blood types without triggering {{HEMOTRANSFUSION_SHOCK}}. Immunity must be below 10% to safely transplant organs if you have organ rejection turned on in the {{CONFIGURATION_MENU}} menu.
  
  - type: reduced_by
    header: "Reduced By:"
    order: 2
    text: |
     - {{AZATHIOPRINE}}
     - Fighting {{INFECTED_WOUNDS}}
  
  - type: helps_heal
    header: "Helps Heal:"
    order: 3
    text: |
     - {{BURNS}}
     - {{OPEN_WOUNDS}}
---