---
layout: contentpage
title: Refrigerated Container
category: items
subcategory: tools
permalink: /items/tools/refrigerated_container
image: /images/svg/anybodypart.svg
inline_image: /images/base_neurotrauma/items/tools/refrigerated_container.png

infobox:
  - title: Labels
    sections:
      - items:
          - Item
          - Important

  - title: Statistics
    sections:
      - items:
          - "Maximum inventory stack: 1"

  - title: Crafting
    sections:
      - header: "Fabricator Requirements (Output: 1x)"
        items:
            - "{{MECHANICAL}} 20"
            - "{{STEEL_BAR}} (1x)"
            - "{{POTASSIUM}} (2x)"
            - "{{PHOSPHORUS}} (1x)"

      - header: "Deconstructor Yield"
        items:
            - "{{STEEL_BAR}} (1x)"
            - "{{POTASSIUM}} (2x)"

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
     A container which shares many properties with the storage container. It has 6 slots and may hold any small item. However, its main use is to hold organ transplants (except for the {{BRAIN_TRANSPLANT}}), severed limbs, and {{GEL_COOLANT_PACK}}s. This will prevent the items from naturally losing condition. Organ transplants will slowly regain condition if they are above 90%, limbs above 95%, and gel ice packs at any condition.

     Organ transplants may be destroyed if they are placed in the container and it is dropped from a large height.

     The container will refrigerate:

     - {{HEART_TRANSPLANT}}
     - {{KIDNEY_TRANSPLANT}}
     - {{LIVER_TRANSPLANT}}
     - {{LUNG_TRANSPLANT}}
     - {{ARM_TRANSPLANT}}
     - {{LEG_TRANSPLANT}}
     - {{GEL_COOLANT_PACK}}

---