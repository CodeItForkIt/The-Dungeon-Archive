---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/vrgr
- monster/cr/6
- monster/size/huge
- monster/type/undead
aliases: ["Zombie Clot"]
---
# Zombie Clot
*Source: Van Richten's Guide to Ravenloft p. 255*  

Among the undead, a lone zombie ranks far from the most menacing. The horror of the shambling dead lies not in their individual menace, though, but their numbers, their persistence, and their disregard for their own well-being. A throng of zombies will douse a forest fire with their own ashes or march into a dragon's maw until the monster chokes. In the course of their relentless marches, zombies might suffer all manner of trauma, potentially reducing them to masses of crawling limbs (see swarm of zombie limbs), infecting them with terrible diseases (see zombie plague spreader), or crushing an entire horde into a single, rotting titan.

## Zombie Apocalypses

Among the types of horror adventures detailed in "chapter 2", tales of uncontrolled zombie outbreaks orbit the "dark fantasy" and "disaster horror" genres. The horror of these adventures focuses not on the terror of a single zombie, but of countless individual threats overwhelming society. When creating your own undead calamities, consider the plots presented on the Zombie Apocalypses table.

**Zombie Apocalypses**

`dice: [](zombie-clot-vrgr.md#^zombie-apocalypses)`

| dice: d4 | Zombie Plot |
|----------|-------------|
| 1 | A twisted wish causes those affected by healing magic and [potions of healing](2-Mechanics/CLI/items/potion-of-healing.md) to rise as zombies. |
| 2 | Overwhelming magic reanimates zombies again and again as [swarms of zombie limbs](2-Mechanics/CLI/bestiary/undead/swarm-of-zombie-limbs-vrgr.md). |
| 3 | The githyanki unleash [zombie plague spreaders](2-Mechanics/CLI/bestiary/undead/zombie-plague-spreader-vrgr.md) to scour mind flayers from a world. |
| 4 | The seals containing an underground zombie horde fail, releasing ancient [zombie clots](2-Mechanics/CLI/bestiary/undead/zombie-clot-vrgr.md). |
^zombie-apocalypses

## Statblock

```ad-statblock
title: Zombie Clot
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/VRGR/Zombie%20Clot.webp#token)
*Huge undead, Unaligned*

- **Armor Class** 12 (natural armor)
- **Hit Points** 104 (`11d12 + 33`)
- **Speed** 40 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|20 (+5)|10 (+0)|16 (+3)| 3 (-4)| 8 (-1)|10 (+0)|

- **Proficiency Bonus** +3
- **Saving Throws** Constitution +6
- **Skills** ⏤
- **Senses** darkvision 60 ft., passive Perception 9
- **Damage Immunities** poison
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed), [petrified](2-Mechanics/CLI/rules/conditions.md#Petrified), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned), [stunned](2-Mechanics/CLI/rules/conditions.md#Stunned)
- **Languages** understands the languages it knew in life but can't speak
- **Challenge** 6

## Traits

***Deathly Stench.*** Any creature that starts its turn within 10 feet of the zombie must succeed on a DC 14 Constitution saving throw or take `dice:2d8|noform|avg|text(9)` (`2d8`) poison damage and be [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned) until the start of the creature's next turn.

***Undead Fortitude.*** If damage reduces the zombie to 0 hit points, it must make a Constitution saving throw with a DC of 5 + the damage taken, unless the damage is radiant or from a critical hit. On a success, the zombie drops to 1 hit point instead.

***Unusual Nature.*** The zombie doesn't require air, food, drink, or sleep.

## Actions

***Multiattack.*** The zombie makes two Slam attacks.

***Slam.*** *Melee Weapon Attack:* `dice:1d20+8|noform|text(+8)` to hit, reach 10 ft., one target. *Hit:* `dice:3d8+5|noform|avg|text(18)` (`3d8 + 5`) bludgeoning damage.

***Flesh Entomb (Recharge 5-6).*** The zombie flings a detached clump of corpses at a creature it can see within 30 feet of it. The target must succeed on a DC 16 Strength saving throw or take `dice:3d10|noform|avg|text(16)` (`3d10`) bludgeoning damage, and if the target is a Large or smaller creature, it becomes entombed in dead flesh.

A creature entombed in the dead flesh is [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained), has total cover against attacks and other effects outside the dead flesh, and takes `dice:3d6|noform|avg|text(10)` (`3d6`) necrotic damage at the start of each of its turns. The creature can be freed if the dead flesh is destroyed. The dead flesh is a Large object with AC 10, 25 hit points, and immunity to poison and psychic damage.
```
^statblock