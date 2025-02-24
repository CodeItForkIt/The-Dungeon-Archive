---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/tob1-2023
- monster/cr/1
- monster/environment/swamp
- monster/size/tiny
- monster/type/fey
aliases: ["Boloti"]
---
# Boloti
*Source: Tome of Beasts 1 (2023 Edition) p. 38*  

*This small, leering water spirit resembles a cross between a gray frog and a damp scarecrow, with small tendrils sprouting from all its extremities. It has water wings seemingly made out of jellyfish flesh.*

## Swamp Robbers

Known as uriska in Draconic, the bolotis are small, swamp-dwelling water spirits which delight in drowning unsuspecting victims in shallow pools and springs, then robbing the corpses of whatever shiny objects they find. Bolotis use their magical vortex abilities to immobilize their victims and drag them to a watery death. They delight in storing up larders of victims under winter ice or under logs.

## Fond of Allies

Bolotis sometimes team up with miremals and will-o'-wisps to create cunning ambushes. They are happy with a single kill at a time.

## Statblock

```ad-statblock
title: Boloti
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ToB1-2023/Boloti.webp#token)
*Tiny fey, Neutral Evil*

- **Armor Class** 15
- **Hit Points** 45 (`10d4 + 20`)
- **Speed** 20 ft., swim 40 ft. (0 ft. swim 60 ft. in vortex form)

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|12 (+1)|20 (+5)|14 (+2)|13 (+1)|12 (+1)|11 (+0)|

- **Proficiency Bonus** +2
- **Saving Throws** ⏤
- **Skills** Perception +3, Stealth +7
- **Senses** darkvision 60 ft., passive Perception 13
- **Languages** Common, Primordial, Sylvan
- **Challenge** 1

## Traits

***Amphibious.*** The boloti can breathe air and water.

***Water Camouflage.*** The boloti has advantage on Dexterity ([Stealth](2-Mechanics/CLI/rules/skills.md#Stealth)) checks made to hide while at least half of its body is submerged in water.

***Water Mastery.*** A boloti has advantage on attack rolls if both it and its target are touching the same body of water. If the target and the boloti are both on dry ground, the boloti has disadvantage on attack rolls.

***Watery Body (Vortex Form Only).*** The boloti can enter a hostile creature's space and stop there. It can move through a space as narrow as 1 inch wide without squeezing. A creature that starts its turn in the boloti's space must succeed on a DC 12 Strength saving throw or take `dice:1d8|noform|avg|text(4)` (`1d8`) bludgeoning damage as it is buffeted by the swirl of water.

***Spellcasting (True Form Only).*** The boloti casts one of the following spells, requiring no material components and using Intelligence as the spellcasting ability (spell save DC 11):

**At will**: [water breathing](2-Mechanics/CLI/spells/water-breathing.md), [water walk](2-Mechanics/CLI/spells/water-walk.md)

**1/day**: [control water](2-Mechanics/CLI/spells/control-water.md)

**3/day each**: [create or destroy water](2-Mechanics/CLI/spells/create-or-destroy-water.md), [fog cloud](2-Mechanics/CLI/spells/fog-cloud.md), [sleep](2-Mechanics/CLI/spells/sleep.md)

## Actions

***Dagger (True Form Only).*** *Melee or Ranged Weapon Attack:* `dice:1d20+7|noform|text(+7)` to hit, reach 5 ft. or range 20/60 ft., one target. *Hit:* `dice:1d4+5|noform|avg|text(7)` (`1d4 + 5`) piercing damage.

***Whirlpool (Vortex Form Only).*** One creature in the boloti's space must make a DC 12 Strength saving throw. On a failure, the target takes `dice:2d8|noform|avg|text(9)` (`2d8`) bludgeoning damage, and if it is Medium or smaller, it is [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) (escape DC 12). Until this grapple ends, the target is [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained) and unable to breathe unless it can breathe water. If the saving throw is successful, the target takes half the damage and is pushed out of the boloti's space.

## Bonus Actions

***Vortex Form.*** The boloti magically transforms into a Small vortex of swirling, churning water or back into its true form, which is Fey. The boloti can transform into its vortex form only while at least half of its body is submerged in water, and any creature it is grappling with Whirlpool is freed if the boloti transforms back to its true form. Its statistics are the same in each form. Any equipment it is wearing or carrying transforms with it. It reverts to its true form if it dies.
```
^statblock

## Environment

swamp