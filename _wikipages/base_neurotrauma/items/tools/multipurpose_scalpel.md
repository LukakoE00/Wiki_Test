---
layout: contentpage
title: Multipurpose Scalpel
category: items
subcategory: tools
permalink: /items/tools/multipurpose_scalpel
image: /images/svg/anybodypart.svg
inline_image: /images/base_neurotrauma/items/tools/multipurpose_scalpel.png

infobox:
  - title: Labels
    sections:
      - items:
          - Item
          - Surgery
          - Essential

  - title: Statistics
    sections:
      - items:
          - "Maximum inventory stack: 1"

  - title: Crafting
    sections:
      - header: "Medical Fabricator Requirements (Output: 1x)"
        items:
            - "{{MEDICAL}} 60"
            - "{{MECHANICAL}} 20"
            - "{{STEEL_BAR}} (1x)"
            - "{{FPGA_CIRCUIT}} (1x)"
            - "{{PLASTIC}} (1x)"
            - "{{ZINC}} (2x)"

      - header: "Deconstructor Yield"
        items:
            - "{{STEEL_BAR}} (1x)"

  - title: Store
    sections:
      - items:
          - "Base Price: 210 Marks"
          - "Buyable at Merchant: Medical"

blocks:
  - type: description
    header: "Description:"
    order: 1
    text: |
     The Multipurpose Scalpel combines the functionality of the regular scalpel, the organ procurement scalpels, and the trauma shears, while also providing the user with a way of intentionally harming the patient.

     This item is craftable at a regular fabricator.

     The mode of this Scalpel is changed by equipping the item (akin to a weapon or tool) and clicking on the available UI buttons which appear.
     <br><br>
     #### Mode: Surgery Incision

     In this mode, the item behaves identically to a regular {{SCALPEL}}.
     <br><br>
     #### Mode: Bandages, Casts, Malpractice

     In this mode, as long as the patient has a bandage or a cast, the item functions identically to {{TRAUMA_SHEARS}}.
     Is this not the case, then using it will result in the patient getting stabbed. Depending on location and surgical status of the patient, this can cause serious damage.

     Notable outcomes include:

     - a chance for causing fractures in extremeties that are currently opened for surgery
     - causing neurotrauma on opened heads
     - causing specific organ damage and internal bleeding on opened torsos
     <br><br>
     #### Mode: Adaptive Organ Extraction

     In this mode, the item will have the ability to extract any organ from a patient, and it is a required item for {{ORGAN_TRANSPLANT_SURGERY}}. The organ extracted depends on which limb has {{RETRACTED_SKIN}}, and which limb the Multipurpose Scalpel is used on:
     <br><br>
     #### Retracted skin: Torso
     - Left arm: {{KIDNEY_TRANSPLANT}}
     - Torso: {{LIVER_TRANSPLANT}}
     - Right arm: {{HEART_TRANSPLANT}}
     - Left leg: {{LUNG_TRANSPLANT}}
     <br><br>
     #### Retracted skin: Head
     - Head: {{BRAIN_TRANSPLANT}}

---