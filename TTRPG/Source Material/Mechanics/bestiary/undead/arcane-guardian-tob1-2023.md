---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/tob1-2023
- monster/cr/8
- monster/environment/any
- monster/environment/urban
- monster/size/medium
- monster/type/undead
statblock: inline
aliases: ["Arcane Guardian"]
---
# [Arcane Guardian](Mechanics\bestiary\undead/arcane-guardian-tob1-2023.md)
*Source: Tome of Beasts 1 (2023 Edition) p. 338*  

*A luminous green mist swirls into the form of an ancient warrior. Dented armor and a ragged cloak enshroud the warrior's skeletal body, and its grinning skull leers out from an open helm.*

Some spectral guardians were not warriors in life, but powerful spellcasters.

## Worn Finery

Composed of faintly glowing green vapor, the arcane guardian is a skeletal being encased in ancient armor or noble's finery. The cloth is worn and tattered, spiraling away into mist at the edges, and the creature glides with the faintest whisper of sound.

## Eternal Disgrace

The arcane guardian is the spirit of an ancient warrior or noble, bound to serve in death as it failed to do in life. A broken oath, an act of cowardice, or a curse laid down by the gods for a terrible betrayal leaves an indelible mark on a soul. After the cursed creature's death, its spirit rises in a place closely related to its disgrace. Compelled by the crushing weight of its deeds, the arcane guardian knows no rest or peace.

```statblock
"name": "Arcane Guardian (ToB1-2023)"
"size": "Medium"
"type": "undead"
"alignment": "Neutral Evil"
"ac": !!int "14"
"hp": !!int "127"
"hit_dice": "15d8 + 60"
"stats":
- !!int "6"
- !!int "18"
- !!int "18"
- !!int "11"
- !!int "16"
- !!int "18"
"speed": "0 ft., fly 60 ft."
"saves":
  "Dexterity": !!int "7"
  "Wisdom": !!int "6"
"damage_resistances": "acid; fire; lightning; thunder; bludgeoning, piercing, slashing\
  \ from nonmagical attacks"
"damage_immunities": "cold, necrotic, poison"
"condition_immunities": "[charmed](Mechanics/Rules/conditions.md#Charmed), [exhaustion](Mechanics/Rules/conditions.md#Exhaustion),\
  \ [frightened](Mechanics/Rules/conditions.md#Frightened), [grappled](Mechanics/Rules/conditions.md#Grappled),\
  \ [paralyzed](Mechanics/Rules/conditions.md#Paralyzed), [petrified](Mechanics/Rules/conditions.md#Petrified),\
  \ [poisoned](Mechanics/Rules/conditions.md#Poisoned), [prone](Mechanics/Rules/conditions.md#Prone),\
  \ [restrained](Mechanics/Rules/conditions.md#Restrained)"
"senses": "blindsight 10 ft., darkvision 60 ft., passive Perception 13"
"languages": "understands the languages it knew in life but can't speak"
"cr": "8"
"traits":
- "desc": "The arcane guardian casts one of the following spells, requiring no material\
    \ components and using Charisma as the spellcasting ability (spell save DC 15):\n\
    \nAt will: [dancing lights](Mechanics/spells/dancing-lights.md), [fog cloud](Mechanics/spells/fog-cloud.md),\
    \ [minor illusion](Mechanics/spells/minor-illusion.md)\n\n1/day each: [Bigby's\
    \ hand](Mechanics/spells/bigbys-hand.md)\n\n3/day each: [fear](Mechanics/spells/fear.md),\
    \ [slow](Mechanics/spells/slow.md)"
  "name": "Spellcasting"
- "desc": "The arcane guardian is bound to a tomb, castle ruins, or other place related\
    \ to the disgrace in life that caused it to rise as a arcane guardian in death.\
    \ If the guardian starts its turn more than 1 mile from its bound location, it\
    \ loses its Spectral Blade action until it returns to the region. If it remains\
    \ outside the region, it automatically teleports back to its bound location after\
    \ 24 hours, regardless of distance."
  "name": "Disgrace Bound"
- "desc": "The arcane guardian can move through other creatures and objects as if\
    \ they were difficult terrain. It takes 5 (1d10) force damage if it ends its\
    \ turn inside an object."
  "name": "Incorporeal Movement"
- "desc": "The arcane guardian doesn't require air, food, drink, or sleep."
  "name": "Undead Nature"
"actions":
- "desc": "The arcane guardian makes three Spectral Burst attacks. It can replace\
    \ one attack with a use of Spellcasting."
  "name": "Multiattack"
- "desc": "Melee or Ranged Spell Attack: +7 to hit, reach 5 ft. or range 120 ft.,\
    \ one target. Hit: 9 (1d10 + 4) force damage plus 9 (2d8) necrotic damage."
  "name": "Spectral Burst"
"source":
- "ToB1-2023"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ToB1-2023/Arcane%20Guardian.webp"
```
^statblock

## Environment

any, urban