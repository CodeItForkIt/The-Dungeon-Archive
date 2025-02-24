---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/tob1-2023
- monster/cr/7
- monster/environment/planar
- monster/environment/urban
- monster/size/medium
- monster/type/undead
statblock: inline
aliases: ["Umbral Vampire"]
---
# [Umbral Vampire](Mechanics\bestiary\undead/umbral-vampire-tob1-2023.md)
*Source: Tome of Beasts 1 (2023 Edition) p. 382*  

*This deathly pale, gaunt human has stringy hair and wears scant rags. Misty strands of darkness leak from its empty eye sockets, yawning nasal cavity, and mouth.*

## Cursed Origin

Legends speak of an ancient city whose origins are lost to the ages, where a cabal of wizards with the power to manipulate the flow of time made its citizens immortal. When the wizards fell and no longer held back the ravages of time, the citizens aged centuries in moments. Instead of dying, the wretches lingered on in their dark realm.

## Bound to Darkness

All umbral vampires originate in the City Fallen into Shadow, and under most circumstances, they're encountered only in that forsaken place. Despite the terrors it holds, adventurers continue to seek the city, chasing legends of potent artifacts and boundless treasure accumulated during its golden age. Occasionally, an umbral vampire slips into the mortal world, where it hides in a place seldom or never touched by sunlight and emerges at night to search for victims.

```statblock
"name": "Umbral Vampire (ToB1-2023)"
"size": "Medium"
"type": "undead"
"alignment": "Chaotic Evil"
"ac": !!int "14"
"hp": !!int "84"
"hit_dice": "13d8 + 26"
"stats":
- !!int "1"
- !!int "18"
- !!int "15"
- !!int "14"
- !!int "14"
- !!int "19"
"speed": "0 ft., fly 40 ft. (hover)"
"saves":
  "Charisma": !!int "7"
  "Dexterity": !!int "7"
"skillsaves":
  "Stealth": !!int "7"
  "Perception": !!int "5"
"damage_resistances": "acid; fire; lightning; bludgeoning, piercing, slashing from\
  \ nonmagical attacks"
"damage_immunities": "cold, necrotic, poison"
"condition_immunities": "[exhaustion](Mechanics/Rules/conditions.md#Exhaustion), [grappled](Mechanics/Rules/conditions.md#Grappled),\
  \ [paralyzed](Mechanics/Rules/conditions.md#Paralyzed), [petrified](Mechanics/Rules/conditions.md#Petrified),\
  \ [poisoned](Mechanics/Rules/conditions.md#Poisoned), [prone](Mechanics/Rules/conditions.md#Prone),\
  \ [restrained](Mechanics/Rules/conditions.md#Restrained)"
"senses": "darkvision 60 ft., passive Perception 15"
"languages": "Common, Umbral, Void Speech"
"cr": "7"
"traits":
- "desc": "The umbral vampire can move through other creatures and objects as if they\
    \ were difficult terrain. It takes 5 (1d10) force damage if it ends its turn\
    \ inside an object."
  "name": "Incorporeal Movement"
- "desc": "While in sunlight, the umbral vampire has disadvantage on attack rolls,\
    \ as well as on Wisdom ([Perception](Mechanics/Rules/skills.md#Perception)) checks\
    \ that rely on sight."
  "name": "Sunlight Sensitivity"
- "desc": "The umbral vampire doesn't require air."
  "name": "Undead Nature"
"actions":
- "desc": "The umbral vampire can use its Umbral Grasp. It then makes two Shadow Touch\
    \ attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +7 to hit, reach 5 ft., one target. Hit: 17\
    \ (3d8 + 4) necrotic damage, and the target's Strength score is reduced by 1d4.\
    \ The target dies if this reduces its Strength to 0. Otherwise, the reduction\
    \ lasts until the target finishes a short or long rest. A non-evil Humanoid slain\
    \ by this attack rises 24 hours later as a shadow under the vampire's control,\
    \ unless the Humanoid is restored to life. The vampire can have no more than five\
    \ shadows under its control at one time."
  "name": "Shadow Touch"
- "desc": "The umbral vampire sends a giant hand of shadow to grab one creature it\
    \ can see that is in dim light or darkness within 30 feet of it. The target must\
    \ succeed on a DC 15 Dexterity saving throw or be [restrained](Mechanics/Rules/conditions.md#Restrained)\
    \ by wisps of magical shadow for 1 minute. While [restrained](Mechanics/Rules/conditions.md#Restrained),\
    \ the target takes 9 (2d8) necrotic damage at the start of each of its turns.\
    \ The target can repeat the saving throw at the end of each of its turns, ending\
    \ the effect on itself on a success. The umbral vampire can have no more than\
    \ two creatures [restrained](Mechanics/Rules/conditions.md#Restrained) by its\
    \ Umbral Grasp at a time."
  "name": "Umbral Grasp"
"bonus_actions":
- "desc": "While in dim light or darkness, the umbral vampire takes the Hide action."
  "name": "Shadow Stealth"
"source":
- "ToB1-2023"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ToB1-2023/Umbral%20Vampire.webp"
```
^statblock

## Environment

planar, urban