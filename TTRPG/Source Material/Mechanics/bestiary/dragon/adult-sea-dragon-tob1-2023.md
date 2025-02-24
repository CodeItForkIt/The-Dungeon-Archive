---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/tob1-2023
- monster/cr/18
- monster/environment/underwater
- monster/size/huge
- monster/type/dragon
statblock: inline
aliases: ["Adult Sea Dragon"]
---
# [Adult Sea Dragon](Mechanics\bestiary\dragon/adult-sea-dragon-tob1-2023.md)
*Source: Tome of Beasts 1 (2023 Edition) p. 126*  

*This aquamarine dragon has a shark's head that tapers off into a sleek eel-like body. Its large fins double as wings.*

## Divine Dragons

Sea dragons are the children of the ocean and believe they are semi-divine beings, worthy of worship. Given their size and power, they might be right; certainly, they are often companions or steeds to gods of the sea. Despite the solemn duties the sea dragons invoke thanks to their lineage, they are extremely whimsical. While these immense creatures are playful, their games can shatter hulls and drown sailors. The sea dragons course through the waves with tangible joy as they hunt whales and entire schools of tuna.

## Shipwreck Art

Sea dragons love collecting treasure. They especially prize the sunken, treasure-filled hulls of ships lost to storm, battle, or their own handiwork. While they appreciate all wealth, they prefer hardy items that stand up to long exposure to sea water. Precious metals and gemstones add a dramatic luster to the dragon's lair when they catch stray beams of light. Sea dragons take more perishable treasures and place them on a reef-altar, to dissolve in the sea as a tithe to the sea gods.

## Sunken Memorials

A sea dragon's lair is littered with meticulously arranged ships consigned to the deeps. These wrecks are often artfully smashed to allow the treasures in the hold to spill out onto the sea floor. It may seem haphazard, but it displays a complex aesthetic that only other sea dragons can truly appreciate. Because they arrange these wrecks so carefully, a dragon notices immediately if its hoard is disturbed.

> [!note] Priests of Seggotan
> 
> Every sea dragon is devoted to the dragon god of the sea. As a result, many sea dragons use the innate spellcasting variant. Sea dragons favor spells that manipulate water or the weather, emulate storms, deal lightning or cold damage, divine the future, or conjure sea creatures to fight alongside the dragon.
^priests-of-seggotan

> [!note] Sea Dragons in Midgard
> 
> Sea dragons are the offspring of Seggotan, the dragon god of time and the sea. A sea dragon shares its god's idea that everything in the sea is the property of Seggotan, and they expect lesser beings to respect that truth. The sea dragons are among the most powerful allies of the Mharoti Empire, securing seaways and acting as a communion point for the tidal priests. Thankfully for the Empire's enemies, the most ancient sea dragons are too consumed with contemplation of time and their inscrutable duties in the depths of the ocean to make war.
^sea-dragons-in-midgard

## A Sea Dragon's Lair

Sea dragons dwell in lairs beneath the waves: ocean fissures and caves, lightless trenches full of strange rock formations, and sheltered reefs of cultivated coral. Whatever the place, it's dedicated to the worship of sea gods. Despite the draconic instinct for seclusion and protection when choosing a lair, sea dragons always choose lairs relatively close to humanoid trade routes and abundant supplies of fish.

The sky surrounding a sea dragon's lair is perpetually stormy, and the seas run high. If a captain is courageous, these high winds and swift-running currents can cut significant time off a voyage.

