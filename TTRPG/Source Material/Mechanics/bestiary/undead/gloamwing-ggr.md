---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/ggr
- monster/cr/8
- monster/size/large
- monster/type/undead
statblock: inline
aliases: ["Gloamwing"]
---
# [Gloamwing](Mechanics\bestiary\undead/gloamwing-ggr.md)
*Source: Guildmasters' Guide to Ravnica p. 215*  

A gloamwing's head is almost ratlike, with prominent teeth, and its leathery skin is stretched tight over its skull, where its eyes are empty sockets. Its body is mottled with bony plates, and great wings stretch from its shoulders.

```statblock
"name": "Gloamwing (GGR)"
"size": "Large"
"type": "undead"
"alignment": "Neutral Evil"
"ac": !!int "16"
"ac_class": "natural armor"
"hp": !!int "136"
"hit_dice": "16d10 + 48"
"stats":
- !!int "20"
- !!int "16"
- !!int "17"
- !!int "2"
- !!int "11"
- !!int "6"
"speed": "30 ft., fly 60 ft."
"saves":
  "Dexterity": !!int "6"
  "Strength": !!int "8"
"skillsaves":
  "Stealth": !!int "6"
  "Perception": !!int "3"
"damage_resistances": "necrotic; bludgeoning, piercing, slashing from nonmagical attacks"
"damage_immunities": "poison"
"condition_immunities": "[charmed](Mechanics/Rules/conditions.md#Charmed), [exhaustion](Mechanics/Rules/conditions.md#Exhaustion),\
  \ [frightened](Mechanics/Rules/conditions.md#Frightened), [poisoned](Mechanics/Rules/conditions.md#Poisoned)"
"senses": "darkvision 120 ft., passive Perception 13"
"languages": "understands Common"
"cr": "8"
"traits":
- "desc": "If its specter rider is reduced to 0 hit points, the gloamwing is destroyed."
  "name": "Death Link"
- "desc": "The gloamwing doesn't provoke an opportunity attack when it flies out of\
    \ an enemy's reach."
  "name": "Flyby"
- "desc": "While in sunlight, the gloamwing has disadvantage on attack rolls, as well\
    \ as on Wisdom ([Perception](Mechanics/Rules/skills.md#Perception)) checks that\
    \ rely on sight."
  "name": "Sunlight Sensitivity"
"actions":
- "desc": "The gloamwing makes two attacks: one with its bite and one with its claws."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +8 to hit, reach 5 ft., one target. Hit: 18\
    \ (3d8 + 5) piercing damage."
  "name": "Bite"
- "desc": "Melee Weapon Attack: +8 to hit, reach 5 ft., one target. Hit: 15\
    \ (3d6 + 5) slashing damage."
  "name": "Claws"
"source":
- "GGR"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/GGR/Gloamwing.webp"
```
^statblock