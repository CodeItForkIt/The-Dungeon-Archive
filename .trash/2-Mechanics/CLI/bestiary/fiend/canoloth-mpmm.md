---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/mpmm
- monster/cr/8
- monster/environment/coastal
- monster/environment/underdark
- monster/environment/urban
- monster/size/medium
- monster/type/fiend/yugoloth
aliases: ["Canoloth"]
---
# Canoloth
*Source: Mordenkainen Presents: Monsters of the Multiverse p. 69, Mordenkainen's Tome of Foes p. 247*  

> [!quote] A quote from Mordenkainen  
> 
> Canoloths are glorified guard dogs. If you must engage one, just find out exactly what it's been assigned to do. I've often found I can waltz right past them by taking advantage of a relevant loophole.

A type of yugoloth, canoloths are fiendish trackers and guardians employed by evil powers. They prefer to enter into contracts to guard valuable treasures and important locations. They always do exactly as asked—never any more, never any less.

With senses sharp enough to pinpoint the locations of nearby [invisible](2-Mechanics/CLI/rules/conditions.md#Invisible) creatures, canoloths respond unfailingly to any threat to their charges. Furthermore, they emit a magical distortion field that prevents creatures close to them from teleporting. Canoloths confront intruders with swift and terrible force, projecting long, spiny tongues to grab their foes and drag them close. What happens next depends on the contract. Unless instructed to kill, a canoloth merely holds on to its prisoner, but if given the order to do so, it tears its prey limb from limb.

```ad-statblock
title: Canoloth
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/MPMM/Canoloth.webp#token)
*Medium fiend (yugoloth), Typically  Neutral Evil*

- **Armor Class** 16 (natural armor)
- **Hit Points** 120 (`16d8 + 48`)
- **Speed** 50 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|18 (+4)|10 (+0)|17 (+3)| 5 (-3)|17 (+3)|12 (+1)|

- **Proficiency Bonus** +3
- **Saving Throws** ⏤
- **Skills** Investigation +3, Perception +9
- **Senses** truesight 120 ft., passive Perception 19
- **Damage Resistances** cold; fire; lightning; bludgeoning, piercing, slashing from nonmagical attacks
- **Damage Immunities** acid, poison
- **Condition Immunities** [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** Abyssal, Infernal, telepathy 60 ft.
- **Challenge** 8

## Traits

***Dimensional Lock.*** Other creatures can't teleport to or from a space within 60 feet of the canoloth. Any attempt to do so is wasted.

***Magic Resistance.*** The canoloth has advantage on saving throws against spells and other magical effects.

***Uncanny Senses.*** The canoloth can't be [surprised](2-Mechanics/CLI/rules/conditions.md#Surprised) unless it's [incapacitated](2-Mechanics/CLI/rules/conditions.md#Incapacitated).

## Actions

***Multiattack.*** The canoloth makes one Bite or Tongue attack and one Claw attack.

***Bite.*** *Melee Weapon Attack:* `dice:1d20+7|noform|text(+7)` to hit, reach 5 ft., one target. *Hit:* `dice:1d6+4|noform|avg|text(7)` (`1d6 + 4`) piercing damage plus `dice:4d8|noform|avg|text(18)` (`4d8`) force damage.

***Claw.*** *Melee Weapon Attack:* `dice:1d20+7|noform|text(+7)` to hit, reach 5 ft., one target. *Hit:* `dice:1d6+4|noform|avg|text(7)` (`1d6 + 4`) slashing damage plus `dice:2d8|noform|avg|text(9)` (`2d8`) force damage.

***Tongue.*** *Melee Weapon Attack:* `dice:1d20+7|noform|text(+7)` to hit, reach 30 ft., one target. *Hit:* `dice:1d12+4|noform|avg|text(10)` (`1d12 + 4`) piercing damage plus `dice:2d6|noform|avg|text(7)` (`2d6`) acid damage. If the target is Medium or smaller, it is [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) (escape DC 15), pulled up to 30 feet toward the canoloth, and [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained) until the grapple ends. The canoloth can grapple one target at a time with its tongue.
```
^statblock

## Environment

coastal, underdark, urban