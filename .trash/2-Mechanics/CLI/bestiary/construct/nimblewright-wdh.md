---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/wdh
- monster/cr/4
- monster/size/medium
- monster/type/construct
aliases: ["Nimblewright"]
---
# Nimblewright
*Source: Waterdeep: Dragon Heist p. 212*  

A nimblewright is a magical construct created to serve as a guard or assassin. Composed predominantly of lightweight wood and powered by magic, it can pass for humanoid while wearing clothing. Some nimblewrights wear plain clothing, while others are clad in flashier attire. A nimblewright is emotionless, its face frozen in whatever expression was given to it by its creator.

## Duelist

A nimblewright moves like a dancer and fights like a swashbuckler, using dodges and parries to avoid damage while deftly skewering its foes.

## Constructed Nature

A nimblewright doesn't require air, food, drink, or sleep. Damage it takes can be repaired with [mending](2-Mechanics/CLI/spells/mending.md) spells, but a nimblewright reduced to 0 hit points is permanently destroyed.

## Statblock

```ad-statblock
title: Nimblewright
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/WDH/Nimblewright.webp#token)
*Medium construct, Unaligned*

- **Armor Class** 18 (natural armor)
- **Hit Points** 45 (`6d8 + 18`)
- **Speed** 60 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|12 (+1)|18 (+4)|17 (+3)| 8 (-1)|10 (+0)| 6 (-2)|

- **Proficiency Bonus** +2
- **Saving Throws** Dexterity +6
- **Skills** Acrobatics +8, Perception +2
- **Senses** darkvision 60 ft., passive Perception 12
- **Damage Resistances** bludgeoning, piercing, slashing from nonmagical attacks
- **Condition Immunities** [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened), [petrified](2-Mechanics/CLI/rules/conditions.md#Petrified), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** understands one language known to its creator but can't speak
- **Challenge** 4

## Traits

***Magic Resistance.*** The nimblewright has advantage on saving throws against spells and other magical effects.

***Magic Weapons.*** The nimblewright's weapon attacks are magical.

***Repairable.*** As long as it has at least 1 hit point remaining, the nimblewright regains 1 hit point when a [mending](2-Mechanics/CLI/spells/mending.md) spell is cast on it.

***Sure-Footed.*** The nimblewright has advantage on Strength and Dexterity saving throws made against effects that would knock it [prone](2-Mechanics/CLI/rules/conditions.md#Prone).

## Actions

***Multiattack.*** The nimblewright makes three attacks: two with its rapier and one with its dagger.

***Rapier.*** *Melee Weapon Attack:* `dice:1d20+6|noform|text(+6)` to hit, reach 5 ft., one target. *Hit:* `dice:1d8+4|noform|avg|text(8)` (`1d8 + 4`) piercing damage.

***Dagger.*** *Melee Weapon Attack:* `dice:1d20+6|noform|text(+6)` to hit, reach 5 ft., one target. *Hit:* `dice:1d4+4|noform|avg|text(6)` (`1d4 + 4`) piercing damage. Or Ranged Weapon Attack: `dice:1d20+6|noform|text(+6)` to hit, range 20/60 ft., one target. *Hit:* `dice:1d4+4|noform|avg|text(6)` (`1d4 + 4`) piercing damage.

## Reactions

***Parry.*** The nimblewright adds 2 to its AC against one melee attack that would hit it. To do so, the nimblewright must see the attacker and be wielding a melee weapon.
```
^statblock