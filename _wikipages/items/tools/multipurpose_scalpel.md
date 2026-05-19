---
layout: contentpage
title: Multipurpose Scalpel
category: items
subcategory: tools
permalink: /items/tools/multipurpose_scalpel
image: /images/svg/anybodypart.svg
inline_image: /images/items/tools/multipurpose_scalpel.png

blocks:
  - type: description
    header: "Description:"
    order: 1
    text: |
     The Multipurpose Scalpel combines the functionality of the regular scalpel, the organ procurement scalpels, and the trauma shears, while also providing the user with a way of intentionally harming the patient.

     This item is craftable at a regular fabricator.

     The mode of this Scalpel is changed by equipping the item (akin to a weapon or tool) and clicking on the available UI buttons which appear.

     ### Mode: Surgery Incision

     In this mode, the item behaves identically to a regular {{SCALPEL}}.

     ### Mode: Bandages, Casts, Malpractice

     In this mode, as long as the patient has a bandage or a cast, the item functions identically to {{TRAUMA_SHEARS}}.
     Is this not the case, then using it will result in the patient getting stabbed. Depending on location and surgical status of the patient, this can cause serious damage.

     Notable outcomes include:

     - a chance for causing fractures in extremeties that are currently opened for surgery
     - causing neurotrauma on opened heads
     - causing specific organ damage and internal bleeding on opened torsos

     ### Mode: Adaptive Organ Extraction

     In this mode, the item will have the ability to extract any organ from a patient, and it is a required item for {{ORGAN_TRANSPLANT_SURGERY}}. The organ extracted depends on which limb has {{RETRACTED_SKIN}}, and which limb the Multipurpose Scalpel is used on:

     Retracted skin: Torso
     Left arm: {{KIDNEY_TRANSPLANT}}
     Torso: {{LIVER_TRANSPLANT}}
     Right arm: {{HEART_TRANSPLANT}}
     Left leg: {{LUNG_TRANSPLANT}}

     Retracted skin: Head
     Head: {{BRAIN_TRANSPLANT}}

---