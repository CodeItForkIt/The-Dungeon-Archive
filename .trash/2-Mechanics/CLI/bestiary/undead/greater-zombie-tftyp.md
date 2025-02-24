---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/tftyp
- monster/cr/5
- monster/size/medium
- monster/type/undead
aliases: ["Greater Zombie"]
---
# Greater Zombie
*Source: Tales from the Yawning Portal p. 237, Divine Contention, Sleeping Dragon's Wake, Infernal Machine Rebuild*  

Many of those who brave the Tomb of Horrors believe they have reached their ultimate destination when they disturb a skeletal figure inside a secluded crypt. It is, in fact, a greater zombie, a creature magically created from a humanoid corpse to be far more resilient than a typical zombie.

## Undead Nature

A zombie doesn't require air, food, drink, or sleep.

## Statblock

```ad-statblock
title: Greater Zombie
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/TftYP/Greater%20Zombie.webp#token)
*Medium undead, Neutral Evil*

- **Armor Class** 15 (natural armor)
- **Hit Points** 97 (`13d8 + 39`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|18 (+4)|10 (+0)|17 (+3)| 4 (-3)| 6 (-2)| 6 (-2)|

- **Proficiency Bonus** +3
- **Saving Throws** Wisdom +1
- **Skills** ⏤
- **Senses** darkvision 60 ft., passive Perception 8
- **Damage Resistances** cold, necrotic
- **Damage Immunities** poison
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened), [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** understands the languages it knew in life but can't speak
- **Challenge** 5

## Traits

***Turn Resistance.*** The zombie has advantage on saving throws against any effect that turns undead.

***Undead Fortitude.*** If damage reduces the zombie to 0 hit points, it must make a Constitution saving throw with a DC of 5 + the damage taken, unless the damage is radiant or from a critical hit. On a success, the zombie drops to 1 hit point instead.

## Actions

***Multiattack.*** The zombie makes two melee attacks.

***Empowered Slam.*** *Melee Weapon Attack:* `dice:1d20+7|noform|text(+7)` to hit, reach 5 ft., one target. *Hit:* `dice:1d6+4|noform|avg|text(7)` (`1d6 + 4`) bludgeoning damage and `dice:2d6|noform|avg|text(7)` (`2d6`) necrotic damage.
```
^statblock