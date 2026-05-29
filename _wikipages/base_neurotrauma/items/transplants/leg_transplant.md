---
layout: contentpage
title: Leg Transplant
category: items
subcategory: transplants
permalink: /items/transplants/leg_transplant
image: /images/svg/anybodypart.svg
inline_image: /images/base_neurotrauma/items/transplants/leg_transplant.png

infobox:
  - title: Labels
    sections:
      - items:
          - Item
          - Surgery

  - title: Statistics
    sections:
      - items:
          - "Maximum inventory stack: 1"
          - "Should be refrigerated"

  - title: Crafting
    sections:
      - header: "Medical Fabricator Requirements"
        items:
            - "Cannot be fabricated."

      - header: "Deconstructor Yield"
        items:
            - "{{CALCIUM}} (1x)"

  - title: Store
    sections:
      - items:
          - "Base Price: 1000 Marks"
          - "Buyable at Merchant: Medical (Bionic Leg)"

blocks:
  - type: description
    header: "Description:"
    order: 1
    text: |
     A replacement Left or Right leg that can be attached to a matching surgically amputated and prepared leg socket.

     Severed legs require refrigeration or they will expire.
     Bionic legs are synthetic and don’t require refrigeration, but are otherwise biologically equivalent to natural legs.

     To add to a patient, perform {{AMPUTATION_SURGERY}} and use the respective limb after 100% sawed bones.
  
  - type: treats
    header: "Treats:"
    order: 2
    text: |
     - {{GANGRENE}}
     - Missing leg
       - {{TRAUMATIC_AMPUTATION}}
       - {{SURGICAL_AMPUTATION}}
---