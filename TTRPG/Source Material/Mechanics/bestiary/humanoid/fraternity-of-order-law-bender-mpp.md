---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/mpp
- monster/cr/9
- monster/size/small-or-medium
- monster/type/humanoid
statblock: inline
aliases: ["Fraternity of Order Law Bender"]
---
# [Fraternity of Order Law Bender](Mechanics\bestiary\humanoid/fraternity-of-order-law-bender-mpp.md)
*Source: Morte's Planar Parade p. 57, Sigil and the Outlands*  

Members of the Fraternity of Order find and exploit loopholes in the laws of the multiverse. Law benders are magistrates who skirt the rules of probability and space, moving freely and manipulating the outcomes of actions around them.

```statblock
"name": "Fraternity of Order Law Bender (MPP)"
"size": "Small or Medium"
"type": "humanoid"
"alignment": "Any alignment"
"ac": !!int "12"
"ac_class": "15 with [mage armor](Mechanics/spells/mage-armor.md)"
"hp": !!int "137"
"hit_dice": "25d8 + 25"
"stats":
- !!int "8"
- !!int "15"
- !!int "12"
- !!int "19"
- !!int "16"
- !!int "14"
"speed": "30 ft."
"saves":
  "Wisdom": !!int "7"
  "Constitution": !!int "5"
"skillsaves":
  "Insight": !!int "7"
  "Perception": !!int "7"
"senses": "passive Perception 17"
"languages": "Common plus three more languages"
"cr": "9"
"traits":
- "desc": "The law bender casts one of the following spells, requiring no material\
    \ components and using Intelligence as the spellcasting ability:\n\nAt will:\
    \ [dispel magic](Mechanics/spells/dispel-magic.md), [fly](Mechanics/spells/fly.md),\
    \ [mage armor](Mechanics/spells/mage-armor.md), [mage hand](Mechanics/spells/mage-hand.md),\
    \ [prestidigitation](Mechanics/spells/prestidigitation.md)"
  "name": "Spellcasting"
"actions":
- "desc": "The law bender makes three Arcane Burst attacks and uses Power of Authority\
    \ or Spellcasting."
  "name": "Multiattack"
- "desc": "Melee or Ranged Spell Attack: +8 to hit, reach 5 ft. or range 90 ft.,\
    \ one target. Hit: 17 (2d12 + 4) force damage."
  "name": "Arcane Burst"
- "desc": "The law bender targets a creature it can see within 60 feet of itself.\
    \ The target must succeed on a DC 16 Intelligence saving throw or take 10 (3d6)\
    \ psychic damage and have the [incapacitated](Mechanics/Rules/conditions.md#Incapacitated)\
    \ condition for 1 minute. At the end of each of the target's turns, it can repeat\
    \ the saving throw, ending the [incapacitated](Mechanics/Rules/conditions.md#Incapacitated)\
    \ condition on itself on a success. A target that succeeds on the saving throw\
    \ becomes immune to this law bender's Power of Authority for 24 hours."
  "name": "Power of Authority"
"bonus_actions":
- "desc": "The law bender teleports, along with any equipment it is wearing or carrying,\
    \ up to 30 feet to an unoccupied space it can see."
  "name": "Spatial Loophole"
"reactions":
- "desc": "When the law bender or a creature it can see makes an attack roll, a saving\
    \ throw, or an ability check, the law bender can cause the roll to be made with\
    \ advantage or disadvantage."
  "name": "Probability Loophole (3/Day)"
"source":
- "MPP"
- "SatO"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/MPP/Fraternity%20of%20Order%20Law%20Bender.webp"
```
^statblock