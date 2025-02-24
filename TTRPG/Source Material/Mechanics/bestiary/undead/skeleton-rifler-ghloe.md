---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/ghloe
- monster/cr/1-2
- monster/size/medium
- monster/type/undead
statblock: inline
aliases: ["Skeleton Rifler"]
---
# [Skeleton Rifler](Mechanics\bestiary\undead/skeleton-rifler-ghloe.md)
*Source: Grim Hollow: Lairs of Etharis p. 86*  

> [!quote]  
> 
> A line of skeletons marches into the town square with military precision. They raise rifles and take aim at the temple in unison.

## Salvage

Firearms recovered from skeleton troopers are nonfunctional, but parts of them might be useful. Each firearm recovered can reduce the cost of making a similar firearm by 10 percent, up to 50 percent.

## Lore

- **DC 10 Intelligence ([Religion](Mechanics/Rules/skills.md#Religion)).** Necromancers with advanced training and hefty resources can make skeletons that are linked in death to their firearms.  
- **DC 15 Intelligence ([Religion](Mechanics/Rules/skills.md#Religion)).** A commander leads some platoons of skeleton troopers. This skeleton directs the attacks and enhances the efficiency of its undead underlings.  

> [!note] GM Advice
> 
> Skeletal troopers are effective when used as minions in the army of a higher-level threat. Cinematic battles focused on sieges or large battles are perfect for troopers. In these cases, having the troopers immune to turning until their powerful leader is defeated prevents anticlimactic encounters.
^gm-advice

```statblock
"name": "Skeleton Rifler (GHLoE)"
"size": "Medium"
"type": "undead"
"alignment": "Lawful Evil"
"ac": !!int "12"
"ac_class": "rotting buff coat"
"hp": !!int "26"
"hit_dice": "4d8 + 8"
"stats":
- !!int "10"
- !!int "15"
- !!int "15"
- !!int "7"
- !!int "10"
- !!int "5"
"speed": "30 ft."
"skillsaves":
  "Perception": !!int "2"
"damage_vulnerabilities": "bludgeoning"
"damage_immunities": "poison"
"condition_immunities": "[exhaustion](Mechanics/Rules/conditions.md#Exhaustion), [poisoned](Mechanics/Rules/conditions.md#Poisoned)"
"senses": "darkvision 60 ft., passive Perception 12"
"languages": "understands languages it knew in life but can't speak"
"cr": "1/2"
"traits":
- "desc": "The rifle a skeleton rifler carries is nonfunctional as a ranged weapon\
    \ for a creature other than a skeleton rifler. For the skeleton rifler, the rifle\
    \ never needs to be reloaded."
  "name": "Dead Rifle"
"actions":
- "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 5 (1d6\
    \ + 2) piercing damage and 3 (1d6) necrotic damage."
  "name": "Bayonet"
- "desc": "Ranged Weapon Attack: +4 to hit, range 40/120 ft., one target. Hit:\
    \ 8 (1d12 + 2) piercing damage and 3 (1d6) necrotic damage."
  "name": "Dead Rifle"
"source":
- "GHLoE"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/GHLoE/Skeleton%20Rifler.webp"
```
^statblock