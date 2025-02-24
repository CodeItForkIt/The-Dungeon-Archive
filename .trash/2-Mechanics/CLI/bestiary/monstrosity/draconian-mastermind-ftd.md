---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/ftd
- monster/cr/6
- monster/size/medium
- monster/type/monstrosity
aliases: ["Draconian Mastermind"]
---
# Draconian Mastermind
*Source: Fizban's Treasury of Dragons p. 180*  

The rarest and most powerful of the draconians are the masterminds—spellcasters and strategists who most often serve as military commanders or as advisors to those who created them. They emerge from gold, red, or amethyst dragon eggs, wingless but possessed of an arsenal of eldritch power. Like their dragon progenitors, masterminds have a breath weapon—a billowing cloud of poisonous gas. They also have formidable claws and teeth they use to rend foes in close combat.

Dying draconian masterminds are a sight to behold, as their magical essence coalesces as a ball of lightning that arcs out at those nearby.

On the world of Krynn, draconian masterminds formed from gold dragon eggs are called aurak draconians.

## Draconians

Draconians are bipedal monsters born from dragon eggs that have been corrupted or warped by powerful magic. Most often, this corruption is a deliberate act, the work of an aspiring tyrant seeking to transform stolen eggs into a draconian army. A single corrupted egg yields several draconians of the same kind. A draconian might be taken for a dragonborn at first glance, though most kinds of draconians have wings.

When draconians die, they do not go quietly. Instead, their lifeless bodies unleash a last act of magical violence.

## Statblock

```ad-statblock
title: Draconian Mastermind
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/FTD/Draconian%20Mastermind.webp#token)
*Medium monstrosity, Any alignment*

- **Armor Class** 17 (natural armor)
- **Hit Points** 67 (`9d8 + 27`)
- **Speed** 35 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|13 (+1)|14 (+2)|16 (+3)|15 (+2)|11 (+0)|17 (+3)|

- **Proficiency Bonus** +3
- **Saving Throws** Intelligence +5, Wisdom +3, Charisma +6
- **Skills** Perception +3
- **Senses** truesight 60 ft., passive Perception 13
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed)
- **Languages** Common, Draconic
- **Challenge** 6

## Traits

***Death Throes.*** When the draconian is reduced to 0 hit points, its magical essence lashes out as a ball of lightning at the closest creature within 30 feet of it before arcing out to up to two other creatures within 15 feet of the first. Each creature must make a DC 14 Dexterity saving throw. On a failed save, the creature takes `dice:2d8|noform|avg|text(9)` (`2d8`) lightning damage and is [stunned](2-Mechanics/CLI/rules/conditions.md#Stunned) until the end of its next turn. On a successful save, the creature takes half as much damage and isn't [stunned](2-Mechanics/CLI/rules/conditions.md#Stunned).

***Spellcasting.*** The draconian casts one of the following spells, requiring no material components and using Charisma as the spellcasting ability (spell save DC 14):

**At will**: [invisibility](2-Mechanics/CLI/spells/invisibility.md), [mage hand](2-Mechanics/CLI/spells/mage-hand.md)

**2/day each**: [dimension door](2-Mechanics/CLI/spells/dimension-door.md), [disguise self](2-Mechanics/CLI/spells/disguise-self.md), [sending](2-Mechanics/CLI/spells/sending.md)

## Actions

***Multiattack.*** The draconian makes three Rend or Energy Ray attacks.

***Rend.*** *Melee Weapon Attack:* `dice:1d20+5|noform|text(+5)` to hit, reach 5 ft., one target. *Hit:* `dice:1d6+2|noform|avg|text(5)` (`1d6 + 2`) slashing damage.

***Energy Ray.*** *Ranged Spell Attack:* `dice:1d20+6|noform|text(+6)` to hit, range 60 ft., one target. *Hit:* `dice:1d10+3|noform|avg|text(8)` (`1d10 + 3`) force damage.

***Noxious Breath (Recharge 5-6).*** The draconian exhales a 15-foot cone of noxious gas. Each creature in that area must make a DC 14 Constitution saving throw. On a failed save, the creature takes `dice:6d6|noform|avg|text(21)` (`6d6`) poison damage and gains 1 level of [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion). On a successful save, the creature takes half as much damage, doesn't gain [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), and is immune to all draconians' Noxious Breath for 24 hours.

## Reactions

***Magic Shield (3/Day).*** When the draconian is hit by an attack roll, it can create an [invisible](2-Mechanics/CLI/rules/conditions.md#Invisible) barrier of magical force around itself, granting it a +5 bonus to its AC against that attack and potentially causing the attack to miss.
```
^statblock