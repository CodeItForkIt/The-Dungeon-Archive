---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/mpmm
- monster/cr/9
- monster/environment/desert
- monster/environment/urban
- monster/size/medium
- monster/type/humanoid
statblock: inline
aliases: ["Necromancer Wizard"]
---
# [Necromancer Wizard](Mechanics\bestiary\humanoid/necromancer-wizard-mpmm.md)
*Source: Mordenkainen Presents: Monsters of the Multiverse p. 264, Vecna: Eve of Ruin*  

Necromancers study the interaction of life, death, and undeath. Some necromancers dig up or purchase corpses to create Undead servitors. A few instead use their powers for good, hunting Undead.

## Wizards

Wizards pursue magical power through the study of arcane texts. Some travel the world searching for esoteric tomes while others train lesser wizards or collaborate with colleagues to create new spells.

```statblock
"name": "Necromancer Wizard (MPMM)"
"size": "Medium"
"type": "humanoid"
"alignment": "Any alignment"
"ac": !!int "12"
"ac_class": "15 with [mage armor](Mechanics/spells/mage-armor.md)"
"hp": !!int "110"
"hit_dice": "20d8 + 20"
"stats":
- !!int "9"
- !!int "14"
- !!int "12"
- !!int "17"
- !!int "12"
- !!int "11"
"speed": "30 ft."
"saves":
  "Wisdom": !!int "5"
  "Intelligence": !!int "7"
"skillsaves":
  "History": !!int "7"
  "Arcana": !!int "7"
"damage_resistances": "necrotic"
"senses": "passive Perception 11"
"languages": "any four languages"
"cr": "9"
"traits":
- "desc": "The necromancer casts one of the following spells, using Intelligence as\
    \ the spellcasting ability (spell save DC 15):\n\nAt will: [dancing lights](Mechanics/spells/dancing-lights.md),\
    \ [mage hand](Mechanics/spells/mage-hand.md), [prestidigitation](Mechanics/spells/prestidigitation.md)\n\
    \n1/day each: [circle of death](Mechanics/spells/circle-of-death.md)\n\n2/day\
    \ each: [bestow curse](Mechanics/spells/bestow-curse.md), [dimension door](Mechanics/spells/dimension-door.md),\
    \ [mage armor](Mechanics/spells/mage-armor.md), [web](Mechanics/spells/web.md)"
  "name": "Spellcasting"
"actions":
- "desc": "The necromancer makes three Arcane Burst attacks."
  "name": "Multiattack"
- "desc": "Melee or Ranged Spell Attack: +7 to hit, reach 5 ft. or range 120 ft.,\
    \ one target. Hit: 25 (4d10 + 3) necrotic damage."
  "name": "Arcane Burst"
"bonus_actions":
- "desc": "The necromancer magically summons five [skeletons](Mechanics/bestiary/undead/skeleton.md)\
    \ or [zombies](Mechanics/bestiary/undead/zombie.md). The summoned creatures appear\
    \ in unoccupied spaces within 60 feet of the necromancer, whom they obey. They\
    \ take their turns immediately after the necromancer. Each lasts for 1 hour, until\
    \ it or the necromancer dies, or until the necromancer dismisses it as a bonus\
    \ action."
  "name": "Summon Undead (1/Day)"
"reactions":
- "desc": "When the necromancer kills a creature with necrotic damage, the necromancer\
    \ regains 9 (2d8) hit points. "
  "name": "Grim Harvest (1/Turn)"
"source":
- "MPMM"
- "VEoR"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/MPMM/Necromancer%20Wizard.webp"
```
^statblock

## Environment

desert, urban