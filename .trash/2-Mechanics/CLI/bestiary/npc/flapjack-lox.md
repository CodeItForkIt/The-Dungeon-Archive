---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/lox
- monster/cr/1-8
- monster/size/small
- monster/type/aberration
aliases: ["Flapjack"]
---
# Flapjack
*Source: Light of Xaryxis p. 13*  

One crew member stayed aboard the Moondancer while it was in port: a flumph named Flapjack, who serves as the ship's spelljammer.

```ad-statblock
title: Flapjack
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/LoX/Flapjack.webp#token)
*Small aberration, Lawful Good*

- **Armor Class** 12
- **Hit Points** 7 (`2d6`)
- **Speed** 5 ft., fly 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
| 6 (-2)|15 (+2)|10 (+0)|14 (+2)|14 (+2)|11 (+0)|

- **Proficiency Bonus** +2
- **Saving Throws** ⏤
- **Skills** Arcana +4, History +4, Religion +4
- **Senses** darkvision 60 ft., passive Perception 12
- **Damage Vulnerabilities** psychic
- **Languages** understands Undercommon but can't speak, telepathy 60 ft.
- **Challenge** 1/8

## Traits

***Advanced Telepathy.*** Flapjack can perceive the content of any telepathic communication used within 60 feet of it, and it can't be [surprised](2-Mechanics/CLI/rules/conditions.md#Surprised) by creatures with any form of telepathy.

***Prone Deficiency.*** If Flapjack is knocked [prone](2-Mechanics/CLI/rules/conditions.md#Prone), roll a die. On an odd result, Flapjack lands upside-down and is [incapacitated](2-Mechanics/CLI/rules/conditions.md#Incapacitated). At the end of each of its turns, Flapjack can make a DC 10 Dexterity saving throw, righting itself and ending the [incapacitated](2-Mechanics/CLI/rules/conditions.md#Incapacitated) condition if it succeeds.

***Telepathic Shroud.*** Flapjack is immune to any effect that would sense its emotions or read its thoughts, as well as all divination spells.

***Spellcasting.*** Flapjack casts one of the following spells, requiring no material components and using Intelligence as the spellcasting ability (spell save DC 12):

**At will**: [mage hand](2-Mechanics/CLI/spells/mage-hand.md), [minor illusion](2-Mechanics/CLI/spells/minor-illusion.md)

**1/day each**: [magic missile](2-Mechanics/CLI/spells/magic-missile.md), [unseen servant](2-Mechanics/CLI/spells/unseen-servant.md)

## Actions

***Tendrils.*** *Melee Weapon Attack:* `dice:1d20+4|noform|text(+4)` to hit, reach 5 ft., one creature. *Hit:* `dice:1d4+2|noform|avg|text(4)` (`1d4 + 2`) piercing damage plus `dice:1d4|noform|avg|text(2)` (`1d4`) acid damage. At the end of each of its turns, the target must make a DC 10 Constitution saving throw, taking `dice:1d4|noform|avg|text(2)` (`1d4`) acid damage on a failure or ending the recurring acid damage on a success. A [lesser restoration](2-Mechanics/CLI/spells/lesser-restoration.md) spell cast on the target also ends the recurring acid damage.

***Stench Spray (1/Day).*** Each creature in a 15-foot cone originating from Flapjack must succeed on a DC 10 Dexterity saving throw or be coated in a foul-smelling liquid. A coated creature exudes a horrible stench for `dice:1d4|noform|avg` (`1d4`) hours. The coated creature is [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned) as long as the stench lasts, and other creatures are [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned) while with in 5 feet of the coated creature. A creature can remove the stench on itself by using a short rest to bathe in water, alcohol, or vinegar.
```
^statblock