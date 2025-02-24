---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/tob1-2023
- monster/cr/2
- monster/environment/badlands
- monster/environment/desert
- monster/size/medium
- monster/type/undead
aliases: ["Gray Thirster"]
---
# Gray Thirster
*Source: Tome of Beasts 1 (2023 Edition) p. 221*  

*This dried-out body of a long dead traveler is still clad in the tattered remains of its clothes. Its skin, as dry as parchment, clings to its bones, and a hoarse moaning emanates from its dry, cracked lips.*

## Thirsting Undead

The greatest danger to people traversing badlands and deserts is thirst, and even the best prepared can find themselves without water. The lucky ones die quickly, while those less fortunate linger in sun-addled torment for days. These souls sometimes rise from the sand as gray thirsters, driven to inflict the torment they suffered upon other travelers.

## Destroy Wells and Oases

Gray thirsters destroy or foul sources of water and often lurk near such sources to ambush those seeking clean water.

## Thirsting Caravan

Though they hunt alone, in at least one case an entire caravan died of thirst and rose again as gray thirsters. Called the dust caravan, it prowls the deep desert accompanied by skin-changing gnolls, shrieking ghouls, and a mummy lord, building a strange, nomadic army.

## Statblock

```ad-statblock
title: Gray Thirster
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ToB1-2023/Gray%20Thirster.webp#token)
*Medium undead, Neutral Evil*

- **Armor Class** 13
- **Hit Points** 52 (`8d8 + 16`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|12 (+1)|16 (+3)|15 (+2)| 6 (-2)|12 (+1)|14 (+2)|

- **Proficiency Bonus** +2
- **Saving Throws** ⏤
- **Skills** Stealth +5
- **Senses** darkvision 60 ft., passive Perception 11
- **Damage Resistances** necrotic
- **Damage Immunities** fire, poison
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** understands the languages it knew in life but can't speak
- **Challenge** 2

## Traits

***Thirst Aura.*** A creature that starts its turn within 30 feet of the gray thirster must succeed on a DC 12 Constitution saving throw or suffer one level of [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion). On a successful saving throw, the creature is immune to the gray thirster's Thirst Aura for the next 24 hours.

***Thirsting Dead Nature.*** The gray thirster doesn't require air, food, or sleep.

## Actions

***Multiattack.*** The gray thirster makes two Claw attacks, or it makes one Claw attack and one Withering Turban attack.

***Claw.*** *Melee Weapon Attack:* `dice:1d20+5|noform|text(+5)` to hit, reach 5 ft., one target. *Hit:* `dice:2d4+3|noform|avg|text(8)` (`2d4 + 3`) slashing damage.

***Withering Turban.*** *Melee Weapon Attack:* `dice:1d20+5|noform|text(+5)` to hit, reach 10 ft., one creature. *Hit:* `dice:1d8+3|noform|avg|text(7)` (`1d8 + 3`) necrotic damage. The target must succeed on a DC 12 Constitution saving throw or its hp maximum is reduced by an amount equal to the damage taken. The target has disadvantage on this saving throw if it failed the saving throw against the thirster's Thirst Aura. This reduction lasts until the target finishes a long rest with no levels of [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion). The target dies if this effect reduces its hp maximum to 0.

***Drought (1/Day).*** The gray thirster draws the moisture from containers and creatures around it. Nonmagical water and other liquids within 20 feet of the thirster that aren't being worn or carried turn to dust. Each creature within 20 feet of the thirster that isn't a Construct or Undead must make a DC 12 Constitution saving throw. On a failure, a creature takes `dice:2d8|noform|avg|text(9)` (`2d8`) necrotic damage and up to 5 gallons of nonmagical liquid it is wearing or carrying turn to dust. On a success, a creature takes half the damage, and nonmagical liquids it is wearing or carrying don't turn to dust. Plants, Oozes, creatures with the Amphibious or Water Breathing trait, and creatures made mostly of water, such as water elementals or steam mephitis, have disadvantage on the saving throw.
```
^statblock

## Environment

badlands, desert