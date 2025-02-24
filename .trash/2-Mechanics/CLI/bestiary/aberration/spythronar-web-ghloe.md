---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/ghloe
- monster/cr/2
- monster/size/large
- monster/type/aberration
aliases: ["Spythronar Web"]
---
# Spythronar Web
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
title: Spythronar Web
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/GHLoE/Spythronar%20Web.webp#token)
*Large aberration, Neutral Evil*

- **Armor Class** 13
- **Hit Points** 65 (`10d10 + 10`)
- **Speed** 30 ft., climb 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|17 (+3)|16 (+3)|13 (+1)| 3 (-4)| 8 (-1)| 1 (-5)|

- **Proficiency Bonus** +2
- **Saving Throws** ⏤
- **Skills** ⏤
- **Senses** tremorsense 60 ft. (blind beyond this radius), passive Perception 9
- **Damage Vulnerabilities** fire
- **Damage Resistances** bludgeoning, piercing
- **Damage Immunities** lightning
- **Condition Immunities** [blinded](2-Mechanics/CLI/rules/conditions.md#Blinded), [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [deafened](2-Mechanics/CLI/rules/conditions.md#Deafened), [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened), [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed), [petrified](2-Mechanics/CLI/rules/conditions.md#Petrified), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned), [prone](2-Mechanics/CLI/rules/conditions.md#Prone), [unconscious](2-Mechanics/CLI/rules/conditions.md#Unconscious)
- **Languages** —
- **Challenge** 2

## Traits

***Adhesive.*** The spythronar web adheres to anything that touches it. To avoid adhering when touching the web, a creature must succeed on a DC 13 Strength saving throw, but a creature hit by the web's crush attack doesn't receive a saving throw. A Huge or smaller creature adhered to the web is also [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) by it (escape DC 13). If adhered to a target larger than it can grapple, the web can release the adhesive or remain adhered and be dragged along as the target moves. Neither choice requires an action from the web. Removing an object adhered to the web or the web from anything it's adhered to requires a successful DC 13 Strength ([Athletics](2-Mechanics/CLI/rules/skills.md#Athletics)) check as an action.

***Amorphous.*** The spythronar web can move through a space as narrow as 1 inch wide without squeezing.

***False Appearance.*** While the spythronar web remains motionless and takes no action, it is indistinguishable from a large, thick spider web.

***Spider Climb.*** A spythronar web can climb difficult surfaces, including upside down on ceilings, without needing to make an ability check.

***Web Sense.*** While in contact with a web, the spythronar web knows the exact location of any other creature in contact with the same web.

***Web Walker.*** The spythronar web ignores movement restrictions caused by webbing.

## Actions

***Crush.*** *Melee Weapon Attack:* `dice:1d20+5|noform|text(+5)` to hit, reach 5 ft., one creature. *Hit:* `dice:2d6+3|noform|avg|text(10)` (`2d6 + 3`) bludgeoning damage and Adhesive. The target is also [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained) while [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) in this way, and the spythronar web can't crush another target.

***Lightning Surge.*** *Melee Weapon Attack:* `dice:1d20+5|noform|text(+5)` to hit, reach 30 ft., one target. *Hit:* `dice:2d8|noform|avg|text(9)` (`2d8`) lightning damage. If the spythronar web has a creature [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) and attacks another target, the [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) creature also takes this damage.
```
^statblock