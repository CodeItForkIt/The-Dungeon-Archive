---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/gos
- monster/cr/2
- monster/size/large
- monster/type/undead
statblock: inline
aliases: ["Skeletal Swarm"]
---
# [Skeletal Swarm](Mechanics\bestiary\undead/skeletal-swarm-gos.md)
*Source: Ghosts of Saltmarsh p. 254, Divine Contention, Infernal Machine Rebuild*  

This swarm of bones found rising out of the sand in Isle of the Abbey is made from the remains of several animated skeletons. A skeletal swarm alternates its appearance between partially formed humanoid shapes and a chaotic, swirling mass.

```statblock
"name": "Skeletal Swarm (GoS)"
"size": "Large"
"type": "undead"
"alignment": "Lawful Evil"
"ac": !!int "13"
"ac_class": "armor scraps"
"hp": !!int "60"
"hit_dice": "8d10 + 16"
"stats":
- !!int "12"
- !!int "14"
- !!int "15"
- !!int "6"
- !!int "8"
- !!int "5"
"speed": "30 ft."
"damage_vulnerabilities": "bludgeoning"
"damage_resistances": "slashing, piercing"
"damage_immunities": "poison"
"condition_immunities": "[charmed](Mechanics/Rules/conditions.md#Charmed), [exhaustion](Mechanics/Rules/conditions.md#Exhaustion),\
  \ [frightened](Mechanics/Rules/conditions.md#Frightened), [paralyzed](Mechanics/Rules/conditions.md#Paralyzed),\
  \ [petrified](Mechanics/Rules/conditions.md#Petrified), [poisoned](Mechanics/Rules/conditions.md#Poisoned),\
  \ [prone](Mechanics/Rules/conditions.md#Prone), [restrained](Mechanics/Rules/conditions.md#Restrained),\
  \ [stunned](Mechanics/Rules/conditions.md#Stunned)"
"senses": "darkvision 60 ft., passive Perception 9"
"languages": ""
"cr": "2"
"traits":
- "desc": "Creatures are [deafened](Mechanics/Rules/conditions.md#Deafened) while\
    \ in the swarm's space."
  "name": "Deafening Clatter"
- "desc": "The swarm can occupy another creature's space and vice versa, and the swarm\
    \ can move through any opening large enough for a Small humanoid. The swarm can't\
    \ regain hit points or gain temporary hit points."
  "name": "Swarm"
"actions":
- "desc": "Melee Weapon Attack: +4 to hit, reach 0 ft., one target in the swarm's\
    \ space. Hit: 11 (2d8 + 2) slashing damage, or 6 (1d8 + 2) slashing damage\
    \ if the swarm has half of its hit points or fewer."
  "name": "Slash"
"source":
- "GoS"
- "DC"
- "IMR"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/GoS/Skeletal%20Swarm.webp"
```
^statblock