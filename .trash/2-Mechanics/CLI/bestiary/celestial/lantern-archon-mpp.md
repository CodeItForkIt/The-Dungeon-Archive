---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/mpp
- monster/cr/2
- monster/size/small
- monster/type/celestial
aliases: ["Lantern Archon"]
---
# Lantern Archon
*Source: Morte's Planar Parade p. 17, Sigil and the Outlands, Turn of Fortune's Wheel*  

The lowest-ranked archons, lantern archons greet newly arrived souls to Mount Celestia and light the path for those who traverse the plane with reverence and respect. They appear as glowing, winged balls of vaporous light wrapped in a gleaming metal lattice, although they have no more physical substance than smoke.

When confronting those who approach with ill intentions, lantern archons strike with searing bolts of focused light, flitting from place to place between blasts to confound their foes.

## Archons

Archons are denizens of the Seven Heavens of Mount Celestia. Created by the powers of order and benevolence, archons defend their home from fiendish incursions and safeguard those threatened by wicked forces. Archons are skilled communicators, able to speak all the languages of the multiverse. When pushed into combat, they prefer to subdue foes. However, against Fiends, archons are wrathful combatants, manifesting the righteous vengeance of Mount Celestia to strike down the wicked.

Each archon's form corresponds to its place within the Celestial hierarchy. When faced in battle, archons radiate the full fury of the Upper Planes, bolstering their allies and cowing their foes.

## Statblock

```ad-statblock
title: Lantern Archon
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/MPP/Lantern%20Archon.webp#token)
*Small celestial, typically  Lawful Good*

- **Armor Class** 13
- **Hit Points** 22 (`5d6 + 5`)
- **Speed** 0 ft., fly 60 ft. (hover)

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
| 1 (-5)|16 (+3)|12 (+1)| 6 (-2)|12 (+1)|13 (+1)|

- **Proficiency Bonus** +2
- **Saving Throws** ⏤
- **Skills** Perception +3
- **Senses** darkvision 120 ft., passive Perception 13
- **Damage Resistances** bludgeoning, piercing, slashing from nonmagical attacks
- **Damage Immunities** lightning, radiant
- **Condition Immunities** [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled), [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed), [prone](2-Mechanics/CLI/rules/conditions.md#Prone), [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained)
- **Languages** all
- **Challenge** 2

## Traits

***Aura of Menace.*** As long as the archon doesn't have the [incapacitated](2-Mechanics/CLI/rules/conditions.md#Incapacitated) condition, each creature of the archon's choice that starts its turn within 20 feet of the archon must make a DC 11 Wisdom saving throw. On a failed save, the creature has the [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened) condition until the start of its next turn. On a successful save, the creature is immune to all archons' Aura of Menace for 24 hours.

***Illumination.*** The archon sheds bright light in a 30-foot radius and dim light for an additional 30 feet.

***Incorporeal Movement.*** The archon can move through creatures and objects as if they were difficult terrain. If it ends its turn inside an object, it takes `dice:1d10|noform|avg|text(5)` (`1d10`) force damage.

***Spellcasting.*** The archon casts one of the following spells, requiring no material components and using Charisma as the spellcasting ability:

**At will**: [detect evil and good](2-Mechanics/CLI/spells/detect-evil-and-good.md)

**1/day**: [aid](2-Mechanics/CLI/spells/aid.md)

## Actions

***Multiattack.*** The archon makes two Radiant Strike attacks. It can replace one attack with a use of Teleport.

***Radiant Strike.*** *Melee or Ranged Weapon Attack:* `dice:1d20+5|noform|text(+5)` to hit, reach 5 ft. or range 60 ft., one target. *Hit:* `dice:1d6+3|noform|avg|text(6)` (`1d6 + 3`) radiant damage.

***Teleport.*** The archon teleports, along with any equipment it is wearing or carrying, to an unoccupied space it can see within 120 feet of itself.

## Bonus Actions

***Shift Radiance.*** The archon reduces its Illumination to shed only dim light in a 5-foot radius, or it returns the light to full intensity.
```
^statblock