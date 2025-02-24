---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/psz
- monster/cr/1-4
- monster/size/medium
- monster/type/beast
statblock: inline
aliases: ["Drake (Small)"]
---
# [Drake (Small)](Mechanics\bestiary\beast/drake-small-psz.md)
*Source: Plane Shift: Zendikar p. 24*  

Drakes are superficially similar to dragons, with reptilian bodies and large, leathery wings. They have only two legs, though. They are strongly associated with blue mana, the air, and the sea, rather than the dragons' mountains and fire. Many drakes are found in Akoum, but they typically live at higher altitudes and farther north than the dragons there.

A [pteranodon](Mechanics/bestiary/beast/pteranodon.md) can represent a smaller drake, while a larger one is more like a [giant eagle](Mechanics/bestiary/beast/giant-eagle.md).

```statblock
"name": "Drake (Small) (PSZ)"
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
- "PSZ"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/PSZ/Drake%20%28Small%29.webp"
```
^statblock