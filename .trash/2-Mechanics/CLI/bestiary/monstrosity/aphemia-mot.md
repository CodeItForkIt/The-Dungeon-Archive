---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/mot
- monster/cr/5
- monster/size/medium
- monster/type/monstrosity
aliases: ["Aphemia"]
---
# Aphemia
*Source: Mythic Odysseys of Theros p. 226*  

The notorious Nyxborn harpy Aphemia prowls the marshy wastes around the necropolis of Asphodel. Her shrill songs enthrall the necropolis's undead inhabitants, which she leads on raids to waylay unsuspecting travelers and settlements.

Cruel, corpse-eating creatures, harpies endlessly seek their next meal, careless of whether it comes from the living or the dead. With equal zeal, these vicious scavengers set upon travelers or claw open fresh graves, stripping bodies of riches and flesh. Then they carry back any treasures or appealing bones they find to reeking nests situated in cramped caves or rotten trees.

```ad-statblock
title: Aphemia
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/MOT/Aphemia.webp#token)
*Medium monstrosity, Chaotic Evil*

- **Armor Class** 15 (natural armor)
- **Hit Points** 52 (`8d8 + 16`)
- **Speed** 20 ft., fly 50 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|13 (+1)|16 (+3)|15 (+2)|13 (+1)|14 (+2)|16 (+3)|

- **Proficiency Bonus** +3
- **Saving Throws** Dexterity +6, Charisma +6
- **Skills** Arcana +4, Intimidation +6, Perception +5
- **Senses** darkvision 120 ft., passive Perception 15
- **Damage Resistances** necrotic
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened)
- **Languages** Common
- **Challenge** 5

## Traits

***Legendary Resistance (2/Day).*** If Aphemia fails a saving throw, she can choose to succeed instead.

***Magic Resistance.*** Aphemia has advantage on saving throws against spells and other magical effects.

## Actions

***Multiattack.*** Aphemia makes two attacks: one with her bite and one with her claws.

***Bite.*** *Melee Weapon Attack:* `dice:1d20+6|noform|text(+6)` to hit, reach 5 ft., one target. *Hit:* `dice:2d4+3|noform|avg|text(8)` (`2d4 + 3`) piercing damage plus `dice:3d8|noform|avg|text(13)` (`3d8`) necrotic damage.

***Claws.*** *Melee Weapon Attack:* `dice:1d20+6|noform|text(+6)` to hit, reach 5 ft., one target. *Hit:* `dice:2d6+3|noform|avg|text(10)` (`2d6 + 3`) slashing damage.

***Discordant Song.*** Aphemia shrieks a cacophony of magical sounds. Each humanoid within 120 feet of her must succeed on a DC 14 Wisdom saving throw or be [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened) of her until the song ends. A [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened) creature takes `dice:2d6|noform|avg|text(7)` (`2d6`) psychic damage at the start of its turn while Aphemia is singing. A [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened) creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success. If a creature's saving throw is successful or the effect ends for it, the creature is immune to Aphemia's Discordant Song for the next 24 hours. Aphemia must take a bonus action on her subsequent turns to continue singing. She can stop singing at any time. The song ends if Aphemia is [incapacitated](2-Mechanics/CLI/rules/conditions.md#Incapacitated) or dies.

***Grave Calling Song.*** Aphemia intones a low, growling magical melody. Every undead within 300 feet of her must succeed on a DC 14 Wisdom saving throw or fall under her control until the song ends. Aphemia must take a bonus action on her subsequent turns to continue singing, and she can mentally command the undead under her control as part of the same bonus action. She can stop singing at any time. The song ends if Aphemia is [incapacitated](2-Mechanics/CLI/rules/conditions.md#Incapacitated) or dies.
```
^statblock