---
layout: contentpage
title: Configuration Menu
category: gamemechanics
subcategory: base_mechanics
permalink: /mechanics/configuration_menu

blocks:
  - type: description
    header: "Description:"
    order: 1
    text: |
     The Configuration Menu, opened by going to the Pause Menu in-game or in the lobby by pressing Escape (by default). Here, you can tweak the settings that the mod uses to determine certain functionalities; you could make the NPC turn hostile if you perform medical actions on them, change item prices or make certain items spawn that otherwise wouldn't.

     The Config Menu has 3 'pages' in Base Neurotrauma, which can be swapped between using the dropdown button at the top left of the menu.
     <br><br>
     ### 1. Neurotrauma Default Settings
     This page contains settings that directly influence gameplay mechanics. Here you can tweak the difficulty of the mod by changing the severity of injuries by making them occur more often (or less, if you prefer!).
     #### There are also a few toggleable options;
     - Should the mod even run its calculations (could be turned off to save performance, but removes functionality);
     - Should the vanilla skill checking system be used instead of the tweaked Neurotrauma formula;
     - Should bots attempt to treat injuries (despite being able to softlock on some);
     - Should screams be played on certain injuries;
     - Should mod conflicts be ignored;
     - Should {{ORGAN_REJECTION}} be turned on/off;
     - Should getting new {{FRACTURES}} remove the {{PLASTER_CAST}} of the old ones;
     - Do NPCs consent to have medical actions performed on them.
     This page also contains customization for the Health Scanner; you can determine which afflictions are considered part of a category - and change the colour that gets used when printing said category of afflictions. If you are having trouble noticing the difference between affliction types, you may want to consider changing this.
     <br><br>

     ### 2. Item Prices
     The item prices tab is pretty self-explanatory; here you can make items more expensive or cheaper to buy, depending on your preference. Fancy a harder campaign? Triple the cost of all basic medicines and see how far you can get! Running a large crew or Dynamic Europa and see only 1 Medical Merchant every 4 months? Maybe make it a bit cheaper instead.

     #### Note that this only changes the *buying* price directly, not the *sell* price. The values changed here will update on level-change. Since these are multipliers, a larger number means it's more expensive.
     
     <br><br>
     ### 3. Item Availability
     Here you can change the amount of uses certain items have (though that only goes for {{OSTEOSYNTHESIS_IMPLANTS}} and {{SPINAL_CORD_IMPLANTS}} as of now). Tired of having to store 20 different Spinal Cord Implants? Just make them last 10 uses instead of 1 - though you may want to make them more expensive if you do..

     You can also enable items that otherwise don't spawn / cannot be crafted / cannot be found, as they are either to similar to another item or have their functions done better by other items. 
     Currently, those would be:
     - {{SODIUM_NITROPRUSSIDE}};
     - The {{ANTISEPTIC_SPRAYER}} and {{ANTISEPTIC}};
     - The old organ scalpels, with 1 scalpel per organ instead of the {{MULTIPURPOSE_SCALPEL}}.

     #### The third type of setting found here are Surgery changes:
     - Aortic Rupture is cured by {{OPEN_CLOSE_SURGERY}} by default. It can be changed to {{AORTIC_RUPTURE_SURGERY}} instead.
     - Cardiac Tamponade is cured by using a {{DRAINAGE}} during {{OPEN_CLOSE_SURGERY}} by default. It can be changed to not require the {{DRAINAGE}}.
---