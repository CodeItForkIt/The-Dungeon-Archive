---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/ghloe
- monster/cr/2
- monster/size/medium
- monster/type/undead
aliases: ["Skeleton Cannoneer"]
---
# Skeleton Cannoneer
*Source: Grim Hollow: Lairs of Etharis p. 87*  

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
title: Skeleton Cannoneer
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/GHLoE/Skeleton%20Cannoneer.webp#token)
*Medium undead, Lawful Evil*

- **Armor Class** 14 (rotting buff coat)
- **Hit Points** 52 (`8d8 + 16`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|12 (+1)|16 (+3)|15 (+2)| 8 (-1)|13 (+1)| 5 (-3)|

- **Proficiency Bonus** +2
- **Saving Throws** ⏤
- **Skills** Perception +3
- **Senses** darkvision 120 ft., passive Perception 13
- **Damage Vulnerabilities** bludgeoning
- **Damage Immunities** poison
- **Condition Immunities** [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** understands languages it knew in life but can't speak
- **Challenge** 2

## Traits

***Dead Firearms.*** The cannon and pistol a skeleton cannoneer uses are nonfunctional as ranged weapons for a creature other than a skeleton cannoneer. For the skeleton cannoneer, the pistol never needs to be reloaded.

## Actions

***Load.*** The skeleton cannoneer loads the dead cannon.

***Dead Cannon.*** The skeleton cannoneer fires its loaded cannon at a point it can see within 500 feet of it, but no closer than 50 feet from it. Each creature within 15 feet of that point must make a DC 13 Dexterity saving throw, taking `dice:2d6|noform|avg|text(7)` (`2d6`) bludgeoning damage and `dice:2d6|noform|avg|text(7)` (`2d6`) necrotic damage on a failed save, or half as much damage on a successful one.

Alternatively, the cannoneer can choose the cannon as the point of fire. Doing so means the shot goes off inside the cannon, destroying it and increasing each type of damage by `dice:1d6|noform|avg|text(3)` (`1d6`).

***Pistol Club.*** *Melee Weapon Attack:* `dice:1d20+5|noform|text(+5)` to hit, reach 5 ft., one target. *Hit:* `dice:1d6+2|noform|avg|text(5)` (`1d6 + 2`) bludgeoning damage and `dice:1d6|noform|avg|text(3)` (`1d6`) necrotic damage.

***Dead Pistol.*** *Ranged Weapon Attack:* `dice:1d20+5|noform|text(+5)` to hit, range 30/90 ft., one target. *Hit:* `dice:1d10+3|noform|avg|text(8)` (`1d10 + 3`) piercing damage plus `dice:1d6|noform|avg|text(3)` (`1d6`) necrotic damage.
```
^statblock