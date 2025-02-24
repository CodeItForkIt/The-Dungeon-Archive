---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/psx
- monster/cr/5
- monster/size/huge
- monster/type/beast
statblock: inline
aliases: ["Sailback"]
---
# [Sailback](Mechanics\bestiary\beast/sailback-psx.md)
*Source: Plane Shift: Ixalan p. 30*  

## Scales, Spikes, and Hammers

Sailbacks are predators that lurk in lakes and rivers to ambush unwary prey. Their statistics are equivalent to those of the [giant crocodile](Mechanics/bestiary/beast/giant-crocodile.md) in the "Monster Manual".

## Dinosaurs

Dinosaurs are the dominant form of animal life in Ixalan—the absolute rulers of the coastal lands held by the Sun Empire, and a force to be reckoned with in the interior jungles. A number of dinosaurs appear in the "Monster Manual", with even more to be found in "Volo's Guide to Monsters", making that a particularly worthwhile resource for an Ixalan campaign. (Many of the dinosaurs in "Volo's Guide" also appear in Tomb of Annihilation.)

```statblock
"name": "Sailback (PSX)"
"size": "Huge"
"type": "beast"
"alignment": "Unaligned"
"ac": !!int "14"
"ac_class": "natural armor"
"hp": !!int "85"
"hit_dice": "9d12 + 27"
"stats":
- !!int "21"
- !!int "9"
- !!int "17"
- !!int "2"
- !!int "10"
- !!int "7"
"speed": "30 ft., swim 50 ft."
"skillsaves":
  "Stealth": !!int "5"
"senses": "passive Perception 10"
"languages": ""
"cr": "5"
"traits":
- "desc": "The sailback can hold its breath for 30 minutes."
  "name": "Hold Breath"
"actions":
- "desc": "The sailback makes two attacks: one with its bite and one with its tail."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +8 to hit, reach 5 ft., one target. Hit: 21\
    \ (3d10 + 5) piercing damage, and the target is [grappled](Mechanics/Rules/conditions.md#Grappled)\
    \ (escape DC 16). Until this grapple ends, the target is [restrained](Mechanics/Rules/conditions.md#Restrained),\
    \ and the sailback can't bite another target."
  "name": "Bite"
- "desc": "Melee Weapon Attack: +8 to hit, reach 10 ft., one target not [grappled](Mechanics/Rules/conditions.md#Grappled)\
    \ by the sailback. Hit: 14 (2d8 + 5) bludgeoning damage. If the target is\
    \ a creature, it must succeed on a DC 16 Strength saving throw or be knocked [prone](Mechanics/Rules/conditions.md#Prone)."
  "name": "Tail"
"source":
- "PSX"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/PSX/Sailback.webp"
```
^statblock