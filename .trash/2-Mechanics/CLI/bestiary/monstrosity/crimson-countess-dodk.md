---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/dodk
- monster/cr/8
- monster/size/medium
- monster/type/monstrosity
aliases: ["Crimson Countess"]
---
# Crimson Countess
*Source: Dungeons of Drakkenheim p. 208*  

The Crimson Countess is a powerful harpy matriarch. Recognizable by her red-feathered wings and deep crimson hair, she is clad in black and gold armour and carries with her a spear that crackles with electrical energies.

-     - **Personality Trait.** I screech blood-curdling war cries and perform aerial stunts as intimidation.    
-     - **Ideal.** Any who walk the earth are prey for those who soar the sky.    
-     - **Bond.** I collect trophies from my kills to remind my flock who is the mightiest.    
-     - **Flaw.** I am aggressively territorial, envious of my rivals, and covetous of my trinkets.    

```ad-statblock
title: Crimson Countess
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/DoDk/Crimson%20Countess.webp#token)
*Medium monstrosity, Chaotic Evil*

- **Armor Class** 17 (natural armor)
- **Hit Points** 130 (`20d8 + 40`)
- **Speed** 20 ft., fly 60 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|10 (+0)|21 (+5)|15 (+2)|13 (+1)|14 (+2)|19 (+4)|

- **Proficiency Bonus** +3
- **Saving Throws** Constitution +5, Wisdom +5
- **Skills** Acrobatics +11, Deception +7, Perception +8
- **Senses** darkvision 120 ft., passive Perception 16
- **Damage Immunities** lightning, thunder
- **Languages** Abyssal
- **Challenge** 8

## Traits

***Aerial Acrobat.*** On each of her turns, the Crimson Countess can use a bonus action to take the Dash, Disengage, or Dodge action.

***Keen Sight.*** The Crimson Countess has advantage on Wisdom ([Perception](2-Mechanics/CLI/rules/skills.md#Perception)) checks that rely on sight.

## Actions

***Multiattack.*** The Crimson Countess can use her Frightful Screech. She then makes two attacks with her talons or one with her javelin.

***Talons.*** *Melee Weapon Attack:* `dice:1d20+8|noform|text(+8)` to hit, reach 5 ft., one target. *Hit:* `dice:1d10+5|noform|avg|text(11)` (`1d10 + 5`) slashing damage.

***Frightful Screech.*** Each creature of the Crimson Countess' choice that is within 120 feet of her and not [deafened](2-Mechanics/CLI/rules/conditions.md#Deafened) must succeed on a DC 15 Wisdom saving throw or become [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened) for 1 minute. If a creature's saving throw is successful or the effect ends for it, the creature is immune to the effects of the Crimson Countess' Frightful Screech for the next 24 hours.

While [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened) by this effect, a creature must take the Dash action and move away from the Crimson Countess by the safest available route on each of its turns, unless there is nowhere to move. If the creature ends its turn in a location where it doesn't have line of sight to the Crimson Countess, the creature can repeat the saving throw. On a successful save, the effect ends for that creature.

***Javelin.*** *Melee or Ranged Weapon Attack:* `dice:1d20+8|noform|text(+8)` to hit, reach 5 ft. or ranged 20/60 feet, one target. *Hit:* `dice:1d6+5|noform|avg|text(9)` (`1d6 + 5`) piercing damage, plus `dice:4d6|noform|avg|text(14)` (`4d6`) lightning damage.

***Thunder Blast (Recharge 5-6).*** The Crimson Countess unleashes a thunderous cry in a 15-foot cube. Each creature in the cube must succeed on a DC 15 Constitution saving throw, taking `dice:4d6|noform|avg|text(14)` (`4d6`) thunder damage on a failed save, or half as much damage on a successful one. Creatures who fail this saving throw are pushed 10 feet and knocked [prone](2-Mechanics/CLI/rules/conditions.md#Prone).
```
^statblock