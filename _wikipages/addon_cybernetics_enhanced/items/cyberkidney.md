---
layout: contentpage
title: Cyberkidney
addon: cybernetics_enhanced
subcategory: items
permalink: /items/cybernetics_enhanced/cyberkidney
# image: /images/svg/anybodypart.svg
# inline_image: /images/addon_cybernetics_enhanced/items/cyberkidney.png

infobox:
  - title: Labels
    sections:
      - items:
          - Item
          - Niche
          - Cybernetics Expansion

  - title: Statistics
    sections:
      - items:
          - "Skill Required: {{MEDICAL}} 70"
          - "Maximum inventory stack: 1"

  - title: Crafting (T1 Augmented Kidney)
    sections:
      - header: "Medical Fabricator Requirements (Output: 1x)"
        items:
            - "{{MECHANICAL}} 70"
            - "{{MEDICAL}} 60"
            - "{{KIDNEY_TRANSPLANT}} (min. condition 30%) (1x)"
            - "{{FULGURIUM_CHUNK}} (1x)"
            - "{{FPGA_CIRCUIT}} (1x)"
            - "{{STABILOZINE}} (1x)"

      - header: "Deconstructor Yield"
        items:
            - "{{FULGURIUM_CHUNK}} (1x)"
            - "{{FPGA_CIRCUIT}} (1x)"

  - title: Store (T1 Augmented Kidney)
    sections:
      - items:
          - "Minimum Difficulty: 8%"
          - "Base Price: 2000 Marks"
          - "Buyable at Merchant: Medical, Research"

  - title: Crafting (T2 Cyberkidney)
    sections:
      - header: "Medical Fabricator Requirements (Output: 1x)"
        items:
            - "Requires Recipe"
            - "{{MECHANICAL}} 90"
            - "{{MEDICAL}} 80"
            - "{{FULGURIUM_CHUNK}} (4x)"
            - "{{FPGA_CIRCUIT}} (3x)"
            - "{{STABILOZINE}} (3x)"
            - "{{PLASTIC}} (3x)"

      - header: "Deconstructor Yield"
        items:
            - "{{FULGURIUM_CHUNK}} (3x)"
            - "{{FPGA_CIRCUIT}} (2x)"
            - "{{PLASTIC}} (3x)"

  - title: Store (T2 Cyberkidney)
    sections:
      - items:
          - "Minimum Difficulty: 30%"
          - "Base Price: 3500 Marks"
          - "Buyable at Merchant: Medical, Research"

blocks:
  - type: description
    header: "Description:"
    order: 1
    text: |
     A cybernetic kidney replacement. Embrace the certainty of steel!

     Available as a more affordable Cyber-augmented Kidney (half meat, half silicon) crafted from an extracted Kidney, or the twice as effective fully-synthetic Cyberkidney.

     #### Advantages of Cyberkidneys:

     - With the power of techology, you only need one!
     - Resistance to {{BLOOD_LOSS}}  and {{BLEEDING}}
     - Switches blood type to C+, which can accept any other blood without {{HEMOTRANSFUSION_SHOCK}}
     - Resistance to {{KIDNEY_DAMAGE}}

     #### Disadvantages of Cyberorgans:

     - Switches blood type to C+, whose cybernanites will cause {{HEMOTRANSFUSION_SHOCK}} if given to anyone else lacking cybernetic blood.
     - Can periodically experience fits of Cyberpsychosis (regular psychosis), which can be avoided by reducing your Immunity in any way, such as the very affordable Immunosuppressant Inhaler.
  
  - type: how_to_add
    header: "How to Add:"
    order: 2
    text: |
     Do {{ORGAN_TRANSPLANT_SURGERY}}, using the Cyberkidney instead of a pair of feeble meat kidneys. Consider refrigerating the procured meat for upgrading into a Cyber-augmented Kidney.

     #### Mechanical Skill Check: 60

     #### Medical/Surgical Skill Check: 70

     #### Application Success:

     Installs the cyberorgan, healing that organ’s damage and some {{VANILLA_ORGAN_DAMAGE}}.

     #### Application Failure (Mechanical):

     Same as Success but causes 20% {{KIDNEY_DAMAGE}}.

     #### Application Failure (Medical):

     Same as Success but causes {{INTERNAL_BLEEDING}}.
  
  - type: how_to_remove
    header: "How to Remove:"
    order: 3
    text: |
     {{ORGAN_TRANSPLANT_SURGERY}} will remove and return the corresponding cybernetic organ.
---