---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/tob1-2023
- monster/cr/2
- monster/environment/underdark
- monster/environment/urban
- monster/size/small
- monster/type/humanoid/kobold
aliases: ["Kobold Alchemist"]
---
# Kobold Alchemist
*Source: Tome of Beasts 1 (2023 Edition) p. 244*  

*This slight, reptilian humanoid is bedecked with ceramic flasks and glass vials. An acrid reek follows in its wake.*

Kobold alchemists are usually smelled before they are seen, thanks to the apothecary's store of chemicals and poisons they carry. Alchemists often sport mottled and discolored scales and skin, caused by the caustic nature of their obsessions. They raid alchemy shops and magical laboratories to gather more material to fuel their alchemical experiments.

## Dangerous Assets

Alchemists can be a great boon to their clan, but at a cost. Not only do the alchemists require rare, expensive, and often dangerous substances to ply their trade, they tend to be a little unhinged. Their experiments yield powerful weapons and defensive concoctions that can save many kobold lives, but the destruction caused by an experiment gone awry can be devastating for the alchemist's neighbors.

## Statblock

```ad-statblock
title: Kobold Alchemist
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ToB1-2023/Kobold%20Alchemist.webp#token)
*Small humanoid (kobold), Lawful Neutral*

- **Armor Class** 15 ([studded leather](2-Mechanics/CLI/items/studded-leather-armor.md))
- **Hit Points** 44 (`8d6 + 16`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
| 7 (-2)|16 (+3)|15 (+2)|16 (+3)| 9 (-1)| 8 (-1)|

- **Proficiency Bonus** +2
- **Saving Throws** Dexterity +5
- **Skills** Arcana +5, Medicine +3
- **Senses** darkvision 60 ft., passive Perception 9
- **Damage Immunities** poison
- **Condition Immunities** [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** Common, Draconic
- **Challenge** 2

## Traits

***Apothecary.*** At the start of each of the kobold alchemist's turns, the alchemist chooses one of the following damage types: acid, cold, fire, lightning, or poison. The alchemist has resistance to that damage type until the start of its next turn.

***Pack Tactics.*** The kobold has advantage on attack rolls against a creature if at least one of the kobold's allies is within 5 feet of the creature and the ally isn't [incapacitated](2-Mechanics/CLI/rules/conditions.md#Incapacitated).

***Sunlight Sensitivity.*** While in sunlight, the kobold has disadvantage on attack rolls, as well as on Wisdom ([Perception](2-Mechanics/CLI/rules/skills.md#Perception)) checks that rely on sight.

## Actions

***Multiattack.*** The kobold makes two Alchemical Dagger or Alchemical Bolt attacks.

***Alchemical Dagger.*** *Melee Weapon Attack:* `dice:1d20+5|noform|text(+5)` to hit, reach 5 ft., one target. *Hit:* 5 `dice:1d4+3|noform|avg` (`1d4 + 3`) piercing damage plus `dice:1d6|noform|avg|text(3)` (`1d6`) damage of the type determined by Apothecary.

***Alchemical Bolt.*** *Ranged Spell Attack:* `dice:1d20+5|noform|text(+5)` to hit, range 60 ft., one target. *Hit:* `dice:2d6+3|noform|avg|text(10)` (`2d6 + 3`) damage of the type determined by Apothecary.

***Alchemical Vapors (Recharge 6).*** The kobold alchemist releases alchemical vapors pleasing to draconic senses and unpleasant to all others. Each creature that isn't a dragonborn or kobold within 15 feet of the alchemist must make a DC 13 Constitution saving throw, taking `dice:5d6|noform|avg|text(17)` (`5d6`) poison damage on a failed save, or half as much damage on a successful one. Each dragonborn and kobold within 15 feet of the alchemist has resistance to damage of the type determined by Apothecary for 1 minute.

***Explosive Flask (Recharge 5-6).*** The kobold alchemist throws a flask of volatile substances at a point it can see within 30 feet of it. The flask explodes, and each creature within 15 feet of that point must make a DC 13 Dexterity saving throw. On a failure, a creature takes 14 `dice:4d6|noform|avg` (`4d6`) damage of the type determined by Apothecary and is [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned) for 1 minute. On a success, a creature takes half the damage and isn't [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned). A [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned) creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.
```
^statblock

## Environment

underdark, urban