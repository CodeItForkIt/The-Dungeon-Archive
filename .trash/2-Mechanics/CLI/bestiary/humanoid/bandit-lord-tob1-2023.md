---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/tob1-2023
- monster/cr/4
- monster/environment/desert
- monster/environment/farmland
- monster/environment/forest
- monster/environment/grassland
- monster/environment/urban
- monster/size/medium
- monster/type/humanoid/any-race
aliases: ["Bandit Lord"]
---
# Bandit Lord
*Source: Tome of Beasts 1 (2023 Edition) p. 406*  

Not just the leader of a simple gang, the bandit lord has gathered a small army of outlaws and brigands together through force of personality, wit, and strength of arms. To keep those followers in line, the bandit leader must rely on loyal captains whom the bandit lord rewards for their successes and brutally punishes for their failures.

## Ambitious Leaders

Unlike those captains, who crave coin and maybe fame, the bandit lord is building an empire. The bandit lord is always on the lookout for ways to expand at the expense of various rivals and plans contingencies for every occasion, realizing that nothing lasts forever. The bandit lord is ruthless when that's beneficial and magnanimous when it costs nothing.

## Statblock

```ad-statblock
title: Bandit Lord
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ToB1-2023/Bandit%20Lord.webp#token)
*Medium humanoid (any race), Any Non-Lawful alignment*

- **Armor Class** 16 ([breastplate](2-Mechanics/CLI/items/breastplate.md))
- **Hit Points** 91 (`14d8 + 28`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|16 (+3)|15 (+2)|14 (+2)|14 (+2)|11 (+0)|14 (+2)|

- **Proficiency Bonus** +2
- **Saving Throws** Strength +5, Dexterity +4, Wisdom +2
- **Skills** Athletics +5, Deception +4, Intimidation +4
- **Senses** passive Perception 10
- **Languages** any two languages
- **Challenge** 4

## Traits

***Brute.*** A melee weapon deals one extra die of its damage when the bandit lord hits with it (included in the attack).

***Pack Tactics.*** The bandit lord has advantage on attack rolls against a creature if at least one of the bandit lord's allies is within 5 feet of the creature and the ally isn't [incapacitated](2-Mechanics/CLI/rules/conditions.md#Incapacitated).

## Actions

***Multiattack.*** The bandit lord makes two Longsword attacks and one Dagger attack.

***Longsword.*** *Melee Weapon Attack:* `dice:1d20+5|noform|text(+5)` to hit, reach 5 ft., one target. *Hit:* `dice:2d8+3|noform|avg|text(12)` (`2d8 + 3`) slashing damage, or `dice:2d10+3|noform|avg|text(14)` (`2d10 + 3`) slashing damage if used with two hands.

***Dagger.*** *Melee or Ranged Weapon Attack:* `dice:1d20+5|noform|text(+5)` to hit, reach 5 ft. or range 20/60 ft., one target. *Hit:* `dice:1d4+3|noform|avg|text(5)` (`1d4 + 3`) piercing damage, or `dice:2d4+3|noform|avg|text(8)` (`2d4 + 3`) piercing damage if used to make a melee attack.

***Leadership (Recharges after a Short or Long Rest).*** For 1 minute, the bandit lord can utter a special command or warning whenever a nonhostile creature that it can see within 30 feet of it makes an attack roll or a saving throw. The creature can add a `dice:d4|noform|avg` (`d4`) to its roll provided it can hear and understand the bandit lord. A creature can benefit from only one Leadership die at a time. This effect ends if the bandit lord is [incapacitated](2-Mechanics/CLI/rules/conditions.md#Incapacitated).

## Reactions

***Parry.*** The bandit lord adds 2 to its AC against one melee attack that would hit it. To do so, the bandit lord must see the attacker and be wielding a weapon.

***Protect Me!.*** When a creature the bandit lord can see targets it with an attack, the bandit lord can sidestep behind an ally within 5 feet of it, moving to an unoccupied space within 5 feet of the ally. The chosen ally becomes the target of the attack instead.
```
^statblock

## Environment

desert, farmland, forest, grassland, urban