---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/psz
- monster/cr/11
- monster/size/huge
- monster/type/monstrosity
aliases: ["Hellion"]
---
# Hellion
*Source: Plane Shift: Zendikar p. 32*  

Similar to wurms, hellions are enormous serpentine creatures that dwell in the lava deep beneath the surface of Akoum. When an eruption brings lava to the surface, hellions occasionally emerge as well. Thrust into what seems to them like freezing air, the hellions begin a rampage of devastation resembling an extension of the lava flow.

A hellion bears a certain resemblance to both a millipede and a crustacean. Small legs tucked close to its body help propel it through its tunnels. Six long, jointed limbs protrude from its head, allowing it to drag prey into its mouth. Its body exudes infernal heat and its movements shake the earth like a tremor.

The [remorhaz](2-Mechanics/CLI/bestiary/monstrosity/remorhaz.md) statistics in the Monster Manual work well for hellions of different sizes.

```ad-statblock
title: Hellion
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/PSZ/Hellion.webp#token)
*Huge monstrosity, Unaligned*

- **Armor Class** 17 (natural armor)
- **Hit Points** 195 (`17d12 + 85`)
- **Speed** 30 ft., burrow 20 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|24 (+7)|13 (+1)|21 (+5)| 4 (-3)|10 (+0)| 5 (-3)|

- **Proficiency Bonus** +4
- **Saving Throws** ⏤
- **Skills** ⏤
- **Senses** darkvision 60 ft., tremorsense 60 ft., passive Perception 10
- **Damage Immunities** cold, fire
- **Languages** —
- **Challenge** 11

## Traits

***Heated Body.*** A creature that touches the hellion or hits it with a melee attack while within 5 feet of it takes `dice:3d6|noform|avg|text(10)` (`3d6`) fire damage.

## Actions

***Bite.*** *Melee Weapon Attack:* `dice:1d20+11|noform|text(+11)` to hit, reach 10 ft., one target. *Hit:* `dice:6d10+7|noform|avg|text(40)` (`6d10 + 7`) piercing damage plus `dice:3d6|noform|avg|text(10)` (`3d6`) fire damage. If the target is a creature, it is [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) (escape DC 17). Until this grapple ends, the target is [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained), and the hellion can't bite another target.

***Swallow.*** The hellion makes one bite attack against a Medium or smaller creature it is grappling. If the attack hits, that creature takes the bite's damage and is swallowed, and the grapple ends. While swallowed, the creature is [blinded](2-Mechanics/CLI/rules/conditions.md#Blinded) and [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained), it has total cover against attacks and other effects outside the hellion, and it takes `dice:6d6|noform|avg|text(21)` (`6d6`) acid damage at the start of each of the hellion's turns.

If the hellion takes 30 damage or more on a single turn from a creature inside it, the hellion must succeed on a DC 15 Constitution saving throw at the end of that turn or regurgitate all swallowed creatures, which fall [prone](2-Mechanics/CLI/rules/conditions.md#Prone) in a space within 10 feet of the hellion. If the hellion dies, a swallowed creature is no longer [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained) by it and can escape from the corpse using 15 feet of movement, exiting [prone](2-Mechanics/CLI/rules/conditions.md#Prone).
```
^statblock