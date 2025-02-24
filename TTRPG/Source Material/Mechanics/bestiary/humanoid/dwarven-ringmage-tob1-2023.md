---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/tob1-2023
- monster/cr/7
- monster/environment/arctic
- monster/environment/urban
- monster/size/medium
- monster/type/humanoid/dwarf
statblock: inline
aliases: ["Dwarven Ringmage"]
---
# [Dwarven Ringmage](Mechanics\bestiary\humanoid/dwarven-ringmage-tob1-2023.md)
*Source: Tome of Beasts 1 (2023 Edition) p. 409*  

Curves are seldom seen in the stacked blocks and precise geometric forms of dwarven architecture. Devoid of angles and planes with no beginning and no end, circles are a mystery and hold power. Dwarven ringmages are those dwarves who have mastered the art of tapping into that power, imbuing it into metal rings and their spellcasting. Rings and circles are sacred to them, and they read omens in the cycle of seasons, the shape of flowers, and in a storm's first rain drops.

```statblock
"name": "Dwarven Ringmage (ToB1-2023)"
"size": "Medium"
"type": "humanoid"
"subtype": "dwarf"
"alignment": "Any alignment"
"ac": !!int "16"
"ac_class": "[breastplate](Mechanics/items/breastplate.md)"
"hp": !!int "136"
"hit_dice": "21d8 + 42"
"stats":
- !!int "10"
- !!int "14"
- !!int "15"
- !!int "18"
- !!int "12"
- !!int "9"
"speed": "30 ft."
"saves":
  "Wisdom": !!int "4"
  "Intelligence": !!int "7"
  "Constitution": !!int "5"
"skillsaves":
  "History": !!int "7"
  "Arcana": !!int "7"
"damage_resistances": "poison"
"senses": "darkvision 60 ft., passive Perception 11"
"languages": "Common, Dwarvish"
"cr": "7"
"traits":
- "desc": "The dwarven ringmage casts one of the following spells, requiring no material\
    \ components and using Intelligence as the spellcasting ability (spell save DC\
    \ 15):\n\nAt will: [color spray](Mechanics/spells/color-spray.md), [mage hand](Mechanics/spells/mage-hand.md),\
    \ [true strike](Mechanics/spells/true-strike.md)\n\n1/day each: [greater invisibility](Mechanics/spells/greater-invisibility.md),\
    \ [wall of stone](Mechanics/spells/wall-of-stone.md)\n\n3/day each: [expeditious\
    \ retreat](Mechanics/spells/expeditious-retreat.md), [fly](Mechanics/spells/fly.md),\
    \ [haste](Mechanics/spells/haste.md)"
  "name": "Spellcasting"
- "desc": "The dwarven ringmage has advantage on saving throws against poison."
  "name": "Dwarven Resilience"
"actions":
- "desc": "The dwarven ringmage can use its Ring Magic. It then makes three Ring Staff\
    \ attacks. It can replace one attack with a use of Spellcasting."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 5 (1d6\
    \ + 2) bludgeoning damage plus 10 (3d6) acid, cold, fire, lightning, or thunder\
    \ damage (the ringmage's choice)."
  "name": "Ring Staff"
- "desc": "The dwarven ringmage draws circles of magic in the air and sends them toward\
    \ one creature it can see within 30 feet of it, causing one of the following effects:\n\
    \n- Rings of Binding. The target must succeed on a DC 15 Strength saving throw\
    \ or be [restrained](Mechanics/Rules/conditions.md#Restrained) by magical rings\
    \ until the end of its next turn.  \n- Rings of Bravery. The target can't\
    \ be [frightened](Mechanics/Rules/conditions.md#Frightened) and has advantage\
    \ on melee weapon attack rolls until the end of its next turn.  \n- Rings of\
    \ Protection. The target has a +2 bonus to its Armor Class until the end of\
    \ its next turn.  \n- Rings of Retribution. When any creature hits the target\
    \ before the start of the ringmage's next turn, the creature takes 4 (1d8) acid,\
    \ cold, fire, lightning, or thunder damage (the ringmage's choice).  "
  "name": "Ring Magic"
"source":
- "ToB1-2023"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ToB1-2023/Dwarven%20Ringmage.webp"
```
^statblock

## Environment

arctic, urban