---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/hwcs
- monster/cr/5
- monster/size/medium
- monster/type/humanoid/corvum
aliases: ["Corvum Assassin"]
---
# Corvum Assassin
*Source: Humblewood Campaign Setting p. 194*  

Frequently members of criminal organizations, contract killers can be found in the Wood's largest and most politically complex perches. They serve powerful figures with a lack of scruples and an abundance of coin. Assassins are trained from a young age to become deadly masters of their craft, learning how to skulk the branchroads and keep hidden in the canopy to time the perfect ambush. Corvums, with their natural intelligence and cunning, make the best assassins.

```ad-statblock
title: Corvum Assassin
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/HWCS/Corvum%20Assassin.webp#token)
*Medium humanoid (corvum), Lawful Neutral*

- **Armor Class** 15 ([studded leather armor](2-Mechanics/CLI/items/studded-leather-armor.md))
- **Hit Points** 54 (`12d8`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|10 (+0)|16 (+3)|11 (+0)|14 (+2)|14 (+2)|10 (+0)|

- **Proficiency Bonus** +3
- **Saving Throws** Dexterity +6, Intelligence +5
- **Skills** Insight +5, Nature +5, Perception +8, Stealth +9
- **Senses** passive Perception 18
- **Languages** Birdfolk, Thieves' Cant, can also understand Auran but can't speak it
- **Challenge** 5

## Traits

***Glide.*** When falling at least 10 feet, the assassin can spend a reaction to fly up to their speed in one direction as they descend. They land in an unoccupied space at the end of their movement, and take no falling damage. They cannot glide while carrying heavy objects, heavy weapons, or shields (though they can drop any held items as part of their reaction).

***Talons.*** The assassin has advantage on Strength ([Athletics](2-Mechanics/CLI/rules/skills.md#Athletics)) checks made to climb any surface their talons could reasonably grip.

***Assassinate.*** During their first turn, the assassin has advantage on attack rolls against any creature that hasn't taken a turn. Any hit the assassin scores against a surprised creature is a critical hit.

***Sneak Attack.*** Once per turn, the assassin deals an extra `dice:3d6|noform|avg|text(10)` (`3d6`) damage when they hit a target with a weapon attack and have advantage on the attack roll, or when the target is within 5 feet of an ally of the assassin that isn't [incapacitated](2-Mechanics/CLI/rules/conditions.md#Incapacitated) and the assassin doesn't have disadvantage on the attack roll.

***Skulker.*** The assassin has advantage on Dexterity ([Stealth](2-Mechanics/CLI/rules/skills.md#Stealth)) checks made in dim light or darkness.

## Actions

***Multiattack.*** The assassin makes two melee attacks: one with their shortsword and one with their dagger. Or the assassin makes two ranged attacks with their daggers.

***Talons.*** *Melee Weapon Attack:* `dice:1d20+5|noform|text(+5)` to hit, reach 5 ft., one target. *Hit:* `dice:1d4+3|noform|avg|text(5)` (`1d4 + 3`) slashing damage.

***Shortsword.*** *Melee Weapon Attack:* `dice:1d20+5|noform|text(+5)` to hit, reach 5 ft., one target. *Hit:* `dice:1d6+3|noform|avg|text(5)` (`1d6 + 3`) piercing damage, and the target must make a DC 13 Constitution saving throw, taking `dice:3d6|noform|avg|text(10)` (`3d6`) poison damage on a failed save, or half as much damage on a successful one. 

***Dagger.*** *Melee or Ranged Weapon Attack:* `dice:1d20+5|noform|text(+5)` to hit, reach 5 ft. or range 20/60 ft., one target. *Hit:* `dice:1d4+3|noform|avg|text(5)` (`1d4 + 3`) piercing damage, and the target must make a DC 13 Constitution saving throw, taking `dice:3d6|noform|avg|text(10)` (`3d6`) poison damage on a failed save, or half as much damage on a successful one. 
```
^statblock