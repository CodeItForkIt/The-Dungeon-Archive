---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/psk
- monster/cr/1-4
- monster/size/tiny
- monster/type/construct
statblock: inline
aliases: ["Thopter (Pseudodragon)"]
---
# [Thopter (Pseudodragon)](Mechanics\bestiary\construct/thopter-pseudodragon-psk.md)
*Source: Plane Shift: Kaladesh p. 33*  

Thopters are small automatons that fly using some combination of whirling rotors and stretched-fabric wings. They are ubiquitous in Ghirapur and other settlements, where they carry messages like carrier pigeons, hunt gremlins like trained hawks, race each other in friendly and not-so-friendly competitions—and serve as remote viewing devices for Consulate authorities and crime lords alike. Thopters range from the size of pigeons to the size of eagles, with extremely intricate gearwork usually partly visible beneath glass orbs and filigree.

Different kinds of thopters could be represented by the statistics for a [bat](Mechanics/bestiary/beast/bat.md), [blood hawk](Mechanics/bestiary/beast/blood-hawk.md), [eagle](Mechanics/bestiary/beast/eagle.md), [hawk](Mechanics/bestiary/beast/hawk.md), [owl](Mechanics/bestiary/beast/owl.md), [pseudodragon](Mechanics/bestiary/dragon/pseudodragon.md), [raven](Mechanics/bestiary/beast/raven.md), or [vulture](Mechanics/bestiary/beast/vulture.md) from the "Monster Manual". All thopters have the construct type, immunity to poison damage, and immunity to the [charmed](Mechanics/Rules/conditions.md#Charmed) and [poisoned](Mechanics/Rules/conditions.md#Poisoned) conditions.

## Artifact Creatures

Many of the products of Kaladesh's most inventive minds are tools meant to be wielded, piloted, or otherwise employed by other people. But the crowning achievement of the artificer's art is the imitation of life itself, crafting artificial creatures with the capability to move, act, and even make decisions independently, according to a comprehensive set of instructions.

Ghirapur is full of such artifact creatures—courier devices dashing through the streets of Bomat, thopters flitting from aerie to aerie, and assembly workers crafting more artifacts in busy foundries. These creatures are as diverse in their forms and appearance as they are in their purposes, but they can be broadly grouped into four categories: constructs, servos, thopters, and lifecraft creatures.

```statblock
"name": "Thopter (Pseudodragon) (PSK)"
"size": "Tiny"
"type": "construct"
"alignment": "Neutral Good"
"ac": !!int "13"
"hp": !!int "7"
"hit_dice": "2d4 + 2"
"stats":
- !!int "6"
- !!int "15"
- !!int "13"
- !!int "10"
- !!int "12"
- !!int "10"
"speed": "15 ft., fly 60 ft."
"skillsaves":
  "Stealth": !!int "4"
  "Perception": !!int "3"
"damage_immunities": "poison"
"condition_immunities": "[charmed](Mechanics/Rules/conditions.md#Charmed), [poisoned](Mechanics/Rules/conditions.md#Poisoned)"
"senses": "blindsight 10 ft., darkvision 60 ft., passive Perception 13"
"languages": "understands Common and Draconic but can't speak"
"cr": "1/4"
"traits":
- "desc": "The thopter has advantage on Wisdom ([Perception](Mechanics/Rules/skills.md#Perception))\
    \ checks that rely on sight, hearing, or smell."
  "name": "Keen Senses"
- "desc": "The thopter has advantage on saving throws against spells and other magical\
    \ effects."
  "name": "Magic Resistance"
- "desc": "The thopter can magically communicate simple ideas, emotions, and images\
    \ telepathically with any creature within 100 feet of it that can understand a\
    \ language."
  "name": "Limited Telepathy"
"actions":
- "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 4 (1d4\
    \ + 2) piercing damage."
  "name": "Bite"
- "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one creature. Hit: 4\
    \ (1d4 + 2) piercing damage, and the target must succeed on a DC 11 Constitution\
    \ saving throw or become [poisoned](Mechanics/Rules/conditions.md#Poisoned) for\
    \ 1 hour. If the saving throw fails by 5 or more, the target falls [unconscious](Mechanics/Rules/conditions.md#Unconscious)\
    \ for the same duration, or until it takes damage or another creature uses an\
    \ action to shake it awake."
  "name": "Sting"
"source":
- "PSK"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/PSK/Thopter%20%28Pseudodragon%29.webp"
```
^statblock