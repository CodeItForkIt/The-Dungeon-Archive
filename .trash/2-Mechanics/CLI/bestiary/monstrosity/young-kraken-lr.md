---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/lr
- monster/cr/14
- monster/size/huge
- monster/type/monstrosity/titan
aliases: ["Young Kraken"]
---
# Young Kraken
*Source: Locathah Rising p. 21*  

```ad-statblock
title: Young Kraken
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/LR/Young%20Kraken.webp#token)
*Huge monstrosity (titan), Chaotic Evil*

- **Armor Class** 16 (natural armor)
- **Hit Points** 207 (`18d12 + 90`)
- **Speed** 20 ft., swim 50 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|24 (+7)|11 (+0)|20 (+5)|19 (+4)|15 (+2)|17 (+3)|

- **Proficiency Bonus** +5
- **Saving Throws** Strength +12, Dexterity +5, Constitution +10, Intelligence +9, Wisdom +7
- **Skills** ⏤
- **Senses** truesight 120 ft., passive Perception 14
- **Damage Immunities** lightning; bludgeoning, piercing, slashing from nonmagical attacks
- **Condition Immunities** [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened), [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed)
- **Languages** Abyssal, Celestial, Infernal, Primordial, telepathy 60 ft. but can't speak
- **Challenge** 14

## Traits

***Amphibious.*** The kraken can breathe air and water.

## Actions

***Multiattack.*** The kraken makes two tentacle attacks, each of which it can replace with one use of Fling.

***Bite.*** *Melee Weapon Attack:* `dice:1d20+12|noform|text(+12)` to hit, reach 5 ft., one target. *Hit:* `dice:3d8+7|noform|avg|text(20)` (`3d8 + 7`) piercing damage.

If the target is a Medium or smaller creature [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) by the kraken, that creature is swallowed and the grapple ends. While swallowed, the creature is [blinded](2-Mechanics/CLI/rules/conditions.md#Blinded) and [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained), it has total cover against attacks and other effects outside the kraken, and it takes `dice:6d6|noform|avg|text(21)` (`6d6`) acid damage at the start of each of the kraken's turns. One Medium or two smaller creatures can be swallowed at the same time.

If the kraken takes 35 damage or more on a single turn from a creature inside it, the kraken must succeed on a DC 23 Constitution saving throw at the end of that turn or regurgitate all swallowed creatures, which fall [prone](2-Mechanics/CLI/rules/conditions.md#Prone) in spaces within 10 feet of the kraken. If the kraken dies, a swallowed creature is no longer [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained) by it and can escape from the corpse using 10 feet of movement, exiting [prone](2-Mechanics/CLI/rules/conditions.md#Prone).

***Tentacle.*** *Melee Weapon Attack:* `dice:1d20+12|noform|text(+12)` to hit, reach 20 ft., one target. *Hit:* `dice:3d6+7|noform|avg|text(17)` (`3d6 + 7`) bludgeoning damage, and the target is [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) (escape DC 20). Until the grapple ends, the target is [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained). The kraken has ten tentacles, each of which can grapple one target.

***Fling.*** One Medium or smaller object held or creature [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) by the kraken is thrown up to 40 feet in a random direction and knocked [prone](2-Mechanics/CLI/rules/conditions.md#Prone). If a thrown target strikes a solid surface, the target takes `dice:1d6|noform|avg|text(3)` (`1d6`) bludgeoning damage for every 10 feet it was thrown. If the target is thrown at another creature, that creature must succeed on a DC 13 Dexterity saving throw or take the same damage and be knocked [prone](2-Mechanics/CLI/rules/conditions.md#Prone).

***Lightning Strike.*** The kraken magically create a bolt of lightning, which can strike a target the kraken can see within 90 feet of it. The target must make a DC 18 Dexterity saving throw, taking `dice:4d10|noform|avg|text(22)` (`4d10`) lightning damage on a failed save, or half as much damage on a successful one.
```
^statblock