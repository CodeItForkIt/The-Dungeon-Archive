---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/tob1-2023
- monster/cr/3
- monster/environment/desert
- monster/size/medium
- monster/type/undead
aliases: ["Venomous Mummy"]
---
# Venomous Mummy
*Source: Tome of Beasts 1 (2023 Edition) p. 279*  

*This shambling corpse warrior is draped in stained linen wrappings. Green liquid drips from rents in the fabric.*

## Servant of the Scorpion Goddess

These mummies are crafted by the faithful of a goddess of poison and scorpions to guard holy sites and tombs and to serve as agents of the goddess's retribution. Should the goddess's faithful feel themselves slighted by an individual or a community, they perform dangerous rituals to awaken these creatures from the crypts of her temples. Venomous mummies delight in wreaking deadly vengeance against those who disrespect the goddess.

## Death to Blasphemers

In most cases, retribution is limited to people who actually undertook acts of blasphemy. However, if the priests determine that an entire community has grown heretical, they may set mummies loose against the entire populace.

## Deadly Smoke

Though fire destroys many undead, burning a venomous mummy releases a toxic smoke.

## Statblock

```ad-statblock
title: Venomous Mummy
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ToB1-2023/Venomous%20Mummy.webp#token)
*Medium undead, Lawful Evil*

- **Armor Class** 11 (natural armor)
- **Hit Points** 58 (`9d8 + 18`)
- **Speed** 20 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|16 (+3)| 8 (-1)|15 (+2)| 7 (-2)|10 (+0)|14 (+2)|

- **Proficiency Bonus** +2
- **Saving Throws** Wisdom +2
- **Skills** ⏤
- **Senses** darkvision 60 ft., passive Perception 10
- **Damage Vulnerabilities** fire
- **Damage Resistances** bludgeoning, piercing, slashing from nonmagical attacks
- **Damage Immunities** necrotic, poison
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened), [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** the languages it knew in life
- **Challenge** 3

## Traits

***Toxic Smoke.*** If the venomous mummy takes fire damage, each creature within 10 feet of it must make a DC 12 Constitution saving throw as its venom-soaked wraps emit a poisonous smoke. On a failure, a creature takes `dice:2d6|noform|avg|text(7)` (`2d6`) poison damage and is [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned) until the end of its next turn. On a success, a creature takes half the damage and isn't [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned). The smoke fills a 10-foot-radius sphere centered on the mummy. The sphere spreads around corners, and its area is lightly obscured. It lasts until the end of the mummy's next turn. A creature that enters the cloud for the first time on a turn or starts its turn there is [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned) until the end of its next turn.

***Venom-Soaked Wraps.*** A creature that touches the mummy or hits it with a melee attack while within 5 feet of it takes `dice:1d6|noform|avg|text(3)` (`1d6`) poison damage.

***Undead Nature.*** The venomous mummy doesn't require air, food, drink, or sleep.

## Actions

***Venomous Fist.*** *Melee Weapon Attack:* `dice:1d20+5|noform|text(+5)` to hit, reach 5 ft., one target. *Hit:* `dice:2d6+3|noform|avg|text(10)` (`2d6 + 3`) bludgeoning damage plus `dice:3d6|noform|avg|text(10)` (`3d6`) poison damage. If the target is a creature, it must succeed on a DC 12 Constitution saving throw or be cursed. Every 24 hours that elapse, the cursed target must succeed on a DC 12 Constitution saving throw or take `dice:2d6|noform|avg|text(7)` (`2d6`) poison damage, and its hp maximum is reduced by that amount. This reduction lasts until the target finishes a long rest after the curse is removed. The target dies if this effect reduces its hp maximum to 0. The curse lasts until removed by the [remove curse](2-Mechanics/CLI/spells/remove-curse.md) spell or similar magic.
```
^statblock

## Environment

desert