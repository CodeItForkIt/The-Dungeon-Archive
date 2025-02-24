---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/ghloe
- monster/cr/1-2
- monster/size/medium
- monster/type/undead
aliases: ["Skeleton Rifler"]
---
# Skeleton Rifler
*Source: Grim Hollow: Lairs of Etharis p. 86*  

> [!quote]  
> 
> A line of skeletons marches into the town square with military precision. They raise rifles and take aim at the temple in unison.

## Salvage

Firearms recovered from skeleton troopers are nonfunctional, but parts of them might be useful. Each firearm recovered can reduce the cost of making a similar firearm by 10 percent, up to 50 percent.

## Lore

- **DC 10 Intelligence ([Religion](2-Mechanics/CLI/rules/skills.md#Religion)).** Necromancers with advanced training and hefty resources can make skeletons that are linked in death to their firearms.  
- **DC 15 Intelligence ([Religion](2-Mechanics/CLI/rules/skills.md#Religion)).** A commander leads some platoons of skeleton troopers. This skeleton directs the attacks and enhances the efficiency of its undead underlings.  

> [!note] GM Advice
> 
> Skeletal troopers are effective when used as minions in the army of a higher-level threat. Cinematic battles focused on sieges or large battles are perfect for troopers. In these cases, having the troopers immune to turning until their powerful leader is defeated prevents anticlimactic encounters.
^gm-advice

## Statblock

```ad-statblock
title: Skeleton Rifler
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/GHLoE/Skeleton%20Rifler.webp#token)
*Medium undead, Lawful Evil*

- **Armor Class** 12 (rotting buff coat)
- **Hit Points** 26 (`4d8 + 8`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|10 (+0)|15 (+2)|15 (+2)| 7 (-2)|10 (+0)| 5 (-3)|

- **Proficiency Bonus** +2
- **Saving Throws** ⏤
- **Skills** Perception +2
- **Senses** darkvision 60 ft., passive Perception 12
- **Damage Vulnerabilities** bludgeoning
- **Damage Immunities** poison
- **Condition Immunities** [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** understands languages it knew in life but can't speak
- **Challenge** 1/2

## Traits

***Dead Rifle.*** The rifle a skeleton rifler carries is nonfunctional as a ranged weapon for a creature other than a skeleton rifler. For the skeleton rifler, the rifle never needs to be reloaded.

## Actions

***Bayonet.*** *Melee Weapon Attack:* `dice:1d20+4|noform|text(+4)` to hit, reach 5 ft., one target. *Hit:* `dice:1d6+2|noform|avg|text(5)` (`1d6 + 2`) piercing damage and `dice:1d6|noform|avg|text(3)` (`1d6`) necrotic damage.

***Dead Rifle.*** *Ranged Weapon Attack:* `dice:1d20+4|noform|text(+4)` to hit, range 40/120 ft., one target. *Hit:* `dice:1d12+2|noform|avg|text(8)` (`1d12 + 2`) piercing damage and `dice:1d6|noform|avg|text(3)` (`1d6`) necrotic damage.
```
^statblock