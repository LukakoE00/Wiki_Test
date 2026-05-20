---
layout: contentpage
title: Wrench
category: items
subcategory: tools
permalink: /items/tools/wrench
image: /images/svg/anybodypart.svg
inline_image: /images/items/tools/wrench.png

blocks:
  - type: description
    header: "Description:"
    order: 1
    text: |
     #### Medical skill check: 60 (30 if the patient has {{ANALGESIA}})

     The wrench is used to treat {{DISLOCATIONS}}. To use, drag it onto the dislocated limb in the health interface and use it as a treatment, like you would a bandage. If the limb has no dislocation, the wrench will not do anything.

     The wrench can also be used to remove an {{AUTOPULSE}} or {{BODY_BAG}} from a person, as long as they aren’t {{UNCONSCIOUSNESS}}, by using the wrench on their torso as treatment. The item will be placed in the inventory of the wrench user.

     Other vanilla wrenches are able to perform the same actions, including:

     - Hardened Wrench
     - Dementonite Wrench
     - Multitool
     - Heavy Wrench
     - Murder Mystery Wrench

  - type: application_success
    header: "Application Success:"
    order: 2
    text: |

     - Cures {{DISLOCATIONS}} on that limb

  - type: application_failure
    header: "Application Failure:"
    order: 3
    text: |

     - Causes {{FRACTURES}} on that limb

---