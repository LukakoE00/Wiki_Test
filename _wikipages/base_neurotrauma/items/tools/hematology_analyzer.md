---
layout: contentpage
title: Hematology Analyzer
category: items
subcategory: tools
permalink: /items/tools/hematology_analyzer
image: /images/svg/anybodypart.svg
inline_image: /images/base_neurotrauma/items/tools/hematology_analyzer.png

infobox:
  - title: Labels
    sections:
      - items:
          - Item
          - Essential

  - title: Statistics
    sections:
      - items:
          - "Skill Required: {{MEDICAL}} 30"
          - "Maximum inventory stack: 1"
          

  - title: Crafting
    sections:
      - header: "Medical Fabricator Requirements (Output: 1x)"
        items:
            - "{{MEDICAL}} 50"
            - "{{PLASTIC}} (1x)"
            - "{{SILICON}} (1x)"
            - "{{FPGA_CIRCUIT}} (1x)"

      - header: "Deconstructor Yield"
        items:
            - "{{PLASTIC}} (1x)"
            - "{{SILICON}} (1x)"
            - "{{COPPER}} (1x)"

  - title: Store
    sections:
      - items:
          - "Base Price: 250 Marks"
          - "Buyable at Merchant: Medical"

blocks:
  - type: description
    header: "Description:"
    order: 1
    text: |
     #### Medical Skill Check: 30

     Whether you fail or pass the skill check, it will also give you a readout of all the blood-related ailments your patient has; such as {{SEPSIS}}, {{ACIDOSIS}} or {{ALKALOSIS}}. The hematology analyzer can also be used to check the blood type of your patient, to avoid {{HEMOTRANSFUSION_SHOCK}}. Putting a donor card in the analyzer and then using it will print their blood type onto the donor card, and put it in their id card slot, allowing you to check their blood type later without the analyzer. Putting a blood pack in the analyzer will give a readout of its type and any of the aforementioned ailments, if it has any.

  - type: application_success
    header: "Application Success:"
    order: 2
    text: |

     - \+1% {{BLOOD_LOSS}}

  - type: application_failure
    header: "Application Failure:"
    order: 3
    text: |

     - \+3% {{BLOOD_LOSS}}


---