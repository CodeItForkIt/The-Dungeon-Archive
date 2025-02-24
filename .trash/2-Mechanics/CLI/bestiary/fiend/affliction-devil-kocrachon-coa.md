---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/coa
- monster/cr/10
- monster/size/medium
- monster/type/fiend/devil
aliases: ["Affliction Devil (Kocrachon)"]
---
# Affliction Devil (Kocrachon)
*Source: Chains of Asmodeus p. 236*  

Masters of torture and pain, kocrachons are some of the most respected lesser devils in the Nine Hells. Each is driven to break the greatest number of creatures during their lifespan—the bigger and more dangerous their charges, the better. The most effective kocrachons study under other torturers, or in infernal schools, to best understand the physiologies of any victim they might come across. Perhaps due to their nature as clandestine torturers, kocrachons abhor direct conflict, choosing instead to flee if given the option.

## Devils with Purpose

They're insect-like and have a brightly colored carapace, with retractable wings, multiple arms and legs, and pincer-like hands. Even their heads appear strangely insectoid, often with multiple proboscises, eyes and false eyes, and waving antennae. Kocrachon inject a lethal poison into victims and, if they acquire the information they needed, may cure said poison.

## Flame and Ice

Though they are just as comfortable in the fires of the Nine Hells as any other devil, unlike many other of their peers, kocrachons are also resilient to the cold. This makes them useful in Stygia and Cania, where they are often employed by the archdevils of those layers to wring information from recalcitrant opponents. Their affinity to the cold also provides kocrachons with other, more interesting avenues of torture.

## Statblock

```ad-statblock
title: Affliction Devil (Kocrachon)
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/CoA/Affliction%20Devil%20%28Kocrachon%29.webp#token)
*Medium fiend (devil), Lawful Evil*

- **Armor Class** 20 (natural armor)
- **Hit Points** 104 (`16d8 + 32`)
- **Speed** 30 ft., fly 60 ft. (hover)

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|16 (+3)|19 (+4)|15 (+2)|17 (+3)|12 (+1)|14 (+2)|

- **Proficiency Bonus** +4
- **Saving Throws** Dexterity +8, Intelligence +7
- **Skills** Deception +6, Intimidation +6, Perception +5, Stealth +8
- **Senses** darkvision 120 ft., passive Perception 15
- **Damage Resistances** bludgeoning, piercing, slashing from nonmagical attacks that aren't silvered
- **Damage Immunities** cold, fire, poison
- **Condition Immunities** [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** Infernal, telepathy 120 ft.
- **Challenge** 10

## Traits

***Devil's Sight.*** Magical darkness doesn't impede the kocrachon's darkvision.

***Infernal Rot.*** A creature afflicted with this disease has the [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned) condition until the disease ends. While diseased, creatures gain no benefits from a long rest, gaining [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion) when necessary. If a creature dies while afflicted with Infernal Rot, its corpse transforms into a newborn kocrachon after `dice:1d8|noform|avg|text(4)` (`1d8`) days.

***Magic Resistance.*** The kocrachon has advantage on saving throws against spells and other magical effects.

***Sadism.*** The kocrachon gains a +1 bonus to attack and damage rolls for each different creature it damaged on its previous turn.

## Actions

***Multiattack.*** The kocrachon makes three Claw attacks. It can replace one of the attacks with a Proboscis attack.

***Claw.*** *Melee Weapon Attack:* `dice:1d20+8|noform|text(+8)` to hit, reach 5 ft., one target. *Hit:* `dice:2d6+4|noform|avg|text(11)` (`2d6 + 4`) slashing damage.

***Proboscis.*** *Melee Weapon Attack:* `dice:1d20+8|noform|text(+8)` to hit, reach 10 ft., one target. *Hit:* `dice:1d12+4|noform|avg|text(10)` (`1d12 + 4`) piercing damage plus `dice:4d6|noform|avg|text(14)` (`4d6`) poison damage. Creatures damaged by this attack must succeed on a DC 16 Constitution saving throw or suffer the Infernal Rot disease.
```
^statblock