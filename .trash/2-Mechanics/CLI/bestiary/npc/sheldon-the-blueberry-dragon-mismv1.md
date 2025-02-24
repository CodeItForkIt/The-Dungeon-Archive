---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/mismv1
- monster/cr/7
- monster/size/large
- monster/type/dragon
aliases: ["Sheldon the Blueberry Dragon"]
---
# Sheldon the Blueberry Dragon
*Source: Misplaced Monsters: Volume 1 p. 14*  

> [!note]
> Created by Samuel B.

Sheldon is a friendly, good-natured dragon who collects and eats blueberries. When he's not attending parties, he lives in Wildspace. His body magically produces air, allowing him to thrive in a vacuum and create powerful gusts of wind. Sheldon uses the wind to knock down foes and propel himself farther than his wings can take him on their own.

```ad-statblock
title: Sheldon the Blueberry Dragon
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/MisMV1/Sheldon%20the%20Blueberry%20Dragon.webp#token)
*Large dragon, Neutral Good*

- **Armor Class** 16 (natural armor)
- **Hit Points** 142 (`15d10 + 60`)
- **Speed** 30 ft., fly 60 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|19 (+4)|13 (+1)|18 (+4)|17 (+3)|14 (+2)|16 (+3)|

- **Proficiency Bonus** +3
- **Saving Throws** Dexterity +4, Constitution +7, Intelligence +6
- **Skills** Acrobatics +7, Athletics +7, Performance +6
- **Senses** blindsight 30 ft., darkvision 120 ft., passive Perception 12
- **Damage Resistances** force, psychic
- **Languages** Common, Draconic, telepathy 120 ft.
- **Challenge** 7

## Traits

***Space Dweller.*** Sheldon can breathe normally in a vacuum.

***Spellcasting (Psionics).*** Sheldon casts one of the following spells, requiring no spell components and using Intelligence as the spellcasting ability (spell save DC 14):

**At will**: [light](2-Mechanics/CLI/spells/light.md), [mage hand](2-Mechanics/CLI/spells/mage-hand.md) (the hand is invisible)

**1/day each**: [dimension door](2-Mechanics/CLI/spells/dimension-door.md), [telekinesis](2-Mechanics/CLI/spells/telekinesis.md)

## Actions

***Multiattack.*** Sheldon makes either two Bite attacks, two Blueberry Fling attacks, or one of each.

***Bite.*** *Melee Weapon Attack:* `dice:1d20+7|noform|text(+7)` to hit, reach 5 ft., one target. *Hit:* `dice:1d6+4|noform|avg|text(7)` (`1d6 + 4`) piercing damage plus `dice:1d8|noform|avg|text(4)` (`1d8`) psychic damage.

***Blueberry Fling.*** *Ranged Weapon Attack:* `dice:1d20+7|noform|text(+7)` to hit, range 30 ft., one creature. *Hit:* `dice:2d6+4|noform|avg|text(11)` (`2d6 + 4`) blueberry damage.

***Jetstream Breath (Recharge 5-6).*** Sheldon exhales a line of magical wind that is 60 feet long and 5 feet wide. Each creature in that area must make a DC 15 Strength saving throw. On a failed save, the creature takes `dice:6d6|noform|avg|text(21)` (`6d6`) force damage, is pushed 15 feet away from Sheldon, and has the [prone](2-Mechanics/CLI/rules/conditions.md#Prone) condition. On a successful save, the creature takes half as much damage only.

## Bonus Actions

***Wind Dash (2/Day).*** Sheldon summons a powerful gust of wind and flies up to his speed. This movement doesn't provoke opportunity attacks. At the end of this movement, each creature within 5 feet of Sheldon must succeed on a DC 15 Strength saving throw or have the [prone](2-Mechanics/CLI/rules/conditions.md#Prone) condition, as the wind bursts around Sheldon.
```
^statblock