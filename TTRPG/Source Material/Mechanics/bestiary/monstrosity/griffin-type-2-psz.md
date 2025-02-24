---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/psz
- monster/cr/1
- monster/size/large
- monster/type/monstrosity
statblock: inline
aliases: ["Griffin (Type 2)"]
---
# [Griffin (Type 2)](Mechanics\bestiary\monstrosity/griffin-type-2-psz.md)
*Source: Plane Shift: Zendikar p. 22*  

Less intelligent and less magical than [felidars](Mechanics/bestiary/celestial/felidar-psz.md), griffins share those great cats' noble nature and alignment with the principles of white mana. Larger griffin species are about the size of horses and can be ridden. Indeed, such griffins are often the only reliable means of reaching certain remote locations, particularly in Akoum. Smaller griffins range from the size of donkeys to large dogs, and are trained to carry messages or supplies without a rider.

Zendikar's griffins are much like D&D's [griffons](Mechanics/bestiary/monstrosity/griffon.md) (aside from the spelling) and [hippogriffs](Mechanics/bestiary/monstrosity/hippogriff.md).

```statblock
"name": "Griffin (Type 2) (PSZ)"
"size": "Large"
"type": "monstrosity"
"alignment": "Unaligned"
"ac": !!int "11"
"hp": !!int "19"
"hit_dice": "3d10 + 3"
"stats":
- !!int "17"
- !!int "13"
- !!int "13"
- !!int "2"
- !!int "12"
- !!int "8"
"speed": "40 ft., fly 60 ft."
"skillsaves":
  "Perception": !!int "5"
"senses": "passive Perception 15"
"languages": ""
"cr": "1"
"traits":
- "desc": "The griffin has advantage on Wisdom ([Perception](Mechanics/Rules/skills.md#Perception))\
    \ checks that rely on sight."
  "name": "Keen Sight"
"actions":
- "desc": "The griffin makes two attacks: one with its beak and one with its claws."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 8 (1d10\
    \ + 3) piercing damage."
  "name": "Beak"
- "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 10\
    \ (2d6 + 3) slashing damage."
  "name": "Claws"
"source":
- "PSZ"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/PSZ/Griffin%20%28Type%202%29.webp"
```
^statblock