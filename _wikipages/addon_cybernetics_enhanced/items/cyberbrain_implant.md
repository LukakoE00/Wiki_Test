---
layout: contentpage
title: Cyberbrain Implant
addon: cybernetics_enhanced
subcategory: items
permalink: /items/cybernetics_enhanced/cyberbrain_implant
# image: /images/svg/anybodypart.svg
# inline_image: /images/addon_cybernetics_enhanced/items/cyberbrain_implant.png

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
          - "Skill Required: {{MEDICAL}} 80"
          - "Maximum inventory stack: 1"

  - title: Crafting (T1 Augmented Brain)
    sections:
      - header: "Medical Fabricator Requirements (Output: 1x)"
        items:
            - "{{MEDICAL}} 60"
            - "{{ELECTRICAL}} 80"
            - "{{FULGURIUM_CHUNK}} (2x)"
            - "{{FPGA_CIRCUIT}} (4x)"
            - "{{STABILOZINE}} (1x)"

      - header: "Deconstructor Yield"
        items:
            - "{{FULGURIUM_CHUNK}} (2x)"
            - "{{FPGA_CIRCUIT}} (3x)"

  - title: Store (T1 Augmented Brain)
    sections:
      - items:
          - "Minimum Difficulty: 8%"
          - "Base Price: 2000 Marks"
          - "Buyable at Merchant: Medical, Research"

  - title: Crafting (T2 Cyberbrain)
    sections:
      - header: "Medical Fabricator Requirements (Output: 1x)"
        items:
            - "Requires Recipe"
            - "{{MEDICAL}} 100"
            - "{{ELECTRICAL}} 100"
            - "Augmented Brain (1x)"
            - "{{FULGURIUM_CHUNK}} (2x)"
            - "{{FPGA_CIRCUIT}} (4x)"
            - "{{STABILOZINE}} (1x)"

      - header: "Deconstructor Yield"
        items:
            - "{{FULGURIUM_CHUNK}} (3x)"
            - "{{FPGA_CIRCUIT}} (4x)"

  - title: Store (T2 Cyberbrain)
    sections:
      - items:
          - "Minimum Difficulty: 30%"
          - "Base Price: 4000 Marks"
          - "Buyable at Merchant: Medical, Research"

blocks:
  - type: description
    header: "Description:"
    order: 1
    text: |
     A cybernetic brain booster. Embrace the certainty of steel!

     Available as a more affordable Cyber-augmented Brain Implant, or the twice as effective top-of-the-line ‘Cyberbrain’ Positronic Implant.

     #### Advantages of Cyberbrain Implants:

     - Boosts all skills by 5 (10 for Positronic)
     - Grants permanent mild {{ANALGESIA}}  for easier surgeries
     - Improves {{NEUROTRAUMA}}  recovery rate
       - Doubles effects of {{MANNITOL}}
       - Doubles natural healing rate once causes are addressed
     - Mild resistance to {{NEUROTRAUMA}}

     #### Disadvantages of Cyberorgans:

     - Can periodically experience fits of Cyberpsychosis (regular psychosis), which can be avoided by reducing your Immunity in any way, such as the very affordable Immunosuppressant Inhaler.
  
  - type: how_to_add
    header: "How to Add:"
    order: 2
    text: |
     Open up the head as a typical surgery with{{RETRACTED_SKIN}}, but do not remove their brain! They’ll still need to keep that! Instead, place the Implant on top.

     #### Electrical Skill Check: 60

     #### Medical/Surgical Skill Check: 80

     #### Application Success:

     Installs the implant, healing some {{NEUROTRAUMA}}  and some {{VANILLA_ORGAN_DAMAGE}}.

     #### Application Failure (Mechanical):

     Same as Success but causes 20% {{NEUROTRAUMA}}.

     #### Application Failure (Medical):

     Same as Success but causes {{INTERNAL_BLEEDING}}.
  
  - type: how_to_remove
    header: "How to Remove:"
    order: 3
    text: |
     {{ORGAN_TRANSPLANT_SURGERY}} _once_ will return the Implant, using the {{MULTIPURPOSE_SCALPEL}} a second time will remove the patient’s brain, which they probably need.

---