```statblock
"name": "Adult Sea Dragon (ToB1-2023)"
"size": "Huge"
"type": "dragon"
"alignment": "Neutral Evil"
"ac": !!int "19"
"ac_class": "natural armor"
"hp": !!int "275"
"hit_dice": "22d12 + 132"
"stats":
- !!int "25"
- !!int "10"
- !!int "23"
- !!int "17"
- !!int "15"
- !!int "19"
"speed": "40 ft., fly 80 ft., swim 60 ft."
"saves":
  "Charisma": !!int "10"
  "Dexterity": !!int "6"
  "Wisdom": !!int "8"
  "Constitution": !!int "12"
"skillsaves":
  "Stealth": !!int "6"
  "Perception": !!int "14"
"damage_immunities": "cold"
"senses": "blindsight 60 ft., darkvision 120 ft., passive Perception 24"
"languages": "Common, Draconic, Primordial"
"cr": "18"
"traits":
- "desc": "The dragon can breathe air and water."
  "name": "Amphibious"
- "desc": "If the dragon fails a saving throw, it can choose to succeed instead."
  "name": "Legendary Resistance (3/Day)"
- "desc": "The dragon deals double damage to objects and structures."
  "name": "Siege Monster"
"actions":
- "desc": "The dragon uses its Frightful Presence. It then makes one Bite attack and\
    \ two Fin attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +13 to hit, reach 10 ft., one target. Hit: 18\
    \ (2d10 + 7) piercing damage plus 10 (3d6) cold damage."
  "name": "Bite"
- "desc": "Melee Weapon Attack: +13 to hit, reach 5 ft., one target. Hit: 14\
    \ (2d6 + 7) slashing damage."
  "name": "Fin"
- "desc": "Melee Weapon Attack: +13 to hit, reach 15 ft., one target. Hit: 16\
    \ (2d8 + 7) bludgeoning damage."
  "name": "Tail"
- "desc": "Each creature of the dragon's choice that is within 120 feet of the dragon\
    \ and aware of it must succeed on a DC 18 Wisdom saving throw or become [frightened](Mechanics/Rules/conditions.md#Frightened)\
    \ for 1 minute. A creature can repeat the saving throw at the end of each of its\
    \ turns, ending the effect on itself on a success. If a creature's saving throw\
    \ is successful or the effect ends for it, the creature is immune to the dragon's\
    \ Frightful Presence for the next 24 hours."
  "name": "Frightful Presence"
- "desc": "The dragon exhales a crushing wave of frigid seawater in a 60-foot cone.\
    \ Each creature in that area must make a DC 20 Dexterity saving throw. On a failure,\
    \ the creature takes 33 (6d10) bludgeoning damage and 33 (6d10) cold damage\
    \ and is pushed up to 30 feet away from the dragon and knocked [prone](Mechanics/Rules/conditions.md#Prone).\
    \ On a success, the creature takes half the damage and isn't pushed or knocked\
    \ [prone](Mechanics/Rules/conditions.md#Prone)."
  "name": "Tidal Breath (Recharge 5-6)"
"legendary_actions":
- "desc": "The dragon makes a Wisdom ([Perception](Mechanics/Rules/skills.md#Perception))\
    \ check."
  "name": "Detect"
- "desc": "The dragon makes a Tail attack."
  "name": "Tail Attack"
- "desc": "The dragon beats its wings. Each creature within 10 feet of the dragon\
    \ must succeed on a DC 21 Dexterity saving throw or take 14 (2d6 + 7) bludgeoning\
    \ damage and be knocked [prone](Mechanics/Rules/conditions.md#Prone). The dragon\
    \ can then move up to half its flying speed, or half its swimming speed if in\
    \ the water."
  "name": "Wing Attack (Costs 2 Actions)"
"lair_actions":
- "desc": "On initiative count 20 (losing initiative ties), the dragon takes a lair\
    \ action to cause one of the following effects; the dragon can't use the same\
    \ effect two rounds in a row:"
  "name": ""
- "desc": "- Create Coral Wall. The dragon creates an opaque wall of living coral\
    \ on a solid surface it can see within 120 feet of it. The wall can be up to 30\
    \ feet long, 30 feet high, and 1 foot thick. When the wall appears, each creature\
    \ in its area is pushed 5 feet out of the wall's space on whichever side of the\
    \ wall it wants, and it must make a DC 15 Dexterity saving throw, taking 18 (4d8)\
    \ slashing damage on a failed save, or half as much damage on a successful one.\
    \ While the wall remains, any creature that touches the wall must also make the\
    \ saving throw. Each 10-foot section of the wall has AC 5, 30 hp, resistance to\
    \ fire damage, and immunity to poison damage and psychic damage. The wall lasts\
    \ until the dragon uses this lair action again or until the dragon dies.  \n-\
    \ Invoke the Sea's Calm. The currents around up to four creatures in the water\
    \ and that the dragon can see within 120 feet of it work against the creatures.\
    \ Each target must succeed on a DC 15 Strength saving throw or it can't use reactions,\
    \ its speed is halved, and it can't make more than one attack on its turn until\
    \ initiative count 20 on the next round.  \n- Whirlpools. Four vortexes of\
    \ water appear centered on points underwater or on the water's surface that the\
    \ dragon can see within 120 feet of it. Each vortex takes the shape of a cylinder\
    \ that is 30 feet tall with a 5-foot radius. Each creature that enters a vortex\
    \ for the first time on a turn or starts its turn there must make a DC 15 Strength\
    \ saving throw or be restrained. A creature, including a restrained creature,\
    \ can take its action to free the restrained creature by succeeding on a DC 15\
    \ Strength check. The vortexes last until the dragon uses this lair action again\
    \ or until the dragon dies.  "
  "name": ""
"regional_effects":
- "desc": "The region containing a legendary sea dragon's lair is warped by the dragon's\
    \ magic, which creates one or more of the following effects:"
  "name": ""
- "desc": "- Chill of the Deeps. Water temperatures drop within 1 mile of the\
    \ dragon's lair, turning the water frigid and endangering swimming creatures not\
    \ accustomed to arctic waters.  \n- Tempestuous Weather. Storms and rough\
    \ water are more common within 6 miles of the lair.  \n- Thriving Waterways.\
    \ Sea life becomes richer within 6 miles of the lair. Schools of fish move into\
    \ new waters, sharks become common, and whale migration paths shift to pass near\
    \ the area.  "
  "name": ""
- "desc": "If the dragon dies, these effects fade over the course of 1d10 days."
  "name": ""
"source":
- "ToB1-2023"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ToB1-2023/Adult%20Sea%20Dragon.webp"
```
^statblock

## Environment

underwater