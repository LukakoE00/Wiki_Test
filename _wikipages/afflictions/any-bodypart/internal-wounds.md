---
layout: contentpage
title: Internal Wounds
category: afflictions
subcategory: any_bodypart
permalink: /afflictions/any-bodypart/internal-wounds/
image: /images/svg/anybodypart.svg
inline_image: /images/afflictions/any-bodypart/internal_wounds.png

blocks:
  - type: description
    header: "Description:"
    order: 1
    text: |
     The damage that a person may receive is divided into two groups based on their properties, {{OPEN_WOUNDS}} and Internal Wounds.

     Internal Wounds do not cause {{INFECTED_WOUNDS}}.

     Unless specified, the following afflictions are gained based on a percentage chance. This means more damage taken will result in a higher chance of gaining them. The afflictions are gained on the limb in which damage was taken, so afflictions not applicable to the limb will not be gained.

  - type: blunt_force_trauma
    header: "Blunt Force Trauma:"
    order: 2
    text: |
     This type of wound is typically not associated with bleeding, but may still cause life-threatening afflictions if it is a strong hit. Does not naturally regenerate past 100 strength.

     ### Causes:

     - Falling, being knocked into a wall
     - Crushed by a submarine
     - Blunt weapons, such as a crowbar.

     ### Effects:

     - Vitality loss, proportional to damage taken
     - {{DISLOCATIONS}}, after taking at least 2 damage
     - {{ARM_FRACTURES}} and {{LEG_FRACTURES}}, >2 damage
     - {{SKULL_FRACTURES}}, >15 damage, at least 70% chance
     - {{NECK_FRACTURES}}, >15 damage
     - {{RIB_FRACTURES}}
     - Organ damage or {{VANILLA_ORGAN_DAMAGE}}, random range between 0 and damage taken
     - {{PNEUMOTHORAX}}, >5 damage
     - {{CONCUSSION}}, >15 damage, at least 70% chance
     - {{TRAUMATIC_AMPUTATION}}, >15 damage and there is a fracture on the limb

     Unless specified, the aforementioned afflictions are gained based on chance. This means more damage taken will result in a higher chance of gaining them. The afflictions are gained on the limb in which damage was taken, so afflictions not applicable to the limb will not be gained.

     ### Treatments:

     - Time, unless it is over 100 strength
     - {{BANDAGED}}, unless it is over 100 strength
     - {{GEL_COOLANT_PACK}}, unless it is over 100 strength
     - Using {{TWEEZERS}} before {{SUTURES}} during {{OPEN_CLOSE_SURGERY}}
     - {{COMBAT_STIMULANT}}
     - Pomegrenade Extract

  - type: internal_damage
    header: "Internal damage:"
    order: 3
    text: |
     An uncommon wound which is typically caused by other afflictions and failed skill checks. Unlike other damage types, internal damage does not appear in the Health UI.

     ### Causes:

     - {{DISLOCATIONS}}, when they are not{{BANDAGED}}
     - {{FRACTURES}}, when they do not have a {{PLASTER_CAST}}
     - Failing the skill check when using:
       - {{TWEEZERS}}
       - {{SUTURES}}
       - {{SKIN_RETRACTORS}}
       - {{SURGICAL_DRILL}}
       - {{SURGICAL_SAW}}
       - {{SPINAL_CORD_IMPLANTS}}
       - {{OSTEOSYNTHESIS_IMPLANTS}}

     ### Effects:

     - Vitality loss, proportional to damage taken
     - {{DISLOCATIONS}}
     - {{ARM_FRACTURES}} and {{LEG_FRACTURES}}, after taking at least 5 damage
     - {{SKULL_FRACTURES}}, >15 damage, at least 70% chance
     - {{NECK_FRACTURES}}, >15 damage
     - {{RIB_FRACTURES}}, >5 damage
     - Organ damage or {{VANILLA_ORGAN_DAMAGE}}, random range between 0 and damage taken
     - {{PNEUMOTHORAX}}, >5 damage
     - {{CONCUSSION}}, >15 damage, at least 70% chance
     - {{TRAUMATIC_AMPUTATION}}, >10 damage and there is a fracture on the limb

     ### Treatments:

     - Time
     - Using {{TWEEZERS}} before {{SUTURES}} during {{OPEN_CLOSE_SURGERY}}
     - {{COMBAT_STIMULANT}}
     - Pomegrenade Extract
---