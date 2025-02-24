---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/gos
- monster/cr/6
- monster/size/large
- monster/type/construct
statblock: inline
aliases: ["Minotaur Living Crystal Statue"]
---
# [Minotaur Living Crystal Statue](Mechanics\bestiary\construct/minotaur-living-crystal-statue-gos.md)
*Source: Ghosts of Saltmarsh p. 245*  

Given life through powerful magic, a large, crudely carved crystal minotaur guards the tunnels in Isle of the Abbey.

```statblock
"name": "Minotaur Living Crystal Statue (GoS)"
"size": "Large"
"type": "construct"
"alignment": "Unaligned"
"ac": !!int "15"
"ac_class": "natural armor"
"hp": !!int "136"
"hit_dice": "16d10 + 48"
"stats":
- !!int "18"
- !!int "9"
- !!int "16"
- !!int "6"
- !!int "10"
- !!int "5"
"speed": "30 ft."
"damage_vulnerabilities": "force"
"damage_immunities": "lightning, poison"
"condition_immunities": "[charmed](Mechanics/Rules/conditions.md#Charmed), [exhaustion](Mechanics/Rules/conditions.md#Exhaustion),\
  \ [frightened](Mechanics/Rules/conditions.md#Frightened), [paralyzed](Mechanics/Rules/conditions.md#Paralyzed),\
  \ [petrified](Mechanics/Rules/conditions.md#Petrified), [poisoned](Mechanics/Rules/conditions.md#Poisoned)"
"senses": "darkvision 60 ft., passive Perception 10"
"languages": "understands the languages of its creator but can't speak"
"cr": "6"
"traits":
- "desc": "The statue is immune to any spell or effect that would alter its form."
  "name": "Immutable Form"
"actions":
- "desc": "The statue makes two attacks: one with its greataxe and one gore attack."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +7 to hit, reach 5 ft., one target. Hit: 17\
    \ (2d12 + 4) slashing damage."
  "name": "Greataxe"
- "desc": "Melee Weapon Attack: +7 to hit, reach 5 ft., one target. Hit: 8 (1d8\
    \ + 4) piercing damage."
  "name": "Gore"
"reactions":
- "desc": "In response to a creature hitting the statue with a melee weapon attack,\
    \ the statue deals 11 (2d10) piercing damage to the attacker."
  "name": "Flying Shards"
"source":
- "GoS"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/GoS/Minotaur%20Living%20Crystal%20Statue.webp"
```
^statblock