---
layout: contentpage
title: Stasis Bag
category: items
subcategory: tools
permalink: /items/tools/stasis_bag
image: /images/svg/anybodypart.svg
inline_image: /images/base_neurotrauma/items/tools/stasis_bag.png

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

  - title: Crafting
    sections:
      - header: "Fabricator Requirements (Output: 1x)"
        items:
            - "{{MEDICAL}} 50"
            - "{{PLASTIC}} (1x)"
            - "{{STABILOZINE}} (1x)"
            - "{{MANNITOL}} (1x)"
            - "{{POTASSIUM}} (1x)"

      - header: "Deconstructor Yield"
        items:
            - "{{PLASTIC}} (1x)"
            - "{{POTASSIUM}} (1x)"

  - title: Store
    sections:
      - items:
          - "Base Price: 700 Marks"
          - "Buyable at Merchant: Medical"

blocks:
  - type: description
    header: "Description:"
    order: 1
    text: |
     A special bag that keeps the body in stasis for transportation to proper treatment if injuries are severe. A stasis bag is worn in the diving suit slot, and wearing it will drain the condition of it by 0.25% per second, meaning a stasis bag will last for 400 seconds or roughly 6 and a half minutes. Wearing a stasis bag will protect the wearer from pressure down to 7,000 meters, will allow the wearer to be dragged at full speed, and will stop the negative effects of the following afflictions:

     - {{CARDIAC_ARREST}}
     - {{RESPIRATORY_ARREST}}
     - {{HEART_ATTACK}}
     - {{NEUROTRAUMA}}
     - {{KIDNEY_DAMAGE}}
     - {{LIVER_DAMAGE}}
     - {{HEART_DAMAGE}}
     - {{LUNG_DAMAGE}}
     - {{BONE_DAMAGE}}
     - {{SEPSIS}}
     - {{HYPOXEMIA}}
     - {{HYPOTENSION}}
     - {{HYPERTENSION}}
     - {{ACIDOSIS}}
     - {{ALKALOSIS}}
     - {{INTERNAL_BLEEDING}}
     - {{STROKE}}
     - {{SEIZURE}}
     - {{COMA}}
     - {{INFECTED_WOUNDS}}
     - {{BLEEDING}}

     Additionally, the wearer’s Husk Infection will be reduced by 0.15/s, if it is lower than 100%.

     Patients in a Stasis Bag cannot receive surgery, and will not be able to receive surgery for 3 seconds after being removed from the bag. They can still receive items such as drugs, however.

     Patients removed from the Stasis Bag will have {{CARDIAC_ARREST}}, {{RESPIRATORY_ARREST}} and {{UNCONSCIOUSNESS}} and will need those afflictions treated.

---