---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/psz
- monster/cr/5
- monster/size/large
- monster/type/celestial
aliases: ["Felidar"]
---
# Felidar
*Source: Plane Shift: Zendikar p. 23*  

Standing fully ten feet high at the shoulder, the great cats called felidars are noble, fierce beasts charged with white mana. Felidars consent to be ridden only by knights they consider virtuous. The crystalline horns rising from a hard plate on their foreheads glow with white or golden light when they spring into battle, sometimes brightly enough to blind their foes.

In game terms, a felidar is similar to a [unicorn](2-Mechanics/CLI/bestiary/celestial/unicorn.md), with changes that reflect its feline nature.

```ad-statblock
title: Felidar
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/PSZ/Felidar.webp#token)
*Large celestial, Lawful Good*

- **Armor Class** 12
- **Hit Points** 67 (`9d10 + 18`)
- **Speed** 50 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|18 (+4)|14 (+2)|15 (+2)|11 (+0)|17 (+3)|16 (+3)|

- **Proficiency Bonus** +3
- **Saving Throws** ⏤
- **Skills** ⏤
- **Senses** darkvision 60 ft., passive Perception 13
- **Damage Immunities** poison
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** Celestial, telepathy 60 ft.
- **Challenge** 5

## Traits

***Pounce.*** If the felidar moves at least 20 feet straight toward a creature and then hits it with a claws attack on the same turn, the target must succeed on a DC 15 Strength saving throw or be knocked [prone](2-Mechanics/CLI/rules/conditions.md#Prone). If the target is [prone](2-Mechanics/CLI/rules/conditions.md#Prone), the felidar can make one bite attack against it as a bonus action.

***Magic Resistance.*** The felidar has advantage on saving throws against spells and other magical effects.

***Magic Weapons.*** The felidar's weapon attacks are magical.

***Innate Spellcasting.*** The felidar's innate spellcasting ability is Charisma (spell save DC 14). The felidar can innately cast the following spells, requiring no components:

**At will**: [detect evil and good](2-Mechanics/CLI/spells/detect-evil-and-good.md), [light](2-Mechanics/CLI/spells/light.md), [thaumaturgy](2-Mechanics/CLI/spells/thaumaturgy.md)

**1/day each**: [calm emotions](2-Mechanics/CLI/spells/calm-emotions.md), [daylight](2-Mechanics/CLI/spells/daylight.md), [dispel evil and good](2-Mechanics/CLI/spells/dispel-evil-and-good.md)

## Actions

***Multiattack.*** The felidar makes two attacks with its claws.

***Claws.*** *Melee Weapon Attack:* `dice:1d20+7|noform|text(+7)` to hit, reach 5 ft., one target. *Hit:* `dice:2d6+4|noform|avg|text(11)` (`2d6 + 4`) slashing damage.

***Bite.*** *Melee Weapon Attack:* `dice:1d20+7|noform|text(+7)` to hit, reach 5 ft., one target. *Hit:* `dice:1d8+4|noform|avg|text(8)` (`1d8 + 4`) piercing damage.

***Healing Touch (3/Day).*** The felidar touches another creature with its horns. The target magically regains `dice:2d8+2|noform|avg|text(11)` (`2d8 + 2`) hit points. In addition, the touch removes all diseases and neutralizes all poisons afflicting the target

***Teleport (1/Day).*** The felidar magically teleports itself and up to three willing creatures it can see within 5 feet of it, along with any equipment they are wearing or carrying, to a location the felidar is familiar with, up to 1 mile away.

## Legendary Actions

***Claws.*** The felidar makes one attack with its claws.

***Shimmering Shield (Costs 2 Actions).*** The felidar creates a shimmering magical field around itself or another creature it can see within 60 feet of it. The target gains a +2 bonus to AC until the end of the felidar's next turn.

***Heal Self (Costs 3 Actions).*** The felidar magically regains `dice:2d8+2|noform|avg|text(11)` (`2d8 + 2`) hit points.
```
^statblock