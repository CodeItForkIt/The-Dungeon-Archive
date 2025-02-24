---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/tob1-2023
- monster/cr/5
- monster/environment/farmland
- monster/environment/urban
- monster/size/small
- monster/type/construct
aliases: ["Quicksilver Siege Orb"]
---
# Quicksilver Siege Orb
*Source: Tome of Beasts 1 (2023 Edition) p. 297*  

*This silver sphere, polished to a mirror-like sheen bobs gently in the air for a moment before suddenly flattening out into a round, serrated blade.*

The quicksilver siege orb is an alchemical construct designed for use as a siege weapon. The orb measures 3 feet in diameter and weighs 30 pounds. When it changes to disk form, its diameter increases to 6 feet, but it is only an inch thin.

## Smart Silver

Arcanists replicated a semi-sentient quicksilver they found in the underworld and provided it to warring factions. The metal changes its disposition to match its form. As an orb, it is contemplative and observant. As a blade, it is aggressive, seeking to kill enemy combatants. Fortunately, it takes commands well and avoids inflicting collateral damage.

## Autonomous Siege Weapon

A quicksilver siege orb can fit into a catapult or other throwing siege weapon while in spherical form. When it reaches its destination, it hovers in place to assess soft targets before changing into its disk form and injuring or killing those targets.

## Customizable Alternate Form

Though the siege orb can have only one alternate form, the orb accepts instructions for several shapes beyond the standard whirling disk, such as spiked balls, borers, and other devices useful in battle.

## Statblock

```ad-statblock
title: Quicksilver Siege Orb
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ToB1-2023/Quicksilver%20Siege%20Orb.webp#token)
*Small construct, Unaligned*

- **Armor Class** 15
- **Hit Points** 82 (`15d6 + 30`)
- **Speed** 10 ft., fly 40 ft. (hover)

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|12 (+1)|21 (+5)|14 (+2)| 5 (-3)|14 (+2)| 7 (-2)|

- **Proficiency Bonus** +3
- **Saving Throws** ⏤
- **Skills** Perception +5, Stealth +8
- **Senses** darkvision 60 ft., passive Perception 15
- **Damage Vulnerabilities** cold
- **Damage Resistances** fire; lightning; piercing, slashing from nonmagical attacks
- **Damage Immunities** bludgeoning, poison, psychic
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened), [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed), [petrified](2-Mechanics/CLI/rules/conditions.md#Petrified), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned), [prone](2-Mechanics/CLI/rules/conditions.md#Prone), [unconscious](2-Mechanics/CLI/rules/conditions.md#Unconscious)
- **Languages** understands one language of its creator but can't speak
- **Challenge** 5

## Traits

***Bludgeoning Bounce (Orb Form Only).*** Whenever the quicksilver siege orb is subjected to bludgeoning damage, it takes no damage and instead is pushed up to 15 feet away from the source of the bludgeoning damage. If the damage is from a critical hit, the orb is pushed up to 30 feet.

***Construct Nature.*** The quicksilver siege orb doesn't require air, food, drink, or sleep.

***Flyby.*** The quicksilver siege orb doesn't provoke opportunity attacks when it flies out of an enemy's reach.

***Immutable Form.*** The quicksilver siege orb is immune to any spell or effect that would alter its form.

***Observant (Orb Form Only).*** The quicksilver siege orb has advantage on Wisdom ([Perception](2-Mechanics/CLI/rules/skills.md#Perception)) and Wisdom ([Insight](2-Mechanics/CLI/rules/skills.md#Insight)) checks. In addition, if the orb observes a creature for at least 1 minute, it has advantage on the first three attack rolls it makes against the creature.

***Slippery.*** The quicksilver siege orb has advantage on saving throws and ability checks made to escape a grapple.

## Actions

***Multiattack.*** The quicksilver siege orb makes three Disk Blade or Slam attacks.

***Disk Blade (Disk Form Only).*** *Melee Weapon Attack:* `dice:1d20+8|noform|text(+8)` to hit, reach 5 ft., one target. *Hit:* `dice:2d6+5|noform|avg|text(12)` (`2d6 + 5`) slashing damage.

***Slam (Orb Form Only).*** *Melee Weapon Attack:* `dice:1d20+8|noform|text(+8)` to hit, reach 5 ft., one target. *Hit:* `dice:2d4+5|noform|avg|text(10)` (`2d4 + 5`) bludgeoning damage.

***Slashing Run (Recharge 4-6).*** The quicksilver siege orb flies up to 20 feet in a straight line, then it flies up to 20 feet in a straight line in a different direction. During this move, it can move through the space of any Large or smaller creature. The first time it enters a creature's space during this move, that creature must make a DC 16 Dexterity saving throw, taking `dice:10d6|noform|avg|text(35)` (`10d6`) slashing damage on a failed save, or half as much damage on a successful one.

## Bonus Actions

***Shape Quicksilver.*** The quicksilver siege orb flattens itself into a razor-sharp, whirling disk or back into its orb form. Its statistics are the same in each form. It becomes a puddle of quicksilver if it dies.
```
^statblock

## Environment

farmland, urban