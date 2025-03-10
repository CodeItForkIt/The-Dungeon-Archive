---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/sdw
- monster/cr/5
- monster/size/huge
- monster/type/undead
statblock: inline
aliases: ["Giant Shark Skeleton"]
---
# [Giant Shark Skeleton](Mechanics\bestiary\undead/giant-shark-skeleton-sdw.md)
*Source: Sleeping Dragon's Wake*  

A giant shark is 30 feet long and normally found in deep oceans. Utterly fearless, it preys on anything that crosses its path, including whales and ships.

The giant shark skeleton doesn't require air, food, drink, or sleep. The shark has had skeletal feet attached by some demented necromancer.

```statblock
"name": "Giant Shark Skeleton (SDW)"
"size": "Huge"
"type": "undead"
"alignment": "Unaligned"
"ac": !!int "13"
"ac_class": "natural armor"
"hp": !!int "126"
"hit_dice": "11d12 + 55"
"stats":
- !!int "23"
- !!int "11"
- !!int "21"
- !!int "1"
- !!int "10"
- !!int "5"
"speed": "20 ft., swim 50 ft."
"skillsaves":
  "Perception": !!int "3"
"damage_vulnerabilities": "bludgeoning"
"damage_immunities": "poison"
"condition_immunities": "[exhaustion](Mechanics/Rules/conditions.md#Exhaustion), [poisoned](Mechanics/Rules/conditions.md#Poisoned)"
"senses": "blindsight 60 ft., passive Perception 13"
"languages": ""
"cr": "5"
"traits":
- "desc": "The giant shark skeleton has advantage on melee attack rolls against any\
    \ creature that doesn't have all its hit points."
  "name": "Blood Frenzy"
"actions":
- "desc": "Melee Weapon Attack: +9 to hit, reach 5 ft., one target. Hit: 22\
    \ (3d10 + 6) piercing damage."
  "name": "Bite"
"source":
- "SDW"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/SDW/Giant%20Shark%20Skeleton.webp"
```
^statblock