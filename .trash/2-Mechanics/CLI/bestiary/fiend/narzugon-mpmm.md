---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/mpmm
- monster/cr/13
- monster/size/medium
- monster/type/fiend/devil
aliases: ["Narzugon"]
---
# Narzugon
*Source: Mordenkainen Presents: Monsters of the Multiverse p. 190, Mordenkainen's Tome of Foes p. 167, Adventure Atlas: The Mortuary*  

Paladins who make deals with devils and carry their twisted sense of honor into the afterlife are especially valuable to the archdukes of the Nine Hells. These narzugons act as horrific perversions of knights errant, carrying out their masters' will.

Narzugons wield hell-forged lances that shunt the souls of any they killed to the River Styx for rebirth as [lemures](2-Mechanics/CLI/bestiary/fiend/lemure.md). Every lance bears the marks of both a narzugon and its master.

Each narzugon claims a [nightmare](2-Mechanics/CLI/bestiary/fiend/nightmare.md) as its mount. These steeds are bound by [infernal tack](2-Mechanics/CLI/items/infernal-tack-mtf.md) and must respond to the summons and commands of the spurs' wearer.

```ad-statblock
title: Narzugon
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/MPMM/Narzugon.webp#token)
*Medium fiend (devil), Typically  Lawful Evil*

- **Armor Class** 20 ([plate armor](2-Mechanics/CLI/items/plate-armor.md), [shield](2-Mechanics/CLI/items/shield.md))
- **Hit Points** 112 (`15d8 + 45`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|20 (+5)|10 (+0)|17 (+3)|16 (+3)|14 (+2)|19 (+4)|

- **Proficiency Bonus** +5
- **Saving Throws** Dexterity +5, Constitution +8, Charisma +9
- **Skills** Perception +12
- **Senses** darkvision 120 ft., passive Perception 22
- **Damage Resistances** acid; cold; bludgeoning, piercing, slashing from nonmagical attacks that aren't silvered
- **Damage Immunities** fire, poison
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** Common, Infernal, telepathy 120 ft.
- **Challenge** 13

## Traits

***Infernal Tack.*** The narzugon wears spurs that are part of [infernal tack](2-Mechanics/CLI/items/infernal-tack-mtf.md), which allow it to summon its [nightmare](2-Mechanics/CLI/bestiary/fiend/nightmare.md) companion as an action.

***Magic Resistance.*** The narzugon has advantage on saving throws against spells and other magical effects.

## Actions

***Multiattack.*** The narzugon makes three Hellfire Lance attacks. It also uses Infernal Command or Terrifying Command.

***Hellfire Lance.*** *Melee Weapon Attack:* `dice:1d20+10|noform|text(+10)` to hit, reach 10 ft., one target. *Hit:* `dice:1d12+5|noform|avg|text(11)` (`1d12 + 5`) piercing damage plus `dice:3d10|noform|avg|text(16)` (`3d10`) fire damage. If this damage kills a creature with a soul, the soul rises from the River Styx as a [lemure](2-Mechanics/CLI/bestiary/fiend/lemure.md) in Avernus in `dice:1d4|noform|avg` (`1d4`) hours. If the creature isn't revived before then, only a [wish](2-Mechanics/CLI/spells/wish.md) spell or killing the lemure and casting true resurrection on the creature's original body can restore it to life. Constructs and devils are immune to this effect.

***Infernal Command.*** Each ally of the narzugon within 60 feet of it can't be [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed) or [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened) until the end of the narzugon's next turn.

***Terrifying Command.*** Each creature within 60 feet of the narzugon that isn't a Fiend must succeed on a DC 17 Charisma saving throw or become [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened) of the narzugon for 1 minute. A creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success. A creature that makes a successful saving throw is immune to this narzugon's Terrifying Command for 24 hours.

***Healing (1/Day).*** The narzugon, or one creature it touches, regains 100 hit points.
```
^statblock