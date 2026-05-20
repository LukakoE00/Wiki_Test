---
layout: contentpage
title: Organ Rejection
category: gamemechanics
subcategory: base_mechanics
permalink: /mechanics/organ_rejection

blocks:
  - type: description
    header: "Description:"
    order: 1
    text: |
     #### This mechanic is off by default. It can be toggled in the {{CONFIGURATION_MENU}}.

     Organ rejection may occur when a patient receives an organ transplant while their {{IMMUNITY}} is higher than 10%. If organ rejection occurs, the organ that was transplanted will immediately gain 100% damage, making it useless.

     Reducing {{IMMUNITY}} is primarily done using {{AZATHIOPRINE}}.

     At 100% {{IMMUNITY}}, the chance for organ rejection is 60%. 

     #### Formula:
     RejectionChance = (CurrentImmunity - 0.1) / 1.5
---