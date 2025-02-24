---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/tob1-2023
- monster/cr/7
- monster/environment/any
- monster/environment/urban
- monster/size/medium
- monster/type/humanoid/elf
aliases: ["Shadow Fey Enchantress"]
---
# Shadow Fey Enchantress
*Source: Tome of Beasts 1 (2023 Edition) p. 160*  

*This ravishing shadow fey woman moves with alluring grace. Her voice rings like a bell, and in her hearing, worldly cares and sorrows melt away.*

Beyond even great physical beauty, the sheer presence of a shadow fey enchantress can lay the most stalwart foes low. Almost universally female, Enchantresses are beautiful beyond compare.

## Enchanting Shadows

Enchantresses are also powerful spellcasters who infuse their words and manner with the beguiling power of shadow to turn enemies against one another with a few words and a deadly smile. They augment the force of their minds with fey-wrought blades, infusing their weapons with power that shreds their victims' psyche as well as their flesh.

## Statblock

```ad-statblock
title: Shadow Fey Enchantress
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ToB1-2023/Shadow%20Fey%20Enchantress.webp#token)
*Medium humanoid (elf), Lawful Evil*

- **Armor Class** 16 ([breastplate](2-Mechanics/CLI/items/breastplate.md))
- **Hit Points** 123 (`19d8 + 38`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|10 (+0)|15 (+2)|14 (+2)|12 (+1)|17 (+3)|18 (+4)|

- **Proficiency Bonus** +3
- **Saving Throws** Dexterity +5, Wisdom +6, Charisma +7
- **Skills** Arcana +4, Deception +7, Perception +6, Persuasion +7, Stealth +5
- **Senses** darkvision 60 ft., passive Perception 16
- **Languages** Common, Elvish, Umbral
- **Challenge** 7

## Traits

***Fey Ancestry.*** The enchantress has advantage on saving throws against being [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), and magic can't put her to sleep.

***Phrenic Weapons.*** The enchantress's weapon attacks are magical. When she hits with any weapon, the weapon deals an extra `dice:4d6|noform|avg` (`4d6`) psychic damage (included in the attack).

***Sunlight Sensitivity.*** While in sunlight, the shadow fey has disadvantage on attack rolls, as well as on Wisdom ([Perception](2-Mechanics/CLI/rules/skills.md#Perception)) checks that rely on sight.

***Spellcasting.*** The enchantress casts one of the following spells, requiring no material components and using Charisma as the spellcasting ability (spell save DC 15):

**At will**: [command](2-Mechanics/CLI/spells/command.md), [message](2-Mechanics/CLI/spells/message.md)

**1/day**: [confusion](2-Mechanics/CLI/spells/confusion.md), [dominate person](2-Mechanics/CLI/spells/dominate-person.md), [greater invisibility](2-Mechanics/CLI/spells/greater-invisibility.md), [hold monster](2-Mechanics/CLI/spells/hold-monster.md), [phantasmal killer](2-Mechanics/CLI/spells/phantasmal-killer.md)

**3/day**: [charm person](2-Mechanics/CLI/spells/charm-person.md), [enthrall](2-Mechanics/CLI/spells/enthrall.md), [fear](2-Mechanics/CLI/spells/fear.md), [hold person](2-Mechanics/CLI/spells/hold-person.md), [hypnotic pattern](2-Mechanics/CLI/spells/hypnotic-pattern.md)

## Actions

***Multiattack.*** The shadow fey enchantress makes two Rapier attacks. She can replace one attack with a use of Spellcasting.

***Rapier.*** *Melee Weapon Attack:* `dice:1d20+5|noform|text(+5)` to hit, reach 5 ft., one target. *Hit:* `dice:1d8+2|noform|avg|text(6)` (`1d8 + 2`) piercing damage plus `dice:4d6|noform|avg|text(14)` (`4d6`) psychic damage.

***Shadow Bolt.*** *Ranged Spell Attack:* `dice:1d20+7|noform|text(+7)` to hit, range 120 ft., one target. *Hit:* `dice:2d6+4|noform|avg|text(11)` (`2d6 + 4`) cold damage plus `dice:2d8|noform|avg|text(9)` (`2d8`) necrotic damage.

***Beguiling Whispers (Recharge 5-6).*** The enchantress speaks sweet words to a creature she can see within 60 feet of her and that can hear her. The creature must succeed on a DC 15 Charisma saving throw or be [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed) for 1 minute. While [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed) in this way, the creature has disadvantage on Wisdom and Charisma saving throws against spells cast by the enchantress.

***Leadership (Recharges after a Short or Long Rest).*** For 1 minute, the enchantress can utter a special command or warning whenever a nonhostile creature that she can see within 30 feet of her makes an attack roll or a saving throw. The creature can add a `dice:d4|noform|avg` (`d4`) to its roll, provided it can hear and understand the enchantress. A creature can benefit from only one Leadership die at a time. This effect ends if the enchantress is [incapacitated](2-Mechanics/CLI/rules/conditions.md#Incapacitated).

## Bonus Actions

***Shadow Traveler (3/Day).*** While in shadows, dim light, or darkness, the shadow fey disappears into the darkness and reappears in an unoccupied space it can see within 30 feet. A tendril of inky smoke appears at the origin and destination when it uses this bonus action.
```
^statblock

## Environment

any, urban