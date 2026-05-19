---
layout: contentpage
title: Heart Transplant
category: items
subcategory: transplants
permalink: /items/transplants/heart_transplant
image: /images/svg/anybodypart.svg
inline_image: /images/items/transplants/heart_transplant.png

blocks:
  - type: description
    header: "Description:"
    order: 1
    text: |
     ### Medical skill check: 40

     A vital organ. The patient’s heart-related afflictions, such as {{HEART_DAMAGE}}, are directly linked to it.

     The heart may be removed or transplanted during an {{ORGAN_TRANSPLANT_SURGERY}} done on the torso. Removal of the heart causes immediate {{CARDIAC_ARREST}}, 100% {{HEART_DAMAGE}}, and up to 20% {{VANILLA_ORGAN_DAMAGE}}, inversely proportional to heart damage before removal. The condition of the organ is inversely proportional to heart damage before removal. The patient cannot gain and will be immediately relieved of {{CARDIAC_TAMPONADE}} and {{HEART_ATTACK}} while their heart is removed.

     If a heart is transplanted back into the patient, their {{HEART_DAMAGE}} and up to 20% {{VANILLA_ORGAN_DAMAGE}}, both inversely proportional to the condition of the organ, will be treated, but their {{CARDIAC_ARREST}} will not be treated. The patient may gain {{ORGAN_REJECTION}} if they receive the organ and their {{IMMUNITY}} is higher than 10%, if the mechanic is toggled on in the mod config.

     The condition of a heart will decay unless placed in a {{REFRIGERATED_CONTAINER}} or {{REFRIGERATED_CRATE}}. While refrigerated, the organ will slowly regain condition if it is above 90%, otherwise it will not change. If the organ or the container it is in hits the ground from a large height, it will be destroyed.
---