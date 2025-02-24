---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/ghloe
- monster/cr/1-8
- monster/size/small
- monster/type/humanoid/kobold
aliases: ["Morbus Kobold"]
---
# Morbus Kobold
*Source: Grim Hollow: Lairs of Etharis p. 29*  

> [!quote]  
> 
> If a group of lions is called a pride, a group of morbus kobolds is called an infection.

## Salvage

Someone who has proficiency with Medicine can attempt a DC 13 Wisdom ([Medicine](2-Mechanics/CLI/rules/skills.md#Medicine)) check to extract the largest tumor from a morbus kobold elder. If this check succeeds, someone who has proficiency with alchemist's supplies or an herbalism kit can wrap the tumor with herbs and reagents worth 200 gp. The wrapped tumor must be left in open air so it receives daily sunlight for 7 days. Someone must cast lesser restoration on the tumor during this time. At the end of the process, the tumor can be polished and set in a necklace, making a periapt of health.

## Lore

- **DC 13 Intelligence ([Nature](2-Mechanics/CLI/rules/skills.md#Nature)).** Morbus kobolds are a known for spreading disease. Despite their role in propagating contagions, they are immune to the effects of all known diseases.  
- **DC 13 Intelligence ([History](2-Mechanics/CLI/rules/skills.md#History)).** The first documented record of an encounter with a morbus kobold was in the city of Liesech during the early days of the Weeping Pox. Shortly after this encounter, the Weeping Pox began spreading in nearby regions.  
- **DC 16 Wisdom ([Medicine](2-Mechanics/CLI/rules/skills.md#Medicine)).** The largest tumors in morbus kobold elders can be treated then dried in sunlight to create a ward against diseases.  

## Statblock

```ad-statblock
title: Morbus Kobold
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/GHLoE/Morbus%20Kobold.webp#token)
*Small humanoid (kobold), Lawful Evil*

- **Armor Class** 12
- **Hit Points** 9 (`2d6 + 2`)
- **Speed** 30 ft., swim 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
| 6 (-2)|14 (+2)|13 (+1)|10 (+0)| 9 (-1)| 8 (-1)|

- **Proficiency Bonus** +2
- **Saving Throws** Constitution +3
- **Skills** Medicine +1, Stealth +4
- **Senses** darkvision 60 ft., passive Perception 9
- **Damage Resistances** poison
- **Languages** Draconic and one other language
- **Challenge** 1/8

## Traits

***Carrier.*** The morbus kobold can contract a disease but is immune to effects other than cosmetic symptoms.

***Infection.*** A creature that touches the morbus kobold or anything it has touched in the past 24 hours is exposed to a disease, usually sewer plague.

***Pack Tactics.*** The morbus kobold has advantage on an attack roll against a creature if at least one of the kobold's allies is within 5 feet of the creature and the ally isn't [incapacitated](2-Mechanics/CLI/rules/conditions.md#Incapacitated).

***Sunlight Sensitivity.*** While in sunlight, the morbus kobold has disadvantage on attack rolls, as well as on Wisdom ([Perception](2-Mechanics/CLI/rules/skills.md#Perception)) checks that rely on sight.

## Actions

***Dagger.*** *Melee or Ranged Weapon Attack:* `dice:1d20+4|noform|text(+4)` to hit, reach 5 ft. or range 20/60 ft., one target. *Hit:* `dice:1d4+2|noform|avg|text(4)` (`1d4 + 2`) piercing damage and Infection.

***Sling.*** *Ranged Weapon Attack:* `dice:1d20+4|noform|text(+4)` to hit, range 30/120 ft., one target. *Hit:* `dice:1d4+2|noform|avg|text(4)` (`1d4 + 2`) bludgeoning damage and Infection.

***Gore Bag.*** The morbus kobold throws a sack filled with diseased gore at a point it can see within 20 feet of it. Each creature within 5 feet of the chosen point is subjected to Infection. A kobold usually carries only one such bag at a time.
```
^statblock