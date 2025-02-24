---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/tob1-2023
- monster/cr/6
- monster/environment/any
- monster/environment/urban
- monster/size/medium
- monster/type/undead
aliases: ["Spectral Guardian"]
---
# Spectral Guardian
*Source: Tome of Beasts 1 (2023 Edition) p. 338*  

*A luminous green mist swirls into the form of an ancient warrior. Dented armor and a ragged cloak enshroud the warrior's skeletal body, and its grinning skull leers out from an open helm.*

## Worn Finery

Composed of faintly glowing green vapor, the spectral guardian is a skeletal being encased in ancient armor or noble's finery. The cloth is worn and tattered, spiraling away into mist at the edges, and the creature glides with the faintest whisper of sound.

## Eternal Disgrace

The spectral guardian is the spirit of an ancient warrior or noble, bound to serve in death as it failed to do in life. A broken oath, an act of cowardice, or a curse laid down by the gods for a terrible betrayal leaves an indelible mark on a soul. After the cursed creature's death, its spirit rises in a place closely related to its disgrace. Compelled by the crushing weight of its deeds, the spectral guardian knows no rest or peace.

## Statblock

```ad-statblock
title: Spectral Guardian
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ToB1-2023/Spectral%20Guardian.webp#token)
*Medium undead, Neutral Evil*

- **Armor Class** 14
- **Hit Points** 93 (`11d8 + 44`)
- **Speed** 0 ft., fly 60 ft. (hover)

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
| 6 (-2)|18 (+4)|18 (+4)|11 (+0)|16 (+3)|18 (+4)|

- **Proficiency Bonus** +3
- **Saving Throws** Dexterity +7, Wisdom +6
- **Skills** ⏤
- **Senses** blindsight 10 ft., darkvision 60 ft., passive Perception 13
- **Damage Resistances** acid; fire; lightning; thunder; bludgeoning, piercing, slashing from nonmagical attacks
- **Damage Immunities** cold, necrotic, poison
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened), [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled), [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed), [petrified](2-Mechanics/CLI/rules/conditions.md#Petrified), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned), [prone](2-Mechanics/CLI/rules/conditions.md#Prone), [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained)
- **Languages** understands the languages it knew in life but can't speak
- **Challenge** 6

## Traits

***Disgrace Bound.*** The spectral guardian is bound to a tomb, castle ruins, or other place related to the disgrace in life that caused it to rise as a spectral guardian in death. If the guardian starts its turn more than 1 mile from its bound location, it loses its Spectral Blade action until it returns to the region. If it remains outside the region, it automatically teleports back to its bound location after 24 hours, regardless of distance.

***Incorporeal Movement.*** The spectral guardian can move through other creatures and objects as if they were difficult terrain. It takes `dice:1d10|noform|avg|text(5)` (`1d10`) force damage if it ends its turn inside an object.

***Undead Nature.*** The spectral guardian doesn't require air, food, drink, or sleep.

## Actions

***Multiattack.*** The spectral guardian makes two Spectral Blade attacks. If both attacks hit one creature, the target must succeed on a DC 15 Constitution saving throw or have its hp maximum reduced by the total necrotic damage dealt by both attacks.

***Spectral Blade.*** *Melee Weapon Attack:* `dice:1d20+7|noform|text(+7)` to hit, reach 5 ft., one target. *Hit:* `dice:2d8+4|noform|avg|text(13)` (`2d8 + 4`) slashing damage plus `dice:2d8|noform|avg|text(9)` (`2d8`) necrotic damage, and the target must succeed on a DC 14 Wisdom saving throw or be [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened) until the end of its next turn.
```
^statblock

## Environment

any, urban