---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/tob1-2023
- monster/cr/5
- monster/environment/underdark
- monster/environment/urban
- monster/size/small
- monster/type/humanoid/kobold
aliases: ["Kobold Chieftain"]
---
# Kobold Chieftain
*Source: Tome of Beasts 1 (2023 Edition) p. 245*  

*This small, draconic humanoid struts as though it were ten feet tall. It wears the gilded skull of a small dragon as a helmet, and its beady eyes gleam out through the skull's sockets. It hefts its spear and shield and lets out a blood-curdling shriek, signaling the attack*.

While most kobolds are scuttling scavengers or pathetic sycophants, a few carry a spark of draconic nobility that can't be ignored. These few forge their tribes into forces to be reckoned with, rising to the rank of chieftain. A kobold chieftain stands proud, clad in war gear of fine quality and good repair. Their weapons are tended by the tribe's tinkerers, particularly evident in their springspike shields.

## Living Legend

A kobold chieftain is more than a leader, it is a symbol of the tribe's greatness. The strongest, most cunning, most ruthless of a kobold tribe embodies their connection to the revered dragons. When a chieftain sounds the call to battle, the kobolds meld into a fearless, deadly force.

## Statblock

```ad-statblock
title: Kobold Chieftain
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ToB1-2023/Kobold%20Chieftain.webp#token)
*Small humanoid (kobold), Lawful Evil*

- **Armor Class** 16 ([studded leather](2-Mechanics/CLI/items/studded-leather-armor.md), [shield](2-Mechanics/CLI/items/shield.md))
- **Hit Points** 110 (`20d6 + 40`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|18 (+4)|14 (+2)|14 (+2)|11 (+0)|13 (+1)|14 (+2)|

- **Proficiency Bonus** +3
- **Saving Throws** Dexterity +5, Charisma +5
- **Skills** Intimidation +6, Stealth +4
- **Senses** darkvision 60 ft., passive Perception 11
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened)
- **Languages** Common, Draconic
- **Challenge** 5

## Traits

***Brute.*** A melee weapon deals one extra die of its damage when the chieftain hits with it (included in the attack).

***Chieftain's Presence.*** Dragons and kobolds within 30 feet of the chieftain can't be [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed) or [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened).

***Pack Tactics.*** The kobold chieftain has advantage on attack rolls against a creature if at least one of the chieftain's allies is within 5 feet of the creature and the ally isn't [incapacitated](2-Mechanics/CLI/rules/conditions.md#Incapacitated).

***Sunlight Sensitivity.*** While in sunlight, the kobold chieftain has disadvantage on attack rolls, as well as on Wisdom ([Perception](2-Mechanics/CLI/rules/skills.md#Perception)) checks that rely on sight.

## Actions

***Multiattack.*** The kobold makes three Spear or Shortbow attacks.

***Spear.*** *Melee or Ranged Weapon Attack:* `dice:1d20+6|noform|text(+6)` to hit, reach 5 ft. or range 20/60 ft., one target. *Hit:* `dice:2d6+4|noform|avg|text(11)` (`2d6 + 4`) piercing damage, or `dice:2d8+4|noform|avg|text(13)` (`2d8 + 4`) piercing damage if used with two hands to make a melee attack.

***Shortbow.*** *Ranged Weapon Attack:* `dice:1d20+4|noform|text(+4)` to hit, range 80/320 ft., one target. *Hit:* `dice:1d6+2|noform|avg|text(5)` (`1d6 + 2`) piercing damage plus `dice:2d6|noform|avg|text(7)` (`2d6`) poison damage, and the target must succeed on a DC 12 Constitution saving throw or be [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned) for 1 minute. A [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned) creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.

***Inspiring Shriek (Recharge after Short or Long Rest).*** The kobold chieftain shrieks a draconic battle cry. Each creature that isn't a dragonborn or kobold within 30 feet of the chieftain must succeed on a DC 14 Wisdom saving throw or be [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened) for 1 minute. A [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened) creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.

Each dragonborn and kobold within 30 feet of the chieftain is inspired for 1 minute. Whenever an inspired creature makes an attack roll or saving throw, the creature can roll a `dice:d4|noform|avg` (`d4`) and add the number rolled to the attack roll or saving throw.

## Reactions

***Springspike Shield.*** When the kobold chieftain is wielding its shield and is hit by a melee attack within 5 feet of it, the chieftain can fire one of its shield spikes at the attacker. The attacker takes `dice:2d4|noform|avg|text(5)` (`2d4`) piercing damage.
```
^statblock

## Environment

underdark, urban