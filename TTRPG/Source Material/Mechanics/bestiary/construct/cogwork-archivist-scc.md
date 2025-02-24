---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/scc
- monster/cr/4
- monster/size/large
- monster/type/construct
statblock: inline
aliases: ["Cogwork Archivist"]
---
# [Cogwork Archivist](Mechanics\bestiary\construct/cogwork-archivist-scc.md)
*Source: Strixhaven: A Curriculum of Chaos p. 188*  

Programmed with knowledge of Strixhaven's extensive lore catalog, cogwork archivists serve as keepers of the university's various libraries. The archivists' towering metal frames are equipped with long, articulated limbs and retractable conservator tools, which they use to organize and preserve documents from throughout Strixhaven's winding history. Many cogwork archivists can be found among the towering shelves of the Biblioplex, simultaneously retrieving scrolls for curious students while keeping a stern eye on any rowdy groups that might disrupt the quiet atmosphere.

```statblock
"name": "Cogwork Archivist (SCC)"
"size": "Large"
"type": "construct"
"alignment": "typically  Lawful Neutral"
"ac": !!int "17"
"ac_class": "natural armor"
"hp": !!int "90"
"hit_dice": "12d10 + 24"
"stats":
- !!int "18"
- !!int "10"
- !!int "15"
- !!int "17"
- !!int "11"
- !!int "6"
"speed": "40 ft."
"skillsaves":
  "Nature": !!int "5"
  "Religion": !!int "5"
  "Perception": !!int "2"
  "History": !!int "5"
  "Arcana": !!int "5"
"damage_immunities": "poison"
"condition_immunities": "[charmed](Mechanics/Rules/conditions.md#Charmed), [exhaustion](Mechanics/Rules/conditions.md#Exhaustion),\
  \ [frightened](Mechanics/Rules/conditions.md#Frightened), [petrified](Mechanics/Rules/conditions.md#Petrified),\
  \ [poisoned](Mechanics/Rules/conditions.md#Poisoned)"
"senses": "darkvision 60 ft., passive Perception 12"
"languages": "all"
"cr": "4"
"traits":
- "desc": "The archivist casts one of the following spells, requiring no material\
    \ components and using Intelligence as the spellcasting ability:\n\nAt will:\
    \ [dancing lights](Mechanics/spells/dancing-lights.md), [prestidigitation](Mechanics/spells/prestidigitation.md)\n\
    \n2/day: [silence](Mechanics/spells/silence.md)"
  "name": "Spellcasting"
- "desc": "The archivist has advantage on saving throws against spells and other magical\
    \ effects."
  "name": "Magic Resistance"
"actions":
- "desc": "The archivist makes two Grasping Limb attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +6 to hit, reach 15 ft., one target. Hit: 13\
    \ (2d8 + 4) bludgeoning damage, and the target is [grappled](Mechanics/Rules/conditions.md#Grappled)\
    \ (escape DC 14). The archivist can have no more than two targets [grappled](Mechanics/Rules/conditions.md#Grappled)\
    \ at a time."
  "name": "Grasping Limb"
"source":
- "SCC"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/SCC/Cogwork%20Archivist.webp"
```
^statblock