---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/tob1-2023
- monster/cr/18
- monster/environment/underwater
- monster/size/huge
- monster/type/dragon
aliases: ["Adult Sea Dragon"]
---
# Adult Sea Dragon
*Source: Tome of Beasts 1 (2023 Edition) p. 126*  

*This aquamarine dragon has a shark's head that tapers off into a sleek eel-like body. Its large fins double as wings.*

## Divine Dragons

Sea dragons are the children of the ocean and believe they are semi-divine beings, worthy of worship. Given their size and power, they might be right; certainly, they are often companions or steeds to gods of the sea. Despite the solemn duties the sea dragons invoke thanks to their lineage, they are extremely whimsical. While these immense creatures are playful, their games can shatter hulls and drown sailors. The sea dragons course through the waves with tangible joy as they hunt whales and entire schools of tuna.

## Shipwreck Art

Sea dragons love collecting treasure. They especially prize the sunken, treasure-filled hulls of ships lost to storm, battle, or their own handiwork. While they appreciate all wealth, they prefer hardy items that stand up to long exposure to sea water. Precious metals and gemstones add a dramatic luster to the dragon's lair when they catch stray beams of light. Sea dragons take more perishable treasures and place them on a reef-altar, to dissolve in the sea as a tithe to the sea gods.

## Sunken Memorials

A sea dragon's lair is littered with meticulously arranged ships consigned to the deeps. These wrecks are often artfully smashed to allow the treasures in the hold to spill out onto the sea floor. It may seem haphazard, but it displays a complex aesthetic that only other sea dragons can truly appreciate. Because they arrange these wrecks so carefully, a dragon notices immediately if its hoard is disturbed.

> [!note] Priests of Seggotan
> 
> Every sea dragon is devoted to the dragon god of the sea. As a result, many sea dragons use the innate spellcasting variant. Sea dragons favor spells that manipulate water or the weather, emulate storms, deal lightning or cold damage, divine the future, or conjure sea creatures to fight alongside the dragon.
^priests-of-seggotan

> [!note] Sea Dragons in Midgard
> 
> Sea dragons are the offspring of Seggotan, the dragon god of time and the sea. A sea dragon shares its god's idea that everything in the sea is the property of Seggotan, and they expect lesser beings to respect that truth. The sea dragons are among the most powerful allies of the Mharoti Empire, securing seaways and acting as a communion point for the tidal priests. Thankfully for the Empire's enemies, the most ancient sea dragons are too consumed with contemplation of time and their inscrutable duties in the depths of the ocean to make war.
^sea-dragons-in-midgard

## A Sea Dragon's Lair

Sea dragons dwell in lairs beneath the waves: ocean fissures and caves, lightless trenches full of strange rock formations, and sheltered reefs of cultivated coral. Whatever the place, it's dedicated to the worship of sea gods. Despite the draconic instinct for seclusion and protection when choosing a lair, sea dragons always choose lairs relatively close to humanoid trade routes and abundant supplies of fish.

The sky surrounding a sea dragon's lair is perpetually stormy, and the seas run high. If a captain is courageous, these high winds and swift-running currents can cut significant time off a voyage.

## Statblock

```ad-statblock
title: Adult Sea Dragon
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ToB1-2023/Adult%20Sea%20Dragon.webp#token)
*Huge dragon, Neutral Evil*

- **Armor Class** 19 (natural armor)
- **Hit Points** 275 (`22d12 + 132`)
- **Speed** 40 ft., fly 80 ft., swim 60 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|25 (+7)|10 (+0)|23 (+6)|17 (+3)|15 (+2)|19 (+4)|

- **Proficiency Bonus** +6
- **Saving Throws** Dexterity +6, Constitution +12, Wisdom +8, Charisma +10
- **Skills** Perception +14, Stealth +6
- **Senses** blindsight 60 ft., darkvision 120 ft., passive Perception 24
- **Damage Immunities** cold
- **Languages** Common, Draconic, Primordial
- **Challenge** 18

## Traits

***Amphibious.*** The dragon can breathe air and water.

***Legendary Resistance (3/Day).*** If the dragon fails a saving throw, it can choose to succeed instead.

***Siege Monster.*** The dragon deals double damage to objects and structures.

## Actions

***Multiattack.*** The dragon uses its Frightful Presence. It then makes one Bite attack and two Fin attacks.

***Bite.*** *Melee Weapon Attack:* `dice:1d20+13|noform|text(+13)` to hit, reach 10 ft., one target. *Hit:* `dice:2d10+7|noform|avg|text(18)` (`2d10 + 7`) piercing damage plus `dice:3d6|noform|avg|text(10)` (`3d6`) cold damage.

***Fin.*** *Melee Weapon Attack:* `dice:1d20+13|noform|text(+13)` to hit, reach 5 ft., one target. *Hit:* `dice:2d6+7|noform|avg|text(14)` (`2d6 + 7`) slashing damage.

***Tail.*** *Melee Weapon Attack:* `dice:1d20+13|noform|text(+13)` to hit, reach 15 ft., one target. *Hit:* `dice:2d8+7|noform|avg|text(16)` (`2d8 + 7`) bludgeoning damage.

***Frightful Presence.*** Each creature of the dragon's choice that is within 120 feet of the dragon and aware of it must succeed on a DC 18 Wisdom saving throw or become [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened) for 1 minute. A creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success. If a creature's saving throw is successful or the effect ends for it, the creature is immune to the dragon's Frightful Presence for the next 24 hours.

***Tidal Breath (Recharge 5-6).*** The dragon exhales a crushing wave of frigid seawater in a 60-foot cone. Each creature in that area must make a DC 20 Dexterity saving throw. On a failure, the creature takes `dice:6d10|noform|avg|text(33)` (`6d10`) bludgeoning damage and `dice:6d10|noform|avg|text(33)` (`6d10`) cold damage and is pushed up to 30 feet away from the dragon and knocked [prone](2-Mechanics/CLI/rules/conditions.md#Prone). On a success, the creature takes half the damage and isn't pushed or knocked [prone](2-Mechanics/CLI/rules/conditions.md#Prone).

## Legendary Actions

***Detect.*** The dragon makes a Wisdom ([Perception](2-Mechanics/CLI/rules/skills.md#Perception)) check.

***Tail Attack.*** The dragon makes a Tail attack.

***Wing Attack (Costs 2 Actions).*** The dragon beats its wings. Each creature within 10 feet of the dragon must succeed on a DC 21 Dexterity saving throw or take `dice:2d6+7|noform|avg|text(14)` (`2d6 + 7`) bludgeoning damage and be knocked [prone](2-Mechanics/CLI/rules/conditions.md#Prone). The dragon can then move up to half its flying speed, or half its swimming speed if in the water.

![Sea Dragon](2-Mechanics/CLI/bestiary/legendary-group/sea-dragon-tob1-2023.md)
```
^statblock

## Environment

underwater