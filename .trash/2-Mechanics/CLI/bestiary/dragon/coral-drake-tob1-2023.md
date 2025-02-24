---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/tob1-2023
- monster/cr/7
- monster/environment/coastal
- monster/environment/underwater
- monster/size/medium
- monster/type/dragon
aliases: ["Coral Drake"]
---
# Coral Drake
*Source: Tome of Beasts 1 (2023 Edition) p. 140*  

*Swimming upright, this creature peels itself from the vibrant seascape and strikes with spined fins, shredding teeth, and a wickedly curved stinger.*

## Camouflaged Hunter

Like a piece of moving coral, this drake's coloration and scale patterns change to match nearby anemones, corals, seaweed, and sea urchins. This adaptation allows the creature considerable stealth in its natural habitat. It avoids combat if it can, preferring to hide and protect its young. Long serrated spines stretch from the coral drake's body, waving in brilliant colors against a blue sea.

## All Spikes and Needles

An array of spikes and slender protrusions form a jagged crown above the creature's narrow face, while a long snout stretches out in front. Inside its mouth, serrated teeth form multiple ringed ridges where its young feed on leftover scraps of food and small parasites. Needle-thin talons spring from finned appendages, and a stinger frilled with tiny barbs curves at the end of its slender tail.

A coral drake measures seven feet from the tip of its snout to its barbed tail. Thin and agile, the beast weighs less than 100 pounds. Both male and female coral drakes gestate their delicate eggs inside sacks within their mouths and throats. This oral incubation protects the vulnerable eggs, but only a handful ever reach maturity, as the parents use their ravenous spawn for defense.

## Poisonous Lairs

Coral drakes live in warm waters near great coral reefs. They hollow out small lairs and protect their meager hoards with the aid of the area's natural inhabitants. Because they are immune to poison, coral drakes often choose lairs nestled in forests of poisonous sea urchins, stinging anemones, and toxic corals. Aside from humankind, the coral drake harbors a great rivalry with dragon turtles. These beasts prize the same hunting grounds and nests and fight for supremacy in the richest reefs.

## Statblock

```ad-statblock
title: Coral Drake
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ToB1-2023/Coral%20Drake.webp#token)
*Medium dragon, Neutral Evil*

- **Armor Class** 16 (natural armor)
- **Hit Points** 127 (`15d8 + 60`)
- **Speed** 15 ft., swim 60 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|19 (+4)|17 (+3)|18 (+4)|10 (+0)|13 (+1)|10 (+0)|

- **Proficiency Bonus** +3
- **Saving Throws** Dexterity +6
- **Skills** Acrobatics +6, Perception +7, Stealth +6
- **Senses** darkvision 120 ft., passive Perception 17
- **Damage Resistances** cold
- **Damage Immunities** poison
- **Condition Immunities** [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** Draconic
- **Challenge** 7

## Traits

***Underwater Camouflage.*** The coral drake has advantage on Dexterity ([Stealth](2-Mechanics/CLI/rules/skills.md#Stealth)) checks made while underwater.

***Water Breathing.*** The coral drake can breathe only underwater.

## Actions

***Multiattack.*** The coral drake makes one Bite attack and two Spined Fin attacks. It can replace its Bite attack with a Stinger attack.

***Bite.*** *Melee Weapon Attack:* `dice:1d20+7|noform|text(+7)` to hit, reach 5 ft., one target. *Hit:* `dice:2d10+4|noform|avg|text(15)` (`2d10 + 4`) piercing damage.

***Spined Fin.*** *Melee Weapon Attack:* `dice:1d20+7|noform|text(+7)` to hit, reach 5 ft., one target. *Hit:* `dice:2d8+4|noform|avg|text(13)` (`2d8 + 4`) piercing damage.

***Stinger.*** *Melee Weapon Attack:* `dice:1d20+7|noform|text(+7)` to hit, reach 5 ft., one target. *Hit:* `dice:2d6+4|noform|avg|text(11)` (`2d6 + 4`) piercing damage, and the target must succeed on a DC 15 Constitution saving throw or be [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned) for 1 minute. While [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned), the target takes `dice:2d4|noform|avg|text(5)` (`2d4`) poison damage at the start of each of its turns. The target can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.

***Biting Breath (Recharge 5-6).*** The coral drake pressurizes the throat sacs that contain its growing young and spews tiny, ravenous hatchling drakes in a 15-foot cone. Each creature in the area must make a DC 15 Dexterity saving throw. On a failure, a creature takes `dice:6d6|noform|avg|text(21)` (`6d6`) piercing damage and is [blinded](2-Mechanics/CLI/rules/conditions.md#Blinded) for 1 minute. On a success, a creature takes half the damage and isn't [blinded](2-Mechanics/CLI/rules/conditions.md#Blinded). A [blinded](2-Mechanics/CLI/rules/conditions.md#Blinded) creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.
```
^statblock

## Environment

coastal, underwater