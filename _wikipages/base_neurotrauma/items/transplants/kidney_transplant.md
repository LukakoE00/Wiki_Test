---
layout: contentpage
title: Kidney Transplant
category: items
subcategory: transplants
permalink: /items/transplants/kidney_transplant
image: /images/svg/anybodypart.svg
inline_image: /images/base_neurotrauma/items/transplants/kidney_transplant.png

infobox:
  - title: Labels
    sections:
      - items:
          - Item
          - Essential

  - title: Statistics
    sections:
      - items:
          - "Skill Required: {{MEDICAL}} 40"
          - "Maximum inventory stack: 1"
          - "Should be refrigerated"

  - title: Crafting
    sections:
      - header: "Medical Fabricator Requirements"
        items:
            - "Cannot be fabricated."

      - header: "Deconstructor Yield"
        items:
            - "Has no deconstructor outputs."

  - title: Store
    sections:
      - items:
          - "Base Price: 400 Marks"
          - "Buyable at Merchant: Medical"

blocks:
  - type: description
    header: "Description:"
    order: 1
    text: |
     A pair of vital organs. The patient’s {{KIDNEY_DAMAGE}} is directly related to it. Unlike other organs, patients will have two kidneys, which are individually damaged. At 50% kidney damage, only one kidney has failed, while the other kidney will be functional. A patient may be healthy with only one kidney. By itself, 50% kidney damage will not cause lethal {{HYPERTENSION}}.

     The kidneys may be removed or transplanted during an {{ORGAN_TRANSPLANT_SURGERY}} done on the torso. Removing the kidneys will remove both at once, causing 100%{{KIDNEY_DAMAGE}} and up to 20% {{VANILLA_ORGAN_DAMAGE}}, inversely proportional to kidney damage before removal. The condition of the organs are inversely proportional to kidney damage before removal, up to 50% for each kidney. Therefore, removal of the kidneys at 25% kidney damage will produce one kidney at 100% and another one at 50%.

     If the kidneys are transplanted back into the patient, up to 50% {{KIDNEY_DAMAGE}} and up to 10% {{VANILLA_ORGAN_DAMAGE}} per kidney, both inversely proportional to their condition, will be treated. The patient may gain {{ORGAN_REJECTION}} if they receive the organ and their {{IMMUNITY}} is higher than 10%, if the mechanic is enabled in the mod {{CONFIGURATION_MENU}}.

     The condition of a kidney will decay unless placed in a {{REFRIGERATED_CONTAINER}} or {{REFRIGERATED_CRATE}}. While refrigerated, the organ will slowly regain condition if it is above 90%, otherwise it will not change. If the organ or the container it is in is dropped from a large height, it will be destroyed.

---