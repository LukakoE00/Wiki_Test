---
layout: contentpage
title: Raptor Bane Extract
category: items
subcategory: consumables
permalink: /items/consumables/raptor_bane_extract
image: /images/svg/anybodypart.svg
inline_image: /images/base_neurotrauma/items/consumables/raptor_bane_extract.png

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
          - Niche
          - First Aid

  - title: Statistics
    sections:
      - items:
          - "Skill Required: {{MEDICAL}} 25"
          - "Maximum inventory stack: 8"

  - title: Crafting
    sections:
      - header: "Medical Fabricator Requirements (Output: 1x)"
        items:
            - "{{MEDICAL}} 20"
            - "{{RAPTOR_BANE}} (4x)"

      - header: "Deconstructor Yield"
        items:
            - "{{CARBON}} (2x)"

  - title: Store
    sections:
      - items:
          - "Base Price: 250 Marks"
          - "Buyable at Outpost: Colony"
          - "Buyable at Merchant: Research"

blocks:
  - type: description
    header: "Description:"
    addon: vanilla
    order: 1
    text: |
     Raptor Bane Extract is used in the treatment of {{ACIDOSIS}} by inducing {{VOMITING}} in the patient to give them {{ALKALOSIS}}.

# ------------------------------------------ NT PHARMACY INGREDIENT -------------------------------------------

  - type: description
    header: "Description:"
    addon: pharmacy
    order: 1
    text: |
      #### - Type: "Active Ingredient"
      #### - Skill Required: {{MEDICAL}} 0
      <br>
      An active pill ingredient made from {{RAPTOR_BANE_EXTRACT}}; has negative effects.

  - type: effects
    header: "Crafting Success:"
    addon: pharmacy
    order: 2
    text: |
      - +25% {{NAUSEA}}
      - Can be used beneficially to induce vomiting which causes {{ALKALOSIS}}, which in turn cancels out {{ACIDOSIS}}.

  - type: effects
    header: "Crafting Failure:"
    addon: pharmacy
    order: 3
    text: |
      - +25% {{NAUSEA}}
      - Can be used beneficially to induce vomiting which causes {{ALKALOSIS}}, which in turn cancels out {{ACIDOSIS}}.
---