---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/cos
- monster/cr/6
- monster/size/medium
- monster/type/construct
aliases: ["Strahd's Animated Armor"]
---
# Strahd's Animated Armor
*Source: Curse of Strahd p. 227*  

The armor that Strahd wore into battle when he was alive lives on today as a headless, animated suit of plate armor. The armor is painted burgundy and adorned with golden angelic motifs.

## Thing of Evil

Strahd imbued his automaton with a sliver of his being, bequeathing unto his armor a malevolence not found in most animated objects. He also fortified his armor and placed a number of permanent spell effects on it to make the armor a better castle defender.

The armor understands Common but obeys only the commands of its master.

## Statblock

```ad-statblock
title: Strahd's Animated Armor
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/CoS/Strahd%27s%20Animated%20Armor.webp#token)
*Medium construct, Lawful Evil*

- **Armor Class** 21 (natural armor)
- **Hit Points** 112 (`15d8 + 45`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|17 (+3)|13 (+1)|16 (+3)| 9 (-1)|10 (+0)| 9 (-1)|

- **Proficiency Bonus** +3
- **Saving Throws** ⏤
- **Skills** Perception +3
- **Senses** blindsight 60 ft. (blind beyond this radius), passive Perception 13
- **Damage Resistances** cold, fire
- **Damage Immunities** lightning, poison
- **Condition Immunities** [blinded](2-Mechanics/CLI/rules/conditions.md#Blinded), [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [deafened](2-Mechanics/CLI/rules/conditions.md#Deafened), [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened), [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed), [petrified](2-Mechanics/CLI/rules/conditions.md#Petrified), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** understands Common but can't speak
- **Challenge** 6

## Traits

***Constructed Nature.*** An animated object doesn't require air, food, drink, or sleep.

The magic that animates an object is dispelled when the construct drops to 0 hit points. An animated object reduced to 0 hit points becomes inanimate and is too damaged to be of much use or value to anyone.

***Antimagic Susceptibility.*** The armor is [incapacitated](2-Mechanics/CLI/rules/conditions.md#Incapacitated) while in the area of an [antimagic field](2-Mechanics/CLI/spells/antimagic-field.md). If targeted by [dispel magic](2-Mechanics/CLI/spells/dispel-magic.md), the armor must succeed on a Constitution saving throw against the caster's spell save DC or fall [unconscious](2-Mechanics/CLI/rules/conditions.md#Unconscious) for 1 minute.

***False Appearance.*** While the armor remains motionless, it is indistinguishable from a normal suit of armor.

## Actions

***Multiattack.*** The armor makes two melee attacks or uses Shocking Bolt twice.

***Greatsword.*** *Melee Weapon Attack:* `dice:1d20+6|noform|text(+6)` to hit, reach 5 ft., one target. *Hit:* `dice:2d6+3|noform|avg|text(10)` (`2d6 + 3`) slashing damage plus `dice:1d6|noform|avg|text(3)` (`1d6`) lightning damage.

***Shocking Bolt.*** *Ranged Spell Attack:* `dice:1d20+4|noform|text(+4)` to hit (with advantage on the attack roll if the target is wearing armor made of metal), range 60 ft., one target. *Hit:* `dice:3d6|noform|avg|text(10)` (`3d6`) lightning damage.
```
^statblock