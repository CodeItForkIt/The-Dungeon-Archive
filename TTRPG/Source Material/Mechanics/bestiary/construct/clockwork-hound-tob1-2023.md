---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/tob1-2023
- monster/cr/2
- monster/environment/urban
- monster/size/medium
- monster/type/construct
statblock: inline
aliases: ["Clockwork Hound"]
---
# [Clockwork Hound](Mechanics\bestiary\construct/clockwork-hound-tob1-2023.md)
*Source: Tome of Beasts 1 (2023 Edition) p. 61*  

*This black, mechanical hunting dog keeps its nose to the ground sniffing and whuffling. Gleaming teeth fill its metal mouth.*

## Ticking Bloodhounds

Partners to clockwork huntsmen, these black hounds follow the trails of criminals, escaped slaves, and other unfortunates. Their infused spirits are those of hunting hounds, and their animating magic allows them to follow a scent with preternatural speed and accuracy.

## Toy Variants

Some claim the infusion of animal spirits into clockwork hounds was one of the great arcane discoveries that made the creation of the gearforged possible; others say that it only made clockwork mages rich. Certainly, the earliest hounds were built for work and war, but recent varieties also include some that are deceptively big-eyed and painted as children's toys or to match a young aristocrat's favorite outfit.

## Serve the Rulers

Despite this brief flirtation with fashion, most clockwork hounds continue to serve town watches, royal huntsmen, road wardens, moneylenders, and criminal gangs as loyal trackers and guards.

> [!note] Clockworks in Midgard
> 
> Clockwork magic in Midgard is common in the Free City of Zobeck and other advanced towns and cities. Devices made with such magic are commonly as much status symbol as functional tool. The Gear Goddess Rava smiles on all such creations, and destroying them is an affront to her sense of balance and industry—smashing a clockwork is said to be quite unlucky. Gear mages practice a school of clockwork magic that creates and sustains many such devices.
^clockworks-in-midgard

```statblock
"name": "Clockwork Hound (ToB1-2023)"
"size": "Medium"
"type": "construct"
"alignment": "Unaligned"
"ac": !!int "12"
"hp": !!int "71"
"hit_dice": "11d8 + 22"
"stats":
- !!int "16"
- !!int "15"
- !!int "14"
- !!int "1"
- !!int "10"
- !!int "1"
"speed": "50 ft."
"saves":
  "Dexterity": !!int "4"
  "Constitution": !!int "4"
"skillsaves":
  "Athletics": !!int "7"
  "Perception": !!int "4"
"damage_immunities": "poison, psychic"
"condition_immunities": "[charmed](Mechanics/Rules/conditions.md#Charmed), [exhaustion](Mechanics/Rules/conditions.md#Exhaustion),\
  \ [frightened](Mechanics/Rules/conditions.md#Frightened), [paralyzed](Mechanics/Rules/conditions.md#Paralyzed),\
  \ [petrified](Mechanics/Rules/conditions.md#Petrified), [poisoned](Mechanics/Rules/conditions.md#Poisoned)"
"senses": "darkvision 60 ft., passive Perception 14"
"languages": "understands Common but can't speak"
"cr": "2"
"traits":
- "desc": "The clockwork hound doesn't require air, food, drink, or sleep."
  "name": "Construct Nature"
- "desc": "The clockwork hound has advantage on Wisdom ([Perception](Mechanics/Rules/skills.md#Perception))\
    \ and Wisdom ([Survival](Mechanics/Rules/skills.md#Survival)) checks that rely\
    \ on scent or that are made to find a creature."
  "name": "Diligent Tracker"
- "desc": "The mechanism that powers the hound explodes when the Construct is destroyed.\
    \ Each creature within 5 feet of the hound when it is destroyed must make a DC\
    \ 12 Dexterity saving throw, taking 7 (2d6) fire damage on a failed save, or\
    \ half as much damage on a successful one."
  "name": "Explosive Core"
- "desc": "The clockwork hound is immune to any spell or effect that would alter its\
    \ form."
  "name": "Immutable Form"
- "desc": "The clockwork hound has advantage on saving throws against spells and other\
    \ magical effects."
  "name": "Magic Resistance"
"actions":
- "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 14\
    \ (2d10 + 3) piercing damage."
  "name": "Bite"
- "desc": "Melee Weapon Attack: +5 to hit, reach 15 ft., one target. Hit: 12\
    \ (2d8 + 3) slashing damage, and the target must succeed on a DC 13 Strength\
    \ saving throw or be knocked [prone](Mechanics/Rules/conditions.md#Prone)."
  "name": "Tripping Tongue"
"source":
- "ToB1-2023"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ToB1-2023/Clockwork%20Hound.webp"
```
^statblock

## Environment

urban