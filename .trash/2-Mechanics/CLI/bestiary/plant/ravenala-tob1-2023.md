---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/tob1-2023
- monster/cr/5
- monster/environment/coastal
- monster/environment/forest
- monster/size/large
- monster/type/plant
aliases: ["Ravenala"]
---
# Ravenala
*Source: Tome of Beasts 1 (2023 Edition) p. 303*  

*The tree steps forward on bark-covered legs. Its head is crowned by long-stemmed, green-paddled fronds and spiked seed pods, and its dangling arms end in hooked, wooden talons.*

## Leafy Advisors

Wise and long-lived like treants, ravenalas tend their coastal forest homes far from most societies. Tribal humanoids respect and venerate ravenalas and sometimes seek their advice or aid in times of great need. Ravenalas seldom interact with others unless approached.

## Prisoner's Lamentation

Unlike treants, ravenalas avoid physical conflict in favor of diplomacy and compromise. If annoyed, they imprison hostile creatures within their trunks rather than killing or eating the attackers. Trapped creatures must sing their own lament as they are carried off to a distant locale away from the ravenala's home.

## Statblock

```ad-statblock
title: Ravenala
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ToB1-2023/Ravenala.webp#token)
*Large plant, Neutral*

- **Armor Class** 15 (natural armor)
- **Hit Points** 126 (`12d10 + 60`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|20 (+5)|10 (+0)|20 (+5)|12 (+1)|16 (+3)|12 (+1)|

- **Proficiency Bonus** +3
- **Saving Throws** Wisdom +6, Charisma +4
- **Skills** ⏤
- **Senses** passive Perception 13
- **Damage Vulnerabilities** cold, fire
- **Damage Resistances** bludgeoning, piercing
- **Condition Immunities** [blinded](2-Mechanics/CLI/rules/conditions.md#Blinded), [deafened](2-Mechanics/CLI/rules/conditions.md#Deafened)
- **Languages** Common, Druidic, Elvish, Sylvan
- **Challenge** 5

## Traits

***Magic Resistance.*** The ravenala has advantage on saving throws against spells and other magical effects.

***Woodland Stride.*** Difficult terrain composed of magical or nonmagical plants doesn't cost the ravenala extra movement. In addition, it can pass through magical or nonmagical plants without being slowed by them and without taking damage from them if they have thorns, spines, or a similar hazard.

## Actions

***Multiattack.*** The ravenala makes two Bursting Pod or Slam attacks. If both Slam attacks hit a Medium or smaller creature, the target is [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) (escape DC 14), and the ravenala uses its Lamenting Engulfment on the target.

***Slam.*** *Melee Weapon Attack:* `dice:1d20+8|noform|text(+8)` to hit, reach 5 ft., one target. *Hit:* `dice:3d8+5|noform|avg|text(18)` (`3d8 + 5`) bludgeoning damage.

***Bursting Pod.*** *Ranged Weapon Attack:* `dice:1d20+8|noform|text(+8)` to hit, range 30/120 ft., one target. *Hit:* `dice:2d6+5|noform|avg|text(12)` (`2d6 + 5`) bludgeoning damage, and each creature within 5 feet of the target, including the target, must make a DC 15 Dexterity saving throw, taking `dice:2d4|noform|avg|text(5)` (`2d4`) piercing damage on a failed save, or half as much damage on a successful one.

***Lamenting Engulfment.*** The ravenala engulfs a Medium or smaller creature [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) by it. The engulfed target is [blinded](2-Mechanics/CLI/rules/conditions.md#Blinded) and [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained), it has total cover against attacks and other effects outside the ravenala, and it must succeed on a DC 14 Charisma saving throw at the start of each of the ravenala's turns or sing a lament of the mistakes and misdeeds it has performed in its lifetime. While singing, the engulfed creature can still act, but it can't otherwise speak, including casting spells with verbal components. If the ravenala moves, the engulfed creature moves with it. The ravenala can have only one creature engulfed at a time.

***Healing Leaves (3/Day).*** The ravenala removes a leaf from its head and wraps the leaf around the wounds of one creature it can see within 5 feet of it. The target magically regains 10 `dice:3d6|noform|avg` (`3d6`) hp and is freed from any disease, poison, blindness, or deafness.

***Encourage Growth (3/Day).*** The ravenala whispers magical words of growth to nonmagical plants on a point it can see within 30 feet of it. The plants burst with life and spread rapidly. The area within 20 feet of that point becomes difficult terrain for 24 hours.
```
^statblock

## Environment

coastal, forest