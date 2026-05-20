---
layout: contentpage
title: Azathioprine
category: items
subcategory: consumables
permalink: /items/consumables/azathioprine
image: /images/svg/anybodypart.svg
inline_image: /images/items/consumables/azathioprine.png

blocks:
  - type: description
    header: "Description:"
    order: 1
    text: |
     #### Medical Skill Check: 10

     Azathioprine is an immunosuppressant medication used during {{ORGAN_TRANSPLANT_SURGERY}} if organ rejection is enabled in the {{CONFIGURATION_MENU}}. It will lower Immunity over time, making it safe to place an organ into the body when Immunity is below 10%.

  - type: application_success
    header: "Application Success:"
    order: 2
    text: |
     - Lowers immunity over time

  - type: application_failure
    header: "Application Failure:"
    order: 3
    text: |
     - Lowers immunity over time
     - Causes {{SEPSIS}}

---