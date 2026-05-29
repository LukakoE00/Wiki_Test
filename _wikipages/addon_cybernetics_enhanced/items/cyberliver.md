---
layout: contentpage
title: Cyberliver
addon: cybernetics_enhanced
subcategory: items
permalink: /items/cybernetics_enhanced/cyberliver
# image: /images/svg/anybodypart.svg
# inline_image: /images/addon_cybernetics_enhanced/items/cyberliver.png

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

  - title: Crafting (T1 Augmented Liver)
    sections:
      - header: "Medical Fabricator Requirements (Output: 1x)"
        items:
            - "{{MECHANICAL}} 70"
            - "{{MEDICAL}} 60"
            - "{{LIVER_TRANSPLANT}} (min. condition 50%) (1x)"
            - "{{FULGURIUM_CHUNK}} (1x)"
            - "{{FPGA_CIRCUIT}} (1x)"
            - "{{STABILOZINE}} (1x)"

      - header: "Deconstructor Yield"
        items:
            - "{{FULGURIUM_CHUNK}} (1x)"
            - "{{FPGA_CIRCUIT}} (1x)"

  - title: Store (T1 Augmented Liver)
    sections:
      - items:
          - "Minimum Difficulty: 8%"
          - "Base Price: 2000 Marks"
          - "Buyable at Merchant: Medical, Research"

  - title: Crafting (T2 Cyberliver)
    sections:
      - header: "Medical Fabricator Requirements (Output: 1x)"
        items:
            - "Super Soldiers Talent (Medical Doctor)"
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

  - title: Store (T2 Cyberliver)
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
     A cybernetic liver replacement. Embrace the certainty of steel!

     Available as a more affordable Cyber-augmented Liver (half meat, half silicon) crafted from an extracted Liver, or the twice as effective fully-synthetic Cyberliver.

     #### Advantages of Cyberlivers:

     - Resistant to poisons, toxins, and {{NAUSEA}}
     - Resistant to {{LIVER_DAMAGE}}

     #### Disadvantages of Cyberorgans:

     - Can periodically experience fits of Cyberpsychosis (regular psychosis), which can be avoided by reducing your Immunity in any way, such as the very affordable Immunosuppressant Inhaler.
  
  - type: how_to_add
    header: "How to Add:"
    order: 2
    text: |
     Do {{ORGAN_TRANSPLANT_SURGERY}}, using the Cyberliver instead of a feeble meat liver. Consider refrigerating the procured meat for upgrading into a Cyber-augmented Liver.

     #### Mechanical Skill Check: 60

     Medical/Surgical Skill Check: 70

     #### Application Success:

     Installs the cyberorgan, healing that organ’s damage and some {{VANILLA_ORGAN_DAMAGE}}.

     #### Application Failure (Mechanical):

     Same as Success but causes 20% {{LIVER_DAMAGE}}.

     #### Application Failure (Medical):

     Same as Success but causes {{INTERNAL_BLEEDING}}.
  
  - type: how_to_remove
    header: "How to Remove:"
    order: 3
    text: |
     {{ORGAN_TRANSPLANT_SURGERY}} will remove and return the corresponding cybernetic organ.
---