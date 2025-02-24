---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/tob1-2023
- monster/cr/11
- monster/environment/urban
- monster/size/medium
- monster/type/fey
aliases: ["Blood Hag"]
---
# Blood Hag
*Source: Tome of Beasts 1 (2023 Edition) p. 226*  

*This bent-backed crone has long, leathery arms and cruel, flesh-shearing talons. Her face is a misshapen mass of leathery flesh with a bulbous nose, like a gnarled knot on an old oak tree, and her hair falls in ringlets of wriggling worms.*

Blood hags have long skulked on the fringes of society. The hags prey on mankind, stealing seed to propagate, blood to satisfy their insatiable thirst, and faces as trophies of these short-lived and bloody trysts.

## Worm Hair

A blood hag's hair is a morass of wriggling worms, ever-thirsty for fresh blood.

## Statblock

```ad-statblock
title: Blood Hag
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ToB1-2023/Blood%20Hag.webp#token)
*Medium fey, Chaotic Evil*

- **Armor Class** 16 (natural armor)
- **Hit Points** 204 (`24d8 + 96`)
- **Speed** 30 ft., climb 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|20 (+5)|16 (+3)|18 (+4)|19 (+4)|21 (+5)|17 (+3)|

- **Proficiency Bonus** +4
- **Saving Throws** Dexterity +7, Constitution +8, Charisma +7
- **Skills** Deception +7, Intimidation +7, Perception +9, Stealth +7
- **Senses** darkvision 60 ft., passive Perception 19
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** Common, Giant, Sylvan
- **Challenge** 11

## Traits

***Blood Sense.*** The blood hag can pinpoint the location of creatures that aren't Constructs or Undead within 60 feet of her and can sense the general direction of such creatures within 1 mile of her.

***Spellcasting.*** The blood hag casts one of the following spells, requiring no material components and using Wisdom as the spellcasting ability (spell save DC 17):

**At will**: [disguise self](2-Mechanics/CLI/spells/disguise-self.md), [knock](2-Mechanics/CLI/spells/knock.md), [tongues](2-Mechanics/CLI/spells/tongues.md)

**3/day each**: [modify memory](2-Mechanics/CLI/spells/modify-memory.md), [pass without trace](2-Mechanics/CLI/spells/pass-without-trace.md)

## Actions

***Multiattack.*** The blood hag makes three Claw or Blood Bolt attacks and can use Blood-Drinking Hair or Face Peel. She can replace one attack with a use of Sanguine Curse.

***Claws.*** *Melee Weapon Attack:* `dice:1d20+9|noform|text(+9)` to hit, reach 5 ft., one target. *Hit:* `dice:4d6+5|noform|avg|text(19)` (`4d6 + 5`) slashing damage, and the target is [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) (escape DC 17) if it is a Medium or smaller creature. The blood hag has two claws, each of which can grapple only one target.

***Blood Bolt.*** *Ranged Spell Attack:* `dice:1d20+9|noform|text(+9)` to hit, range 60 ft., one target. *Hit:* `dice:3d8+5|noform|avg|text(18)` (`3d8 + 5`) necrotic damage. If the target is a creature with blood, it must succeed on a DC 17 Constitution saving throw or be [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned) until the end of its next turn.

***Blood-Drinking Hair.*** The hag drains blood from one creature [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) by her. The target must make a DC 17 Constitution saving throw, taking `dice:4d8|noform|avg|text(18)` (`4d8`) necrotic damage on a failed save, or half as much damage on a successful one. The blood hag regains hp equal to half the necrotic damage taken.

***Face Peel.*** The blood hag peels the face off one creature [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) by her. The target must succeed on a DC 17 Dexterity saving throw or take `dice:4d6|noform|avg|text(14)` (`4d6`) slashing damage and be [stunned](2-Mechanics/CLI/rules/conditions.md#Stunned) until the end of its next turn. The target's hp maximum is reduced by an amount equal to the damage taken. This reduction lasts until the target finishes a long rest. While its hp maximum is reduced in this way, the target has disadvantage on all Charisma checks. The target dies if this effect reduces its hp maximum to 0.

***Sanguine Curse.*** The blood hag curses one creature she can see or sense within 60 feet of her. The target must succeed on a DC 17 Wisdom saving throw or be cursed for 1 minute. A creature automatically succeeds on this saving throw if it doesn't have blood. While cursed, the target is [incapacitated](2-Mechanics/CLI/rules/conditions.md#Incapacitated) and takes `dice:2d8|noform|avg|text(9)` (`2d8`) necrotic damage at the start of each of its turns as its internal blood vessels rupture. The cursed target can repeat the saving throw at the end of each of its turns, ending the curse on itself on a success.

The blood hag can have only one target cursed at a time. If it curses another, the effect on the previous target ends.
```
^statblock

## Environment

urban