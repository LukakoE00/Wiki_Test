---
layout: contentpage
title: Gel Coolant Pack
category: items
subcategory: tools
permalink: /items/tools/gel_coolant_pack
image: /images/svg/anybodypart.svg
inline_image: /images/items/tools/gel_coolant_pack.png

blocks:
  - type: description
    header: "Description:"
    order: 1
    text: |
     #### Medical Skill Check: 40
     A reusable cold pack used to promote the healing of blunt force trauma and for the treatment of internal bleeding. Usage will decrease its condition along with leaving it outside of refrigeration, but its condition will be restored if refrigerated. Even if its condition reaches 0% from usage or being left outside, its condition will increase once refrigerated.

  - type: application_success
    header: "Application Success:"
    order: 2
    text: |

     - +100% {{CHILLED}}
     - -35% condition on the Coolant Pack

  - type: application_failure
    header: "Application Failure:"
    order: 3
    text: |

     - +75% {{CHILLED}}
     - -35% condition on the Coolant Pack

---