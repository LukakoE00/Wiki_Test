---
layout: contentpage
title: Cyberarm
addon: cybernetics_enhanced
subcategory: items
permalink: /items/cybernetics_enhanced/cyberarm
# image: /images/svg/anybodypart.svg
inline_image: /images/addon_cybernetics_enhanced/items/cyberarm.png

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
          - "Skill Required: {{MECHANICAL}} 70"
          - "Maximum inventory stack: 1"

  - title: Crafting (Normal)
    sections:
      - header: "Fabricator Requirements (Output: 1x)"
        items:
            - "{{MECHANICAL}} 70"
            - "{{MEDICAL}} 20"
            - "{{TITANIUM_ALUMINIUM_ALLOY}} (2x)"
            - "{{STEEL_BAR}} (4x)"
            - "{{FPGA_CIRCUIT}} (4x)"
            - "{{FULGURIUM_CHUNK}} (1x)"

      - header: "Deconstructor Yield"
        items:
            - "{{TITANIUM_ALUMINIUM_ALLOY}} (1x)"
            - "{{STEEL_BAR}} (3x)"
            - "{{FPGA_CIRCUIT}} (3x)"
            - "{{FULGURIUM_CHUNK}} (1x)"

  - title: Store (Normal)
    sections:
      - items:
          - "Base Price: 500 Marks"
          - "Buyable at Merchant: Medical, Engineering, Research"
          
  - title: Crafting (Waterproof)
    sections:
      - header: "Fabricator Requirements (Output: 1x)"
        items:
            - "{{MECHANICAL}} 70"
            - "{{MEDICAL}} 35"
            - "{{CYBERARM}} (1x)"
            - "{{FULGURIUM_CHUNK}} (1x)"
            - "{{PLASTIC}} (3x)"
            - "{{RUBBER}} (4x)"

      - header: "Deconstructor Yield"
        items:
            - "{{TITANIUM_ALUMINIUM_ALLOY}} (1x)"
            - "{{STEEL_BAR}} (3x)"
            - "{{FPGA_CIRCUIT}} (3x)"
            - "{{FULGURIUM_CHUNK}} (2x)"
            - "{{PLASTIC}} (2x)"
            - "{{RUBBER}} (2x)"

  - title: Store (Waterproof)
    sections:
      - items:
          - "Minimum Difficulty: 15%"
          - "Base Price: 2000 Marks"
          - "Buyable at Merchant: Medical, Engineering, Research"

blocks:
  - type: description
    header: "Description:"
    order: 1
    text: |
     A cybernetic arm that can be attached to any Surgically Amputated arm socket. Can be removed with a Crowbar.

     #### Advantages of Cyberarms:

     - Improves melee attack speed and swim speed.
     - Great at taking sustained gunfire without malfunctioning.
     - Excellent at tanking attacks from creatures without malfunctioning or breaking.
     - Ideal at sustaining attacks that would otherwise cause life-threatening bleeding.
     - When well maintained, is much less likely to be forcefully amputated when attacked.
     - Does not fracture or dislocate. Make sure you fix any dislocations or fractures BEFORE you add a cyber limb or else it will be permanent until you take off the limb.

     #### Disadvantages of Cyberarms:

     - They do not mix well with water. Won’t shock you, but will break over time if you don’t wear a suit.
       - The expensive Waterproof Cyberarm upgraded item prevents this, and otherwise has identical characteristics.
     - Requires maintenance if damaged.
     - Costly maintenance, especially if your sub doesn’t have an ample source of STEEL_BAR and FPGA circuits.
     - Costly/expensive to make/buy.
     - Violently detach if critically damaged through material loss.

  - type: application_success
    header: "Application Success:"
    order: 2
    text: |
     - Applies the Cyberarm on the selected limb and heals any internal damage caused by any previous failed attempts.

  - type: application_failure
    header: "Application Failure:"
    order: 3
    text: |
     - Applies between 15% to 50% {{BLEEDING}} on the Torso. Does not delete the Cyberarm.
---