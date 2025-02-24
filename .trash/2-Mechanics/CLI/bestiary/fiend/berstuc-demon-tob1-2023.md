---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/tob1-2023
- monster/cr/11
- monster/environment/forest
- monster/environment/planar
- monster/size/large
- monster/type/fiend/demon
aliases: ["Berstuc Demon"]
---
# Berstuc Demon
*Source: Tome of Beasts 1 (2023 Edition) p. 83*  

*Although slightly stooped, this male figure is muscular and broad‑shouldered. The creature's head is lost in a riot of moss, while a thick mustache and beard reach almost to its waist.*

The hulking, moss-haired berstuc looks sculpted out of a primordial forest—it stands over 12 feet tall and weighs 800 pounds. Despite its great stature, it seems strangely gentle, with a serene, almost soothing presence. Nothing could be further from the truth; the berstuc is a murderous demon that stalks woodlands and jungles of the Material Plane.

## Poisoned Fruit

Berstuc prowl forests in search of travelers to torment. A berstuc demon poses as a benevolent, or at least indifferent, wood spirit to gain the trust of mortals. It allows itself to be persuaded to help lost travelers (reluctantly) or to lead them to their destinations. Once it draws its unwitting prey deep into the woods, it strikes.

## Statblock

```ad-statblock
title: Berstuc Demon
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ToB1-2023/Berstuc%20Demon.webp#token)
*Large fiend (demon), Chaotic Evil*

- **Armor Class** 18 (natural armor)
- **Hit Points** 157 (`15d10 + 75`)
- **Speed** 40 ft., burrow 20 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|22 (+6)|10 (+0)|20 (+5)|12 (+1)|14 (+2)|19 (+4)|

- **Proficiency Bonus** +4
- **Saving Throws** Strength +10, Wisdom +6, Charisma +8
- **Skills** Deception +8, Nature +9, Stealth +4, Survival +6
- **Senses** darkvision 120 ft., passive Perception 12
- **Damage Resistances** acid; cold; fire; bludgeoning, piercing, slashing from nonmagical attacks
- **Damage Immunities** lightning, poison
- **Condition Immunities** [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** Abyssal, Common, Sylvan, telepathy 120 ft.
- **Challenge** 11

## Traits

***False Presence.*** The berstuc detects as a Fey when sensed by spells and features, such as the [detect evil and good](2-Mechanics/CLI/spells/detect-evil-and-good.md) spell or a paladin's Divine Sense. However, it is still a Fiend and can be subjected to spells and features that affect Fiends, such as Divine Smite. Beasts and Plants find the berstuc's presence soothing and don't attack the berstuc unless ordered to or provoked.

***Forest Camouflage.*** The berstuc has advantage on Dexterity ([Stealth](2-Mechanics/CLI/rules/skills.md#Stealth)) checks made to hide in forest terrain.

***Magic Resistance.*** The berstuc has advantage on saving throws against spells and other magical effects.

***Twisted Path.*** While in a nonmagical forest, the berstuc leaves no trail and can't be tracked, except by magical means. Creatures of the berstuc's choice within 30 feet of it that travel with it can't retrace their own trails, and become hopelessly lost after 1 hour of travel with the berstuc. Creatures led astray by the berstuc have disadvantage on ability checks to discern their location or to navigate for 24 hours.

***Verdant Nature.*** The berstuc doesn't require food or sleep.

## Actions

***Multiattack.*** The berstuc makes three Slam attacks. If two Slam attacks hit a Medium or smaller creature, the berstuc can use Enclose on it.

***Slam.*** *Melee Weapon Attack:* `dice:1d20+10|noform|text(+10)` to hit, reach 5 ft., one target. *Hit:* `dice:3d8+6|noform|avg|text(19)` (`3d8 + 6`) bludgeoning damage, and the target is [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) (escape DC 17) if it is a Large or smaller creature and the berstuc doesn't have two other creatures [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled).

***Enclose.*** The berstuc encloses a Medium or smaller creature [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) by it in a mossy growth on the berstuc's body, and the grapple ends. While enclosed in the berstuc's growth, the target is [blinded](2-Mechanics/CLI/rules/conditions.md#Blinded) and [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained), it has total cover from attacks and other effects outside the berstuc, and it takes `dice:6d6|noform|avg|text(21)` (`6d6`) poison damage at the start of each of the berstuc's turns. The berstuc can have only one creature enclosed at a time.

If the berstuc takes 30 damage or more on a single turn from a creature inside its growth, the berstuc must succeed on a DC 15 Constitution saving throw at the end of that turn or expel the enclosed creature as the growth bursts. The expelled creature falls [prone](2-Mechanics/CLI/rules/conditions.md#Prone) in a space within 5 feet of the berstuc. If the berstuc dies, an enclosed creature is no longer [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained) by it and can escape from the growth by using 5 feet of movement, exiting [prone](2-Mechanics/CLI/rules/conditions.md#Prone).
```
^statblock

## Environment

forest, planar