---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/tob1-2023
- monster/cr/1-8
- monster/environment/any
- monster/size/medium
- monster/type/undead
aliases: ["Shroud"]
---
# Shroud
*Source: Tome of Beasts 1 (2023 Edition) p. 327*  

*The translucent person calls out a name in a barely audible whisper.*

## Bitter Spirits

Shrouds are transitional creatures: remnants of wicked people who died but refuse to rest in peace, yet have not grown strong enough to become shadows. They are aggressive enemies of all living creatures and the light that nurtures life. Shrouds blend naturally into darkness, but they stand out starkly in bright light.

## Thin Outlines

Shrouds look like flickering shadowy outlines of the people they were before they died, retaining the same height and body type.

## Repetitive Speech

Shrouds cannot converse, but they occasionally can be heard cruelly whispering a name, term, or phrase over and over again: something that must have had meaning to them in life.

## Statblock

```ad-statblock
title: Shroud
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ToB1-2023/Shroud.webp#token)
*Medium undead, Neutral Evil*

- **Armor Class** 11
- **Hit Points** 13 (`3d8`)
- **Speed** 0 ft., fly 30 ft. (hover)

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
| 4 (-3)|13 (+1)|10 (+0)| 2 (-4)|10 (+0)| 8 (-1)|

- **Proficiency Bonus** +2
- **Saving Throws** ⏤
- **Skills** Stealth +3
- **Senses** darkvision 60 ft., passive Perception 10
- **Damage Vulnerabilities** radiant
- **Damage Resistances** acid; cold; fire; lightning; thunder; bludgeoning, piercing, slashing from nonmagical attacks
- **Damage Immunities** necrotic, poison
- **Condition Immunities** [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened), [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled), [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed), [petrified](2-Mechanics/CLI/rules/conditions.md#Petrified), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned), [prone](2-Mechanics/CLI/rules/conditions.md#Prone), [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained)
- **Languages** Common
- **Challenge** 1/8

## Traits

***Amorphous.*** The shroud can move through a space as narrow as 1 inch wide without squeezing.

***Shadow Evolution.*** If the shroud deals at least 12 necrotic damage to a creature that isn't a Construct or Undead in 1 minute or less, the shroud transforms into a shadow at the start of the turn after it last dealt damage. It uses the statistics of the shadow, except it reduces the shadow's hp by an amount equal to the damage the shroud took before it transformed.

***Sunlight Weakness.*** While in sunlight, the shroud has disadvantage on attack rolls, ability checks, and saving throws.

***Undead Nature.*** The shroud doesn't require air, food, drink, or sleep.

## Actions

***Strength Drain.*** *Melee Weapon Attack:* `dice:1d20+3|noform|text(+3)` to hit, reach 5 ft., one creature. *Hit:* `dice:1d4+1|noform|avg|text(3)` (`1d4 + 1`) necrotic damage, and the target has disadvantage on weapon attacks that use Strength until the end of its next turn. If a non-evil humanoid dies from this attack, a new shroud rises from the corpse `dice:1d4|noform|avg` (`1d4`) hours later.

## Bonus Actions

***Shadow Stealth.*** While in dim light or darkness, the shroud takes the Hide action.
```
^statblock

## Environment

any