---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/ghloe
- monster/cr/1
- monster/size/medium
- monster/type/undead
aliases: ["Shatter Corpse"]
---
# Shatter Corpse
*Source: Grim Hollow: Lairs of Etharis p. 16*  

> [!quote]  
> 
> The sound of breaking glass startles most, but think twice before going to see what caused it if it is followed by the sound of moaning.

## Salvage

The glass from ten shatter corpses can be used to create a suit of [glass-studded armor](2-Mechanics/CLI/items/glass-studded-armor-ghloe.md) (see Appendix A of Lairs of Etharis) with a successful DC 10 Dexterity ([Sleight of Hand](2-Mechanics/CLI/rules/skills.md#Sleight%20of%20Hand)) check by someone proficient with jeweler's tools. Crafting this item takes 10 days and costs 1000 gp.

## Lore

- **DC 10 Intelligence ([Religion](2-Mechanics/CLI/rules/skills.md#Religion)).** Shatter corpses are a stronger kind of zombie that arises when someone dies from being impaled on broken glass.  
- **DC 15 Intelligence ([History](2-Mechanics/CLI/rules/skills.md#History)).** Those that attempt to use a melee attack against a shatter corpse are likely to cut themselves unless they attack with carefully.  
- **DC 20 Intelligence ([Arcana](2-Mechanics/CLI/rules/skills.md#Arcana)).** Shatter corpses can launch volleys of broken glass.  

## Statblock

```ad-statblock
title: Shatter Corpse
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/GHLoE/Shatter%20Corpse.webp#token)
*Medium undead, Chaotic Neutral*

- **Armor Class** 10 (natural armor)
- **Hit Points** 45 (`6d8 + 18`)
- **Speed** 20 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|13 (+1)| 6 (-2)|16 (+3)| 3 (-4)| 6 (-2)| 5 (-3)|

- **Proficiency Bonus** +2
- **Saving Throws** Wisdom +0
- **Skills** ⏤
- **Senses** darkvision 60 ft., passive Perception 8
- **Damage Immunities** piercing, poison
- **Condition Immunities** [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** understands the languages it knew in life but can't speak
- **Challenge** 1

## Traits

***Glass Spikes.*** Each time a creature makes a melee attack against a shatter corpse, it takes 3 piercing damage. A creature can choose to make an attack with disadvantage to avoid this damage.

***Loud.*** Creatures have advantage on Wisdom ([Perception](2-Mechanics/CLI/rules/skills.md#Perception)) checks made to hear the approach of a shatter corpse.

***Turn Resistance.*** The shatter corpse has advantage on saving throws against any effect that turns undead.

***Undead Fortitude.*** If damage reduces the shatter corpse to 0 hit points, it must make a Constitution saving throw with a DC of 5 + the damage taken, unless the damage is radiant or from a critical hit. On a success, the shatter corpse drops to 1 hit point instead.

## Actions

***Slam.*** *Melee Weapon Attack:* `dice:1d20+3|noform|text(+3)` to hit, reach 5 ft., one target. *Hit:* `dice:1d6+1|noform|avg|text(4)` (`1d6 + 1`) bludgeoning damage and `dice:1d4|noform|avg|text(2)` (`1d4`) piercing damage.

***Volley of Glass (Recharge 6).*** The shatter corpse flicks a volley of glass shards in a 15-foot cone. Each creature in that area must make a DC 13 Dexterity saving throw, taking `dice:3d6|noform|avg|text(10)` (`3d6`) slashing damage on a failed save, or half as much damage on a successful one.
```
^statblock