---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/oow
- monster/cr/0
- monster/size/huge
- monster/type/beast
statblock: inline
aliases: ["Onyx"]
---
# [Onyx](Mechanics\bestiary\npc/onyx-oow.md)
*Source: The Orrery of the Wanderer p. 186*  

Onyx is a regular cat, with special traits, and a modified attack, that only apply when used in the Onyx Ascendant encounter.

Further information can be found within that encounter on how to run it.

Without the special circumstances from that encounter, Onyx can be considered a standard cat

```statblock
"name": "Onyx (OoW)"
"size": "Huge"
"type": "beast"
"alignment": "Unaligned"
"ac": !!int "12"
"hp": !!int "2"
"hit_dice": "1d4"
"stats":
- !!int "3"
- !!int "15"
- !!int "10"
- !!int "3"
- !!int "12"
- !!int "7"
"speed": "400 ft., climb 200 ft."
"skillsaves":
  "Stealth": !!int "4"
  "Perception": !!int "3"
"senses": "passive Perception 13"
"languages": ""
"cr": "0"
"traits":
- "desc": "The cat has advantage on Wisdom ([Perception](Mechanics/Rules/skills.md#Perception))\
    \ checks that rely on smell."
  "name": "Keen Smell"
- "desc": "Any damage Onyx would take is reduced to 0. She has advantage on ability\
    \ checks and saving throws."
  "name": "Relative Size"
- "desc": "Onyx cannot be overcome or killed by combat. Any weapon attack against\
    \ her that hits AC 12 makes contact but deals no lasting damage. However, if the\
    \ attack would deal 10 or more damage, Onyx has disadvantage on attack rolls until\
    \ the end of her next turn. If Onyx would take 10 or more damage from spells or\
    \ other effects, it yields the same result. Spells that impose conditions function\
    \ normally against Onyx, but those conditions end automatically at the end of\
    \ the cat's next turn."
  "name": "Dealing with Onyx"
"actions":
- "desc": "Melee Weapon Attack: +7 to hit, reach 20 ft., one target. Hit: 11\
    \ (2d10) slashing damage."
  "name": "Claws"
"source":
- "OoW"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/OoW/Onyx.webp"
```
^statblock