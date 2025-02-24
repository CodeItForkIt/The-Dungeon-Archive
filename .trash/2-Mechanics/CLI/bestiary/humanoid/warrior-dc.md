---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/dc
- monster/cr/
- monster/size/medium
- monster/type/humanoid
aliases: ["Warrior"]
---
# Warrior
*Source: Divine Contention*  

```ad-statblock
title: Warrior
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/DC/Warrior.webp#token)
*Medium humanoid, Unaligned*

- **Armor Class** 21 ([plate](2-Mechanics/CLI/items/plate-armor.md), [shield](2-Mechanics/CLI/items/shield.md))
- **Hit Points** 78 (`12d8 + 24`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|18 (+4)|14 (+2)|14 (+2)|10 (+0)|12 (+1)|10 (+0)|

- **Proficiency Bonus** +2
- **Saving Throws** Constitution +6
- **Skills** Athletics +8, Perception +5, Survival +5
- **Senses** passive Perception 15
- **Languages** Common, plus one of your choice
- **Challenge** 

## Traits

***Battle Readiness.*** The warrior has advantage on initiative rolls.

***Improved Critical.*** The warrior's attack rolls score a critical hit on a roll of 19 or 20 on the `dice:d20|noform|avg` (`d20`).

***Improved Defense.*** The warrior's AC increases by 1.

***Indomitable (1/Day).*** The warriorcan reroll a saving throw that it fails, but it must use the new result.

***Martial Role.*** The warrior has one of the following traits of your choice:

- **Attacker.** The warrior gains a +2 bonus to attack rolls.  
- **Defender.** The warrior gains the Protection reaction below.  

***Second Wind (Recharges after a Short or Long Rest).*** The warrior can use a bonus action on its turn to regain hit points equal to `dice:1d10|noform|avg` (`1d10`) + its level.

## Actions

***Extra Attack.*** The warrior can attack three times, instead of once, whenever it takes the attack action on its turn.

***Longsword.*** *Melee Weapon Attack:* `dice:1d20+8|noform|text(+8)` to hit, reach 5 ft., one target. *Hit:* `dice:1d8+4|noform|avg|text(8)` (`1d8 + 4`) slashing damage, or `dice:1d10+4|noform|avg|text(9)` (`1d10 + 4`) slashing damage if used with two hands.

***Longbow.*** *Ranged Weapon Attack:* `dice:1d20+6|noform|text(+6)` to hit, range 150/600 ft., one target. *Hit:* `dice:1d8+2|noform|avg|text(6)` (`1d8 + 2`) piercing damage.

## Reactions

***Protection (Defender Only).*** When a creature the warrior can see attacks a target other than the warrior that is within 5 feet of the warrior, the warrior can use their reaction to impose disadvantage on the attack roll. The warrior must be wielding a shield.
```
^statblock