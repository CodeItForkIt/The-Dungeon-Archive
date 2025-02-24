---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/mpmm
- monster/cr/5
- monster/environment/urban
- monster/size/medium
- monster/type/humanoid
statblock: inline
aliases: ["Transmuter Wizard"]
---
# [Transmuter Wizard](Mechanics\bestiary\humanoid/transmuter-wizard-mpmm.md)
*Source: Mordenkainen Presents: Monsters of the Multiverse p. 265*  

Transmuters are masters at transforming physical forms. They typically view magical transmutation as a path to riches, enlightenment, or apotheosis.

## Wizards

Wizards pursue magical power through the study of arcane texts. Some travel the world searching for esoteric tomes while others train lesser wizards or collaborate with colleagues to create new spells.

```statblock
"name": "Transmuter Wizard (MPMM)"
"size": "Medium"
"type": "humanoid"
"alignment": "Any alignment"
"ac": !!int "12"
"ac_class": "15 with [mage armor](Mechanics/spells/mage-armor.md)"
"hp": !!int "49"
"hit_dice": "11d8"
"stats":
- !!int "9"
- !!int "14"
- !!int "11"
- !!int "17"
- !!int "12"
- !!int "11"
"speed": "30 ft."
"saves":
  "Wisdom": !!int "4"
  "Intelligence": !!int "6"
"skillsaves":
  "History": !!int "6"
  "Arcana": !!int "6"
"senses": "passive Perception 11"
"languages": "any four languages"
"cr": "5"
"traits":
- "desc": "The transmuter casts one of the following spells, using Intelligence as\
    \ the spellcasting ability (spell save DC 14):\n\nAt will: [light](Mechanics/spells/light.md),\
    \ [message](Mechanics/spells/message.md), [prestidigitation](Mechanics/spells/prestidigitation.md)\n\
    \n1/day each: [telekinesis](Mechanics/spells/telekinesis.md)\n\n2/day each:\
    \ [fireball](Mechanics/spells/fireball.md), [hold person](Mechanics/spells/hold-person.md),\
    \ [knock](Mechanics/spells/knock.md), [mage armor](Mechanics/spells/mage-armor.md),\
    \ [polymorph](Mechanics/spells/polymorph.md), [slow](Mechanics/spells/slow.md)"
  "name": "Spellcasting"
- "desc": "The transmuter carries a magic stone it crafted. The stone grants it one\
    \ of the following benefits while bearing the stone; the transmuter chooses the\
    \ benefit at the end of each long rest:\n\n- Darkvision. The transmuter has\
    \ [darkvision](Mechanics/Rules/senses.md#Darkvision) out to a range of 60 feet.\
    \  \n- Resilience. The transmuter has proficiency in Constitution saving throws.\
    \   \n- Resistance. Resistance. The transmuter has resistance to acid, cold,\
    \ fire, lightning, or thunder damage (transmuter's choice whenever choosing this\
    \ benefit).  \n- Speed. The transmuter's walking speed is increased by 10\
    \ feet.  "
  "name": "Transmuter's Stone"
"actions":
- "desc": "The transmuter makes three Arcane Burst attacks."
  "name": "Multiattack"
- "desc": "Melee or Ranged Spell Attack: +6 to hit, reach 5 ft. or range 120 ft.,\
    \ one target. Hit: 19 (3d10 + 3) acid damage."
  "name": "Arcane Burst"
"bonus_actions":
- "desc": "The transmuter casts [alter self](Mechanics/spells/alter-self.md) or changes\
    \ the benefit of Transmuter's Stone if bearing the stone."
  "name": "Transmute (Recharge 4-6)"
"source":
- "MPMM"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/MPMM/Transmuter%20Wizard.webp"
```
^statblock

## Environment

urban