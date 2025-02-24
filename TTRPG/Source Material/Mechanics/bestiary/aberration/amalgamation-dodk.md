---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/dodk
- monster/cr/23
- monster/size/gargantuan
- monster/type/aberration
statblock: inline
aliases: ["Amalgamation"]
---
# [Amalgamation](Mechanics\bestiary\aberration/amalgamation-dodk.md)
*Source: Dungeons of Drakkenheim p. 206*  

> [!quote] A quote from Eldrick Runeweaver  
> 
> Formed only in places where dimensional rifts are torn open, this blasphemous abomination is a conduit by which beings from realms of chaos untold can enter our world. It is an interdimensional cancer which infects our earth.


```statblock
"name": "Amalgamation (DoDk)"
"size": "Gargantuan"
"type": "aberration"
"alignment": "Chaotic Evil"
"ac": !!int "18"
"ac_class": "natural armor"
"hp": !!int "525"
"hit_dice": "30d20 + 210"
"stats":
- !!int "30"
- !!int "11"
- !!int "27"
- !!int "22"
- !!int "18"
- !!int "20"
"speed": "5 ft."
"saves":
  "Dexterity": !!int "7"
  "Wisdom": !!int "11"
  "Intelligence": !!int "13"
  "Strength": !!int "17"
  "Constitution": !!int "15"
"skillsaves":
  "Deception": !!int "12"
  "Insight": !!int "11"
  "Perception": !!int "11"
  "Arcana": !!int "13"
"damage_immunities": "bludgeoning, piercing, slashing from nonmagical attacks"
"condition_immunities": "[charmed](Mechanics/Rules/conditions.md#Charmed), [exhaustion](Mechanics/Rules/conditions.md#Exhaustion),\
  \ [frightened](Mechanics/Rules/conditions.md#Frightened), [paralyzed](Mechanics/Rules/conditions.md#Paralyzed),\
  \ [petrified](Mechanics/Rules/conditions.md#Petrified), [poisoned](Mechanics/Rules/conditions.md#Poisoned),\
  \ [prone](Mechanics/Rules/conditions.md#Prone), [stunned](Mechanics/Rules/conditions.md#Stunned)"
"senses": "truesight 120 ft., passive Perception 21"
"languages": "all, telepathy 1 mile"
"cr": "23"
"traits":
- "desc": "The amalgamation's innate spellcasting ability is Charisma (spell save\
    \ DC 20). It can innately cast the following spells, requiring no components:\n\
    \nAt will: [detect thoughts](Mechanics/spells/detect-thoughts.md), [dispel\
    \ magic](Mechanics/spells/dispel-magic.md)"
  "name": "Innate Spellcasting"
- "desc": "If the amalgamation fails a saving throw, it can choose to succeed instead."
  "name": "Legendary Resistance (3/Day)"
- "desc": "The amalgamation can't be teleported or travel to another plane against\
    \ its will."
  "name": "Malignancy"
- "desc": "The amalgamation is immune to any spell or effect that would alter its\
    \ form."
  "name": "Immutable Form"
- "desc": "The amalgamation's weapon attacks are magical."
  "name": "Magic Weapons"
"actions":
- "desc": "The amalgamation uses its Contaminating Presence. It then makes three tentacle\
    \ attacks, each of which it can replace with one use of Fling."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +17 to hit, reach 5 ft., one target. Hit: 23\
    \ (3d8 + 10) piercing damage. If the target is a Large or smaller creature [grappled](Mechanics/Rules/conditions.md#Grappled)\
    \ by the amalgamation, that creature is swallowed, and the grapple ends.\n\nWhile\
    \ swallowed, the creature is [blinded](Mechanics/Rules/conditions.md#Blinded)\
    \ and [restrained](Mechanics/Rules/conditions.md#Restrained), it has total cover\
    \ against attacks and other effects outside the amalgamation, and it takes 42\
    \ (12d6) acid damage and gains one level of contamination at the start of each\
    \ of the amalgamation's turns.\n\nIf the amalgamation takes 50 damage or more\
    \ on a single turn from a creature inside it, the amalgamation must succeed on\
    \ a DC 25 Constitution saving throw at the end of that turn or regurgitate all\
    \ swallowed creatures, which fall [prone](Mechanics/Rules/conditions.md#Prone)\
    \ in a space within 10 feet of the amalgamation. If the amalgamation dies, a swallowed\
    \ creature is no longer [restrained](Mechanics/Rules/conditions.md#Restrained)\
    \ by it and can escape from the corpse using 15 feet of movement, exiting [prone](Mechanics/Rules/conditions.md#Prone)."
  "name": "Bite"
- "desc": "Melee Weapon Attack: +17 to hit, reach 50 ft., one target. Hit: 20\
    \ (3d6 + 10) bludgeoning damage, and the target is [grappled](Mechanics/Rules/conditions.md#Grappled)\
    \ (escape DC 18). Until this grapple ends, the target is [restrained](Mechanics/Rules/conditions.md#Restrained).\
    \ The amalgamation has twelve tentacles, each of which can grapple one target."
  "name": "Tentacle"
- "desc": "One Large or smaller object held or creature [grappled](Mechanics/Rules/conditions.md#Grappled)\
    \ by the amalgamation is thrown up to 60 feet in a direction of the amalgamation's\
    \ choice and knocked [prone](Mechanics/Rules/conditions.md#Prone). If a thrown\
    \ target strikes a solid surface, the target takes 3 (1d6) bludgeoning damage\
    \ for every 10 feet it was thrown. If the target is thrown at another creature,\
    \ that creature must succeed on a DC 18 Dexterity saving throw or take the same\
    \ damage and be knocked [prone](Mechanics/Rules/conditions.md#Prone)."
  "name": "Fling"
- "desc": "The amalgamation utters a terrible truth within the mind of one creature\
    \ within 120 feet of it. That creature must succeed on a DC 20 Intelligence saving\
    \ throw. On a failure, it takes 35 (10d6) psychic damage and becomes insane\
    \ until it finishes a long rest. While insane, it can't take actions, can't understand\
    \ what other creatures say, can't read, and can speak only in gibberish. A [greater\
    \ restoration](Mechanics/spells/greater-restoration.md) spell cast on the creature\
    \ ends this effect."
  "name": "Mind-breaking Whispers"
- "desc": "Humanoid creatures within 120 feet of the amalgamation must succeed on\
    \ a DC 20 Constitution saving throw or take 10 (3d6) necrotic damage and gain\
    \ one level of contamination."
  "name": "Contaminating Presence"
"legendary_actions":
- "desc": "The amalgamation makes one tentacle attack or uses its Fling."
  "name": "Tentacle Attack or Fling"
- "desc": "The amalgamation uses Mind-breaking Whispers."
  "name": "Mind-breaking Whispers (Costs 2 Actions)"
- "desc": "Up to five gibbering mouthers appear in unoccupied spaces within 30 feet\
    \ of the amalgamation and remain until destroyed. These creatures act after the\
    \ amalgamation on the same initiative count and are under its control. The amalgamation\
    \ can have up to ten gibbering mouthers summoned by this ability at a time."
  "name": "Piper at the Gate (Costs 3 Actions)"
"source":
- "DoDk"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/DoDk/Amalgamation.webp"
```
^statblock