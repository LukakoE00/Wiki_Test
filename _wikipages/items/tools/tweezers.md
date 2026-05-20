---
layout: contentpage
title: Tweezers
category: items
subcategory: tools
permalink: /items/tools/tweezers
image: /images/svg/anybodypart.svg
inline_image: /images/items/tools/tweezers.png

blocks:
  - type: description
    header: "Description:"
    order: 1
    text: |
     #### Medical Skill Check: 30

     A pair of tweezers used to remove damaged tissue or bullets.

     This item is not directly craftable. To obtain it from a fabricator, the player must craft the “Surgery toolbox (kit)”.

     Its effects depend on if:

     - there is {{RETRACTED_SKIN}}, gunshot wound or deep tissue injury on the limb (surgery use case)

     - or none of those apply (no surgery use case)

     The tweezers can work without {{RETRACTED_SKIN}}  if the limb you are tweezing has gunshot wounds or deep tissue injuries, using the tweezer through gunshot wounds or deep tissue injuries will cause 5% {{TRAUMATIC_SHOCK}} . Do note that tweezing through gunshot wounds or deep tissue injuries only works on foreign bodies, and not on blunt force trauma. Tweezing out foreign bodies also has a 5% chance to yield scrap.

     Using tweezers in cases where it otherwise wouldn’t do anything will cause you to pinch the patient instead, causing minor damage which is worse if on the head.

  - type: effects
    header: "Application Effects (No Surgery):"
    order: 2
    text: |

     - minor {{BLEEDING}}
     - minor {{OPEN_WOUNDS}}
     - {{INTENSE_PAIN}}

  - type: application_success
    header: "Application Success (Surgery):"
    order: 3
    text: |

     - -3% to -10% {{INTERNAL_WOUNDS}}
     - -3% to -10% {{INTERNAL_WOUNDS}}
     - -3% to -10% {{FOREIGN_BODIES}}
     - +5% {{OPEN_WOUNDS}}

  - type: application_failure
    header: "Application Failure (Surgery):"
    order: 4
    text: |

     - +6% {{INTERNAL_WOUNDS}}

---