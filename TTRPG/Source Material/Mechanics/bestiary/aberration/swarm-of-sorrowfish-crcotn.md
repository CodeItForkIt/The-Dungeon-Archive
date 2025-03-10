---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/crcotn
- monster/cr/6
- monster/size/medium
- monster/type/aberration
statblock: inline
aliases: ["Swarm of Sorrowfish"]
---
# [Swarm of Sorrowfish](Mechanics\bestiary\aberration/swarm-of-sorrowfish-crcotn.md)
*Source: Critical Role: Call of the Netherdeep p. 210*  

A swarm of sorrowfish attacks out of hunger. Although sorrowfish have no sense of fear, they often adopt the tactic of lurking among the petrifying tendrils of a death embrace, using the tendrils for protection against other predators.

## Sorrowfish

Sorrowfish dwell in deep underwater trenches and thus are rarely encountered by surface-dwelling creatures. Some say sorrowfish get their name from their flavor, which is distasteful enough to put the creatures that eat them in a dismal mood. The true sorrow for other creatures comes when the sorrowfish gather in swarms. The malevolent presences that lurk in the abysses of the ocean exert their influence on these fish, transforming their swarms into vicious hordes.

```statblock
"name": "Swarm of Sorrowfish (CRCotN)"
"size": "Medium"
"type": "aberration"
"alignment": "Unaligned"
"ac": !!int "14"
"hp": !!int "104"
"hit_dice": "16d8 + 32"
"stats":
- !!int "16"
- !!int "19"
- !!int "14"
- !!int "1"
- !!int "11"
- !!int "3"
"speed": "0 ft., swim 30 ft."
"damage_resistances": "bludgeoning, piercing, slashing"
"damage_immunities": "psychic"
"condition_immunities": "[charmed](Mechanics/Rules/conditions.md#Charmed), [frightened](Mechanics/Rules/conditions.md#Frightened),\
  \ [grappled](Mechanics/Rules/conditions.md#Grappled), [paralyzed](Mechanics/Rules/conditions.md#Paralyzed),\
  \ [petrified](Mechanics/Rules/conditions.md#Petrified), [prone](Mechanics/Rules/conditions.md#Prone),\
  \ [restrained](Mechanics/Rules/conditions.md#Restrained), [stunned](Mechanics/Rules/conditions.md#Stunned)"
"senses": "blindsight 60 ft. (blind beyond this radius), passive Perception 10"
"languages": ""
"cr": "6"
"traits":
- "desc": "The swarm can occupy another creature's space and vice versa, and the swarm\
    \ can move through an opening as narrow as 1 foot wide. The swarm can't regain\
    \ hit points or gain temporary hit points."
  "name": "Swarm"
- "desc": "Each time the swarm takes damage, any creature within 5 feet of it must\
    \ make a DC 13 Wisdom saving throw. On a failed saving throw, the creature suffers\
    \ the following effects until the end of its next turn: it has disadvantage on\
    \ its attack rolls, it can't take reactions, and its speed is halved."
  "name": "Virulent Sorrow"
- "desc": "The swarm can breathe only underwater."
  "name": "Water Breathing"
"actions":
- "desc": "Melee Weapon Attack: +8 to hit, reach 0 ft., one target in the swarm's\
    \ space. Hit: 21 (6d6) piercing damage, or 10 (3d6) piercing damage if the\
    \ swarm has half its hit points or fewer."
  "name": "Swarm of Bites"
- "desc": "Each creature in the swarm's space must make a DC 13 Wisdom saving throw.\
    \ On a failed saving throw, a creature takes 24 (7d6) psychic damage and is\
    \ [stunned](Mechanics/Rules/conditions.md#Stunned) until the end of its next turn.\
    \ The effect ends on a creature if the swarm moves out of the creature's space\
    \ or if another creature within 5 feet of the swarm uses an action to make a DC\
    \ 14 Strength check, pulling the affected creature out of the swarm on a successful\
    \ check. On a successful saving throw, a creature takes half as much damage and\
    \ suffers no other effects."
  "name": "Desolate Drain (Recharge 5-6)"
"source":
- "CRCotN"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/CRCotN/Swarm%20of%20Sorrowfish.webp"
```
^statblock