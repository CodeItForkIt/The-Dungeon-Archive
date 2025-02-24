---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/tob1-2023
- monster/cr/6
- monster/environment/underdark
- monster/environment/urban
- monster/size/small
- monster/type/fey
statblock: inline
aliases: ["Scheznyki"]
---
# [Scheznyki](Mechanics\bestiary\fey/scheznyki-tob1-2023.md)
*Source: Tome of Beasts 1 (2023 Edition) p. 319*  

*The small, dwarf-like creature is bootless with broken, dirty toenails and wearing rough burlap and a leather tam hat. It brandishes a pick as it grins maliciously.*

## Corrupted Dwarves

These small, vicious, dwarf-like fey haunt abandoned quarries and ancient ruins, killing and robbing unsuspecting visitors. Legend says the scheznykis are lazy dwarves corrupted by the fey, though others claim that these are dwarves who swore allegiance to fey lords and ladies long ago.

## Magical Hats

Scheznykis prize their tam hats and viciously hunt down any who steal their hats. When a scheznyki dies or if its hat is separated from it for more than 24 hours, some of the scheznyki's magic imbues the hat (see Scheznyki's Hat sidebar).

## Arcane Beards

The majority of a scheznyki's magic is tied to its beard, and its beard hair is a valuable component for creating exotic inks. If the majority of its beard is cut off, the scheznyki can't cast spells until its beard regrows. If the scheznyki loses its hat and beard within the same 24-hour period, it falls into a deep, wasting coma and dies in 24 hours, crumbling to dust. If its beard is magically mended or regrown, or its hat restored to its head before this happens, the scheznyki recovers immediately.

> [!note] Scheznyki's Hat
> 
> When a scheznyki dies or 24 hours after its hat is stolen, its hat is imbued with the scheznyki's magic and becomes a vanisher hat.
^scheznykis-hat

```statblock
"name": "Scheznyki (ToB1-2023)"
"size": "Small"
"type": "fey"
"alignment": "Chaotic Evil"
"ac": !!int "16"
"ac_class": "natural armor"
"hp": !!int "135"
"hit_dice": "18d6 + 72"
"stats":
- !!int "19"
- !!int "15"
- !!int "18"
- !!int "15"
- !!int "16"
- !!int "16"
"speed": "20 ft., climb 15 ft., fly 40 ft."
"saves":
  "Strength": !!int "7"
  "Constitution": !!int "7"
"condition_immunities": "[unconscious](Mechanics/Rules/conditions.md#Unconscious)"
"senses": "darkvision 60 ft., passive Perception 13"
"languages": "Common, Dwarvish, Sylvan"
"cr": "6"
"traits":
- "desc": "The scheznyki casts one of the following spells, requiring no material\
    \ components and using Charisma as the spellcasting ability (spell save DC 14):\n\
    \nAt will: [dancing lights](Mechanics/spells/dancing-lights.md), [faerie fire](Mechanics/spells/faerie-fire.md)\n\
    \n1/day each: [dispel magic](Mechanics/spells/dispel-magic.md), [hold person](Mechanics/spells/hold-person.md)\n\
    \n3/day each: [locate object](Mechanics/spells/locate-object.md), [Tasha's\
    \ hideous laughter](Mechanics/spells/tashas-hideous-laughter.md), [ray of enfeeblement](Mechanics/spells/ray-of-enfeeblement.md)"
  "name": "Spellcasting"
- "desc": "A creature grappling the scheznyki can take its action to cut off the scheznyki's\
    \ beard by succeeding on a DC 15 Strength check while holding an edged weapon.\
    \ If its beard is cut off, the scheznyki can't use Spellcasting until its beard\
    \ regrows."
  "name": "Beard Weakness"
- "desc": "A melee weapon deals one extra die of its damage when the scheznyki hits\
    \ with it (included in the attack)."
  "name": "Brute"
- "desc": "The scheznyki has advantage on saving throws against spells and other magical\
    \ effects."
  "name": "Magic Resistance"
"actions":
- "desc": "The scheznyki makes three War Pick or Arcane Bolt attacks. It can replace\
    \ one attack with a use of Spellcasting."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +7 to hit, reach 5 ft., one target. Hit: 13\
    \ (2d8 + 4) piercing damage."
  "name": "War Pick"
- "desc": "Ranged Spell Attack: +6 to hit, range 60 ft., one target. Hit: 13\
    \ (3d6 + 3) force damage."
  "name": "Arcane Bolt"
- "desc": "The scheznyki magically turns [invisible](Mechanics/Rules/conditions.md#Invisible)\
    \ until it attacks or casts a spell, or until its [concentration](Mechanics/Rules/conditions.md#Concentration)\
    \ ends (as if concentrating on a spell). Any equipment it wears or carries is\
    \ [invisible](Mechanics/Rules/conditions.md#Invisible) with it."
  "name": "Invisibility"
"source":
- "ToB1-2023"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ToB1-2023/Scheznyki.webp"
```
^statblock

## Environment

underdark, urban