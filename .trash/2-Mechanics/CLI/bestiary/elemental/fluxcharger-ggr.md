---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/ggr
- monster/cr/7
- monster/size/large
- monster/type/elemental
aliases: ["Fluxcharger"]
---
# Fluxcharger
*Source: Guildmasters' Guide to Ravnica p. 208*  

In an effort to create a weird that could be more easily controlled, Izzet mages tried binding elemental lightning, fire, and smoke into a framework made of the magical alloy mizzium. The experiment was partly successful: the resulting weird, a fluxcharger, doesn't explode like some other weirds do, but it is more intelligent and more headstrong than other weirds.

A fluxcharger's mizzium frame is suggestive of an angel. A faceplate is meant to give it some personality, but most people find its solemn expression and unblinking stare more unnerving than relatable.

## Izzet Weirds

Weirds are the products of Izzet League experiments intended to combine two opposing elemental types in the hope of creating elementals that were more stable than the norm and easier to control. As commonly happens with Izzet experiments, the outcome was the exact opposite. Weirds are even wilder and more unpredictable than elementals of either of their component elements. Nevertheless, they can make potent guardian creatures and can be urged into fighting on behalf of their creators.

### Elemental Nature

An Izzet weird doesn't require air, food, drink, or sleep.

## Statblock

```ad-statblock
title: Fluxcharger
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/GGR/Fluxcharger.webp#token)
*Large elemental, Chaotic Neutral*

- **Armor Class** 16 (natural armor)
- **Hit Points** 60 (`8d10 + 16`)
- **Speed** 0 ft., fly 60 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|15 (+2)|18 (+4)|15 (+2)| 6 (-2)|10 (+0)| 7 (-2)|

- **Proficiency Bonus** +3
- **Saving Throws** ⏤
- **Skills** ⏤
- **Senses** darkvision 60 ft., passive Perception 10
- **Damage Resistances** thunder; bludgeoning, piercing, slashing from nonmagical attacks
- **Damage Immunities** lightning, poison
- **Condition Immunities** [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled), [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed), [petrified](2-Mechanics/CLI/rules/conditions.md#Petrified), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned), [prone](2-Mechanics/CLI/rules/conditions.md#Prone), [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained), [unconscious](2-Mechanics/CLI/rules/conditions.md#Unconscious)
- **Languages** Draconic
- **Challenge** 7

## Traits

***Amplify Lightning.*** Whenever a spell that deals lightning damage includes one or more fluxchargers in its area, the spell deals an extra `dice:2d8|noform|avg|text(9)` (`2d8`) lightning damage.

## Actions

***Multiattack.*** The fluxcharger makes two slam attacks or uses Arc Lightning twice.

***Slam.*** *Melee Weapon Attack:* `dice:1d20+7|noform|text(+7)` to hit, reach 10 ft., one target. *Hit:* `dice:2d8+4|noform|avg|text(13)` (`2d8 + 4`) bludgeoning damage plus `dice:3d6|noform|avg|text(10)` (`3d6`) fire damage.

***Arc Lightning.*** *Ranged Spell Attack:* `dice:1d20+7|noform|text(+7)` to hit, range 30 ft., one target. *Hit:* `dice:3d10|noform|avg|text(16)` (`3d10`) lightning damage, and lightning jumps from the target to one creature of the fluxcharger's choice that it can see within 30 feet of the target. That second creature must succeed on a DC 15 Dexterity saving throw or take `dice:3d8|noform|avg|text(13)` (`3d8`) lightning damage. Hit or Miss: The fluxcharger takes `dice:1d10|noform|avg|text(5)` (`1d10`) force damage after resolving the attack.
```
^statblock