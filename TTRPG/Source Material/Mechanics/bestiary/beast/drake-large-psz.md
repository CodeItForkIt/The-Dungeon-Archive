---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/psz
- monster/cr/1
- monster/size/large
- monster/type/beast
statblock: inline
aliases: ["Drake (Large)"]
---
# [Drake (Large)](Mechanics\bestiary\beast/drake-large-psz.md)
*Source: Plane Shift: Zendikar p. 24*  

Drakes are superficially similar to dragons, with reptilian bodies and large, leathery wings. They have only two legs, though. They are strongly associated with blue mana, the air, and the sea, rather than the dragons' mountains and fire. Many drakes are found in Akoum, but they typically live at higher altitudes and farther north than the dragons there.

A [pteranodon](Mechanics/bestiary/beast/pteranodon.md) can represent a smaller drake, while a larger one is more like a [giant eagle](Mechanics/bestiary/beast/giant-eagle.md).

```statblock
"name": "Drake (Large) (PSZ)"
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
- "PSZ"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/PSZ/Drake%20%28Large%29.webp"
```
^statblock