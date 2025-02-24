---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/psa
- monster/cr/1-4
- monster/size/medium
- monster/type/beast
statblock: inline
aliases: ["Small Drake"]
---
# [Small Drake](Mechanics\bestiary\beast/small-drake-psa.md)
*Source: Plane Shift: Amonkhet p. 33*  

Drakes are similar to dragons, though they lack any ability to breathe fire and have only two legs in addi-tion to their huge wings. They are less aggressive than dragons, and possibly slightly more intelligent. They are drawn by the glint of lazotep in mines, the shine of gold in Naktamun, and the glimmer of the sun on the water of the Luxa river. They also like to perch on obelisks and other spires on city buildings.

A [pteranodon](Mechanics/bestiary/beast/pteranodon.md) can represent a smaller drake, while a larger one is more like a [giant eagle](Mechanics/bestiary/beast/giant-eagle.md).

```statblock
"name": "Small Drake (PSA)"
"size": "Medium"
"type": "beast"
"alignment": "Unaligned"
"ac": !!int "13"
"ac_class": "natural armor"
"hp": !!int "13"
"hit_dice": "3d8"
"stats":
- !!int "12"
- !!int "15"
- !!int "10"
- !!int "2"
- !!int "9"
- !!int "5"
"speed": "10 ft., fly 60 ft."
"skillsaves":
  "Perception": !!int "1"
"senses": "passive Perception 11"
"languages": ""
"cr": "1/4"
"traits":
- "desc": "The drake doesn't provoke opportunity attacks when it flies out of an enemy's\
    \ reach."
  "name": "Flyby"
"actions":
- "desc": "Melee Weapon Attack: +3 to hit, reach 5 ft., one target. Hit: 6 (2d4\
    \ + 1) piercing damage"
  "name": "Bite"
"source":
- "PSA"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/PSA/Small%20Drake.webp"
```
^statblock