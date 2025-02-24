---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/tce
- monster/cr/
- monster/size/medium
- monster/type/aberration
aliases: ["Aberrant Spirit"]
---
# Aberrant Spirit
*Source: Tasha's Cauldron of Everything p. 109*  

```ad-statblock
title: Aberrant Spirit
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/TCE/Aberrant%20Spirit.webp#token)
*Medium aberration, Unaligned*


- **Speed** 30 ft., fly 30 ft. (beholderkin only; hover)

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|16 (+3)|10 (+0)|15 (+2)|16 (+3)|10 (+0)| 6 (-2)|

- **Proficiency Bonus** +2
- **Saving Throws** ⏤
- **Skills** ⏤
- **Senses** darkvision 60 ft., passive Perception 10
- **Damage Immunities** psychic
- **Languages** Deep Speech, understands the languages you speak
- **Challenge** 

## Traits

***Regeneration (Slaad Only).*** The aberration regains 5 hit points at the start of its turn if it has at least 1 hit point.

***Whispering Aura (Star Spawn Only).*** At the start of each of the aberration's turns, each creature within 5 feet of the aberration must succeed on a Wisdom saving throw against your spell save DC or take `dice:2d6|noform|avg` (`2d6`) psychic damage, provided that the aberration isn't [incapacitated](2-Mechanics/CLI/rules/conditions.md#Incapacitated).

## Actions

***Multiattack.*** The aberration makes a number of attacks equal to half this spell's level (rounded down).

***Eye Ray (Beholderkin Only).*** *Ranged Spell Attack:* `YourSpellAttack` to hit, range 150 ft., one creature. *Hit:* `1d8 + 3` + the spell's level psychic damage.

***Claws (Slaad Only).*** *Melee Weapon Attack:* `YourSpellAttack` to hit, reach 5 ft., one target. *Hit:* `1d10 + 3` + the spell's level slashing damage. If the target is a creature, it can't regain hit points until the start of the aberration's next turn.

***Psychic Slam (Star Spawn Only).*** *Melee Spell Attack:* `YourSpellAttack` to hit, reach 5 ft., one creature. *Hit:* `1d8 + 3` + the spell's level psychic damage.
```
^statblock