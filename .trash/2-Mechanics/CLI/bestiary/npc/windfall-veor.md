---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/veor
- monster/cr/23
- monster/size/medium
- monster/type/humanoid/bard
- monster/type/humanoid/tiefling
aliases: ["Windfall"]
---
# Windfall
*Source: Vecna: Eve of Ruin p. 153*  

As a dedicated champion of Tiamat, Windfall has been granted phenomenal power by her master. Her skin glitters with patches of multicolored scales, and in combat, her blade sings with all five of the chromatic dragons' elements. Windfall's enchanted tailcoat shimmers with the colors of the Dragon Queen, and she uses this coat to dazzle patrons and enemies alike.

A performer at heart, Windfall is ostentatious and charismatic, making small talk with regular patrons and jovially welcoming new faces to the casino.

```ad-statblock
title: Windfall
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/VEoR/Windfall.webp#token)
*Medium humanoid (bard, tiefling), Chaotic Evil*

- **Armor Class** 19 ([studded leather armor](2-Mechanics/CLI/items/studded-leather-armor.md))
- **Hit Points** 323 (`34d8 + 170`)
- **Speed** 30 ft., fly 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|14 (+2)|24 (+7)|20 (+5)|22 (+6)|18 (+4)|26 (+8)|

- **Proficiency Bonus** +7
- **Saving Throws** Strength +9, Dexterity +14, Wisdom +11, Charisma +15
- **Skills** Arcana +13, Deception +22, Insight +18, Perception +11, Performance +22, Persuasion +22, Sleight of Hand +14
- **Senses** darkvision 60 ft., passive Perception 21
- **Damage Resistances** acid, cold, fire, lightning, thunder
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened)
- **Languages** Common, Draconic, Infernal
- **Challenge** 23

## Traits

***Dazzling Visage.*** A brilliant array of chromatic colors emanates from Windfall, causing attack rolls against her to have disadvantage. This trait ceases to function while Windfall has the [incapacitated](2-Mechanics/CLI/rules/conditions.md#Incapacitated) condition or has a speed of 0.

***Legendary Resistance (3/Day).*** If Windfall fails a saving throw, she can choose to succeed instead.

***Special Equipment.*** Windfall wears an iridescent magic coat that was tailored specifically for her and imbued with Tiamat's power. When she dies, the coat functions as a Robe of Scintillating Colors.

***Spellcasting.*** Windfall casts one of the following spells, requiring no material components and using Charisma as the spellcasting ability (spell save DC 23):

**At will**: [Detect Magic](2-Mechanics/CLI/spells/detect-magic.md), [Light](2-Mechanics/CLI/spells/light.md), [Thaumaturgy](2-Mechanics/CLI/spells/thaumaturgy.md)

**1/day**: [Hold Monster](2-Mechanics/CLI/spells/hold-monster.md)

**2/day each**: [Hypnotic Pattern](2-Mechanics/CLI/spells/hypnotic-pattern.md), [Sending](2-Mechanics/CLI/spells/sending.md)

**3/day each**: [Shatter](2-Mechanics/CLI/spells/shatter.md), [Unseen Servant](2-Mechanics/CLI/spells/unseen-servant.md)

## Actions

***Multiattack.*** Windfall makes two Chromatic Rapier attacks and uses Dragon's Fury once.

***Chromatic Rapier.*** *Melee Weapon Attack:* `dice:1d20+14|noform|text(+14)` to hit, reach 5 ft., one target. *Hit:* `dice:1d8+7|noform|avg|text(11)` (`1d8 + 7`) piercing damage plus `dice:6d6|noform|avg|text(21)` (`6d6`) acid, cold, fire, lightning, or poison damage (Windfall's choice).

***Dragon's Fury.*** Windfall targets one creature she can see within 60 feet of herself and unleashes a burst of magical ire. The target must make a DC 23 Wisdom saving throw. On a failed save, the target takes `dice:8d8|noform|avg|text(36)` (`8d8`) psychic damage and has the [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened) condition until the start of Windfall's next turn. On a successful save, the target takes half as much damage only.

## Bonus Actions

***Stunning Scintillation (Recharge 5-6).*** Windfall emits an overwhelming array of colors from her coat. Each creature within 30 feet of Windfall that can see her must succeed on a DC 23 Constitution saving throw or have the [stunned](2-Mechanics/CLI/rules/conditions.md#Stunned) condition until the start of Windfall's next turn.

## Legendary Actions

***Deft Dance.*** Windfall moves up to her speed without provoking opportunity attacks.

***Dragon's Flare.*** Windfall flares with multicolored flames and targets a creature she can see within 30 feet of herself. The target must make a DC 23 Dexterity saving throw. On a failed save, the target takes `dice:4d12|noform|avg|text(26)` (`4d12`) damage of a type chosen by Windfall: acid, cold, fire, lightning, or poison. On a successful save, the target takes half as much damage.

***Cast a Spell (Costs 2 Actions).*** Windfall uses Spellcasting.
```
^statblock