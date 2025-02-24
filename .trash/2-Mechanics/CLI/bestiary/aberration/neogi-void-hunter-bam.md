---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/bam
- monster/cr/4
- monster/size/medium
- monster/type/aberration/warlock
aliases: ["Neogi Void Hunter"]
---
# Neogi Void Hunter
*Source: Boo's Astral Menagerie p. 41*  

A neogi void hunter is bigger than a typical adult neogi and often fills the role of captain aboard a nightspider (see the *Astral Adventurer's Guide*). The void hunter pledges fealty to one or more stellar entities in exchange for a taste of their immense power. These entities—known by such names as Acamar, Caiphon, Gibbeth, and Hadar—resemble stars and embody the essence of evil.

```ad-statblock
title: Neogi Void Hunter
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/BAM/Neogi%20Void%20Hunter.webp#token)
*Medium aberration (warlock), typically  Lawful Evil*

- **Armor Class** 14 (natural armor)
- **Hit Points** 58 (`9d8 + 18`)
- **Speed** 30 ft., climb 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
| 6 (-2)|16 (+3)|14 (+2)|16 (+3)|12 (+1)|18 (+4)|

- **Proficiency Bonus** +2
- **Saving Throws** Wisdom +3, Charisma +6
- **Skills** Arcana +5, Deception +6, Intimidation +6, Perception +3, Persuasion +6
- **Senses** darkvision 120 ft., passive Perception 13
- **Languages** Common, Deep Speech, telepathy 30 ft., Undercommon
- **Challenge** 4

## Traits

***Devil's Sight.*** Magical darkness doesn't impede the neogi's darkvision.

***Mental Fortitude.*** The neogi has advantage on saving throws against being [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed) or [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened), and magic can't put the neogi to sleep.

***Spider Climb.*** The neogi can climb difficult surfaces, including upside down on ceilings, without needing to make an ability check.

***Spellcasting.*** The neogi casts one of the following spells, using Charisma as the spellcasting ability:

**1/day each**: [dimension door](2-Mechanics/CLI/spells/dimension-door.md), [invisibility](2-Mechanics/CLI/spells/invisibility.md)

## Actions

***Multiattack.*** The neogi makes one Bite attack and two Claw attacks, or it makes two Eldritch Bolt attacks.

***Bite.*** *Melee Weapon Attack:* `dice:1d20+5|noform|text(+5)` to hit, reach 5 ft., one target. *Hit:* `dice:1d8+3|noform|avg|text(7)` (`1d8 + 3`) piercing damage plus `dice:4d6|noform|avg|text(14)` (`4d6`) poison damage, and the target must succeed on a DC 12 Constitution saving throw or become [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned) for 1 minute. A target can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.

***Claw.*** *Melee Weapon Attack:* `dice:1d20+5|noform|text(+5)` to hit, reach 5 ft., one target. *Hit:* `dice:1d8+3|noform|avg|text(7)` (`1d8 + 3`) piercing damage.

***Eldritch Bolt.*** *Ranged Spell Attack:* `dice:1d20+6|noform|text(+6)` to hit, range 120 ft., one creature. *Hit:* `dice:3d10+4|noform|avg|text(20)` (`3d10 + 4`) force damage.

## Bonus Actions

***Enslave (Recharges after a Short or Long Rest).*** The neogi targets one creature it can see within 30 feet of itself. The target must succeed on a DC 14 Wisdom saving throw or be magically [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed) by the neogi for 1 day, or until the neogi dies or is more than 1 mile from the target. The [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed) target obeys the neogi's commands and can't take reactions, and the neogi and the target can communicate telepathically with each other at a distance of up to 1 mile. Whenever the [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed) target takes damage, it can repeat the saving throw, ending the effect on itself on a success.
```
^statblock