---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/psk
- monster/cr/1-8
- monster/size/small
- monster/type/construct
statblock: inline
aliases: ["Thopter (Blood Hawk)"]
---
# [Thopter (Blood Hawk)](Mechanics\bestiary\construct/thopter-blood-hawk-psk.md)
*Source: Plane Shift: Kaladesh p. 33*  

Thopters are small automatons that fly using some combination of whirling rotors and stretched-fabric wings. They are ubiquitous in Ghirapur and other settlements, where they carry messages like carrier pigeons, hunt gremlins like trained hawks, race each other in friendly and not-so-friendly competitions—and serve as remote viewing devices for Consulate authorities and crime lords alike. Thopters range from the size of pigeons to the size of eagles, with extremely intricate gearwork usually partly visible beneath glass orbs and filigree.

Different kinds of thopters could be represented by the statistics for a [bat](Mechanics/bestiary/beast/bat.md), [blood hawk](Mechanics/bestiary/beast/blood-hawk.md), [eagle](Mechanics/bestiary/beast/eagle.md), [hawk](Mechanics/bestiary/beast/hawk.md), [owl](Mechanics/bestiary/beast/owl.md), [pseudodragon](Mechanics/bestiary/dragon/pseudodragon.md), [raven](Mechanics/bestiary/beast/raven.md), or [vulture](Mechanics/bestiary/beast/vulture.md) from the "Monster Manual". All thopters have the construct type, immunity to poison damage, and immunity to the [charmed](Mechanics/Rules/conditions.md#Charmed) and [poisoned](Mechanics/Rules/conditions.md#Poisoned) conditions.

## Artifact Creatures

Many of the products of Kaladesh's most inventive minds are tools meant to be wielded, piloted, or otherwise employed by other people. But the crowning achievement of the artificer's art is the imitation of life itself, crafting artificial creatures with the capability to move, act, and even make decisions independently, according to a comprehensive set of instructions.

Ghirapur is full of such artifact creatures—courier devices dashing through the streets of Bomat, thopters flitting from aerie to aerie, and assembly workers crafting more artifacts in busy foundries. These creatures are as diverse in their forms and appearance as they are in their purposes, but they can be broadly grouped into four categories: constructs, servos, thopters, and lifecraft creatures.

```statblock
"name": "Thopter (Blood Hawk) (PSK)"
"size": "Small"
"type": "construct"
"alignment": "Unaligned"
"ac": !!int "12"
"hp": !!int "7"
"hit_dice": "2d6"
"stats":
- !!int "6"
- !!int "14"
- !!int "10"
- !!int "3"
- !!int "14"
- !!int "5"
"speed": "10 ft., fly 60 ft."
"skillsaves":
  "Perception": !!int "4"
"damage_immunities": "poison"
"condition_immunities": "[charmed](Mechanics/Rules/conditions.md#Charmed), [poisoned](Mechanics/Rules/conditions.md#Poisoned)"
"senses": "passive Perception 14"
"languages": ""
"cr": "1/8"
"traits":
- "desc": "The thopter has advantage on Wisdom ([Perception](Mechanics/Rules/skills.md#Perception))\
    \ checks that rely on sight."
  "name": "Keen Sight"
- "desc": "The thopter has advantage on an attack roll against a creature if at least\
    \ one of the thopter's allies is within 5 feet of the creature and the ally isn't\
    \ [incapacitated](Mechanics/Rules/conditions.md#Incapacitated)."
  "name": "Pack Tactics"
"actions":
- "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 4 (1d4\
    \ + 2) piercing damage."
  "name": "Beak"
"source":
- "PSK"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/PSK/Thopter%20%28Blood%20Hawk%29.webp"
```
^statblock