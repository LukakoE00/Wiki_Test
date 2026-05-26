---
layout: contentpage
title: Blood Packs
category: items
subcategory: consumables
permalink: /items/consumables/blood_packs
image: /images/svg/anybodypart.svg
inline_image: //images/base_neurotrauma/items/consumables/blood_packs.png

addons:
  - id: vanilla
    label: Base Neurotrauma

  - id: pharmacy
    label: NT Pharmacy Ingredient

infobox:
  - title: Labels
    sections:
      - items:
          - Item
          - Essential
          - First Aid

  - title: Statistics
    sections:
      - items:
          - "Skill Required: None"
          - "Maximum inventory stack: 8"

  - title: Crafting
    sections:
      - header: "Medical Fabricator Requirements"
        items:
            - "Cannot be fabricated."

      - header: "Deconstructor Yield"
        items:
            - "{{SALINE}} (1x)"
            - "{{STABILOZINE}} (1x)"
            
  - title: Store
    sections:
      - items:
          - "Base Price: 240 marks"
          - "Buyable at Merchant: Medical, Husk"

blocks:
  - type: description
    header: "Description:"
    addon: vanilla
    order: 1
    text: |
     Blood packs are acquired from using an {{EMPTY_BLOOD_PACK}} on a human with less than 31% {{BLOOD_LOSS}}. Blood packs must be administered to the correct bloodtype, which are listed in the description of the item.

  - type: compatible_bloodtype
    header: "Compatible Blood-type Application:"
    addon: vanilla
    order: 2
    text: |
     - \-30% {{BLOOD_LOSS}}
     - \+30% Blood Pressure

  - type: incompatible_bloodtype
    header: "Incompatible Blood-type Application:"
    addon: vanilla
    order: 3
    text: |
     - \-20% {{BLOOD_LOSS}}
     - \+30% Blood Pressure
     - \+100% {{HEMOTRANSFUSION_SHOCK}}

     If the human that the blood pack came from was suffering from either {{ACIDOSIS}}, {{ALKALOSIS}}, or {{SEPSIS}}, then those afflictions will be stored in the blood pack (1/10 of the donor’s affliction strength for acidosis or alkalosis). Placing a blood pack in a {{HEMATOLOGY_ANALYZER}} will show if it has any of these afflictions and their strength. Additionally, if a recipient has acidosis or alkalosis, administering neutral blood will multiply it by 0.9, unless they have 0% bloodloss.

# ------------------------------------------ NT PHARMACY INGREDIENT -------------------------------------------

  - type: description
    header: "Description:"
    addon: pharmacy
    order: 1
    text: |
      #### - Type: "Base"
      #### - Skill Required: {{MEDICAL}} 40
      <br>
      A pill base using blood packs. Provides a medium capacity and a mild potency boost with no side effects.

  - type: effects
    header: "Crafting Success:"
    addon: pharmacy
    order: 2
    text: |
      - Increases capacity to 2
      - Multiplies potency by 1.1x


  - type: effects
    header: "Crafting Failure:"
    addon: pharmacy
    order: 3
    text: |
      - Increases capacity to 2
      - Multiplies potency by 0.9x
---