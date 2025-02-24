---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/tob1-2023
- monster/cr/3
- monster/environment/desert
- monster/size/medium
- monster/type/fey
aliases: ["Mirager"]
---
# Mirager
*Source: Tome of Beasts 1 (2023 Edition) p. 271*  

*Diaphanous veils cover a graceful woman, flowing like water across her as she dances through the dust.*

## Humanoid Sand

Cursed with crumbling, sandy bodies by a long-since-forgotten fey lord, miragers rely on blood and moisture from mortal creatures to replenish and sustain their forms. With such sustenance hard to acquire in their desert homes, miragers don't gather in groups and can be particularly vicious when starved. Some miragers might make bargains or forge friendships with mortal creatures, but the mirager's everpresent need for blood and moisture means such alliances rarely survive the dry season.

## Enticing Illusion

A mirager can take on the guise of a lovely man or woman with luminous eyes, delicate features, and seductive garments. Whatever its form, a mirager dresses in veils and flowing robes that accentuate its enticing beauty.

## Statblock

```ad-statblock
title: Mirager
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ToB1-2023/Mirager.webp#token)
*Medium fey, Neutral Evil*

- **Armor Class** 13
- **Hit Points** 78 (`12d8 + 24`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|12 (+1)|16 (+3)|14 (+2)|10 (+0)|14 (+2)|19 (+4)|

- **Proficiency Bonus** +2
- **Saving Throws** ⏤
- **Skills** Deception +6, Perception +4, Performance +8
- **Senses** darkvision 60 ft., passive Perception 14
- **Languages** Common, Sylvan
- **Challenge** 3

## Traits

***Sensuous Grace.*** The mirager moves with a flowing grace that Humanoids find appealing. If the mirager moves at least 10 feet on its turn, each Humanoid within 30 feet of it that can see it must succeed on a DC 14 Charisma saving throw or be [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed) until the end of its next turn.

***Spellcasting.*** The mirager casts one of the following spells, requiring no material components and using Charisma as the spellcasting ability (spell save DC 14):

**1/day each**: [hallucinatory terrain](2-Mechanics/CLI/spells/hallucinatory-terrain.md) (as an action), [suggestion](2-Mechanics/CLI/spells/suggestion.md)

**3/day**: [charm person](2-Mechanics/CLI/spells/charm-person.md)

## Actions

***Multiattack.*** The mirager makes two Slam attacks. If both Slam attacks hit a Medium or smaller creature, the target is also [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) (escape DC 13). The mirager can grapple only one creature at a time.

***Slam.*** *Melee Weapon Attack:* `dice:1d20+5|noform|text(+5)` to hit, reach 5 ft., one target. *Hit:* `dice:2d6+3|noform|avg|text(10)` (`2d6 + 3`) bludgeoning damage.

***Thirsting Kiss.*** *Melee Spell Attack:* `dice:1d20+6|noform|text(+6)` to hit, reach 5 ft., one willing creature, or a creature that is [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) by the mirager, [incapacitated](2-Mechanics/CLI/rules/conditions.md#Incapacitated), or [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained). *Hit:* `dice:4d8+4|noform|avg|text(22)` (`4d8 + 4`) necrotic damage, and the mirager gains temporary hp equal to half that amount.

***Blow Kiss.*** The mirager blows a kiss at a creature [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed) by it. The target must make a DC 14 Charisma saving throw. On a failure, a creature takes `dice:5d6|noform|avg|text(17)` (`5d6`) psychic damage and is [stunned](2-Mechanics/CLI/rules/conditions.md#Stunned) until the end of its next turn. On a success, a creature takes half the damage and the [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed) condition immediately ends on it.

***Illusory Appearance.*** The mirager covers itself and anything it is wearing or carrying with a magical illusion that makes it look like another creature of its general size and Humanoid shape. The illusion ends if the mirager takes a bonus action to end it or if the mirager dies.

The changes wrought by this effect fail to hold up to physical inspection. For example, the mirager could appear to have smooth skin, but someone touching it would feel its rough, sand-like skin. Otherwise, a creature must take an action to visually inspect the illusion and succeed on a DC 20 Intelligence ([Investigation](2-Mechanics/CLI/rules/skills.md#Investigation)) check to discern that the mirager is disguised.

## Bonus Actions

***Sand Dancer.*** While in sandy terrain, the mirager takes the Dash or Disengage action.
```
^statblock

## Environment

desert