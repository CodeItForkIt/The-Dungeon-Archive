---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/tob1-2023
- monster/cr/1-8
- monster/environment/any
- monster/size/medium
- monster/type/undead
statblock: inline
aliases: ["Shroud"]
---
# [Shroud](Mechanics\bestiary\undead/shroud-tob1-2023.md)
*Source: Tome of Beasts 1 (2023 Edition) p. 327*  

*The translucent person calls out a name in a barely audible whisper.*

## Bitter Spirits

Shrouds are transitional creatures: remnants of wicked people who died but refuse to rest in peace, yet have not grown strong enough to become shadows. They are aggressive enemies of all living creatures and the light that nurtures life. Shrouds blend naturally into darkness, but they stand out starkly in bright light.

## Thin Outlines

Shrouds look like flickering shadowy outlines of the people they were before they died, retaining the same height and body type.

## Repetitive Speech

Shrouds cannot converse, but they occasionally can be heard cruelly whispering a name, term, or phrase over and over again: something that must have had meaning to them in life.

```statblock
"name": "Shroud (ToB1-2023)"
"size": "Medium"
"type": "undead"
"alignment": "Neutral Evil"
"ac": !!int "11"
"hp": !!int "13"
"hit_dice": "3d8"
"stats":
- !!int "4"
- !!int "13"
- !!int "10"
- !!int "2"
- !!int "10"
- !!int "8"
"speed": "0 ft., fly 30 ft. (hover)"
"skillsaves":
  "Stealth": !!int "3"
"damage_vulnerabilities": "radiant"
"damage_resistances": "acid; cold; fire; lightning; thunder; bludgeoning, piercing,\
  \ slashing from nonmagical attacks"
"damage_immunities": "necrotic, poison"
"condition_immunities": "[exhaustion](Mechanics/Rules/conditions.md#Exhaustion), [frightened](Mechanics/Rules/conditions.md#Frightened),\
  \ [grappled](Mechanics/Rules/conditions.md#Grappled), [paralyzed](Mechanics/Rules/conditions.md#Paralyzed),\
  \ [petrified](Mechanics/Rules/conditions.md#Petrified), [poisoned](Mechanics/Rules/conditions.md#Poisoned),\
  \ [prone](Mechanics/Rules/conditions.md#Prone), [restrained](Mechanics/Rules/conditions.md#Restrained)"
"senses": "darkvision 60 ft., passive Perception 10"
"languages": "Common"
"cr": "1/8"
"traits":
- "desc": "The shroud can move through a space as narrow as 1 inch wide without squeezing."
  "name": "Amorphous"
- "desc": "If the shroud deals at least 12 necrotic damage to a creature that isn't\
    \ a Construct or Undead in 1 minute or less, the shroud transforms into a shadow\
    \ at the start of the turn after it last dealt damage. It uses the statistics\
    \ of the shadow, except it reduces the shadow's hp by an amount equal to the damage\
    \ the shroud took before it transformed."
  "name": "Shadow Evolution"
- "desc": "While in sunlight, the shroud has disadvantage on attack rolls, ability\
    \ checks, and saving throws."
  "name": "Sunlight Weakness"
- "desc": "The shroud doesn't require air, food, drink, or sleep."
  "name": "Undead Nature"
"actions":
- "desc": "Melee Weapon Attack: +3 to hit, reach 5 ft., one creature. Hit: 3\
    \ (1d4 + 1) necrotic damage, and the target has disadvantage on weapon attacks\
    \ that use Strength until the end of its next turn. If a non-evil humanoid dies\
    \ from this attack, a new shroud rises from the corpse 1d4 hours later."
  "name": "Strength Drain"
"bonus_actions":
- "desc": "While in dim light or darkness, the shroud takes the Hide action."
  "name": "Shadow Stealth"
"source":
- "ToB1-2023"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ToB1-2023/Shroud.webp"
```
^statblock

## Environment

any