---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/tob1-2023
- monster/cr/10
- monster/environment/farmland
- monster/environment/urban
- monster/size/medium
- monster/type/fiend/demon
aliases: ["Rubezahl Demon"]
---
# Rubezahl Demon
*Source: Tome of Beasts 1 (2023 Edition) p. 87*  

*A pair of immense, branching antlers arches above this man's coldly gleaming eyes, and wicked claws tip his long fingers.*

## Assume Mortal Form

Rubezahls are capricious creatures with an affinity for weather, particularly lightning. Like the ever-changing weather, they are driven by constantly shifting motivations and mannerisms. They are consummate tricksters who delight in taking the form of innocuous mortals, like traveling monks, tinkers, or lost merchants. They love to play the friend with their nearly undetectable lies, slipping into the confidence of unsuspecting mortals before murdering them.

## Counting Demons

Rubezahls have a weakness, however. They are known as counting demons, and a savvy mortal who knows its nature can confound one with groups of objects: a handful of coins, a basket of apples, even a bed of flowers. If the objects are clearly pointed out to the rubezahl, the creature becomes distracted until it counts each item in the group. Unfortunately for mortals, rebezahls can count startlingly fast; even a mound of gravel takes no more than a few moments for a rubezahl to assess. Rubezahl loathe being compelled this way, and they are driven to annihilate any mortal bold enough to exploit this weakness.

## Statblock

```ad-statblock
title: Rubezahl Demon
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ToB1-2023/Rubezahl%20Demon.webp#token)
*Medium fiend (demon), Chaotic Evil*

- **Armor Class** 15 (natural armor)
- **Hit Points** 136 (`21d8 + 42`)
- **Speed** 50 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|20 (+5)|15 (+2)|14 (+2)|11 (+0)|12 (+1)|18 (+4)|

- **Proficiency Bonus** +4
- **Saving Throws** Dexterity +6, Constitution +6, Wisdom +5
- **Skills** Deception +8, Perception +5, Survival +5
- **Senses** blindsight 10 ft., darkvision 120 ft., passive Perception 15
- **Damage Resistances** cold; fire; bludgeoning, piercing, slashing from nonmagical attacks
- **Damage Immunities** lightning, poison, thunder
- **Condition Immunities** [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned), [stunned](2-Mechanics/CLI/rules/conditions.md#Stunned)
- **Languages** Abyssal, Common, telepathy 120 ft.
- **Challenge** 10

## Traits

***Counting Compulsion.*** If a creature uses an action to point out an ordered group of objects that the rubezahl can see, such as a pile of gravel, the demon is compelled to count the entire group. Until the end of its next turn, the rubezahl has disadvantage on attack rolls and ability checks, and it can't take reactions. Once it has counted a given group of objects, it can't be compelled to count those objects again.

***False Tongue.*** The rubezahl has advantage on Charisma ([Deception](2-Mechanics/CLI/rules/skills.md#Deception)) checks. In addition, magical attempts to discern lies always report that the rubezahl's words are true, and it can't be magically forced to tell the truth.

***Magic Resistance.*** The rubezahl has advantage on saving throws against spells and other magical effects.

***Spellcasting.*** The rubezahl casts one of the following spells, requiring no material components and using Charisma as the spellcasting ability (spell save DC 16):

**At will**: [disguise self](2-Mechanics/CLI/spells/disguise-self.md), [fog cloud](2-Mechanics/CLI/spells/fog-cloud.md)

**1/day**: [control weather](2-Mechanics/CLI/spells/control-weather.md) (as an action)

**3/day each**: [gust of wind](2-Mechanics/CLI/spells/gust-of-wind.md), [sleet storm](2-Mechanics/CLI/spells/sleet-storm.md)

## Actions

***Multiattack.*** The rubezahl makes one Gore attack and two Claw attacks.

***Claw.*** *Melee Weapon Attack:* `dice:1d20+9|noform|text(+9)` to hit, reach 5 ft., one target. *Hit:* `dice:3d6+5|noform|avg|text(15)` (`3d6 + 5`) slashing damage plus `dice:2d6|noform|avg|text(7)` (`2d6`) lightning damage.

***Gore.*** *Melee Weapon Attack:* `dice:1d20+9|noform|text(+9)` to hit, reach 5 ft., one target. *Hit:* `dice:3d8+5|noform|avg|text(18)` (`3d8 + 5`) piercing damage, and the target creature must succeed on a DC 16 Strength saving throw or be knocked [prone](2-Mechanics/CLI/rules/conditions.md#Prone).

***Thunderstrike (Recharge 5-6).*** The rubezahl calls a sizzling bolt of lightning out of the sky, or from the air if underground or indoors, to strike a point the rubezahl can see within 150 feet of it. Each creature within 20 feet of that point must make a DC 16 Dexterity saving throw. On a failure, the creature takes `dice:8d8|noform|avg|text(36)` (`8d8`) lightning damage and is [stunned](2-Mechanics/CLI/rules/conditions.md#Stunned) until the end of its next turn. On a success, the creature takes half the damage and isn't [stunned](2-Mechanics/CLI/rules/conditions.md#Stunned).
```
^statblock

## Environment

farmland, urban