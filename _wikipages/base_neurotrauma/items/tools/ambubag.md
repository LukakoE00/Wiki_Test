---
layout: contentpage
title: Ambubag
category: items
subcategory: tools
permalink: /items/tools/ambubag
image: /images/svg/anybodypart.svg
inline_image: /images/base_neurotrauma/items/tools/ambubag.png

infobox:
  - title: Labels
    sections:
      - items:
          - Item
          - First Aid
          - Important

  - title: Statistics
    sections:
      - items:
          - "Maximum inventory stack: 1"
          - "Requires an Oxygen Tank (or similar)"

  - title: Crafting
    sections:
      - header: "Medical Fabricator Requirements (Output: 1x)"
        items:
            - "{{MEDICAL}} 30"
            - "{{PLASTIC}} (1x)"

      - header: "Deconstructor Yield"
        items:
            - "Has no deconstructor outputs."

  - title: Store
    sections:
      - items:
          - "Base Price: 100 Marks"
          - "Buyable at Merchant: Medical"

blocks:
  - type: description
    header: "Description:"
    order: 1
    text: |
     An item used to provide supplementary oxygen if a patient isn't breathing enough or isn't breathing at all.

     Using the ambubag with a regular oxygen tank in it will treat 90% {{OXYGEN_LOW}}, and use 2% of the oxygen in the tank.

     Using the ambubag with an oxygenite tank in it will treat 90% {{OXYGEN_LOW}}, cure {{RESPIRATORY_ARREST}} , and use 2% of the oxygen in the tank.

     Using the ambubag with a welding fuel tank in it will cause 110% {{OXYGEN_LOW}}, cause 10% {{LUNG_DAMAGE}} , and use 5% of the welding fuel in the tank.

     Using the ambubag with a incendium fuel tank in it will cause 110% {{OXYGEN_LOW}}, cause 20% {{LUNG_DAMAGE}} , cause 10% {{BURNS}}, and use 5% of the incendium in the tank.

     Using the ambubag with paint in it will cause 50% {{OXYGEN_LOW}}, cause 3% lung damage, cause 5% chemical addiction, treat 20% chemical withdrawal, and use 5% of the paint in the can.

     Using the ambubag with {{ANALGESIC_TANK}} will give {{ANALGESIA}}, {{OPIATE_ADDICTION}}, {{OPIATE_OVERDOSE}}, and {{WITHDRAWAL}}. The amount depends on whether the patient is drunk or not.

---