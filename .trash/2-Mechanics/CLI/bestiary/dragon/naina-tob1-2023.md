---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/tob1-2023
- monster/cr/11
- monster/environment/farmland
- monster/environment/urban
- monster/size/large
- monster/type/dragon/shapechanger
aliases: ["Naina"]
---
# Naina
*Source: Tome of Beasts 1 (2023 Edition) p. 282*  

*This draconic creature is plumed and scaled in glittering, multicolored hues.*

## Dragons in Human Form

These minor dragons can take the shape of wise, old, human women. They retain full use of their sorcerous powers in their humanoid forms, and they can retain that form indefinitely.

## Difficult to Spot

A naina shapeshifted into human form is nearly impossible to spot as anything but human unless she makes a mistake that gives away her true nature. This seldom happens. Draconic roars, a flash of scales, a fondness for raw meat, and a flash of wrathful dragon breath are the most common tells.

## Hunted by Rumor

When rumors of a naina circulate, any woman who is a stranger may be persecuted, ostracized, or even tortured unless she can prove that she's entirely human.

## Statblock

```ad-statblock
title: Naina
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ToB1-2023/Naina.webp#token)
*Large dragon (shapechanger), Lawful Evil*

- **Armor Class** 17 (natural armor)
- **Hit Points** 231 (`22d10 + 110`)
- **Speed** 40 ft., fly 120 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|20 (+5)|16 (+3)|21 (+5)|15 (+2)|18 (+4)|18 (+4)|

- **Proficiency Bonus** +4
- **Saving Throws** Dexterity +7, Constitution +9, Wisdom +8, Charisma +8
- **Skills** Deception +8, Insight +8, Perception +8, Persuasion +8
- **Senses** magic. the naina senses magic within 120 feet of her at will. this trait otherwise works like the detect magic spell but isn't itself magical., passive Perception 18
- **Damage Resistances** bludgeoning, piercing, slashing from nonmagical attacks
- **Damage Immunities** poison
- **Condition Immunities** [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned), [unconscious](2-Mechanics/CLI/rules/conditions.md#Unconscious)
- **Languages** Common, Draconic, Sylvan
- **Challenge** 11

***Spellcasting.*** The naina casts one of the following spells, requiring no material components and using Charisma as the spellcasting ability (spell save DC 16):

**At will**: [charm person](2-Mechanics/CLI/spells/charm-person.md), [dancing lights](2-Mechanics/CLI/spells/dancing-lights.md), [silent image](2-Mechanics/CLI/spells/silent-image.md)

**1/day each**: [dimension door](2-Mechanics/CLI/spells/dimension-door.md), [dominate person](2-Mechanics/CLI/spells/dominate-person.md)

**3/day each**: [dispel magic](2-Mechanics/CLI/spells/dispel-magic.md), [hypnotic pattern](2-Mechanics/CLI/spells/hypnotic-pattern.md), [invisibility](2-Mechanics/CLI/spells/invisibility.md)

## Actions

***Multiattack.*** The naina makes one Bite attack and two Claw attacks, or she makes three Slam attacks.

***Bite (True Form Only).*** *Melee Weapon Attack:* `dice:1d20+9|noform|text(+9)` to hit, reach 5 ft., one target. *Hit:* `dice:3d12+5|noform|avg|text(24)` (`3d12 + 5`) piercing damage.

***Claw (True Form Only).*** *Melee Weapon Attack:* `dice:1d20+9|noform|text(+9)` to hit, reach 5 ft., one target. *Hit:* `dice:3d12+5|noform|avg|text(24)` (`3d12 + 5`) slashing damage.

***Slam (Humanoid Form Only).*** *Melee Weapon Attack:* `dice:1d20+9|noform|text(+9)` to hit, reach 5 ft., one target. *Hit:* `dice:4d8+5|noform|avg|text(23)` (`4d8 + 5`) bludgeoning damage.

***Breath Weapons (Recharge 5-6).*** The naina uses one of the following breath weapons:

- **Poison Breath.** The naina exhales poison breath in a 60-foot cone. Each creature in the area must make a DC 17 Constitution saving throw. On a failure, a creature takes `dice:9d8|noform|avg|text(40)` (`9d8`) poison damage and is [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned) for 1 minute. On a success, a creature takes half the damage and isn't [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned). The creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.  
- **Paralysis Breath.** The naina exhales paralyzing breath in a 30-foot cone. Each creature in that area must succeed on a DC 17 Constitution saving throw or be [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed) for 1 minute. The creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.  
- **Sleep Breath.** The naina exhales sleep gas around it. Each creature within 20 feet of the naina must succeed on a DC 17 Constitution saving throw or fall [unconscious](2-Mechanics/CLI/rules/conditions.md#Unconscious) for 10 minutes. This effect ends for a creature if the creature takes damage or another creature uses an action to wake it.  

## Bonus Actions

***Change Shape.*** The naina transforms into a Medium Humanoid or back into her true form, which is a Dragon. Her statistics, other than her size, are the same in each form. Any equipment she is wearing or carrying isn't transformed. It reverts to its true from if she dies.
```
^statblock

## Environment

farmland, urban