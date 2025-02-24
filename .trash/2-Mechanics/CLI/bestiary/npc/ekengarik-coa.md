---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/coa
- monster/cr/16
- monster/size/large
- monster/type/fiend
aliases: ["Ekengarik"]
---
# Ekengarik
*Source: Chains of Asmodeus p. 141*  

```ad-statblock
title: Ekengarik
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/CoA/Ekengarik.webp#token)
*Large fiend, Lawful Evil*

- **Armor Class** 16 (natural armor)
- **Hit Points** 231 (`22d10 + 110`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|23 (+6)|16 (+3)|21 (+5)|14 (+2)|17 (+3)|21 (+5)|

- **Proficiency Bonus** +5
- **Saving Throws** Constitution +10, Charisma +10
- **Skills** Deception +10, Insight +8, Persuasion +10
- **Senses** blindsight 30 ft., darkvision 120 ft., passive Perception 13
- **Damage Resistances** acid; lightning; bludgeoning, piercing, slashing from nonmagical attacks
- **Damage Immunities** cold, fire, poison
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** Common, Formian, telepathy 120 ft.
- **Challenge** 16

## Traits

***Hive Mind.*** All fiendish formians within 1 mile of Ekengarik can telepathically communicate with each other and Ekengarik.

***Regeneration.*** Ekengarik regenerates 10 hit points at the start of her turn, unless she took radiant damage in the last round.

***Spellcasting.*** Ekengarik casts one of the following spells, requiring no material components and using Charisma as the spellcasting ability (spell save DC 18):

**At will**: [Detect Magic](2-Mechanics/CLI/spells/detect-magic.md), [Dispel Magic](2-Mechanics/CLI/spells/dispel-magic.md), [Heroism](2-Mechanics/CLI/spells/heroism.md), [Magic Missile](2-Mechanics/CLI/spells/magic-missile.md)

**1/day each**: [Evard's Black Tentacles](2-Mechanics/CLI/spells/evards-black-tentacles.md), [Cone of Cold](2-Mechanics/CLI/spells/cone-of-cold.md), [Confusion](2-Mechanics/CLI/spells/confusion.md), [Dimension Door](2-Mechanics/CLI/spells/dimension-door.md), [Geas](2-Mechanics/CLI/spells/geas.md), [Invisibility](2-Mechanics/CLI/spells/invisibility.md), [Prismatic Wall](2-Mechanics/CLI/spells/prismatic-wall.md), [Slow](2-Mechanics/CLI/spells/slow.md)

## Actions

***Multiattack.*** Ekengarik makes three Bite attacks. She can replace one of the attacks with an Acid Spray (if available) attack or a use of Spellcasting.

***Bite.*** *Melee Weapon Attack:* `dice:1d20+11|noform|text(+11)` to hit, reach 5 ft., one target. *Hit:* `dice:2d8+6|noform|avg|text(15)` (`2d8 + 6`) piercing damage and the target must make a DC 19 Constitution saving throw. On a failed save, the target's Strength score is reduced by `dice:1d4|noform|avg|text(2)` (`1d4`). The target dies if this reduces its Strength to 0. Otherwise, the reduction lasts until the target finishes a short or long rest.

***Acid Spray (Recharge 5-6).*** Ekengarik spits acid at one creature within 60 feet of her, or two creatures within 60 feet of her and 5 feet of each other. Targets must make a DC 18 Dexterity saving throw, taking `dice:6d10|noform|avg|text(33)` (`6d10`) acid damage on a failed saving throw, or half as much on a successful one.

## Reactions

***Hardened Carapace (Recharge 4-6).*** When hit with an attack, Ekengarik temporarily hardens her carapace, reducing her speed to 0 and increasing her AC by 5 until the start of her next turn.
```
^statblock