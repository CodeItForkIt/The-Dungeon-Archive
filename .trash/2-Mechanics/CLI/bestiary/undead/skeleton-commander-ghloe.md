---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/ghloe
- monster/cr/3
- monster/size/medium
- monster/type/undead
aliases: ["Skeleton Commander"]
---
# Skeleton Commander
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
title: Skeleton Commander
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/GHLoE/Skeleton%20Commander.webp#token)
*Medium undead, Lawful Evil*

- **Armor Class** 17 (battered splint mail)
- **Hit Points** 65 (`10d8 + 20`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|16 (+3)|10 (+0)|15 (+2)|11 (+0)|12 (+1)|14 (+2)|

- **Proficiency Bonus** +2
- **Saving Throws** Wisdom +3
- **Skills** Insight +3, Perception +3
- **Senses** darkvision 60 ft., passive Perception 13
- **Damage Vulnerabilities** bludgeoning
- **Damage Immunities** poison
- **Condition Immunities** [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** understands languages it knew in life but can't speak
- **Challenge** 3

## Actions

***Multiattack.*** The skeleton commander makes two pike attacks.

***Pike.*** *Melee Weapon Attack:* `dice:1d20+5|noform|text(+5)` to hit, reach 10 ft., one target. *Hit:* `dice:1d10+3|noform|avg|text(8)` (`1d10 + 3`) piercing damage and `dice:2d4|noform|avg|text(5)` (`2d4`) necrotic damage.

***Warlord Strike (Recharge 5-6).*** The skeleton commander makes one pike attack. The commander can use a bonus action to direct another undead who can see or hear the commander to attack the target the commander attacked this turn. That undead can use a reaction to make the attack, adding the commander's proficiency bonus to the damage roll.

## Reactions

***Brandish Standard.*** If an undead the skeleton commander can see within 30 feet of the commander makes an attack roll or saving throw, the commander can brandish the tattered banner on its pike. If the commander does so, the target can add a `dice:d4|noform|avg` (`d4`) to its roll, provided it can see the commander and isn't receiving this benefit from another commander.
```
^statblock