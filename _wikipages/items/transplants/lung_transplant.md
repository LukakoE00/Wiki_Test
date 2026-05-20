---
layout: contentpage
title: Lung Transplant
category: items
subcategory: transplants
permalink: /items/transplants/lung_transplant
image: /images/svg/anybodypart.svg
inline_image: /images/items/transplants/lung_transplant.png

blocks:
  - type: description
    header: "Description:"
    order: 1
    text: |
     #### Medical Skill Check: 40

     A vital organ. The patient’s lung-related afflictions, such as {{LUNG_DAMAGE}}, are directly linked to it.

     The lungs may be removed or transplanted during an {{ORGAN_TRANSPLANT_SURGERY}} done on the torso. Removal of the lungs causes immediate {{RESPIRATORY_ARREST}}, 100% {{LUNG_DAMAGE}}, and up to 20% {{VANILLA_ORGAN_DAMAGE}}, inversely proportional to lung damage before removal. The condition of the organ is inversely proportional to lung damage before removal. The patient cannot gain and will be immediately relieved of {{PNEUMOTHORAX}}, and will gain {{OXYGEN_LOW}} even if they are receiving {{SURGERY_TABLE}} or wearing an {{AUTOPULSE}}, while their lungs are removed.

     If the lungs are transplanted back into the patient, their {{LUNG_DAMAGE}} and up to 20% {{VANILLA_ORGAN_DAMAGE}}, both inversely proportional to the condition of the organ, will be treated, but their {{RESPIRATORY_ARREST}} will not be treated. The patient may gain {{ORGAN_REJECTION}} if they receive the organ and their {{IMMUNITY}} is higher than 10%, if the mechanic is toggled on in the mod {{CONFIGURATION_MENU}}.

     The condition of the lungs will decay unless placed in a {{REFRIGERATED_CONTAINER}} or {{REFRIGERATED_CRATE}}. While refrigerated, the organ will slowly regain condition if it is above 90%, otherwise it will not change. If the organ or the container it is in hits the ground from a large height, it will be destroyed.

---