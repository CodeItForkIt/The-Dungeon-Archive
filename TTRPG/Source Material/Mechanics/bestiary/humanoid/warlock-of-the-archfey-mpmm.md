---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/mpmm
- monster/cr/4
- monster/environment/arctic
- monster/environment/forest
- monster/environment/mountain
- monster/environment/swamp
- monster/environment/urban
- monster/size/medium
- monster/type/humanoid
statblock: inline
aliases: ["Warlock of the Archfey"]
---
# [Warlock of the Archfey](Mechanics\bestiary\humanoid/warlock-of-the-archfey-mpmm.md)
*Source: Mordenkainen Presents: Monsters of the Multiverse p. 255*  

Warlocks of the Archfey gain their powers through magical pacts forged with lords of the Feywild. These warlocks commonly associate with lesser Fey creatures such as [boggles](Mechanics/bestiary/fey/boggle-mpmm.md), [quicklings](Mechanics/bestiary/fey/quickling-mpmm.md), and [redcaps](Mechanics/bestiary/fey/redcap-mpmm.md) (all appear in "this book") or even [satyrs](Mechanics/bestiary/fey/satyr.md) and [sprites](Mechanics/bestiary/fey/sprite.md).

## Warlocks

Warlocks gain arcane might through magical pacts with mysterious entities. While some use their abilities to serve the sources of their power, others use them to undermine or even destroy these entities.

```statblock
"name": "Warlock of the Archfey (MPMM)"
"size": "Medium"
"type": "humanoid"
"alignment": "Any alignment"
"ac": !!int "13"
"ac_class": "16 with [mage armor](Mechanics/spells/mage-armor.md)"
"hp": !!int "67"
"hit_dice": "15d8"
"stats":
- !!int "9"
- !!int "16"
- !!int "11"
- !!int "11"
- !!int "12"
- !!int "18"
"speed": "30 ft."
"saves":
  "Charisma": !!int "6"
  "Wisdom": !!int "3"
"skillsaves":
  "Nature": !!int "2"
  "Deception": !!int "6"
  "Arcana": !!int "2"
  "Persuasion": !!int "6"
"condition_immunities": "[charmed](Mechanics/Rules/conditions.md#Charmed)"
"senses": "passive Perception 11"
"languages": "any two languages (usually Sylvan)"
"cr": "4"
"traits":
- "desc": "The warlock casts one of the following spells, using Charisma as the spellcasting\
    \ ability (spell save DC 14): \n\nAt will: [dancing lights](Mechanics/spells/dancing-lights.md),\
    \ [disguise self](Mechanics/spells/disguise-self.md), [mage armor](Mechanics/spells/mage-armor.md)\
    \ (self only), [mage hand](Mechanics/spells/mage-hand.md), [minor illusion](Mechanics/spells/minor-illusion.md),\
    \ [prestidigitation](Mechanics/spells/prestidigitation.md), [speak with animals](Mechanics/spells/speak-with-animals.md)\n\
    \n1/day each: [charm person](Mechanics/spells/charm-person.md), [dimension\
    \ door](Mechanics/spells/dimension-door.md), [hold monster](Mechanics/spells/hold-monster.md)"
  "name": "Spellcasting"
"actions":
- "desc": "The warlock makes two Rapier attacks, or it uses Bewildering Word twice."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 7 (1d8\
    \ + 3) piercing damage plus 7 (2d6) force damage."
  "name": "Rapier"
- "desc": "The warlock utters a magical bewilderment, targeting one creature it can\
    \ see within 60 feet of it. The target must succeed on a DC 14 Wisdom saving throw\
    \ or take 9 (2d8) psychic damage and have disadvantage on attack rolls until\
    \ the end of the warlock's next turn."
  "name": "Bewildering Word"
"reactions":
- "desc": "In response to taking damage, the warlock turns [invisible](Mechanics/Rules/conditions.md#Invisible)\
    \ and teleports, along with any equipment it is wearing or carrying, up to 60\
    \ feet to an unoccupied space it can see. It remains [invisible](Mechanics/Rules/conditions.md#Invisible)\
    \ until the start of its next turn or until it attacks, makes a damage roll, or\
    \ casts a spell."
  "name": "Misty Escape (Recharges after a Short or Long Rest)"
"source":
- "MPMM"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/MPMM/Warlock%20of%20the%20Archfey.webp"
```
^statblock

## Environment

arctic, forest, mountain, swamp, urban