---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/pabtso
- monster/cr/15
- monster/size/huge
- monster/type/aberration/mind-flayer
aliases: ["Refraction of Ilvaash"]
---
# Refraction of Ilvaash
*Source: Phandelver and Below: The Shattered Obelisk p. 197*  

Ilvaash was formed from the remains of the mind flayer god Ilsensine, the God-Brain. When Ilsensine left the Far Realm to establish a divine domain elsewhere, pieces of the God-Brain sloughed away and awoke to sentience. This is Ilvaash, the Dissonant Psyche.

The refraction of Ilvaash wields only a sliver of the godlet's power but is nevertheless a formidable foe.

```ad-statblock
title: Refraction of Ilvaash
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/PaBTSO/Refraction%20of%20Ilvaash.webp#token)
*Huge aberration (mind flayer), Lawful Evil*

- **Armor Class** 11 (natural armor)
- **Hit Points** 199 (`21d12 + 63`)
- **Speed** 10 ft., fly 30 ft. (hover), swim 10 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|17 (+3)|10 (+0)|17 (+3)|23 (+6)|20 (+5)|22 (+6)|

- **Proficiency Bonus** +5
- **Saving Throws** Intelligence +11, Wisdom +10
- **Skills** Arcana +11, Insight +15, Intimidation +11, Persuasion +11
- **Senses** blindsight 120 ft., passive Perception 15
- **Damage Resistances** bludgeoning, piercing, slashing from nonmagical attacks
- **Damage Immunities** poison, psychic
- **Condition Immunities** [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled), [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed), [petrified](2-Mechanics/CLI/rules/conditions.md#Petrified), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned), [prone](2-Mechanics/CLI/rules/conditions.md#Prone), [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained)
- **Languages** Common, Deep Speech, telepathy 100 miles, Undercommon
- **Challenge** 15

## Traits

***Creature Sense.*** The refraction is aware of creatures within 100 miles of it that have an Intelligence score of 4 or higher. It knows the distance and direction to each creature, as well as each one's Intelligence score, but can't sense anything else about it. A creature protected by a [mind blank](2-Mechanics/CLI/spells/mind-blank.md) spell, a [nondetection](2-Mechanics/CLI/spells/nondetection.md) spell, or similar magic can't be perceived in this manner.

***Incorporeal Movement.*** The refraction can move through other creatures and objects as if they were difficult terrain. It takes `dice:1d10|noform|avg|text(5)` (`1d10`) force damage if it ends its turn inside an object.

***Legendary Resistance (5/Day).*** If the refraction fails a saving throw, it can choose to succeed instead.

***Magic Resistance.*** The refraction has advantage on saving throws against spells and other magical effects.

***Spellcasting (Psionics).*** The refraction casts one of the following spells, requiring no spell components and using Intelligence as the spellcasting ability (spell save DC 19):

**At will**: [detect magic](2-Mechanics/CLI/spells/detect-magic.md), [detect thoughts](2-Mechanics/CLI/spells/detect-thoughts.md)

**1/day each**: [feeblemind](2-Mechanics/CLI/spells/feeblemind.md), [plane shift](2-Mechanics/CLI/spells/plane-shift.md) (self only)

**3/day each**: [dispel magic](2-Mechanics/CLI/spells/dispel-magic.md), [modify memory](2-Mechanics/CLI/spells/modify-memory.md)

## Actions

***Multiattack.*** The refraction makes two Dissonant Claw attacks.

***Dissonant Claw.*** *Melee Weapon Attack:* `dice:1d20+11|noform|text(+11)` to hit, reach 10 ft. or range 120 ft., one creature. *Hit:* `dice:3d12+6|noform|avg|text(25)` (`3d12 + 6`) psychic damage. If the target is a creature concentrating on a spell, its [concentration](2-Mechanics/CLI/rules/conditions.md#Concentration) is broken.

***Mind Blast (Recharge 5-6).*** Creatures of the refraction's choice within 60 feet of it must succeed on a DC 19 Intelligence saving throw or take `dice:5d10+6|noform|avg|text(33)` (`5d10 + 6`) psychic damage and have the [stunned](2-Mechanics/CLI/rules/conditions.md#Stunned) condition for 1 minute. A [stunned](2-Mechanics/CLI/rules/conditions.md#Stunned) creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.

***Teleport.*** The refraction teleports, along with any equipment it is wearing or carrying, up to 120 feet to an unoccupied place that it can see.

## Legendary Actions

***Mindbreaker.*** The refraction targets a creature within 120 feet of itself and disrupts its mental processes, causing the target to have disadvantage on all ability checks, attack rolls, and saving throws until the end of the target's next turn.

***Projected Claw (Costs 2 Actions).*** The refraction makes one Dissonant Claw attack.
```
^statblock