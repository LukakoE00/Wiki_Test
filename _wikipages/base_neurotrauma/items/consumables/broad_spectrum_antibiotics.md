---
layout: contentpage
title: Broad-Spectrum Antibiotics
category: items
subcategory: consumables
permalink: /items/consumables/broad_spectrum_antibiotics
image: /images/svg/anybodypart.svg
inline_image: /images/base_neurotrauma/items/consumables/broad_spectrum_antibiotics.png

addons:
  - id: vanilla
    label: Base Neurotrauma

  - id: pharmacy
    label: NT Pharmacy Ingredient

infobox:
  - title: Labels
    sections:
      - items:
          - Item
          - First Aid
          - Essential

  - title: Statistics
    sections:
      - items:
          - "Skill Required: {{MEDICAL}} 25"
          - "Maximum inventory stack: 8"

  - title: Crafting
    sections:
      - header: "Medical Fabricator Requirements"
        items:
            - "Cannot be fabricated."

      - header: "Deconstructor Yield"
        items:
            - "Has no deconstructor outputs."
            
  - title: Store
    sections:
      - items:
          - "Base Price: 60 Marks"
          - "Buyable at Outposts: Habitation, Colony, Research"
          - "Buyable at Merchant: Medical"
          - "Available in Vending Machines"

blocks:
  - type: description
    header: "Description:"
    addon: vanilla
    order: 1
    text: |
     Broad-spectrum Antibiotics are the only treatment for {{SEPSIS}}. Still applies the husk infection resistance buff and reduces existing husk infection over time as per vanilla. Obtained by deconstructing {{SLIME_BACTERIA}}.

  - type: application_success
    header: "Application Success:"
    addon: vanilla
    order: 2
    text: |
     A successful use of the antibiotics will provide an affliction strength of 50%, which will decrease at 0.5% a second, totaling for 100 seconds with one dose. 50% Broad-spectrum Antibiotics will treat 0.95% {{SEPSIS}} per second for 100 seconds.

     However, it will cause:

     - 0.2% {{VANILLA_ORGAN_DAMAGE}} a second for 100 seconds
     - 0.175% {{KIDNEY_DAMAGE}} a second for 100 seconds
     - 0.175% {{LIVER_DAMAGE}} a second for 100 seconds
     - 0.1% {{HEART_DAMAGE}} a second for 100 seconds
     - 0.1% {{LUNG_DAMAGE}} a second for 100 seconds
     - In total, the organs will end up with 20% Organ Damage, 17.5% Kidney and Liver Damage, and 10% Heart and Lung Damage.

  - type: application_failure
    header: "Application Failure:"
    addon: vanilla
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

# ------------------------------------------ NT PHARMACY INGREDIENT -------------------------------------------

  - type: description
    header: "Description:"
    addon: pharmacy
    order: 1
    text: |
      #### - Type: "Active Ingredient"
      #### - Skill Required: {{MEDICAL}} 25
      <br>
      An active pill ingredient made from {{BROAD_SPECTRUM_ANTIBIOTICS}}; has positive effects. Affliction is applied instantly; however, vanilla husk infection resistance is not applied in pill form. Still reduces existing husk infection over time.

  - type: effects
    header: "Crafting Success:"
    addon: pharmacy
    order: 2
    text: |
      - 50% of a {{BROAD_SPECTRUM_ANTIBIOTICS}}

  - type: effects
    header: "Crafting Failure:"
    addon: pharmacy
    order: 3
    text: |
      - 30% of a {{BROAD_SPECTRUM_ANTIBIOTICS}}
---