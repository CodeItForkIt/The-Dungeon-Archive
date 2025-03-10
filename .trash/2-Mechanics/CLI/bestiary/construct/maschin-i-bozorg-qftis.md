---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/qftis
- monster/cr/8
- monster/size/large
- monster/type/construct
aliases: ["Maschin-i-Bozorg"]
---
# Maschin-i-Bozorg
*Source: Quests from the Infinite Staircase p. 207*  

The kagu-svirfneblin's most prized invention is the maschin-i-bozorg: a dome-shaped, steam-powered battle construct propelled by a multitude of wheels along its flat underside. Maschin-i-bozorgs typically act as guardians and sentries, tirelessly patrolling the sites they're assigned to protect. Each machine obeys the commands of its creator.

A machin-i-bozorg can roll over its enemies to crush them with its immense weight. It can also fire poison darts with deadly precision, jab creatures with similar darts attached to extendable arms that retract inside its body, and spray jets of scalding steam to fend off intruders.

```ad-statblock
title: Maschin-i-Bozorg
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/QftIS/Maschin-i-Bozorg.webp#token)
*Large construct, Unaligned*

- **Armor Class** 17 (natural armor)
- **Hit Points** 94 (`9d10 + 45`)
- **Speed** 20 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|18 (+4)|16 (+3)|20 (+5)| 2 (-4)|10 (+0)| 1 (-5)|

- **Proficiency Bonus** +3
- **Saving Throws** ⏤
- **Skills** ⏤
- **Senses** darkvision 120 ft., passive Perception 10
- **Damage Immunities** poison, psychic
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [deafened](2-Mechanics/CLI/rules/conditions.md#Deafened), [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened), [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned), [unconscious](2-Mechanics/CLI/rules/conditions.md#Unconscious)
- **Languages** understands Gnomish but can't speak
- **Challenge** 8

## Traits

***Overheat.*** When the maschin-i-bozorg is reduced to 0 hit points, its power source overloads, briefly superheating its outer shell. Each creature within 10 feet of the maschin-i-bozorg must make a DC 16 Constitution saving throw, taking `dice:2d6|noform|avg|text(7)` (`2d6`) fire damage on a failed save or half as much damage on a successful one.

## Actions

***Multiattack.*** The maschin-i-bozorg makes two Poison Jab attacks.

***Poison Jab.*** *Melee or Ranged Weapon Attack:* `dice:1d20+6|noform|text(+6)` to hit, reach 5 ft. or range 30/120 ft., one target. *Hit:* `dice:4d4+3|noform|avg|text(13)` (`4d4 + 3`) piercing damage, and the target must succeed on a DC 16 Constitution saving throw or have the [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned) condition for 1 minute. The target can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.

***Steam Jet (Recharge 5-6).*** The maschin-i-bozorg emits scalding steam in a 30-foot cone. Each creature in that area must make a DC 16 Constitution saving throw, taking `dice:8d6|noform|avg|text(28)` (`8d6`) fire damage on a failed save or half as much damage on a successful one.

## Bonus Actions

***Crushing Stride.*** The maschin-i-bozorg moves up to its speed in a straight line. During this movement, it can enter Medium and smaller creatures' spaces. A creature whose space the maschin-i-bozorg enters must make a DC 15 Dexterity saving throw. On a successful save, the creature is pushed to the nearest unoccupied space out of the maschin-i-bozorg's path. On a failed save, the creature takes `dice:3d6|noform|avg|text(10)` (`3d6`) bludgeoning damage and has the [prone](2-Mechanics/CLI/rules/conditions.md#Prone) condition.

If the maschin-i-bozorg remains in the [prone](2-Mechanics/CLI/rules/conditions.md#Prone) creature's space, the creature also has the [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained) condition until it's no longer in the same space as the maschin-i-bozorg. While [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained) in this way, the creature, or another creature within 5 feet of it, can use its action to make a DC 15 Strength ([Athletics](2-Mechanics/CLI/rules/skills.md#Athletics)) check. On a successful check, the creature is shunted to an unoccupied space of its choice within 5 feet of the maschin-i-bozorg.
```
^statblock