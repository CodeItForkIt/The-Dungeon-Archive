---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/tftyp
- monster/cr/9
- monster/size/large
- monster/type/construct
aliases: ["Reduced-Threat Clay Golem"]
---
# Reduced-Threat Clay Golem
*Source: Tales from the Yawning Portal p. 113*  

```ad-statblock
title: Reduced-Threat Clay Golem
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/TftYP/Reduced-Threat%20Clay%20Golem.webp#token)
*Large construct, Unaligned*

- **Armor Class** 14 (natural armor)
- **Hit Points** 66 (`14d10 + 56`)
- **Speed** 20 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|20 (+5)| 9 (-1)|18 (+4)| 3 (-4)| 8 (-1)| 1 (-5)|

- **Proficiency Bonus** +4
- **Saving Throws** ⏤
- **Skills** ⏤
- **Senses** darkvision 60 ft., passive Perception 9
- **Damage Immunities** acid; poison; psychic; bludgeoning, piercing, slashing from nonmagical attacks that aren't adamantine
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened), [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed), [petrified](2-Mechanics/CLI/rules/conditions.md#Petrified), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** understands the languages of its creator but can't speak
- **Challenge** 9

## Traits

***Reduced Threat.*** A reduced-threat monster takes a −2 penalty on attack rolls (included in the stat block), ability checks (included in the stat block for skill proficiencies), saving throws (included in the stat block for saving throw proficiencies), and saving throw DCs (included in the stat block).

***Acid Absorption.*** Whenever the golem is subjected to acid damage, it takes no damage and instead regains a number of hit points equal to the acid damage dealt.

***Berserk.*** Whenever the golem starts its turn with 60 hit points or fewer, roll a `dice:d6|noform|avg` (`d6`). On a 6, the golem goes berserk. On each of its turns while berserk, the golem attacks the nearest creature it can see. If no creature is near enough to move to and attack, the golem attacks an object, with preference for an object smaller than itself. Once the golem goes berserk, it continues to do so until it is destroyed or regains all its hit points.

***Immutable Form.*** The golem is immune to any spell or effect that would alter its form.

***Magic Resistance.*** The golem has advantage on saving throws against spells and other magical effects.

***Magic Weapons.*** The golem's weapon attacks are magical.

## Actions

***Multiattack.*** The golem makes two slam attacks.

***Slam.*** *Melee Weapon Attack:* `dice:1d20+6|noform|text(+6)` to hit, reach 5 ft., one target. *Hit:* `dice:2d10+5|noform|avg|text(16)` (`2d10 + 5`) bludgeoning damage. If the target is a creature, it must succeed on a DC 13 Constitution saving throw or have its hit point maximum reduced by an amount equal to the damage taken. The target dies if this attack reduces its hit point maximum to 0. The reduction lasts until removed by the  [greater restoration](2-Mechanics/CLI/spells/greater-restoration.md) spell or other magic.

***Haste (Recharge 5-6).*** Until the end of its next turn, the golem magically gains a +2 bonus to its AC, has advantage on Dexterity saving throws, and can use its slam attack as a bonus action.
```
^statblock