---
layout: contentpage
title: Diving Knife
category: items
subcategory: tools
permalink: /items/tools/diving_knife
image: /images/svg/anybodypart.svg
inline_image: /images/items/tools/diving_knife.png

blocks:
  - type: description
    header: "Description:"
    order: 1
    text: |
     #### Medical Skill Check: 30

     In addition to the normal uses of a knife, they can be used to remove {{BANDAGES}}.

  - type: application_success
    header: "Application Success:"
    order: 2
    text: |

     - Removes {{BANDAGED}} on the limb the knife was used on.

  - type: application_failure
    header: "Application Failure:"
    order: 3
    text: |

     - \+15% {{BLEEDING}}
     - \+10% {{OPEN_WOUNDS}}
---