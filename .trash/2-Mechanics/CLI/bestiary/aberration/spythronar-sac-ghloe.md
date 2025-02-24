---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/ghloe
- monster/cr/0
- monster/size/tiny
- monster/type/aberration
aliases: ["Spythronar Sac"]
---
# Spythronar Sac
*Source: Grim Hollow: Lairs of Etharis p. 31*  

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
title: Spythronar Sac
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/GHLoE/Spythronar%20Sac.webp#token)
*Tiny aberration, Unaligned*

- **Armor Class** 5
- **Hit Points** 1 (`1d4 - 1`)
- **Speed** 0 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
| 1 (-5)| 1 (-5)| 8 (-1)| 1 (-5)| 3 (-4)| 1 (-5)|

- **Proficiency Bonus** +2
- **Saving Throws** ⏤
- **Skills** ⏤
- **Senses** tremorsense (blind beyond this radius), passive Perception 6
- **Condition Immunities** [blinded](2-Mechanics/CLI/rules/conditions.md#Blinded), [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [deafened](2-Mechanics/CLI/rules/conditions.md#Deafened), [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened), [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed), [petrified](2-Mechanics/CLI/rules/conditions.md#Petrified), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned), [prone](2-Mechanics/CLI/rules/conditions.md#Prone), [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained), [unconscious](2-Mechanics/CLI/rules/conditions.md#Unconscious)
- **Languages** —
- **Challenge** 0

## Traits

***False Appearance.*** The spythronar sac appears to be a tangled ball of string, twigs, and dirt. Someone who can see the sac can identify it with a successful DC 15 Intelligence ([Arcana](2-Mechanics/CLI/rules/skills.md#Arcana) or [Nature](2-Mechanics/CLI/rules/skills.md#Nature)) check.

***Fragile.*** A creature who enters the spythronar sac's space must succeed on a DC 10 Dexterity saving throw, or the sac is destroyed.

***Lightning Release.*** When the spythronar sac is destroyed, it releases lightning in a 10-foot radius. A creature who destroyed the sac by entering its space receives no saving throw. Other creatures in that area must succeed on a DC 10 Dexterity saving throw or take `dice:1d8|noform|avg|text(4)` (`1d8`) lightning damage. Each spythronar swarm and web in this area instead gains advantage on its next attack roll.

***Shocking Birth.*** When a spythronar sac takes lightning damage from a source other than another spythronar, it hatches, transforming into a spythronar swarm with half the normal hit points. This swarm rolls initiative and enters the combat.
```
^statblock