---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/psx
- monster/cr/1-4
- monster/size/medium
- monster/type/beast
statblock: inline
aliases: ["Aerosaur (Small)"]
---
# [Aerosaur (Small)](Mechanics\bestiary\beast/aerosaur-small-psx.md)
*Source: Plane Shift: Ixalan p. 29*  

Aerosaurs include several varieties of large reptiles with leathery wings, including pterodons and sunwings. Though they are generally clumsy fliers, better at gliding from high perches or riding coastal updrafts than at lifting themselves from the ground, aerosaurs are sometimes used as mounts by knights of the Sun Empire. Smaller aerosaurs can be represented by the [pteranodon](Mechanics/bestiary/beast/pteranodon.md) in the "Monster Manual", while larger ones are more like the [quetzalcoatlus](Mechanics/bestiary/beast/quetzalcoatlus-mpmm.md) in "Volo's Guide to Monsters".

```statblock
"name": "Aerosaur (Small) (PSX)"
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
- "desc": "The aerosaur doesn't provoke opportunity attacks when it flies out of an\
    \ enemy's reach."
  "name": "Flyby"
"actions":
- "desc": "Melee Weapon Attack: +3 to hit, reach 5 ft., one target. Hit: 6 (2d4\
    \ + 1) piercing damage"
  "name": "Bite"
"source":
- "PSX"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/PSX/Aerosaur%20%28Small%29.webp"
```
^statblock