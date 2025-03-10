---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/ftd
- monster/cr/6
- monster/size/huge
- monster/type/monstrosity
aliases: ["Dragonflesh Abomination"]
---
# Dragonflesh Abomination
*Source: Fizban's Treasury of Dragons p. 187*  

A dragonflesh abomination is the final stage of a grafter's transformation—a hulking monster whose corrupted brain is ablaze with desire for treasure. Its abhorrent transformation erases the last vestiges of its previous life. It sprouts a tail and clumsy wings and grows to enormous size, barely retaining a bipedal shape. Its stomach churns with acid, causing noxious fumes to waft from its mouth and providing it with a caustic breath weapon. Its body is in a constant state of growth and change, allowing it to quickly heal from its wounds.

These creatures are most often found in abandoned dragon lairs, temples to Tiamat, or other sites associated with the dragons they love.

## Dragonflesh Grafters

Dragonflesh grafters practice forbidden rituals and risky experiments on themselves, modifying their bodies and minds to emulate the dragons they revere. They collect dragon parts—scales, teeth, skin, flesh, wings, and bones—that they scavenge from around dragon lairs, take from dragon corpses, or buy from merchants and adventurers. They stitch on, implant, or ingest these dragon parts, attempting to incorporate them into their own bodies and absorb the latent magic that lingers in a draconic corpse.

While most would-be grafters wind up hideously scarred or dead, a few survive as wretched horrors. Their minds become twisted by magical malevolence, with only a shadow of their former selves remaining. In the most extreme cases, the resulting abomination holds no remnant of the person it once was and is utterly ruled by a dragon's lust for treasure.

## Statblock

```ad-statblock
title: Dragonflesh Abomination
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/FTD/Dragonflesh%20Abomination.webp#token)
*Huge monstrosity, typically  Neutral Evil*

- **Armor Class** 15 (natural armor)
- **Hit Points** 66 (`7d12 + 21`)
- **Speed** 30 ft., fly 40 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|18 (+4)|14 (+2)|17 (+3)| 5 (-3)|12 (+1)| 6 (-2)|

- **Proficiency Bonus** +3
- **Saving Throws** Strength +7, Constitution +6
- **Skills** ⏤
- **Senses** passive Perception 11
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** understands Common and Draconic but can't speak
- **Challenge** 6

## Traits

***Cloying Miasma.*** The abomination is surrounded by a noxious stench. At the start of the abomination's turn, any creature within 5 feet of it must succeed on a DC 14 Constitution saving throw or be [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned) until the start of the abomination's next turn.

***Regeneration.*** The abomination regains 10 hit points at the start of its turns if it has at least 1 hit point.

## Actions

***Multiattack.*** The abomination makes three attacks using Claw, Acidic Spit, or a combination of them. It can replace one of the attacks with a Tail attack.

***Claw.*** *Melee Weapon Attack:* `dice:1d20+7|noform|text(+7)` to hit, reach 10 ft., one target. *Hit:* `dice:1d8+4|noform|avg|text(8)` (`1d8 + 4`) slashing damage plus `dice:1d10|noform|avg|text(5)` (`1d10`) poison damage.

***Tail.*** *Melee Weapon Attack:* `dice:1d20+7|noform|text(+7)` to hit, reach 15 ft., one target. *Hit:* `dice:1d12+4|noform|avg|text(10)` (`1d12 + 4`) bludgeoning damage. If the target is a creature, it must succeed on a DC 15 Strength saving throw or be knocked [prone](2-Mechanics/CLI/rules/conditions.md#Prone).

***Acidic Spit.*** *Ranged Weapon Attack:* `dice:1d20+5|noform|text(+5)` to hit, range 60 ft., one target. *Hit:* `dice:3d6|noform|avg|text(10)` (`3d6`) acid damage.

***Acid Belch (Recharge 5-6).*** The abomination belches forth a cloud of acidic gas in a 30-foot cone. Each creature in that area must make a DC 14 Constitution saving throw, taking `dice:8d6|noform|avg|text(28)` (`8d6`) acid damage on a failed save, or half as much damage on a successful one.
```
^statblock