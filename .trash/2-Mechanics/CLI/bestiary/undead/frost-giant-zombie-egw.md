---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/egw
- monster/cr/9
- monster/size/huge
- monster/type/undead
aliases: ["Frost Giant Zombie"]
---
# Frost Giant Zombie
*Source: Explorer's Guide to Wildemount p. 288*  

An unknown Aeorian object of immense power and mystery was uncovered and brought to the Fortress of the Dead Jarl in Eiselcross to please the ruling frost giant, Conessa Berg. The object's unstable nature unleashed a burst of corroding arcane power, ravaging the denizens of the stronghold with twisting necromantic energies, transforming them into monstrous, rime-infused undead. These hulking brutes now wander the ruined landscape surrounding their cursed home, hunting and destroying all living things with a frightening ferocity.

The battered, butchered, and frozen remains of would-be heroes litter battle sites where these undead giants have been encountered. Underestimating these towering horrors has been the folly of numerous expeditions to the northern reaches of Eiselcross, with only rumors often finding their way back as proof that these frigid monsters even exist.

```ad-statblock
title: Frost Giant Zombie
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/EGW/Frost%20Giant%20Zombie.webp#token)
*Huge undead, Neutral Evil*

- **Armor Class** 15 (patchwork armor)
- **Hit Points** 138 (`12d12 + 60`)
- **Speed** 40 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|23 (+6)| 6 (-2)|21 (+5)| 3 (-4)| 6 (-2)| 5 (-3)|

- **Proficiency Bonus** +4
- **Saving Throws** Wisdom +2
- **Skills** ⏤
- **Senses** darkvision 60 ft., passive Perception 8
- **Damage Immunities** cold, poison
- **Condition Immunities** [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** understands Giant but can't speak
- **Challenge** 9

## Traits

***Numbing Aura.*** Any creature that starts its turn within 10 feet of the zombie must make a DC 17 Constitution saving throw. Unless the save succeeds, the creature can't make more than one attack, or take a bonus action on that turn.

***Undead Fortitude.*** If damage reduces the zombie to 0 hit points, it must make a Constitution saving throw with a DC of 5 + the damage taken, unless the damage is fire, radiant, or from a critical hit. On a success, the zombie drops to 1 hit point instead.

## Actions

***Multiattack.*** The zombie makes two weapon attacks.

***Greataxe.*** *Melee Weapon Attack:* `dice:1d20+10|noform|text(+10)` to hit, reach 10 ft., one target. *Hit:* `dice:3d12+6|noform|avg|text(25)` (`3d12 + 6`) slashing damage.

***Hurl Rock.*** *Ranged Weapon Attack:* `dice:1d20+10|noform|text(+10)` to hit, range 60/240 ft., one target. *Hit:* `dice:4d10+6|noform|avg|text(28)` (`4d10 + 6`) bludgeoning damage.

***Freezing Stare.*** The zombie targets one creature it can see within 60 feet of it. The target must succeed on a DC 17 Constitution saving throw or take `dice:10d6|noform|avg|text(35)` (`10d6`) cold damage and be [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed) until the end of its next turn.
```
^statblock