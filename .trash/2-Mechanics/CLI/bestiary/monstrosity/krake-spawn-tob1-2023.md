---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/tob1-2023
- monster/cr/14
- monster/environment/arctic
- monster/environment/underwater
- monster/size/huge
- monster/type/monstrosity
aliases: ["Krake Spawn"]
---
# Krake Spawn
*Source: Tome of Beasts 1 (2023 Edition) p. 249*  

*This twisted, beast looks like the unholy union of squid and spider. Its shell-covered core has six small rubbery legs, peculiar antennae, and six tentacles around a squid's enormous beak.*

## Demonic Crossbreeds

Some believe krake spawn are demonic crossbreeds created by the aboleth, fusing kraken blood with demonic souls. Others say that krake spawn are the horrible creation of a long-forgotten meddling god, summoned to the mortal world by deep ones. Certainly, krake spawn respond to summoning magic, and spellcasters summon krake spawn through blood sacrifices to work evil in the world. However, they do so at considerable peril: unlike demons and devils, krake spawn are seldom bound by pacts of any kind.

## Outwit Humans

Though enormous and carrying an armored green shell on their six spindly legs, krake spawn are surprisingly quick and agile. Worse, they have a malicious and bloodthirsty intellect. A krake spawn is considerably smarter than most humans, who often mistake them for dumb beasts—an error that can often prove fatal.

## Iceberg Fortresses

Krake spawn live in remote, icy regions, where they fashion elaborate iceberg fortresses. These fortresses are stocked with frozen creatures (an emergency food supply), the krake spawn's treasure and library, slaves or prisoners of many races, and a hellish nest filled with the krake spawn's offspring.

## Statblock

```ad-statblock
title: Krake Spawn
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ToB1-2023/Krake%20Spawn.webp#token)
*Huge monstrosity, Neutral Evil*

- **Armor Class** 16 (natural armor)
- **Hit Points** 175 (`14d12 + 84`)
- **Speed** 20 ft., swim 60 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|24 (+7)|12 (+1)|22 (+6)|17 (+3)|15 (+2)|18 (+4)|

- **Proficiency Bonus** +5
- **Saving Throws** Strength +12, Constitution +11, Intelligence +8, Charisma +9
- **Skills** ⏤
- **Senses** blindsight 60 ft., darkvision 120 ft., passive Perception 12
- **Damage Immunities** cold, poison, psychic
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** Common, Infernal, Primordial, Void Speech
- **Challenge** 14

## Traits

***Amphibious.*** The krake spawn can breathe air and water.

## Actions

***Multiattack.*** The krake spawn makes one Bite attack and eight Tentacle attacks, or it makes four Freezing Water Bolt attacks.

***Bite.*** *Melee Weapon Attack:* `dice:1d20+12|noform|text(+12)` to hit, reach 10 ft, one target. *Hit:* `dice:1d10+7|noform|avg|text(12)` (`1d10 + 7`) slashing damage.

***Tentacle.*** *Melee Weapon Attack:* `dice:1d20+12|noform|text(+12)` to hit, reach 15 ft., one target. *Hit:* `dice:1d6+7|noform|avg|text(10)` (`1d6 + 7`) bludgeoning damage. If the target is a Large or smaller creature, it is [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) (escape DC 17). Until this grapple ends, the target is [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained). The krake spawn has eight tentacles, each of which can grapple only one target.

***Freezing Water Bolt.*** *Ranged Spell Attack:* `dice:1d20+9|noform|text(+9)` to hit, range 60 ft., one target. *Hit:* `dice:2d8+4|noform|avg|text(13)` (`2d8 + 4`) bludgeoning damage plus `dice:3d6|noform|avg|text(10)` (`3d6`) cold damage.

***Ink Cloud (Recharge 5-6).*** While underwater, the krake spawn emits a 20-foot-radius cloud of ink all around itself. Each creature in the cloud must make a DC 17 Constitution saving throw, taking `dice:10d10|noform|avg|text(55)` (`10d10`) poison damage on a failed save, or half as much damage on a successful one. The area is heavily obscured for 1 minute, although a significant current can disperse the ink.

***Vomit Forth the Deeps (Recharge 5-6).*** The krake spawn sprays half‑digested food from its maw in a 30-foot cone. Each creature in the area must make a DC 17 Dexterity saving throw. On a failure, a creature takes `dice:6d8|noform|avg|text(27)` (`6d8`) acid damage plus `dice:5d10|noform|avg|text(27)` (`5d10`) poison damage and is [incapacitated](2-Mechanics/CLI/rules/conditions.md#Incapacitated). On a success, a creature takes half the damage and isn't [incapacitated](2-Mechanics/CLI/rules/conditions.md#Incapacitated).

## Bonus Actions

***Water Jet.*** Each creature within 5 feet of the krake spawn must succeed on a DC 17 Dexterity saving throw or be knocked [prone](2-Mechanics/CLI/rules/conditions.md#Prone). The spawn then swims up to half its swimming speed without provoking opportunity attacks. The spawn must be underwater to use this bonus action.
```
^statblock

## Environment

arctic, underwater