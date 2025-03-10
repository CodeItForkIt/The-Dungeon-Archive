---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/erlw
- monster/cr/3
- monster/size/medium
- monster/type/undead
aliases: ["Karrnathi Undead Soldier"]
---
# Karrnathi Undead Soldier
*Source: Eberron: Rising from the Last War p. 295*  

Undead soldiers form the elite core of the army of Karrnath. Fearless and tireless, they are a terrifying sight on the battlefield. With the end of the Last War, most Karrnathi undead have been sealed in vaults below the city of Atur. However, the Karrnathi army keeps numerous undead in its service, while others have been commandeered by the malevolent Order of the Emerald Claw.

## The Odakyr Rites

The nation of Karrnath has a proud martial heritage, and its soldiers are unmatched in discipline. But in the early years of the Last War, Karrnath was crippled by famine and plague. In desperation, King Kaius I embraced the Blood of Vol, whose priests bolstered the armies of Karrnath with undead.

Initially, those skeletons and zombies required constant control and served as cannon fodder. Over decades, a high priest named Malevanor worked with the necromancers of the Blood of Vol to develop the Odakyr Rites, which grant Karrnathi undead the ability to make tactical decisions and operate without direct guidance.

The Odakyr Rites work only when performed on the remains of a soldier slain in battle, and only in manifest zones tied to the plane of Mabar. The most significant such zones in Karrnath exist in the cities of Atur and Odakyr (now called Fort Bones). The number of Karrnathi undead soldiers steadily increased over the course of the war, with the losses of Karrnath's living troops offset by the recovery and raising of their remains.

Malevanor claimed that Karrnathi undead are animated and granted intelligence by the patriotic spirit of Karrnath. However, many Karrns fear that the undead are vessels for a darker power—and that Lady Illmarrow or someone else will turn the undead against the living.

## Intelligent and Inhuman

Karrnathi undead bear little resemblance to the people they were in life. These undead are content to stand motionless and silent for days. They show no emotion, and certainly no mercy or compassion. Undead soldiers kill any opposing forces—including civilians among those forces—unless given explicit instructions to the contrary.

A few exceptional Karrnathi undead retain their individuality and the memories of their former lives. Such undead are often found as champions of the Blood of Vol or agents of the Order of the Emerald Claw.

## Undead Nature

A Karrnathi undead soldier doesn't require air, food, drink, or sleep.

## Statblock

```ad-statblock
title: Karrnathi Undead Soldier
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ERLW/Karrnathi%20Undead%20Soldier.webp#token)
*Medium undead, Lawful Evil*

- **Armor Class** 17 ([half plate armor](2-Mechanics/CLI/items/half-plate-armor.md))
- **Hit Points** 52 (`7d8 + 21`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|16 (+3)|14 (+2)|16 (+3)|12 (+1)|13 (+1)| 5 (-3)|

- **Proficiency Bonus** +2
- **Saving Throws** ⏤
- **Skills** Athletics +5, Perception +3
- **Senses** darkvision 60 ft., passive Perception 13
- **Damage Resistances** cold, poison
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** Common
- **Challenge** 3

## Traits

***Pack Tactics.*** The soldier has advantage on an attack roll against a creature if at least one of the soldier's allies is within 5 feet of the creature and the ally isn't [incapacitated](2-Mechanics/CLI/rules/conditions.md#Incapacitated).

***Undead Fortitude.*** If damage reduces the soldier to 0 hit points, it must make a Constitution saving throw with a DC of 5 + the damage taken, unless the damage is radiant or from a critical hit. On a success, the soldier drops to 1 hit point instead.

## Actions

***Multiattack.*** The soldier attacks three times with one of its weapons.

***Longsword.*** *Melee Weapon Attack:* `dice:1d20+5|noform|text(+5)` to hit, reach 5 ft., one target. *Hit:* `dice:1d8+3|noform|avg|text(7)` (`1d8 + 3`) slashing damage, or `dice:1d10+3|noform|avg|text(8)` (`1d10 + 3`) slashing damage if used with two hands.

***Longbow.*** *Ranged Weapon Attack:* `dice:1d20+4|noform|text(+4)` to hit, range 150/600 ft., one target. *Hit:* `dice:1d8+2|noform|avg|text(6)` (`1d8 + 2`) piercing damage.

## Reactions

***Parry.*** The soldier adds 3 to its AC against one melee attack that would hit it. To do so, the soldier must see the attacker and be wielding a melee weapon.
```
^statblock