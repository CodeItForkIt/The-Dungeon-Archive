---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/psa
- monster/cr/1
- monster/size/large
- monster/type/beast
statblock: inline
aliases: ["Large Drake"]
---
# [Large Drake](Mechanics\bestiary\beast/large-drake-psa.md)
*Source: Plane Shift: Amonkhet p. 33*  

Drakes are similar to dragons, though they lack any ability to breathe fire and have only two legs in addi-tion to their huge wings. They are less aggressive than dragons, and possibly slightly more intelligent. They are drawn by the glint of lazotep in mines, the shine of gold in Naktamun, and the glimmer of the sun on the water of the Luxa river. They also like to perch on obelisks and other spires on city buildings.

A [pteranodon](Mechanics/bestiary/beast/pteranodon.md) can represent a smaller drake, while a larger one is more like a [giant eagle](Mechanics/bestiary/beast/giant-eagle.md).

```statblock
"name": "Large Drake (PSA)"
"size": "Large"
"type": "beast"
"alignment": "Neutral Good"
"ac": !!int "13"
"hp": !!int "26"
"hit_dice": "4d10 + 4"
"stats":
- !!int "16"
- !!int "17"
- !!int "13"
- !!int "8"
- !!int "14"
- !!int "10"
"speed": "10 ft., fly 80 ft."
"skillsaves":
  "Perception": !!int "4"
"senses": "passive Perception 14"
"languages": "Giant Eagle, understands Common and Auran but can't speak them"
"cr": "1"
"traits":
- "desc": "The drake has advantage on Wisdom ([Perception](Mechanics/Rules/skills.md#Perception))\
    \ checks that rely on sight."
  "name": "Keen Sight"
"actions":
- "desc": "The drake makes two attacks: one with its beak and one with its talons."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 6 (1d6\
    \ + 3) piercing damage."
  "name": "Beak"
- "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 10\
    \ (2d6 + 3) slashing damage."
  "name": "Talons"
"source":
- "PSA"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/PSA/Large%20Drake.webp"
```
^statblock