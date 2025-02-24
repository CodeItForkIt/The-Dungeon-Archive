---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/psx
- monster/cr/6
- monster/size/large
- monster/type/fiend/demon
aliases: ["Demon"]
---
# Demon
*Source: Plane Shift: Ixalan p. 36*  

Resembling twisted bats, the demons of Ixalan are the spawn of a bat-god, the source of all darkness. While the sun's aspects include destruction as well as creation and growth, the demons represent stagnation and decay. The sun consumes in glorious fire; demons work through rot and degeneration. They are said to be active at night, when the sun is hidden, and their efforts are directed toward preventing the sun from rising again each morning. In the meantime, they spread plague and corruption across the land. The [vrock](2-Mechanics/CLI/bestiary/fiend/vrock.md) in the "Monster Manual" is a good representation of Ixalan's demons.

## Night Terrors

The legends of the Sun Empire are populated with the enemies of the sun—terrible monsters that threaten to devour its light and undo its work. Unfortunately for the people of Ixalan, these are not just creatures of legend but real monsters with supernatural power, lurking in the darkness of night and the shadows of ancient ruins and crypts.

## Statblock

```ad-statblock
title: Demon
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/PSX/Demon.webp#token)
*Large fiend (demon), Chaotic Evil*

- **Armor Class** 15 (natural armor)
- **Hit Points** 104 (`11d10 + 44`)
- **Speed** 40 ft., fly 60 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|17 (+3)|15 (+2)|18 (+4)| 8 (-1)|13 (+1)| 8 (-1)|

- **Proficiency Bonus** +3
- **Saving Throws** Dexterity +5, Wisdom +4, Charisma +2
- **Skills** ⏤
- **Senses** darkvision 120 ft., passive Perception 11
- **Damage Resistances** cold; fire; lightning; bludgeoning, piercing, slashing from nonmagical attacks
- **Damage Immunities** poison
- **Condition Immunities** [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** Abyssal, telepathy 120 ft.
- **Challenge** 6

## Traits

***Magic Resistance.*** The demon has advantage on saving throws against spells and other magical effects.

## Actions

***Multiattack.*** The demon makes two attacks: one with its beak and one with its talons.

***Beak.*** *Melee Weapon Attack:* `dice:1d20+6|noform|text(+6)` to hit, reach 5 ft., one target. *Hit:* `dice:2d6+3|noform|avg|text(10)` (`2d6 + 3`) piercing damage.

***Talons.*** *Melee Weapon Attack:* `dice:1d20+6|noform|text(+6)` to hit, reach 5 ft., one target. *Hit:* `dice:2d10+3|noform|avg|text(14)` (`2d10 + 3`) slashing damage.

***Spores (Recharge 6).*** A 15-foot-radius cloud of toxic spores extends out from the demon. The spores spread around corners. Each creature in that area must succeed on a DC 14 Constitution saving throw or become [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned). While [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned) in this way, a target takes `dice:1d10|noform|avg|text(5)` (`1d10`) poison damage at the start of each of its turns. A target can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success. Emptying a vial of holy water on the target also ends the effect on it.

***Stunning Screech (1/Day).*** The demon emits a horrific screech. Each creature within 20 feet of it that can hear it and that isn't a demon must succeed on a DC 14 Constitution saving throw or be [stunned](2-Mechanics/CLI/rules/conditions.md#Stunned) until the end of the demon's next turn.
```
^statblock