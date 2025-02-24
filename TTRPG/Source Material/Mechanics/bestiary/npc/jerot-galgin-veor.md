---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/veor
- monster/cr/9
- monster/size/medium
- monster/type/humanoid
statblock: inline
aliases: ["Jerot Galgin"]
---
# [Jerot Galgin](Mechanics\bestiary\npc/jerot-galgin-veor.md)
*Source: Vecna: Eve of Ruin*  

```statblock
"name": "Jerot Galgin (VEoR)"
"size": "Medium"
"type": "humanoid"
"alignment": "Neutral Evil"
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
- "desc": "Jerot casts one of the following spells, using Intelligence as the spellcasting\
    \ ability (spell save DC 15):\n\nAt will: [dancing lights](Mechanics/spells/dancing-lights.md),\
    \ [mage hand](Mechanics/spells/mage-hand.md), [prestidigitation](Mechanics/spells/prestidigitation.md)\n\
    \n1/day each: [circle of death](Mechanics/spells/circle-of-death.md)\n\n2/day\
    \ each: [bestow curse](Mechanics/spells/bestow-curse.md), [dimension door](Mechanics/spells/dimension-door.md),\
    \ [mage armor](Mechanics/spells/mage-armor.md), [web](Mechanics/spells/web.md)"
  "name": "Spellcasting"
"actions":
- "desc": "Jerot makes three Arcane Burst attacks."
  "name": "Multiattack"
- "desc": "Melee or Ranged Spell Attack: +7 to hit, reach 5 ft. or range 120 ft.,\
    \ one target. Hit: 25 (4d10 + 3) necrotic damage."
  "name": "Arcane Burst"
"bonus_actions":
- "desc": "Jerot magically summons five [skeletons](Mechanics/bestiary/undead/skeleton.md)\
    \ or [zombies](Mechanics/bestiary/undead/zombie.md). The summoned creatures appear\
    \ in unoccupied spaces within 60 feet of Jerot, whom they obey. They take their\
    \ turns immediately after Jerot. Each lasts for 1 hour, until it or Jerot dies,\
    \ or until Jerot dismisses it as a bonus action."
  "name": "Summon Undead (1/Day)"
"reactions":
- "desc": "When Jerot kills a creature with necrotic damage, Jerot regains 9 (2d8)\
    \ hit points. "
  "name": "Grim Harvest (1/Turn)"
"source":
- "VEoR"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/VEoR/Jerot%20Galgin.webp"
```
^statblock