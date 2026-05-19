---
layout: contentpage
title: Open Wounds
category: afflictions
subcategory: any_bodypart
permalink: /afflictions/any-bodypart/open-wounds/
image: /images/svg/anybodypart.svg
inline_image: /images/afflictions/any-bodypart/open_wounds.png

blocks:
  - type: description
    header: "Description:"
    order: 1
    text: |
     The damage that a person may receive is divided into two groups based on their properties, open wounds and {{INTERNAL_WOUNDS}}.

     All open wounds will cause {{INFECTED_WOUNDS}} proportional to their severity, and may be treated with {{SUTURES}}. They will also typically, but not always, be caused by sources which also inflict {{BLEEDING}}.

      Unless specified, the following afflictions are gained based on chance. This means more damage taken will result in a higher chance of gaining them. The afflictions are gained on the limb in which damage was taken, so afflictions not applicable to the limb will not be gained.

  - type: lacerations
    header: "Lacerations:"
    order: 2
    text: |
     A wound typically resulting from injuries involving sharps.

     ### Causes:

     - Being hit by sharp weapons, such as a {{DIVING_KNIFE}}
     - Submarine spalling
     - Using {{TWEEZERS}} when removing {{FOREIGN_BODIES}} or {{INTERNAL_WOUNDS}}

     ### Effects:

     - Vitality loss, proportional to damage taken
     - {{INFECTED_WOUNDS}} over time, depending on severity
     - Arm and {{LEG_FRACTURES}}, after taking at least 5 damage
     - Skull{{FRACTURES}}, >15 damage, at least 70% chance
     - {{RIB_FRACTURES}}, >10 damage
     - {{PNEUMOTHORAX}}, >5 damage
     - {{CARDIAC_TAMPONADE}}, >5 damage
     - {{INTERNAL_BLEEDING}}, >5 damage, random range between 0.2-0.5 times damage taken
     - {{TRAUMATIC_AMPUTATION}}, >1 damage and there is a fracture on the limb

     ### Treatments:

     - Time, unless it is over 50 strength
     - {{BANDAGED}}, unless it is over 50 strength
     - {{SUTURES}}
     - Pomegrenade Extract
     - {{COMBAT_STIMULANT}}

  - type: deep_tissue_injury
    header: "Deep tissue injury:"
    order: 3
    text: |
     A wound typically resulting from injuries involving explosions.

     ### Causes:

     - Being hit by explosives, such as a Frag Grenade.

     ### Effects:

     - Vitality loss, proportional to damage taken
     - {{INFECTED_WOUNDS}} over time, depending on severity
     - {{ARM_FRACTURES}} and {{LEG_FRACTURES}}, after taking at least 1 damage
     - {{SKULL_FRACTURES}}, >15 damage, at least 70% chance
     - {{NECK_FRACTURES}}, >15 damage
     - {{RIB_FRACTURES}}, >10 damage
     - {{PNEUMOTHORAX}}, >5 damage
     - {{CARDIAC_TAMPONADE}}, >5 damage
     - {{INTERNAL_BLEEDING}}, >5 damage, random range between 0.2-0.5 times damage taken
     - {{TRAUMATIC_AMPUTATION}}, >1 damage and there is a fracture on the limb
     - {{FOREIGN_BODIES}}, 75% chance, half of damage taken
     - {{CONCUSSION}}, >15 damage, at least 70% chance
     - {{DISLOCATIONS}}, >1 damage, 35% chance

     ### Treatments:

     - Time, unless it is over 50 strength
     - {{BANDAGED}}, unless it is over 50 strength
     - {{SUTURES}}
     - Pomegrenade Extract
     - {{COMBAT_STIMULANT}}

  - type: gunshot_wound
    header: "Gunshot wound:"
    order: 4
    text: |
     A wound typically resulting from injuries involving firearms.

     ### Causes:

     - Being shot by firearms, like a Revolver.

     ### Effects:

     - Vitality loss, proportional to damage taken
     - {{INFECTED_WOUNDS}} over time, depending on severity
     - {{ARM_FRACTURES}} and {{LEG_FRACTURES}}, after taking at least 1 damage
     - {{SKULL_FRACTURES}}, >15 damage, at least 70% chance
     - {{RIB_FRACTURES}}, >1 damage, no more than 30% chance
     - {{LUNG_DAMAGE}}, >1 damage, proportional to damage taken
     - {{HEART_DAMAGE}}, >5 damage, proportional to damage taken
     - {{KIDNEY_DAMAGE}} or {{LIVER_DAMAGE}}, >2 damage, proportional to damage taken
     - {{VANILLA_ORGAN_DAMAGE}}, >1 damage, a fourth of damage taken
     - {{PNEUMOTHORAX}}, >1 damage
     - {{CARDIAC_TAMPONADE}}, >5 damage
     - {{INTERNAL_BLEEDING}}, >5 damage, random range between 0.2-0.6 times damage taken
     - {{TRAUMATIC_AMPUTATION}}, >1 damage and there is a fracture on the limb
     - {{FOREIGN_BODIES}}, up to 30 strength proportional to damage taken when a fracture occurs, or at a 75% chance up to 20 strength proportional to a fourth of damage taken
     - {{NEUROTRAUMA}}, >5 damage, 70% chance at a random range between 0.1-0.4 times damage taken

     ### Treatments:

     - Time, unless it is over 50 strength
     - {{BANDAGED}}, unless it is over 50 strength
     - {{SUTURES}}
     - Pomegrenade Extract
     - {{COMBAT_STIMULANT}}

  - type: bite_wounds
    header: "Bite wounds:"
    order: 5
    text: |
     A wound typically resulting from injuries involving creature attacks.

     ### Causes:

     - Being hit by creatures, such as a Crawler.
     - Being bit by a human’s husk ovipositor

     ### Effects:

     - Vitality loss, proportional to damage taken
     - {{INFECTED_WOUNDS}} over time, depending on severity
     - {{ARM_FRACTURES}} and {{LEG_FRACTURES}}, after taking at least 5 damage
     - {{SKULL_FRACTURES}}, >15 damage, at least 70% chance
     - {{RIB_FRACTURES}}, >10 damage
     - {{PNEUMOTHORAX}}, >5 damage
     - {{INTERNAL_BLEEDING}}, >5 damage, random range between 0.2-0.5 times damage taken
     - {{TRAUMATIC_AMPUTATION}}, >5 damage and there is a fracture on the limb
     - {{CONCUSSION}}, >15 damage, at least 70% chance

     ### Treatments:

     - Time, unless it is over 100 strength
     - {{BANDAGED}}, unless it is over 100 strength
     - {{SUTURES}}
     - Pomegrenade Extract
     - {{COMBAT_STIMULANT}}

---