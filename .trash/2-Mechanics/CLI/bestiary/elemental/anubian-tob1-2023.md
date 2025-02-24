---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/tob1-2023
- monster/cr/2
- monster/environment/desert
- monster/size/medium
- monster/type/elemental
aliases: ["Anubian"]
---
# Anubian
*Source: Tome of Beasts 1 (2023 Edition) p. 23*  

*Swirling sand comes together to form a snarling, canine-faced humanoid whose eyes shine with an eerie, blue glow.*

Anubians are elementals summoned to guard tombs or protect treasures.

## Piles of Dust

An anubian at rest resembles a pile of sand or dust, often strewn about an already dusty location. When active, it rises up to form a muscular humanoid with the head of a jackal. A destroyed anubian collapses into an inert pile of sand.

## Death to the Unarmored

In combat, anubians prefer to fight unarmored foes rather than creatures wearing armor. They associate unarmored creatures with spellcasters, and their latent resentment over centuries of being summoned as servants drives them to attack such figures when they aren't shackled by magical bondage.

## Sandstorm Tag Teams

Anubians fight effectively as teams, using their haboob attacks to corner and isolate the most vulnerable targets.

## Statblock

```ad-statblock
title: Anubian
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ToB1-2023/Anubian.webp#token)
*Medium elemental, Chaotic Evil*

- **Armor Class** 13
- **Hit Points** 44 (`8d8 + 8`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|12 (+1)|16 (+3)|12 (+1)|10 (+0)|12 (+1)|10 (+0)|

- **Proficiency Bonus** +2
- **Saving Throws** ⏤
- **Skills** Stealth +5
- **Senses** darkvision 60 ft., tremorsense 30 ft., passive Perception 11
- **Damage Resistances** bludgeoning, piercing, slashing from nonmagical attacks
- **Damage Immunities** poison
- **Condition Immunities** [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled), [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed), [petrified](2-Mechanics/CLI/rules/conditions.md#Petrified), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned), [prone](2-Mechanics/CLI/rules/conditions.md#Prone), [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained), [unconscious](2-Mechanics/CLI/rules/conditions.md#Unconscious)
- **Languages** Primordial
- **Challenge** 2

## Traits

***Elemental Nature.*** The anubian doesn't require air, food, drink, or sleep.

***Sand Camouflage.*** The anubian has advantage on Dexterity ([Stealth](2-Mechanics/CLI/rules/skills.md#Stealth)) checks made to hide in sandy terrain.

***Sand Form.*** The anubian can enter a hostile creature's space and stop there. It can move through a space as narrow as 1 inch wide without squeezing.

***Vulnerability to Water.*** For every 5 feet the anubian moves in water, or for every gallon of water splashed on it, it takes `dice:1d4|noform|avg|text(2)` (`1d4`) cold damage. An anubian completely immersed in water takes `dice:4d4|noform|avg|text(10)` (`4d4`) cold damage at the start of its turn.

## Actions

***Multiattack.*** The anubian makes two Claw attacks.

***Claw.*** *Melee Weapon Attack:* `dice:1d20+5|noform|text(+5)` to hit, reach 5 ft., one target. *Hit:* `dice:1d6+3|noform|avg|text(6)` (`1d6 + 3`) slashing damage.

***Haboob (1/Day).*** A 30-foot-tall cylinder of sand forms in the anubian's space and moves with it for 10 minutes, until the anubian ends the storm as a bonus action, or until its [concentration](2-Mechanics/CLI/rules/conditions.md#Concentration) ends (as if concentrating on a spell). The area within 5 feet of the anubian is heavily obscured. A creature that starts its turn in that area or enters the area for the first time on a turn must succeed on a DC 13 Strength saving throw or be [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained) by the storm. While [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained), the creature takes `dice:1d6|noform|avg|text(3)` (`1d6`) slashing damage at the start of each of its turns, and moves with the anubian when the anubian moves. A creature, including the [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained) creature, can use its action to free the [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained) creature by succeeding on a DC 13 Strength check.

## Bonus Actions

***Sand Step.*** The anubian collapses into loose sand and teleports up to 30 feet to an unoccupied space it can see, reforming in that space. If the destination space contains sand, the anubian can immediately Hide. The anubian can't use Sand Step while Haboob is active.
```
^statblock

## Environment

desert