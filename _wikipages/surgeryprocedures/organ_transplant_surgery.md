---
layout: contentpage
title: Organ Transplant Surgery
category: surgeryprocedures
subcategory: base_procedures
permalink: /procedures/organ_transplant_surgery

blocks:
  - type: description
    header: "Description:"
    order: 1
    text: |
     (if {{ORGAN_REJECTION}} is turned on in the {{CONFIGURATION_MENU}}): Make sure to use {{AZATHIOPRINE}} before placing the organ in, and make sure their immunity is 10% or lower. If organ damage is 100% after placing it in, that means it got rejected.
  
  - type: steps
    header: "Steps:"
    order: 2
    text: |
     1. Anesthetic of your choice ({{ANALGESIA}}, {{ANESTHESIA}} )
     2. {{SCALPEL}}, on the torso
     3. {{HEMOSTAT}}, on the torso
     4. {{SKIN_RETRACTORS}}, on the torso
     5. {{MULTIPURPOSE_SCALPEL}}, adaptive organ extraction mode (read item description for instructions)
     6. The respective organ transplant item (trades organ) **or** Multipurpose scalpel again (removes organ)
     7. {{SUTURES}}
---