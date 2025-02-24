---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/ghloe
- monster/cr/3
- monster/size/medium
- monster/type/humanoid/any-race
- monster/type/humanoid/elemental
aliases: ["Panjaian Ilharan"]
---
# Panjaian Ilharan
*Source: Grim Hollow: Lairs of Etharis p. 96*  

> [!quote]  
> 
> Instilled with the power of the Primordials, panjaians are literal forces of nature.

## Salvage

Someone who has proficiency in [Medicine](2-Mechanics/CLI/rules/skills.md#Medicine) can attempt a DC 13 Wisdom ([Medicine](2-Mechanics/CLI/rules/skills.md#Medicine)) check to remove a panjaian's heart intact. Somebody who has proficiency with alchemist's supplies can treat the heart with reagents worth 100 gp in a process that takes 3 days and a successful DC 13 Intelligence or Wisdom check. This process, if successful, hardens the heart into an elemental gem: blue sapphire for ilharan, yellow diamond for citrolachi, red corundum for morakeshi, and emerald for alondon. What this process creates when used on the heart of a panjaian gormadraugon is unknown. History records no such act. (A gem of brightness is a good possibility, however.)

## Lore

- **DC 13 Intelligence ([Religion](2-Mechanics/CLI/rules/skills.md#Religion)).** Panjaians first appeared near the end of the Primordial's war with the gods. Some scholars believe if panjaians had been created earlier, it might have changed the conflict's outcome.  
- **DC 13 Intelligence ([Nature](2-Mechanics/CLI/rules/skills.md#Nature)).** Every panjaian has an affinity for the element of their Primordial patron. This affinity manifests in resistances, control over the element, and the ability to wield that element as a weapon.  

## Statblock

```ad-statblock
title: Panjaian Ilharan
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/GHLoE/Panjaian%20Ilharan.webp#token)
*Medium humanoid (any race, elemental), Any alignment*

- **Armor Class** 15 (natural armor)
- **Hit Points** 55 (`10d8 + 10`)
- **Speed** 30 ft., fly 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|10 (+0)|16 (+3)|13 (+1)|12 (+1)|15 (+2)|13 (+1)|

- **Proficiency Bonus** +2
- **Saving Throws** Dexterity +5
- **Skills** Acrobatics +5, Deception +3, Perception +4, Sleight of Hand +5, Stealth +5
- **Senses** darkvision 60 ft., passive Perception 14
- **Damage Resistances** lightning, thunder
- **Languages** Primordial and two other languages
- **Challenge** 3

## Traits

***Returning Wind.*** The panjaian ilharan can take a bonus action to choose up to four objects it can see within 60 feet of it. These objects can't be carried or worn by another creature, and they can weigh up to 5 pounds combined. Those objects fly up to 60 feet toward the ilharan, delivered into its hands or open containers, such as sheathes, once within 5 feet.

***Innate Spellcasting.*** The panjaian ilharan's innate spellcasting ability is Wisdom (spell save DC 12). It can innately cast the following spells, requiring no material components:

**At will**: [mage hand](2-Mechanics/CLI/spells/mage-hand.md) (the hand is invisible)

**3/day each**: [gust of wind](2-Mechanics/CLI/spells/gust-of-wind.md), [invisibility](2-Mechanics/CLI/spells/invisibility.md) (self only)

## Actions

***Multiattack.*** The panjaian ilharan makes four dagger attacks. It can draw the daggers as part of this action.

***Dagger.*** *Melee or Ranged Weapon Attack:* `dice:1d20+5|noform|text(+5)` to hit, reach 5 ft. or range 20/60 ft., one target. *Hit:* `dice:1d4+3|noform|avg|text(5)` (`1d4 + 3`) piercing damage.

***Storm Wave (Recharge 5-6).*** The panjaian ilharan unleashes lightning, thunder, and strong wind in a 15-foot cone. Each creature in that area must make a DC 13 Constitution saving throw, taking `dice:2d4+1|noform|avg|text(6)` (`2d4 + 1`) lightning damage and `dice:2d4+1|noform|avg|text(6)` (`2d4 + 1`) thunder damage on a failed save, or half as much damage on a successful one. Those who fail the saving throw are also pushed up to 15 feet to the edge of the area.

***Gift of Flight (1/Day).*** The panjaian ilharan touches up to four willing creatures. Each target gains a flying speed of 30 feet for 1 hour. When the effect ends, the target descends at 60 feet per round for 1 minute, taking no falling damage and landing on its feet if on the ground after that minute.
```
^statblock