---
layout: contentpage
title: Fractures
category: afflictions
subcategory: bones
permalink: /afflictions/bones/fractures/
image: /images/svg/bones.svg
inline_image: /images/afflictions/bones/fractures.png

blocks:
  - type: description
    header: "Description:"
    order: 1
    text: |
     Fractures are common injuries, which most crewmembers will get often. Fractures will not kill, and should be treated last in an emergency. Having a fractured limb is required for it to become a {{TRAUMATIC_AMPUTATION}}, except for that on the head. Cyberlimbs cannot be fractured. The limb locking and character slowdown can be prevented with {{ADRENALINE}}, however, it will cause a lot of bleeding.
  
  - type: caused_by
    header: "Caused By:"
    order: 2
    text: |
     - {{INTERNAL_WOUNDS}}
     - {{OPEN_WOUNDS}}
     - {{BONE_DEATH}}
     - Failing the {{WRENCH}} skill check when treating {{DISLOCATIONS}}
  
  - type: effects
    header: "Effects:"
    order: 3
    text: |
     ### In leg fractures:

     - 1 leg fracture will halve speed
     - 2 leg fractures will force you to go prone.
     - {{INTENSE_PAIN}}
     - {{INTERNAL_WOUNDS}}, if not {{BANDAGED}}, in a {{PLASTER_CAST}}, or {{ANALGESIA}}

     ### In arm fractures:

     - 1 arm fracture will prevent you from using that arm (you can't hold 2-handed items anymore)
     - 2 arm fractures will prevent you from interacting with anything, such as doors, ladders, buttons, etc.
     - Arm locking doesn’t occur until the fracture reaches 100% or the user attempts to use a melee or ranged weapon, which additionally causes 70% {{BLEEDING}}
     - {{INTENSE_PAIN}}
     - {{INTERNAL_WOUNDS}}, if not {{BANDAGED}}, in a {{PLASTER_CAST}}, or {{ANALGESIA}}

     ### In skull fractures:

     - Prevents {{NEUROTRAUMA}} from naturally decreasing
     - {{HEADACHE}}

     ### In neck fractures:

     - {{SPINAL_CORD_INJURY}}randomly after reaching 100%, unless {{BANDAGED}}
     - {{INTERNAL_WOUNDS}}, if not {{BANDAGED}}

     ### In rib fractures:

     - {{PNEUMOTHORAX}} (unless {{BANDAGED}} )
     - {{CHEST_PAIN}}
  
  - type: treatments
    header: "Treatments:"
    order: 4
    text: |
     - {{PLASTER_CAST}} **(ONLY FOR ARM AND LEG FRACTURES)**
     - {{OSTEOSYNTHETIC_SURGERY}} (works on all fractures)
  
  - type: first_aid
    header: "First Aid:"
    order: 5
    text: |
     - {{BANDAGES}}
---