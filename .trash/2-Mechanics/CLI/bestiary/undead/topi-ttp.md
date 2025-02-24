---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/ttp
- monster/cr/1-2
- monster/size/small
- monster/type/undead
aliases: ["Topi"]
---
# Topi
*Source: The Tortle Package p. 22*  

Topis are similar to zombies. Before a topi is animated, its corpse is shrunk until it stands only 2 feet tall, and its heart is cut out and replaced with a leather bag that contains a live poisonous snake. The snake requires neither air nor sustenance, and it magically renders the topi's claws venomous. When a topi dies, the snake inside it dies too. The process of creating a topi is known only to a handful of evil priests and necromancers.

Topis are more difficult to turn than ordinary zombies, and their spongy bodies make them resistant to bludgeoning.

## Undead Traits

A topi doesn't require air, food, drink, or sleep.

## Statblock

```ad-statblock
title: Topi
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/TTP/Topi.webp#token)
*Small undead, Chaotic Evil*

- **Armor Class** 13 (natural armor)
- **Hit Points** 13 (`3d6 + 3`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
| 7 (-2)|15 (+2)|12 (+1)| 6 (-2)|10 (+0)| 5 (-3)|

- **Proficiency Bonus** +2
- **Saving Throws** ⏤
- **Skills** ⏤
- **Senses** darkvision 60 ft., passive Perception 10
- **Damage Resistances** bludgeoning
- **Damage Immunities** poison
- **Condition Immunities** [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** understands the languages it knew in life but can't speak
- **Challenge** 1/2

## Traits

***Turn Resistance.*** The topi has advantage on saving throws against any effect that turns undead.

***Undead Fortitude.*** If damage reduces the topi to 0 hit points, it must make a Constitution saving throw with a DC of 5+the damage taken, unless the damage is radiant or from a critical hit. On a success, the topi drops to 1 hit point instead.

## Actions

***Venomous Claws.*** *Melee Weapon Attack:* `dice:1d20+4|noform|text(+4)` to hit, reach 5 ft., one target. *Hit:* `dice:1d4+2|noform|avg|text(4)` (`1d4 + 2`) slashing damage plus `dice:1d4|noform|avg|text(2)` (`1d4`) poison damage, and the target must succeed on a DC 11 Constitution saving throw or be [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned) until the end of the target's next turn.
```
^statblock