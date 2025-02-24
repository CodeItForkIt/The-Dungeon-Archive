---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/psx
- monster/cr/2
- monster/size/huge
- monster/type/beast
statblock: inline
aliases: ["Aerosaur (Large)"]
---
# [Aerosaur (Large)](Mechanics\bestiary\beast/aerosaur-large-psx.md)
*Source: Plane Shift: Ixalan p. 29*  

Aerosaurs include several varieties of large reptiles with leathery wings, including pterodons and sunwings. Though they are generally clumsy fliers, better at gliding from high perches or riding coastal updrafts than at lifting themselves from the ground, aerosaurs are sometimes used as mounts by knights of the Sun Empire. Smaller aerosaurs can be represented by the [pteranodon](Mechanics/bestiary/beast/pteranodon.md) in the "Monster Manual", while larger ones are more like the [quetzalcoatlus](Mechanics/bestiary/beast/quetzalcoatlus-mpmm.md) in "Volo's Guide to Monsters".

```statblock
"name": "Aerosaur (Large) (PSX)"
"size": "Huge"
"type": "beast"
"alignment": "Unaligned"
"ac": !!int "13"
"ac_class": "natural armor"
"hp": !!int "30"
"hit_dice": "4d12 + 4"
"stats":
- !!int "15"
- !!int "13"
- !!int "13"
- !!int "2"
- !!int "10"
- !!int "5"
"speed": "10 ft., fly 80 ft."
"skillsaves":
  "Perception": !!int "2"
"senses": "passive Perception 12"
"languages": ""
"cr": "2"
"traits":
- "desc": "If the aerosaur is flying and dives at least 30 feet toward a target and\
    \ then hits with a bite attack, the attack deals an extra 10 (3d6) damage to\
    \ the target."
  "name": "Dive Attack"
- "desc": "The aerosaur doesn't provoke an opportunity attack when it flies out of\
    \ an enemy's reach."
  "name": "Flyby"
"actions":
- "desc": "Melee Weapon Attack: +4 to hit, reach 10 ft., one creature. Hit:\
    \ 12 (3d6 + 2) piercing damage."
  "name": "Bite"
"source":
- "PSX"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/PSX/Aerosaur%20%28Large%29.webp"
```
^statblock