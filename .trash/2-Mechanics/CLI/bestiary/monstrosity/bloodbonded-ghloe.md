---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/ghloe
- monster/cr/4
- monster/size/medium
- monster/type/monstrosity
aliases: ["Bloodbonded"]
---
# Bloodbonded
*Source: Grim Hollow: Lairs of Etharis p. 39*  

> [!quote]  
> 
> Those who've turned their back on both the Seraphs and the Daemons? That way lies madness.

## Salvage

Bloodbonded still possess the damaged and scarred remnants of their past devotions. When a bloodbonded dies, its blood still pulses and gives off light as it did when it was alive. One vial of this blood can be harvested from a single bloodbonded with a successful DC 10 Wisdom ([Medicine](2-Mechanics/CLI/rules/skills.md#Medicine)) check. Drinking it within one day causes the user to be affected by a bless spell. When the spell ends, the user suffers one level of exhaustion.

## Lore

- **DC 10 Intelligence ([History](2-Mechanics/CLI/rules/skills.md#History)).** Bloodbonded are victims of their own foolish choices, worshipping false gods and then being driven mad by the ruse.  
- **DC 15 Intelligence ([Arcana](2-Mechanics/CLI/rules/skills.md#Arcana)).** Bloodbonded use their followers as weapons, even causing them to explode in a wave of fiery blood, which damages nearby creatures.  

## Statblock

```ad-statblock
title: Bloodbonded
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/GHLoE/Bloodbonded.webp#token)
*Medium monstrosity, Chaotic Evil*

- **Armor Class** 16 ([studded leather](2-Mechanics/CLI/items/studded-leather-armor.md), [shield](2-Mechanics/CLI/items/shield.md))
- **Hit Points** 66 (`12d8 + 12`)
- **Speed** 30 ft. (or 10 ft. if missing a leg)

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|12 (+1)|15 (+2)|13 (+1)|15 (+2)| 7 (-2)|18 (+4)|

- **Proficiency Bonus** +2
- **Saving Throws** Constitution +3, Wisdom +0
- **Skills** Deception +6, Insight +0, Persuasion +6
- **Senses** passive Perception 8
- **Damage Vulnerabilities** psychic
- **Damage Resistances** necrotic, radiant
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened)
- **Languages** Celestial, Infernal, one national language
- **Challenge** 4

## Traits

***Bloody Inspiration.*** As a bonus action, the bloodbonded can inspire an ally within 30 feet to an enraged state of bloodlust for one minute. These followers gain 5 temporary hp, resistance to bludgeoning, piercing, and slashing damage, and vulnerability to psychic damage. All attacks made by the bloodbonded followers are reckless, gaining advantage to hit enemies but granting enemies advantage on attacks against them.

***Resolute Followers.*** Allies of the bloodbonded within 60 feet of it have advantage on Charisma and Wisdom saving throws.

## Actions

***Mace.*** *Melee Weapon Attack:* `dice:1d20+3|noform|text(+3)` to hit, reach 5 ft., one target. *Hit:* `dice:1d6+1|noform|avg|text(4)` (`1d6 + 1`) bludgeoning damage.

***Rage Bomb (2/Day).*** As a bonus action, the bloodbonded can infuse one of its bloodbonded followers who is under the effects of Bloody Inspiration with a fatal fury. This magic causes the follower to foam bloodily at the mouth. If the follower is not slain before the start of the bloodbonded's next turn, the follower dies and explodes in a shower of superheated blood. Creatures within 10 feet must make a DC 14 Dexterity saving throw, taking `dice:2d8+3|noform|avg|text(12)` (`2d8 + 3`) fire damage on a failure and taking half damage on a success.

***Blood Boil.*** The bloodbonded targets a creature it can see within 60 feet and utters words of madness. The target must succeed on a DC 14 Constitution saving throw or take `dice:2d8|noform|avg|text(9)` (`2d8`) fire damage as its blood superheats. The bloodbonded must be able to speak to use this ability.

## Reactions

***Loyal Followers.*** When a bloodbonded would take damage from a melee or ranged attack it can see that targets only the bloodbonded, it can use its reaction to call on one of its followers within 5 feet to take the damage instead.
```
^statblock