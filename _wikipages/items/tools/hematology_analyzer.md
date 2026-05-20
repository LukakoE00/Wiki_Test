---
layout: contentpage
title: Hematology Analyzer
category: items
subcategory: tools
permalink: /items/tools/hematology_analyzer
image: /images/svg/anybodypart.svg
inline_image: /images/items/tools/hematology_analyzer.png

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