---
layout: contentpage
title: Propofol
category: items
subcategory: consumables
permalink: /items/consumables/propofol
image: /images/svg/anybodypart.svg
inline_image: /images/base_neurotrauma/items/consumables/propofol.png

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

  - title: Statistics
    sections:
      - items:
          - "Skill Required: None"
          - "Maximum inventory stack: 2"

  - title: Crafting
    sections:
      - header: "Medical Fabricator Requirements"
        items:
            - "Cannot be fabricated."

      - header: "Deconstructor Yield"
        items:
            - "{{PARALYXIS}} (1x)"

  - title: Store
    sections:
      - items:
          - "Base Price: 200 Marks"
          - "Buyable at Outposts: Merchant: Medical"

blocks:
  - type: description
    header: "Description:"
    addon: vanilla
    order: 1
    text: |
     **Propofol is no longer craftable**

     A drug used to induce controlled {{UNCONSCIOUSNESS}}  for the purpose of preventing {{TRAUMATIC_SHOCK}}.

     Upon use, the patient will gain {{ANESTHESIA}} at 0.3% per second. Between 1-15% anesthesia, the patient will have 5% {{ANALGESIA}}. Beyond 15% anesthesia, the patient will be unconscious. At 100% anesthesia, the patient will no longer be under the effect of propofol. Application of {{ANAPARALYZANT}} will reduce anesthesia to 0%, also removing its effect.

     Side effects of propofol include:

     - {{HYPOTENSION}}
     - {{CONFUSION}}
     - {{BLURRED_VISION}}
     - {{FEVER}}
     - {{FIBRILLATION}}
     - {{SEIZURE}}
     - {{VOMITING_BLOOD}}
     - \-100% {{PSYCHOSIS}}

# ------------------------------------------ NT PHARMACY INGREDIENT -------------------------------------------

  - type: description
    header: "Description:"
    addon: pharmacy
    order: 1
    text: |
      #### - Type: "Active Ingredient"
      #### - Skill Required: {{MEDICAL}} 0
      <br>
      An active pill ingredient made from {{PROPOFOL}}; has positive effects.

  - type: effects
    header: "Crafting Success:"
    addon: pharmacy
    order: 2
    text: |
      - Minor {{ANALGESIA}} until full effect as per base {{PROPOFOL}}.
---