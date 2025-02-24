---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/rot
- monster/cr/5
- monster/size/medium
- monster/type/humanoid/any-race
aliases: ["Half-Red Dragon Gladiator"]
---
# Half-Red Dragon Gladiator
*Source: The Rise of Tiamat p. 56, Tyranny of Dragons p. 142*  

```ad-statblock
title: Half-Red Dragon Gladiator
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/RoT/Half-Red%20Dragon%20Gladiator.webp#token)
*Medium humanoid (any race), Any alignment*

- **Armor Class** 16 ([studded leather](2-Mechanics/CLI/items/studded-leather-armor.md), [shield](2-Mechanics/CLI/items/shield.md))
- **Hit Points** 112 (`15d8 + 45`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|18 (+4)|15 (+2)|16 (+3)|10 (+0)|12 (+1)|15 (+2)|

- **Proficiency Bonus** +3
- **Saving Throws** Strength +7, Dexterity +5, Constitution +6
- **Skills** Athletics +10, Intimidation +5
- **Senses** blindsight 10 ft., darkvision 60 ft., passive Perception 11
- **Damage Resistances** fire
- **Languages** any one language (usually Common), Draconic
- **Challenge** 5

## Traits

***Brave.*** The half-dragon has advantage on saving throws against being [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened).

***Brute.*** A melee weapon deals one extra die of its damage when the half-dragon hits with it (included in the attack).

## Actions

***Multiattack.*** The half-dragon makes three melee attacks or two ranged attacks.

***Spear.*** *Melee or Ranged Weapon Attack:* `dice:1d20+7|noform|text(+7)` to hit, reach 5 ft. and range 20/60 ft., one target. *Hit:* `dice:2d6+4|noform|avg|text(11)` (`2d6 + 4`) piercing damage, or `dice:2d8+4|noform|avg|text(13)` (`2d8 + 4`) piercing damage if used with two hands to make a melee attack.

***Shield Bash.*** *Melee Weapon Attack:* `dice:1d20+7|noform|text(+7)` to hit, reach 5 ft., one creature. *Hit:* `dice:2d4+4|noform|avg|text(9)` (`2d4 + 4`) bludgeoning damage. If the target is a Medium or smaller creature, it must succeed on a DC 15 Strength saving throw or be knocked [prone](2-Mechanics/CLI/rules/conditions.md#Prone).

***Fire Breath (Recharge 5-6).*** The half-dragon exhales fire in a 15-foot cone. Each creature in that area must make a DC 13 Dexterity saving throw, taking `dice:7d6|noform|avg|text(24)` (`7d6`) fire damage on a failed save, or half as much damage on a successful one.

## Reactions

***Parry.*** The half-dragon adds 3 to its AC against one melee attack that would hit it. To do so, the half-dragon must see the attacker and be wielding a melee weapon.
```
^statblock