---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/mpp
- monster/cr/8
- monster/size/large
- monster/type/celestial
aliases: ["Warden Archon"]
---
# Warden Archon
*Source: Morte's Planar Parade p. 18, Sigil and the Outlands, Turn of Fortune's Wheel*  

Warden archons are vigilant, ursine guardians of portals and paths connected to goodly realms. They have powerfully built, bipedal bodies with the heads of great bears and eyes like pools of silvery light. When warden archons speak, glimmering radiance shines from within their mouths, punctuating their deep, resonant voices.

A warden archon knows when a creature uses a portal the archon is tasked to guard, and it moves swiftly to interrogate any who cross that planar boundary. If an invader enters the archon's plane, the warden strikes with claw and tooth, using its powerful bite to magically mark the intruder, which the archon pursues relentlessly.

## Archons

Archons are denizens of the Seven Heavens of Mount Celestia. Created by the powers of order and benevolence, archons defend their home from fiendish incursions and safeguard those threatened by wicked forces. Archons are skilled communicators, able to speak all the languages of the multiverse. When pushed into combat, they prefer to subdue foes. However, against Fiends, archons are wrathful combatants, manifesting the righteous vengeance of Mount Celestia to strike down the wicked.

Each archon's form corresponds to its place within the Celestial hierarchy. When faced in battle, archons radiate the full fury of the Upper Planes, bolstering their allies and cowing their foes.

## Statblock

```ad-statblock
title: Warden Archon
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/MPP/Warden%20Archon.webp#token)
*Large celestial, typically  Lawful Good*

- **Armor Class** 18 ([plate armor](2-Mechanics/CLI/items/plate-armor.md))
- **Hit Points** 136 (`16d10 + 48`)
- **Speed** 30 ft., climb 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|20 (+5)|10 (+0)|17 (+3)|15 (+2)|18 (+4)|18 (+4)|

- **Proficiency Bonus** +3
- **Saving Throws** Constitution +6, Wisdom +7
- **Skills** Arcana +5, Athletics +8, Perception +10
- **Senses** darkvision 120 ft., truesight 30 ft., passive Perception 20
- **Damage Immunities** lightning
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened), [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed)
- **Languages** all
- **Challenge** 8

## Traits

***Aura of Menace.*** As long as the archon doesn't have the [incapacitated](2-Mechanics/CLI/rules/conditions.md#Incapacitated) condition, each creature of the archon's choice that starts its turn within 20 feet of the archon must make a DC 15 Wisdom saving throw. On a failed save, the creature has the [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened) condition until the start of its next turn. On a successful save, the creature is immune to all archons' Aura of Menace for 24 hours.

***Eternal Vigil.*** The archon can't be surprised. Moreover, it knows when any creature uses a portal it is assigned to guard.

***Spellcasting.*** The archon casts one of the following spells, requiring no material components and using Charisma as the spellcasting ability (spell save DC 15):

**At will**: [detect evil and good](2-Mechanics/CLI/spells/detect-evil-and-good.md)

**1/day each**: [aid](2-Mechanics/CLI/spells/aid.md), [continual flame](2-Mechanics/CLI/spells/continual-flame.md), [protection from evil and good](2-Mechanics/CLI/spells/protection-from-evil-and-good.md), [scrying](2-Mechanics/CLI/spells/scrying.md) (as an action)

## Actions

***Multiattack.*** The archon makes two Claw attacks and one Tracker's Bite attack.

***Claw.*** *Melee Weapon Attack:* `dice:1d20+8|noform|text(+8)` to hit, reach 10 ft., one target. *Hit:* `dice:2d6+5|noform|avg|text(12)` (`2d6 + 5`) slashing damage. If the target is a Medium or smaller creature, the target has the [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) condition (escape DC 18). The archon can have only one creature [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) in this way at a time.

***Tracker's Bite.*** *Melee Weapon Attack:* `dice:1d20+8|noform|text(+8)` to hit, reach 5 ft., one target. *Hit:* `dice:3d6+5|noform|avg|text(15)` (`3d6 + 5`) piercing damage. If the target is a creature, for the next 24 hours, the archon knows the distance and direction to the target while they are both on the same plane of existence.

***Teleport.*** The archon teleports, along with any equipment it is wearing or carrying, to an unoccupied space it can see within 120 feet of itself.
```
^statblock