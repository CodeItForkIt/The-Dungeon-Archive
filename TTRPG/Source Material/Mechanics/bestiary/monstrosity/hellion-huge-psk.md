---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/psk
- monster/cr/11
- monster/size/huge
- monster/type/monstrosity
statblock: inline
aliases: ["Hellion (Huge)"]
---
# [Hellion (Huge)](Mechanics\bestiary\monstrosity/hellion-huge-psk.md)
*Source: Plane Shift: Kaladesh p. 31*  

Hellions appear similar to wurms, though the two creatures are unrelated. A hellion has a long, segmented body like that of a centipede, with innumerable short legs that propel it above or below ground. Its huge, toothy maw is surrounded by anywhere from six to twelve long appendages resembling clawed fingers, which it uses to grasp and pull prey to its mouth. Hellions are found in mountainous areas, where they burst up from the rocky ground to ambush their prey.

The [remorhaz](Mechanics/bestiary/monstrosity/remorhaz.md) statistics in the "Monster Manual" work well for hellions of different sizes.

```statblock
"name": "Hellion (Huge) (PSK)"
"size": "Huge"
"type": "monstrosity"
"alignment": "Unaligned"
"ac": !!int "17"
"ac_class": "natural armor"
"hp": !!int "195"
"hit_dice": "17d12 + 85"
"stats":
- !!int "24"
- !!int "13"
- !!int "21"
- !!int "4"
- !!int "10"
- !!int "5"
"speed": "30 ft., burrow 20 ft."
"damage_immunities": "cold, fire"
"senses": "darkvision 60 ft., tremorsense 60 ft., passive Perception 10"
"languages": ""
"cr": "11"
"traits":
- "desc": "A creature that touches the hellion or hits it with a melee attack while\
    \ within 5 feet of it takes 10 (3d6) fire damage."
  "name": "Heated Body"
"actions":
- "desc": "Melee Weapon Attack: +11 to hit, reach 10 ft., one target. Hit: 40\
    \ (6d10 + 7) piercing damage plus 10 (3d6) fire damage. If the target is a\
    \ creature, it is [grappled](Mechanics/Rules/conditions.md#Grappled) (escape DC\
    \ 17). Until this grapple ends, the target is [restrained](Mechanics/Rules/conditions.md#Restrained),\
    \ and the hellion can't bite another target."
  "name": "Bite"
- "desc": "The hellion makes one bite attack against a Medium or smaller creature\
    \ it is grappling. If the attack hits, that creature takes the bite's damage and\
    \ is swallowed, and the grapple ends. While swallowed, the creature is [blinded](Mechanics/Rules/conditions.md#Blinded)\
    \ and [restrained](Mechanics/Rules/conditions.md#Restrained), it has total cover\
    \ against attacks and other effects outside the hellion, and it takes 21 (6d6)\
    \ acid damage at the start of each of the hellion's turns.\n\nIf the hellion takes\
    \ 30 damage or more on a single turn from a creature inside it, the hellion must\
    \ succeed on a DC 15 Constitution saving throw at the end of that turn or regurgitate\
    \ all swallowed creatures, which fall [prone](Mechanics/Rules/conditions.md#Prone)\
    \ in a space within 10 feet of the hellion. If the hellion dies, a swallowed creature\
    \ is no longer [restrained](Mechanics/Rules/conditions.md#Restrained) by it and\
    \ can escape from the corpse using 15 feet of movement, exiting [prone](Mechanics/Rules/conditions.md#Prone)."
  "name": "Swallow"
"source":
- "PSK"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/PSK/Hellion%20%28Huge%29.webp"
```
^statblock