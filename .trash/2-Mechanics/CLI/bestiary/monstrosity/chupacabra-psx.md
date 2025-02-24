---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/psx
- monster/cr/3
- monster/size/medium
- monster/type/monstrosity
aliases: ["Chupacabra"]
---
# Chupacabra
*Source: Plane Shift: Ixalan p. 9*  

Indescribable creatures of nightmare lurk in the ruins and dark places of Ixalan. Many are thought to be the corrupted remnants of the life energy and brilliant light left behind in places the Sun Empire has abandoned. Such creatures include a monster that lurks in the darkness of the jungle and feeds on the blood of mammals and dinosaurs, called the chupacabra. It is stealthy and elusive, known more by the blood-drained prey it leaves behind than by actual physical sightings.

## Night Terrors

The legends of the Sun Empire are populated with the enemies of the sun—terrible monsters that threaten to devour its light and undo its work. Unfortunately for the people of Ixalan, these are not just creatures of legend but real monsters with supernatural power, lurking in the darkness of night and the shadows of ancient ruins and crypts.

## Statblock

```ad-statblock
title: Chupacabra
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/PSX/Chupacabra.webp#token)
*Medium monstrosity, Neutral Evil*

- **Armor Class** 14 (natural armor)
- **Hit Points** 45 (`6d8 + 18`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|15 (+2)|14 (+2)|16 (+3)| 6 (-2)|13 (+1)| 9 (-1)|

- **Proficiency Bonus** +2
- **Saving Throws** ⏤
- **Skills** Perception +3, Stealth +4
- **Senses** darkvision 120 ft., passive Perception 13
- **Damage Resistances** bludgeoning, piercing, slashing from nonmagical weapons
- **Languages** —
- **Challenge** 3

## Traits

***Sunlight Sensitivity.*** While in sunlight, the chupacabra has disadvantage on attack rolls, as well as on Wisdom ([Perception](2-Mechanics/CLI/rules/skills.md#Perception)) checks that rely on sight.

## Actions

***Bite.*** *Melee Weapon Attack:* `dice:1d20+4|noform|text(+4)` to hit, reach 5 ft., one target. *Hit:* `dice:2d4+2|noform|avg|text(7)` (`2d4 + 2`) piercing damage. If the target is a creature, it must succeed on a DC 13 Strength saving throw or be knocked [prone](2-Mechanics/CLI/rules/conditions.md#Prone).

***Drain Blood.*** *Melee Weapon Attack:* `dice:1d20+4|noform|text(+4)` to hit, reach 5 ft., one creature that is [prone](2-Mechanics/CLI/rules/conditions.md#Prone), [incapacitated](2-Mechanics/CLI/rules/conditions.md#Incapacitated), or [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained). *Hit:* `dice:1d6+2|noform|avg|text(5)` (`1d6 + 2`) necrotic damage. The target must succeed on a DC 13 Constitution saving throw or its hit point maximum is reduced by an amount equal to the damage taken, and the chupacabra regains hit points equal to that amount. The reduction lasts until the target finishes a long rest. The target dies if this effect reduces its hit point maximum to 0.

## Reactions

***Pin.*** If a creature within 5 feet of the chupacabra stands up, the chupacabra can use its reaction to make a bite attack.
```
^statblock