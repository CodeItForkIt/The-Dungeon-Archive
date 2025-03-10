---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/ggr
- monster/cr/1-2
- monster/size/medium
- monster/type/humanoid/any-race
statblock: inline
aliases: ["Soldier"]
---
# [Soldier](Mechanics\bestiary\humanoid/soldier-ggr.md)
*Source: Guildmasters' Guide to Ravnica p. 226, Mythic Odysseys of Theros*  

Soldiers are found in many of Ravnica's guilds. The soldier stat block represents a typical member of the rank and file, though weaponry and armor can vary.

```statblock
"name": "Soldier (GGR)"
"size": "Medium"
"type": "humanoid"
"subtype": "any race"
"alignment": "Any alignment"
"ac": !!int "18"
"ac_class": "[chain mail](Mechanics/items/chain-mail.md), [shield](Mechanics/items/shield.md)"
"hp": !!int "16"
"hit_dice": "3d8 + 3"
"stats":
- !!int "13"
- !!int "12"
- !!int "12"
- !!int "10"
- !!int "11"
- !!int "11"
"speed": "30 ft."
"skillsaves":
  "Athletics": !!int "3"
  "Perception": !!int "2"
"senses": "passive Perception 12"
"languages": "any one language (usually Common)"
"cr": "1/2"
"traits":
- "desc": "The soldier has advantage on saving throws against being [charmed](Mechanics/Rules/conditions.md#Charmed),\
    \ [frightened](Mechanics/Rules/conditions.md#Frightened), [grappled](Mechanics/Rules/conditions.md#Grappled),\
    \ or [restrained](Mechanics/Rules/conditions.md#Restrained) while it is within\
    \ 5 feet of at least one ally."
  "name": "Formation Tactics"
"actions":
- "desc": "The soldier makes two melee attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +3 to hit, reach 5 ft., one target. Hit: 6 (1d8\
    \ + 2) slashing damage, or 7 (1d10 + 2) slashing damage if used with two hands."
  "name": "Longsword"
"source":
- "GGR"
- "MOT"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/GGR/Soldier.webp"
```
^statblock