---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/psk
- monster/cr/1
- monster/size/large
- monster/type/beast
statblock: inline
aliases: ["Drake (Large)"]
---
# [Drake (Large)](Mechanics\bestiary\beast/drake-large-psk.md)
*Source: Plane Shift: Kaladesh p. 29*  

Drakes are skittish, opportunistic predators that hunt the skies of Kaladesh in units called rushes, made up of as many as a dozen drakes. Though they prey mostly on birds, they can also be seen clinging to the hides of leviathans and whales, picking off winged leeches and other parasites and scavengers that attach themselves to the huge sky beasts. Occasionally, a rush of drakes will descend on a herd of mountain goats or other game found at high elevations.

Drakes have reptilian bodies and large, leathery wings. They use the sharp claws on their two legs to cling to rocky crags, whales, or leviathans, as well as to grasp and tear at larger prey. Drakes are highly territori al, and have been known to attack airships from time to time. A drake is intelligent enough to recognize specific airships that have killed other members of its rush, and drake harassment often forces such ships to find new routes to avoid a rush's territory.

A [pteranodon](Mechanics/bestiary/beast/pteranodon.md) can represent a smaller drake, while a larger one is more like a [giant eagle](Mechanics/bestiary/beast/giant-eagle.md).

```statblock
"name": "Drake (Large) (PSK)"
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
"languages": ""
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
- "PSK"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/PSK/Drake%20%28Large%29.webp"
```
^statblock