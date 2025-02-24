---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/mpp
- monster/cr/5
- monster/size/small-or-medium
- monster/type/humanoid
statblock: inline
aliases: ["Fated Shaker"]
---
# [Fated Shaker](Mechanics\bestiary\humanoid/fated-shaker-mpp.md)
*Source: Morte's Planar Parade p. 56, Sigil and the Outlands*  

Fated shakers are bullies who shake down those indebted to the faction's tax collectors and evictors. These enforcers use their magic to intimidate and subjugate those who try to stand up to them.

```statblock
"name": "Fated Shaker (MPP)"
"size": "Small or Medium"
"type": "humanoid"
"alignment": "Any alignment"
"ac": !!int "13"
"ac_class": "16 with [mage armor](Mechanics/spells/mage-armor.md)"
"hp": !!int "76"
"hit_dice": "17d8"
"stats":
- !!int "10"
- !!int "16"
- !!int "10"
- !!int "15"
- !!int "16"
- !!int "15"
"speed": "30 ft."
"saves":
  "Wisdom": !!int "6"
  "Intelligence": !!int "5"
"skillsaves":
  "Investigation": !!int "5"
  "Insight": !!int "6"
  "Perception": !!int "6"
"senses": "passive Perception 16"
"languages": "Common plus two more languages"
"cr": "5"
"traits":
- "desc": "The shaker casts one of the following spells, requiring no material components\
    \ and using Wisdom as the spellcasting ability (spell save DC 14):\n\nAt will:\
    \ [mage armor](Mechanics/spells/mage-armor.md), [mage hand](Mechanics/spells/mage-hand.md)\n\
    \n1/day each: [enlarge/reduce](Mechanics/spells/enlarge-reduce.md), [fly](Mechanics/spells/fly.md),\
    \ [suggestion](Mechanics/spells/suggestion.md)"
  "name": "Spellcasting"
"actions":
- "desc": "The shaker makes two Golden Rod or Radiant Bolt attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +6 to hit, reach 5 ft., one target. Hit: 6 (1d6\
    \ + 3) bludgeoning damage plus 9 (2d8) radiant damage."
  "name": "Golden Rod"
- "desc": "Ranged Spell Attack: +6 to hit, range 120 ft., one target. Hit: 14\
    \ (2d10 + 3) radiant damage."
  "name": "Radiant Bolt"
"bonus_actions":
- "desc": "The shaker speaks magical words to order a creature it can see within 30\
    \ feet of itself. The target must succeed on a DC 14 Wisdom saving throw or be\
    \ affected by one of the following effects (choose one or roll a d4):\n\n- 1-2\
    \ Grovel. The target takes 14 (4d6) psychic damage, drops whatever it is holding,\
    \ and has the [prone](Mechanics/Rules/conditions.md#Prone) condition.  \n- 3-4\
    \ Cower. The target takes 10 (3d6) psychic damage and has the [frightened](Mechanics/Rules/conditions.md#Frightened)\
    \ condition until the end of its next turn.  "
  "name": "Commanding Words"
"source":
- "MPP"
- "SatO"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/MPP/Fated%20Shaker.webp"
```
^statblock