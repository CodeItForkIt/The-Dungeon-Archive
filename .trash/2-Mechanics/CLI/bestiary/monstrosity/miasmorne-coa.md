---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/coa
- monster/cr/16
- monster/size/huge
- monster/type/monstrosity
aliases: ["Miasmorne"]
---
# Miasmorne
*Source: Chains of Asmodeus p. 246*  

Avernus is a bleak wasteland of jagged mountains and metal-studded hills, but the true ugliness to a devil's eyes is in the scars of war where demonic corpses, arms, and armor pile, infecting the plane with their chaotic ichor and breeding fresh monsters to trouble the order of the Nine Hells. The miasmorne were bred to clean up after Abyssal invasion: great lumbering Monstrosities able to devour demonic flesh, armor, weapons, and ruined war engines and return the plane to its pristine starkness. The monsters prospered beyond anyone's reckoning and now drag their bellies across many layers of the Nine Hells.

## Voracious Detritovores

Miasmorne resemble bulky, wingless dragons, their broad heads flanked with great fans that they spread when challenged. While they will gorge themselves on dead flesh—or create fresh corpses with their impressive teeth and jaws—their preferred meal is mineral. Where their populations have grown, they seek out concentrations of metal. Iron and steel are their staple fare, but they will take gold, silver, adamantine or mithril if available. As infernal cities and fortresses are often constructed of iron this leads to literal holes in the Fiends' security.

## Armored in Rust

As well as sustaining the monsters, the metals they devour go towards fortifying their hides, bones, and jaws. Miasmorne are formidably heavy and strong, proof against mundane blades and as resistant to heat as most denizens of the Nine Hells. Not naturally aggressive, the dull-witted brutes are hard to dissuade once they decide to feed. Miasmorne saliva corrodes metal efficiently, and they frequently pause mid-fight to slobber down the brittle flakes of whatever they've just destroyed. Under threat, their head fans bristle with thousands of extruded metal spines which they launch in a cloud of flechettes at foes, scouring the air both with sharp-edged missiles and a great spray of their rusting spittle. When injured, those that have devoured magic weapons or defenses manifest those same effects in their hide and claws, expending their internal store of swallowed arcana to drive away those who disturb their feasting.

## Pests and War-beasts

Miasmorne are a serious problem in some regions, chewing at the walls of castles and cities, swallowing whole armories, and tearing the armaments off the hosts of the Nine Hells. Mortal intruders who can lure the creatures with meals of enchanted or high-quality metal can even use them as siege engines to get past infernal walls. In other parts of the Nine Hells, the creatures are kept as semi-domesticated guards or waste disposal monsters. In Avernus, where they were first bred, Zariel maintains a crack corps of handlers who goad the beasts into wallowing through hosts of invading demons, chewing on Abyssal mail, and eating the prized magic blades of demon princes.

## Statblock

```ad-statblock
title: Miasmorne
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/CoA/Miasmorne.webp#token)
*Huge monstrosity, Unaligned*

- **Armor Class** 19 (natural armor)
- **Hit Points** 230 (`20d12 + 100`)
- **Speed** 20 ft., burrow 20 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|22 (+6)|10 (+0)|21 (+5)| 3 (-4)|10 (+0)|10 (+0)|

- **Proficiency Bonus** +5
- **Saving Throws** Strength +11, Constitution +10
- **Skills** Arcana +1, Athletics +16, Survival +5
- **Senses** tremorsense 60 ft., passive Perception 10
- **Damage Immunities** acid; fire; bludgeoning, piercing, slashing from nonmagical attacks
- **Condition Immunities** [petrified](2-Mechanics/CLI/rules/conditions.md#Petrified)
- **Languages** —
- **Challenge** 16

## Traits

***Acidic Attacks.*** If a creature takes acid damage from the miasmorne and that creature is wearing nonmagical metal armor, that armor is destroyed.

***Acidic Hide.*** After a nonmagical metal weapon hits the miasmorne that weapon melts and is destroyed. Likewise, nonmagical metal ammunition that hits the miasmorne is destroyed.

## Actions

***Multiattack.*** The miasmorne makes three attacks using Bite, Flechette or a combination of the two.

***Bite.*** *Melee Weapon Attack:* `dice:1d20+11|noform|text(+11)` to hit, reach 5 ft., one target. *Hit:* `dice:3d10+6|noform|avg|text(22)` (`3d10 + 6`) bludgeoning damage plus `dice:2d6|noform|avg|text(7)` (`2d6`) acid damage. If the target is a Large or smaller creature, it has the [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) condition (escape DC 18). The miasmorne can't make Bite attacks while a creature is [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) in this way.

***Flechette.*** *Ranged Weapon Attack:* `dice:1d20+11|noform|text(+11)` to hit, range 60/120 ft., one target. *Hit:* `dice:3d6+6|noform|avg|text(16)` (`3d6 + 6`) acid damage.

***Flechette Spray (Recharge 5-6).*** The miasmorne launches flechettes from its fins in a 90-foot cone in front of it. All creatures in the cone must make a DC 19 Dexterity saving throw, taking `dice:6d6|noform|avg|text(21)` (`6d6`) acid damage on a failed save, or half as much damage on a successful one.

***Acidic Secretion (1/Day).*** The miasmorne secretes an acidic solution, then sprays it around itself. All creatures in a 20-foot-radius sphere, centered on the miasmorne, must make a DC 19 Dexterity saving throw. Targets take `dice:4d12|noform|avg|text(26)` (`4d12`) acid damage on a failed save, or half as much damage on a successful one. All nonmagical metals within the radius that aren't being carried, as well as nonmagical metal items carried or worn by creatures that failed the save, are destroyed.
```
^statblock