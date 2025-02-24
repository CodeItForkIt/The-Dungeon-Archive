---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/coa
- monster/cr/26
- monster/size/medium
- monster/type/fiend/devil
aliases: ["Levistus"]
---
# Levistus
*Source: Chains of Asmodeus p. 229*  

No archdevil is more hated than the Frozen Prince, Levistus, despite his reputation as an honorable and chivalrous archdevil. Rivaling Asmodeus and Dis in their ability to plan and strategize, Levistus is generally considered one of the most plausible archdevils for overthrowing the throne. His ambition was somewhat stifled when he committed an unspeakable betrayal and was imprisoned by Asmodeus deep within the ice of Stygia.

Even while imprisoned, Levistus continues to plot, choosing to force his rage inward and reflect. Divination and communication magic helps aid this effort, and even from within his icy tomb Levistus manages legions. Levistus is known to make many deals with adventurers, provided they can aid his search for freedom.

When the Reckoning happened. Asmodeus, noticing that Levistus played no part in the war, chose to reinstate him as ruler of Stygia. While Levistus still desired revenge on his jailor, he recognized the opportunity and pledged temporary allegiance to Asmodeus. Publicly, Levistus completely supports Asmodeus and his plans, though from beneath the ice he continues to plot his revenge.

Other archdevils describe Levistus as clever, charming, and observant, if not also traitorous. He was often known to engage adversaries in single combat, only calling upon his magic and followers if someone or something intervened. For this reason, he is often worshipped by honorable thieves and charlatans—rogues with a code.

Levistus is described as an attractive humanoid male, with dark hair, an impeccable goatee, and pale-white skin.

## Levistus' Lair

The ruler of Stygia's lair is within his floating prison. This great glacier moves ponderously over the ages, carrying with it Levistus, and the effects of his lair.

## Statblock

```ad-statblock
title: Levistus
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/CoA/Levistus.webp#token)
*Medium fiend (devil), Lawful Evil*

- **Armor Class** 23 (natural armor)
- **Hit Points** 336 (`32d8 + 192`)
- **Speed** 0 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|19 (+4)|26 (+8)|22 (+6)|25 (+7)|28 (+9)|26 (+8)|

- **Proficiency Bonus** +8
- **Saving Throws** Dexterity +16, Constitution +14, Intelligence +15, Wisdom +17
- **Skills** Acrobatics +24, Deception +16, Intimidation +16, Perception +25, Persuasion +16, Stealth +16
- **Senses** darkvision 120 ft., passive Perception 35
- **Damage Resistances** bludgeoning, piercing, slashing from nonmagical attacks that aren't silvered
- **Damage Immunities** cold, fire, poison
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** Celestial, Common, Draconic, Infernal, telepathy 1,000 ft.
- **Challenge** 26

## Traits

***Armor of Ice.*** Levistus is always entombed in ice. The ice provides 100 temporary hit points. While Levistus has these temporary hit points, he has vulnerability to fire damage. If Levistus starts his turn with no temporary hit points from the ice, he regains 100 temporary hit points.

***Devil's Sight.*** Magical darkness doesn't impede Levistus's darkvision.

***Legendary Resistance (3/Day).*** If Levistus fails a saving throw, he can choose to succeed instead.

***Magic Resistance.*** Levistus has advantage on saving throws against spells and other magical effects.

***Sub-zero.*** Cold damage dealt by Levistus ignores resistances and immunities.

***Spellcasting.*** Levistus casts one of the following spells, requiring no material components and using Intelligence as the spellcasting ability (spell save DC 23):

**At will**: [Cone of Cold](2-Mechanics/CLI/spells/cone-of-cold.md), [Darkness](2-Mechanics/CLI/spells/darkness.md), [Ice Storm](2-Mechanics/CLI/spells/ice-storm.md), [Wall of Ice](2-Mechanics/CLI/spells/wall-of-ice.md)

## Actions

***Multiattack.*** Levistus makes three Touch of Stygia or Ice Bolt attacks. He can replace one of the attacks with Blizzard (if available).

***Touch of Stygia.*** *Melee Spell Attack:* `dice:1d20+15|noform|text(+15)` to hit, reach 5 ft., one target. *Hit:* `dice:3d8+7|noform|avg|text(20)` (`3d8 + 7`) psychic damage, and the target must succeed on a DC 23 Intelligence saving throw or have the [stunned](2-Mechanics/CLI/rules/conditions.md#Stunned) condition for 1 minute. The target may repeat the saving throw at the end of its turns, ending the effect on a success. A creature that succeeds on the saving throw is immune to this effect for 1 hour.

***Ice Bolt.*** *Ranged Spell Attack:* `dice:1d20+15|noform|text(+15)` to hit, range 120 ft., one target. *Hit:* `dice:3d10+7|noform|avg|text(23)` (`3d10 + 7`) cold damage.

***Blizzard (Recharge 4-6).*** Levistus chooses a point he can see within 300 feet of him. Each creature in a 20-foot-radius, 40-foot-high cylinder centered on that point must make a DC 23 Dexterity saving throw. Targets take `dice:3d8|noform|avg|text(13)` (`3d8`) force damage plus `dice:3d8|noform|avg|text(13)` (`3d8`) cold damage on a failed save, or half as much damage on a successful one.

## Reactions

***Counterspell.*** As a reaction to a creature he can see casting a spell, Levistus can attempt to prevent the casting. Levistus makes an Intelligence check (+7) against a DC of (10 + spell level). On a success, the creature's spell fails and has no effect.

## Legendary Actions

***Amnesia.*** Levistus selects a [stunned](2-Mechanics/CLI/rules/conditions.md#Stunned) creature that he can see. The creature must succeed on a DC 23 Charisma saving throw or Levistus erases a specific memory from the target. The memory must be one that the target experienced in the last 24 hours and that lasted no more than 10 minutes. The memory can only be restored with a [Remove Curse](2-Mechanics/CLI/spells/remove-curse.md) or a [Greater Restoration](2-Mechanics/CLI/spells/greater-restoration.md) spell.

***Froststrike.*** Levistus makes an Ice Bolt attack. On a hit, the target falls and has the [prone](2-Mechanics/CLI/rules/conditions.md#Prone) condition.

***Call Underling (Costs 3 Actions).*** Levistus summons an allied [ice devil](2-Mechanics/CLI/bestiary/fiend/ice-devil.md) in an unoccupied space that he can see.

![Levistus](2-Mechanics/CLI/bestiary/legendary-group/levistus-coa.md)
```
^statblock