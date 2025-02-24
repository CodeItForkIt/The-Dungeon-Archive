---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/tob1-2023
- monster/cr/1
- monster/environment/underdark
- monster/size/tiny
- monster/type/fey
statblock: inline
aliases: ["Chernomoi"]
---
# [Chernomoi](Mechanics\bestiary\fey/chernomoi-tob1-2023.md)
*Source: Tome of Beasts 1 (2023 Edition) p. 54*  

*These batwinged fey sport horns, scales, and other minor draconic features.*

## Dragon Sprites

Chernomoi (which means "lair sprite" in Draconic) often reside discreetly in a dragon lair or dragonborn household, cleaning and tidying up at night and only occasionally keeping a small trinket or shiny gemstone as compensation. They appear as tiny, winged humanoids, dressed in metallic armor made of small coins and semi-precious stones.

## Lair Alarms

Chernomoi are terrified of wyverns and never lair anywhere near them. Otherwise, they are very protective of their draconic masters and raise an alarm if an intruder is undetected. They fight with their tiny blades if cornered, though they always flee from danger as a first option—usually straight to a dragon, dragonborn, or drake ally.

> [!note] Chernomoi in Midgard
> 
> Dragons of the Mharoti Empire consider chernomoi cute guardian pets and treat them roughly the way humans treat a parrot or other pet bird. In some cases, chernomoi serve elder dragons as familiars and messengers, dressed in dazzling armor made of gemstones. Chernomoi familiars and messengers are as much valued companions as they are a visible sign of their master's wealth and power.
^chernomoi-in-midgard

```statblock
"name": "Chernomoi (ToB1-2023)"
"size": "Tiny"
"type": "fey"
"alignment": "Neutral"
"ac": !!int "14"
"hp": !!int "32"
"hit_dice": "5d4 + 20"
"stats":
- !!int "9"
- !!int "18"
- !!int "18"
- !!int "12"
- !!int "11"
- !!int "16"
"speed": "20 ft., fly 20 ft."
"skillsaves":
  "Stealth": !!int "6"
  "Perception": !!int "2"
  "Acrobatics": !!int "6"
"damage_resistances": "bludgeoning, piercing, slashing from nonmagical attacks that\
  \ aren't silvered"
"senses": "darkvision 60 ft., passive Perception 12"
"languages": "Common, Draconic, Sylvan"
"cr": "1"
"traits":
- "desc": "The chernomoi casts one of the following spells, requiring no material\
    \ components and using Charisma as the spellcasting ability (spell save DC 13):\n\
    \nAt will: [detect magic](Mechanics/spells/detect-magic.md), [mage hand](Mechanics/spells/mage-hand.md),\
    \ [mending](Mechanics/spells/mending.md), [message](Mechanics/spells/message.md),\
    \ [prestidigitation](Mechanics/spells/prestidigitation.md)\n\n1/day each:\
    \ [detect poison and disease](Mechanics/spells/detect-poison-and-disease.md),\
    \ [dimension door](Mechanics/spells/dimension-door.md)"
  "name": "Spellcasting"
"actions":
- "desc": "Melee Weapon Attack: +6 to hit, reach 5 ft., one target. Hit: 7 (1d6\
    \ + 4) slashing damage."
  "name": "Scimitar"
- "desc": "The chernomoi emits a loud shriek that is audible out to 100 feet. Each\
    \ creature within 60 feet of the chernomoi and that can hear it must make a DC\
    \ 13 Constitution saving throw, taking 10 (3d6) thunder damage on a failed save,\
    \ or half as much damage on a successful one."
  "name": "Shriek (Recharge 5-6)"
- "desc": "The chernomoi magically turns [invisible](Mechanics/Rules/conditions.md#Invisible)\
    \ until it attacks or uses Spellcasting, or until its [concentration](Mechanics/Rules/conditions.md#Concentration)\
    \ ends (as if concentrating on a spell). Any equipment the chernomoi wears or\
    \ carries is [invisible](Mechanics/Rules/conditions.md#Invisible) with it."
  "name": "Invisibility"
"source":
- "ToB1-2023"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ToB1-2023/Chernomoi.webp"
```
^statblock

## Environment

underdark