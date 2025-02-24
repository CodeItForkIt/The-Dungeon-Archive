---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/ghloe
- monster/cr/2
- monster/size/medium
- monster/type/aberration
aliases: ["Spythronar Swarm"]
---
# Spythronar Swarm
*Source: Grim Hollow: Lairs of Etharis p. 32*  

> [!quote]  
> 
> Armored corpses in the cavern, resting among thick strands of webbing, have sparks of lightning playing off them.

## Salvage

Spythronar silk is prized, although it's worthless if acid or fire touched the web. One web can be used to make silk rope or fine clothing. A proficient alchemist can use the same amount of silk to produce a [potion of lightning resistance](2-Mechanics/CLI/items/potion-of-lightning-resistance.md) or a dose of an oil that allows a metal weapon to deal `dice:1d6|noform|avg` (`1d6`) extra lightning damage for 1 hour. Producing either concoction takes 4 hours of work and a successful DC 13 Intelligence check.

A proficient weaver can turn three spythronar webs into a rope of entanglement or 10 webs into leather armor of lightning resistance. Doing either requires other materials worth 500 gp, 5 days of work, and a successful DC 15 Intelligence ([Arcana](2-Mechanics/CLI/rules/skills.md#Arcana)) check.

## Lore

- **DC 10 Intelligence ([Nature](2-Mechanics/CLI/rules/skills.md#Nature)).** Spythronar swarms can weave dangerous webbing, making egg sacs quickly. It takes them some time to weave a sentient web.  
- **DC 15 Intelligence ([Arcana](2-Mechanics/CLI/rules/skills.md#Arcana)).** The sentient spythronar webs adhere to you if you touch them, and they charge their silken strands with lightning. Crushing spythronar egg sacs sets off a lightning discharge, but hitting them with lightning releases a new spythronar swarm.  

## Statblock

```ad-statblock
title: Spythronar Swarm
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/GHLoE/Spythronar%20Swarm.webp#token)
*Medium aberration, Neutral Evil*

- **Armor Class** 13
- **Hit Points** 45 (`10d8`)
- **Speed** 30 ft., climb 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
| 5 (-3)|17 (+3)|10 (+0)| 3 (-4)|11 (+0)| 3 (-4)|

- **Proficiency Bonus** +2
- **Saving Throws** ⏤
- **Skills** Stealth +5
- **Senses** darkvision 60 ft., tremorsense 30 ft., passive Perception 10
- **Damage Resistances** bludgeoning, piercing, slashing
- **Damage Immunities** lightning
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened), [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled), [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed), [prone](2-Mechanics/CLI/rules/conditions.md#Prone), [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained), [stunned](2-Mechanics/CLI/rules/conditions.md#Stunned)
- **Languages** —
- **Challenge** 2

## Traits

***Furtive.*** The spythronar swarm can use a bonus action to take the Hide action.

***Spider Climb.*** The spythronar swarm can climb difficult surfaces, including upside down on ceilings, without needing to make an ability check.

***Swarm.*** The spythronar swarm can occupy another creature's space and vice versa, and the swarm can move through any opening large enough for a Tiny arachnid. The swarm can't regain hit points or gain temporary hit points.

***Web Sense.*** While in contact with a web, the spythronar swarm knows the exact location of any other creature in contact with the same web.

***Web Walker.*** The spythronar swarm ignores movement restrictions caused by webbing.

## Actions

***Bites.*** *Melee Weapon Attack:* `dice:1d20+5|noform|text(+5)` to hit, reach 0 ft., one creature in the swarm's space. *Hit:* `dice:4d4|noform|avg|text(10)` (`4d4`) piercing damage and `dice:2d8|noform|avg|text(9)` (`2d8`) lightning damage, or `dice:2d4|noform|avg|text(5)` (`2d4`) piercing damage and `dice:1d8|noform|avg|text(4)` (`1d8`) lightning damage if the swarm has half of its hit points or fewer.

***Weave (4/Day).*** The spythronar swarm weaves webbing, covering a 5-foot square. The swarm can then give up 1 hit point to create a spythronar sac in that space. If the swarm's webbing covers a 10-foot square, it can give up 23 hit points as part of the same action, creating a spythronar web with the same number of hit points. The swarm can't drop to 0 hit points to create a sac or web.

If the swarm weaves an incomplete web, that web is a normal web rather than a sentient, monstrous one. A creature that enters this normal web's space must succeed on a DC 10 Strength saving throw or become [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) (escape DC 10) and [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained) while [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) in this way. Each 5-foot square of this web has AC 10; the damage vulnerabilities, immunities, and resistances of a spythronar web; and 5 hit points.
```
^statblock