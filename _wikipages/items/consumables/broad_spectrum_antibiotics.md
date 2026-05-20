---
layout: contentpage
title: Broad-Spectrum Antibiotics
category: items
subcategory: consumables
permalink: /items/consumables/broad_spectrum_antibiotics
image: /images/svg/anybodypart.svg
inline_image: /images/items/consumables/broad_spectrum_antibiotics.png

blocks:
  - type: description
    header: "Description:"
    order: 1
    text: |
     #### Medical Skill Check: 25

     Broad-spectrum Antibiotics are the only treatment for {{SEPSIS}}. Still applies the husk infection resistance buff and reduces existing husk infection over time as per vanilla.

  - type: application_success
    header: "Application Success:"
    order: 2
    text: |
     A successful use of the antibiotics will provide an affliction strength of 50%, which will decrease at 0.5% a second, totaling for 100 seconds with one dose. 50% Broad-spectrum Antibiotics will treat 0.95% {{SEPSIS}} per second for 100 seconds.

     However, it will cause:

     - 0.2% {{VANILLA_ORGAN_DAMAGE}} a second for 100 seconds
     - 0.175% {{KIDNEY_DAMAGE}} a second for 100 seconds
     - 0.175%{{LIVER_DAMAGE}} a second for 100 seconds
     - 0.1% {{HEART_DAMAGE}} a second for 100 seconds
     - 0.1% {{LUNG_DAMAGE}} a second for 100 seconds
     - In total, the organs will end up with 20% Organ Damage, 17.5% Kidney and Liver Damage, and 10% Heart and Lung Damage.

  - type: application_failure
    header: "Application Failure:"
    order: 3
    text: |
     A failed use will provide an affliction strength of 30%. It will decrease and treat Sepsis at the same rate as a successful use. 30% Broad-spectrum Antibiotics will treat 0.95% {{SEPSIS}} per second for 60 seconds.

     However, it will cause:

     - 0.2% {{VANILLA_ORGAN_DAMAGE}} a second for 60 seconds
     - 0.175% {{KIDNEY_DAMAGE}} a second for 60 seconds
     - 0.175%{{LIVER_DAMAGE}} a second for 60 seconds
     - 0.1% {{HEART_DAMAGE}} a second for 60 seconds
     - 0.1% {{LUNG_DAMAGE}} a second for 60 seconds
     - In total, the organs will end up with 12% Organ Damage, 10.5% Kidney and Liver Damage, and 6% Heart and Lung Damage.

---