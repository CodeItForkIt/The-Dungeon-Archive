---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/dsotdq
- monster/cr/3
- monster/size/medium
- monster/type/monstrosity
aliases: ["Dracophage Subject"]
---
# Dracophage Subject
*Source: Dragonlance: Shadow of the Dragon Queen p. 118*  

Kapak draconians are created using copper dragon eggs. These cunning opponents relish striking foes who are distracted or unaware. Kapaks often coat their weapons with their paralytic saliva, making them formidable assassins as well. Their small wings don't allow kapaks to fly, but they do help the draconians turn a fall into a rough glide. When they die, kapaks dissolve into acid that can splash onto nearby creatures.

## Draconians

Draconians are bipedal monsters born from metallic dragon eggs that have been corrupted by a combination of warped alchemy and the Dragon Queen's foul magic. The Dragon Armies closely guard the secret of the draconians' creation, allowing Krynn's metallic dragons to continue to think their eggs are being held hostage so they don't oppose the Dragon Queen's conquests.

## Statblock

```ad-statblock
title: Dracophage Subject
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/DSotDQ/Dracophage%20Subject.webp#token)
*Medium monstrosity, typically  Lawful Evil*

- **Armor Class** 15 (natural armor)
- **Hit Points** 39 (`6d8 + 12`)
- **Speed** 40 ft., climb 40 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|11 (+0)|17 (+3)|14 (+2)|12 (+1)|13 (+1)|11 (+0)|

- **Proficiency Bonus** +2
- **Saving Throws** Dexterity +5
- **Skills** Deception +4, Perception +3, Stealth +7
- **Senses** darkvision 60 ft., passive Perception 13
- **Damage Immunities** poison
- **Condition Immunities** [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** Common, Draconic
- **Challenge** 3

## Traits

***Death Throes.*** When the subject is reduced to 0 hit points, it dissolves into acid that splashes on those around it. Each creature within 5 feet of the subject must succeed on a DC 12 Dexterity saving throw or be covered in acid for 1 minute. A creature covered in the acid takes `dice:2d6|noform|avg|text(7)` (`2d6`) acid damage at the start of each of its turns. A creature can use its action to scrape or wash the acid off itself or another creature.

***Glide.*** When the subject falls and isn't [incapacitated](2-Mechanics/CLI/rules/conditions.md#Incapacitated), it subtracts up to 100 feet from the fall when calculating the fall's damage, and it can move up to 2 feet horizontally for every 1 foot it descends.

## Actions

***Claw.*** *Melee Weapon Attack:* `dice:1d20+5|noform|text(+5)` to hit, reach 5 ft., one target. *Hit:* `dice:1d4+3|noform|avg|text(5)` (`1d4 + 3`) piercing damage plus `dice:2d6|noform|avg|text(7)` (`2d6`) poison damage. If the target is a Humanoid, it must succeed on a DC 12 Constitution saving throw or be infected with a disease—a minuscule slaad egg.

A Humanoid host can carry only one slaad egg at a time. Over three months, the egg moves to the chest cavity, gestates, and forms a slaad tadpole. In the 24-hour period before the tadpole is born, the host feels unwell; its speed is halved; and it has disadvantage on attack rolls, ability checks, and saving throws. At birth, the tadpole chews its way through vital organs and out of the host's chest in 1 round, killing the host in the process.

If the disease is cured before the tadpole's emergence, the tadpole disintegrates.
```
^statblock