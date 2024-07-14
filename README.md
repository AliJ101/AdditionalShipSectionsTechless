# Stellaris-MoreShipSections
A mod for Stellaris that adds more ship sections to use, balanced fairly close to the vanilla ones.

I strongly recommend using UI Overhaul Dynamic, or something similar, otherwise some of the more populated ship sections may be hard to use.

The current list of new sections is below:

  Titan:
  
    Lancer Bow - 3 X-Large slots 
    Carrier Bow - 4 Hangar, 4 Small, and 4 Point Defence slots
    Broadside Core - 2 Large, and 4 Medium slots
    Carrier Core - 3 Hangar, 2 Small, and 2 Point Defence slots
    Storm Core - 4 Medium, and 8 Small slots
    Broadside Stern - 4 Medium slots
    Carrier Stern - 1 Hangar, 1 Medium, and 2 Point Defence slots
    Storm Stern - 2 Medium, and 4 Small slots

  Juggernaut

      Pulsar - 4 X-Large, 3 Hangar, and 3 Medium slots
      Hive - 10 Hangar, and 5 Medium slots 

  Ion Cannon:
  
      Lancer Core - 3 X-Large slots

  Battleship:

      Storm Bow - 2 Medium, and 4 Small slots
      Storm Core - 3 Medium, and 6 Small slots
      Storm Stern - 1 Medium, and 2 Small slots
      Carrier Stern - 1 Hangar slot

  Cruiser:

      Gunship Bow - 1 Medium, and 2 Small slots
      Hangar Bow - 1 Hangar slot
      Aegis Bow - 1 Medium, and 2 Point Defence slots
      Gunship Core - 1 Medium, and 4 Small slots
      Aegis Core - 2 Small, and 4 Point Defence slots
      Aegis Stern - 2 Point Defence slots

  Destroyer:

      Picket Bow - 2 Small, and 2 Point Defence slots (modified vanilla section to fit with the others)
      Hangar Bow - 1 Hangar slot
      Aegis Bow - 1 Medium, and 2 Point Defence slots

  Frigate:

      Picket Boat - 1 Point Defence, and 1 G slots

  Corvette:

      Aegis Ship - 1 Small, and 2 Point Defence slots

How is this balanced?

In Stellaris, the slots available for weapons work on a system where one Large weapon slot can be "traded" for two Medium weapon slots, four Small weapon slots, or one Medium and two Point Defence slots, and so on. This is shown in the vanilla ship sections, ignoring the Destroyer's Picket Ship Bow. This can be written out in a table, which I used as reference for the ship sections in this mod.

    Slot Type | S | P | M | G | L | H | X | T
    Cost      | 1 | 1 | 2 | 2 | 4 | 4 | 8 | 24

The Titanic weapons (T slot) are the odd one out, but I compared the X-Large slot weapons to the Titanic weapons, and thought that the damage-per-tick with just two X slot weapons was not comparable. Three X slot weapons somewhat balances the shorter range and higher cost with the multi-target capability and better damage-per-tick compared to a Peridition Beam. A Ruination Glare will still do more damage-per-tick than 3 X slot weapons, but the shorter range should compensate a little. Of course, when the Ruination Glare is enhanced by the Archaeo-Engineers perk, it outstrips every other choice by a significant margin, as it should given you are spending an Ascension Perk on it.

Given these numbers for weapon slots, we can work out how much "weight" in weapons each class gets in vanilla Stellaris, as detailed below:

    Ship Class | Total | Bow | Mid | Aft
      Corvette |   3   | N/A |  3  | N/A
       Frigate |   3   | N/A |  3  | N/A
     Destroyer |   6*  |  4* | N/A |  2
       Cruiser |   12  |  4  |  6  |  2
    Battleship |   24  |  8  |  12 |  4
         Titan |   48  |  24 |  16 |  8
    Juggernaut |   50  | N/A |  50 | N/A
    *The Picket Ship Bow only uses 3, resulting in a total of 5. This is changed by this mod.

This makes a fairly pleasing sequence for all but the Juggernaut, which is an odd duck anyway as it's a mobile shipyard, and gives a guideline for new ship sections to be built around, while keeping fairly close to the original balance.
A note with Auxiliary Slots: Vanilla ship sections give most sterns with smaller weapon slots an additional Auxiliary slot, a pattern I've stuck to in these sections.

FAQ:


Q: Why does this mod exist?

A: This mod exists because I looked at my Titans, and went "Why can't I stick strike craft on these? Why just big guns?". It expanded from there.


Q: Does this add new graphics for the new ship sections?

A: No.

Q: Why are there no G slots on things that aren't Cruisers or Frigates?

A: Giving ships G slot weapons would also mean you should be able to give the ship the "Torpedo" computer to use them properly, as well as tell the AI to use them like torpedo ships. Unfortunately, this means changing how combat computers are defined, which would cause incompatabilities seemingly unrelated to the premise of the mod, the bane of any modlist maker. 

Q: Where are the T slots on Juggernauts?

A: For some reason, vanilla T slot weapons have restrictions on what kind of craft you can put them in defined in the files for the weapon, with two instances of otherwise identical weapons in the files, one locked to Titans, one to Ion Cannons. This means I'd have to
change files otherwise unrelated to ship sections to make them work, causing the same headaches to mod users as the previous question.

Q: Why not have armed Colossi?

A: The colossus, as the devs envisioned, is meant to be a planet killer with engines strapped to it. If you want a planet killer that can defend itself, take "Become the Crisis" and get Star Eaters.

Q: Why not change the Crisis Ships?

A: The Crisis ships (Menacing ships) are balanced differently, being cheaper, faster to build, less customisable, and, in the case of cruisers, a completely different weapon weight. These facts, particularly their less customisable nature, means I'm unwilling to change them.

Q: Is this compatible with [insert mod here]?

A: Does change how ship sections work? If it does, then no. Specifically, if the mod changes any of the following files, then the new sections for that ship will not show up:

    battleship.txt
    corvette.txt
    cruiser.txt
    destroyer.txt
    juggernaut.txt
    starbase.txt
    titan.txt
All of these are in common\section_templates


Q: Can you make a version compatible with [insert mod here]?

A: Maybe. For the likes of NSC, the changes they make would mean that the mod would need to be remade from scratch to add more sections, both from a technical and a balance perspective. 





