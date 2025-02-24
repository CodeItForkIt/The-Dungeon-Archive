---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/tob1-2023
- monster/cr/7
- monster/environment/farmland
- monster/environment/urban
- monster/size/medium
- monster/type/undead
aliases: ["Ghost Knight"]
---
# Ghost Knight
*Source: Tome of Beasts 1 (2023 Edition) p. 199*  

*The skeleton's armor creaks as its decaying mount shifts and emits a ghostly whinny. The skeleton sets its lance, skulls dangling from the hilt, and charges.*

## Servants Beyond Death

Some orders of knighthood require service after death; ghost knights are one such group. Both the willing and the conscripts enter the order as living men and women, and those who serve bravely and loyally for five years or more are "raised up" into the ranks of the undead by their undead lords, becoming fully-fledged ghost knights.

## Undead Mounts

To advance through the ranks of the order, the ghost knight accepts the blessing of undeath, which extends to its mount. Riding an undead warhorse (use the statistics of a warhorse skeleton), the ghost knight is a dangerous foe, spearing enemies with its lance and trampling foes under its mount's hooves.

## Statblock

```ad-statblock
title: Ghost Knight
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ToB1-2023/Ghost%20Knight.webp#token)
*Medium undead, Lawful Evil*

- **Armor Class** 17 ([half plate](2-Mechanics/CLI/items/half-plate-armor.md))
- **Hit Points** 130 (`20d8 + 40`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|17 (+3)|15 (+2)|14 (+2)| 8 (-1)|10 (+0)| 7 (-2)|

- **Proficiency Bonus** +3
- **Saving Throws** ⏤
- **Skills** Animal Handling +3, Athletics +6, Perception +3, Stealth +5
- **Senses** darkvision 60 ft., passive Perception 13
- **Damage Resistances** necrotic
- **Damage Immunities** poison
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** Common
- **Challenge** 7

## Traits

***Locked Saddle.*** The ghost knight can't be knocked [prone](2-Mechanics/CLI/rules/conditions.md#Prone), dismounted, or moved against its will while mounted.

***Mounted Warrior.*** The ghost knight is rarely seen without its warhorse skeleton mount. The warhorse skeleton wears custom barding that raises its Armor Class to 15, and it has immunity to necrotic damage. While the ghost knight is mounted, its mount can't be [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed) or [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened).

***Necrotic Weapons.*** The ghost knight's weapon attacks are magical. When the knight hits with any weapon, the weapon deals an extra `dice:2d6|noform|avg` (`2d6`) necrotic damage (included in the attack).

***Spirited Charge.*** If the ghost knight moves at least 20 feet straight toward a creature while mounted and then hits with a Lance attack on the same turn, the ghost knight can use a bonus action to command its mount to make one melee weapon attack against that creature as a reaction.

***Turning Defiance.*** The ghost knight and any undead within 30 feet of it have advantage on saving throws against effects that turn undead.

***Undead Nature.*** The ghost knight doesn't require air, food, drink, or sleep.

## Actions

***Multiattack.*** The ghost knight makes three Battleaxe or Lance attacks. If the ghost knight is mounted, it can make two Battleaxe or Lance attacks, and its mount can make one melee weapon attack.

***Battleaxe.*** *Melee Weapon Attack:* `dice:1d20+6|noform|text(+6)` to hit, reach 5 ft., one target. *Hit:* `dice:1d8+3|noform|avg|text(7)` (`1d8 + 3`) slashing damage, or `dice:1d10+3|noform|avg|text(8)` (`1d10 + 3`) slashing damage if used with two hands, plus `dice:2d6|noform|avg|text(7)` (`2d6`) necrotic damage.

***Lance.*** *Melee Weapon Attack:* `dice:1d20+6|noform|text(+6)` to hit, reach 10 ft., one target. *Hit:* `dice:1d12+3|noform|avg|text(9)` (`1d12 + 3`) piercing damage plus `dice:2d6|noform|avg|text(7)` (`2d6`) necrotic damage.
```
^statblock

## Environment

farmland, urban