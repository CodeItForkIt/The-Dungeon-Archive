---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/vrgr
- monster/cr/1
- monster/size/medium
- monster/type/undead
statblock: inline
aliases: ["Swarm of Zombie Limbs"]
---
# [Swarm of Zombie Limbs](Mechanics\bestiary\undead/swarm-of-zombie-limbs-vrgr.md)
*Source: Van Richten's Guide to Ravenloft p. 254*  

Among the undead, a lone zombie ranks far from the most menacing. The horror of the shambling dead lies not in their individual menace, though, but their numbers, their persistence, and their disregard for their own well-being. A throng of zombies will douse a forest fire with their own ashes or march into a dragon's maw until the monster chokes. In the course of their relentless marches, zombies might suffer all manner of trauma, potentially reducing them to masses of crawling limbs, infecting them with terrible diseases (see zombie plague spreader), or crushing an entire horde into a single, rotting titan (see zombie clot).

## Zombie Apocalypses

Among the types of horror adventures detailed in "chapter 2", tales of uncontrolled zombie outbreaks orbit the "dark fantasy" and "disaster horror" genres. The horror of these adventures focuses not on the terror of a single zombie, but of countless individual threats overwhelming society. When creating your own undead calamities, consider the plots presented on the Zombie Apocalypses table.

**Zombie Apocalypses**

`dice: [](swarm-of-zombie-limbs-vrgr.md#^zombie-apocalypses)`

| dice: d4 | Zombie Plot |
|----------|-------------|
| 1 | A twisted wish causes those affected by healing magic and [potions of healing](Mechanics/items/potion-of-healing.md) to rise as zombies. |
| 2 | Overwhelming magic reanimates zombies again and again as [swarms of zombie limbs](Mechanics/bestiary/undead/swarm-of-zombie-limbs-vrgr.md). |
| 3 | The githyanki unleash [zombie plague spreaders](Mechanics/bestiary/undead/zombie-plague-spreader-vrgr.md) to scour mind flayers from a world. |
| 4 | The seals containing an underground zombie horde fail, releasing ancient [zombie clots](Mechanics/bestiary/undead/zombie-clot-vrgr.md). |
^zombie-apocalypses

```statblock
"name": "Swarm of Zombie Limbs (VRGR)"
"size": "Medium"
"type": "undead"
"alignment": "Unaligned"
"ac": !!int "10"
"hp": !!int "22"
"hit_dice": "5d8"
"stats":
- !!int "14"
- !!int "10"
- !!int "10"
- !!int "3"
- !!int "8"
- !!int "5"
"speed": "30 ft., climb 30 ft."
"damage_resistances": "bludgeoning, piercing, slashing"
"damage_immunities": "poison"
"condition_immunities": "[charmed](Mechanics/Rules/conditions.md#Charmed), [exhaustion](Mechanics/Rules/conditions.md#Exhaustion),\
  \ [frightened](Mechanics/Rules/conditions.md#Frightened), [grappled](Mechanics/Rules/conditions.md#Grappled),\
  \ [paralyzed](Mechanics/Rules/conditions.md#Paralyzed), [petrified](Mechanics/Rules/conditions.md#Petrified),\
  \ [poisoned](Mechanics/Rules/conditions.md#Poisoned), [prone](Mechanics/Rules/conditions.md#Prone),\
  \ [restrained](Mechanics/Rules/conditions.md#Restrained), [stunned](Mechanics/Rules/conditions.md#Stunned)"
"senses": "blindsight 30 ft. (blind beyond this radius), passive Perception 9"
"languages": ""
"cr": "1"
"traits":
- "desc": "The swarm can occupy another creature's space and vice versa, and the swarm\
    \ can move through any opening large enough for a Tiny limb. The swarm can't regain\
    \ hit points or gain temporary hit points."
  "name": "Swarm"
- "desc": "The swarm doesn't require air, food, drink, or sleep."
  "name": "Unusual Nature"
"actions":
- "desc": "The swarm makes one Undead Mass attack and one Grasping Limbs attack."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +4 to hit, reach 0 ft., one target in the swarm's\
    \ space. Hit: 5 (1d6 + 2) bludgeoning damage, or 4 (1d4 + 2) bludgeoning\
    \ damage if the swarm has half of its hit points or fewer."
  "name": "Undead Mass"
- "desc": "Melee Weapon Attack: +4 to hit, reach 0 ft., one creature in the swarm's\
    \ space. Hit: 7 (2d6) necrotic damage, and the creature must succeed on a\
    \ DC 12 Strength saving throw or be [restrained](Mechanics/Rules/conditions.md#Restrained).\
    \ The creature can repeat the saving throw at the end of each of its turns, taking\
    \ 7 (2d6) necrotic damage on a failed save. The creature is freed if it succeeds\
    \ on this saving throw, the swarm moves out of the creature's space, or the swarm\
    \ dies."
  "name": "Grasping Limbs"
"source":
- "VRGR"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/VRGR/Swarm%20of%20Zombie%20Limbs.webp"
```
^statblock