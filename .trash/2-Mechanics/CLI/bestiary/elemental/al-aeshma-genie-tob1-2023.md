---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/tob1-2023
- monster/cr/9
- monster/environment/desert
- monster/size/large
- monster/type/elemental
aliases: ["Al-Aeshma Genie"]
---
# Al-Aeshma Genie
*Source: Tome of Beasts 1 (2023 Edition) p. 197*  

*The lower half of this genie is composed of scorching winds and desert sand.*

## Sand Djinnis

The al-aeshma are former djinn and share the same powers, albeit in a twisted style. Their skin is black as pitch, and their whirlwind form includes much dust and sand. When they are injured, the desert sand flows to seal their wounds and reattach severed limbs.

## Obligation of Wishes

Granting three wishes to a mortal is a sacred obligation among the genies, referred to as being wishbound. The Lords of Air mandate this as celestial law, and many believe that a djinni cannot refuse to grant a wish. Certainly, the consequences of disobedience are dire. Djinn who decline to grant a wish, are stripped of their wish power and handed to efreeti for 1,001 years of torture and debasement. Those who survive are banished to wander the Material Plane.

## Statblock

```ad-statblock
title: Al-Aeshma Genie
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ToB1-2023/Al-Aeshma%20Genie.webp#token)
*Large elemental, Chaotic Evil*

- **Armor Class** 17 (natural armor)
- **Hit Points** 149 (`13d10 + 78`)
- **Speed** 30 ft., fly 90 ft. (hover)

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|21 (+5)|15 (+2)|22 (+6)|15 (+2)|16 (+3)|20 (+5)|

- **Proficiency Bonus** +4
- **Saving Throws** Dexterity +6, Wisdom +7, Charisma +9
- **Skills** ⏤
- **Senses** darkvision 120 ft., passive Perception 13
- **Damage Immunities** lightning, thunder
- **Languages** Auran, Common, Ignan
- **Challenge** 9

## Traits

***Air Hatred.*** The al-aeshma has advantage on attack rolls against creatures that are flying.

***Earth Bound.*** The al-aeshma is anchored to the earth and can't fly far from it. The al-aeshma can't willingly fly more than 30 feet above the ground. If it starts its turn more than 30 feet away from the ground, it loses its damage immunities and is vulnerable to lightning and thunder damage until it starts its turn within 30 feet of the ground.

***Elemental Demise.*** When an al-aeshma dies, its body disintegrates into a swirling spray of coarse sand, leaving behind only equipment it was wearing or carrying.

***Regeneration.*** The al-aeshma regains 10 hp at the start of its turn. If it takes fire or radiant damage, this trait doesn't function at the start of the al-Aeshma's next turn. The al‑aeshma dies only if it starts its turn at 0 hp and doesn't regenerate.

***Spellcasting.*** The al-aeshma casts one of the following spells, requiring no material components and using Charisma as the spellcasting ability (spell save DC 17):

**At will**: [detect magic](2-Mechanics/CLI/spells/detect-magic.md)

**1/day each**: [gaseous form](2-Mechanics/CLI/spells/gaseous-form.md), [invisibility](2-Mechanics/CLI/spells/invisibility.md)

**3/day each**: [create or destroy water](2-Mechanics/CLI/spells/create-or-destroy-water.md) (destroy only), [wind walk](2-Mechanics/CLI/spells/wind-walk.md) (as an action)

## Actions

***Multiattack.*** The al-aeshma makes three Scimitar attacks. It can replace one attack with a use of Dust Devil or Spellcasting.

***Scimitar.*** *Melee Weapon Attack:* `dice:1d20+9|noform|text(+9)` to hit, reach 5 ft., one target. *Hit:* `dice:2d6+5|noform|avg|text(12)` (`2d6 + 5`) slashing damage plus `dice:2d6|noform|avg|text(7)` (`2d6`) necrotic damage.

***Dust Devil.*** The al-aeshma creates a swirling dust devil centered on a point it can see within 120 feet of it. The dust devil appears in the shape of a cylinder that is 30 feet tall with a 5-foot radius. Each creature in the area and each creature that enters the area for the first time on a turn or starts its turn there must succeed on a DC 17 Strength saving throw or be [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained). While [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained), a creature takes `dice:2d6|noform|avg|text(7)` (`2d6`) slashing damage and `dice:2d6|noform|avg|text(7)` (`2d6`) necrotic damage at the start of each of the al-aeshma's turns. A creature, including a [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained) creature, can take an action to free the [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained) creature by succeeding on a DC 17 Strength check.

The al-aeshma can use a bonus action on its turn to move the dust devil up to 30 feet. A [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained) creature doesn't move with the dust devil when the dust devil moves and is freed if the dust devil moves out of its space. The dust devil lasts until the al-aeshma loses its [concentration](2-Mechanics/CLI/rules/conditions.md#Concentration) (as if concentrating on a spell), and the alaeshma can have only one dust devil active at a time.
```
^statblock

## Environment

desert