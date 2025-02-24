---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/coa
- monster/cr/18
- monster/size/medium
- monster/type/fiend/devil
aliases: ["Avatar of Baalzebul"]
---
# Avatar of Baalzebul
*Source: Chains of Asmodeus p. 38*  

```ad-statblock
title: Avatar of Baalzebul
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/CoA/Avatar%20of%20Baalzebul.webp#token)
*Medium fiend (devil), Lawful Evil*

- **Armor Class** 14 (natural armor)
- **Hit Points** 285 (`30d8 + 150`)
- **Speed** 20 ft., fly 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|21 (+5)|13 (+1)|20 (+5)|17 (+3)|18 (+4)|20 (+5)|

- **Proficiency Bonus** +6
- **Saving Throws** Strength +11, Charisma +11
- **Skills** Deception +11, Insight +10, Intimidation +11, Persuasion +11
- **Senses** darkvision 120 ft., passive Perception 14
- **Damage Vulnerabilities** radiant
- **Damage Resistances** acid; cold; bludgeoning, piercing, slashing from nonmagical attacks that aren't silvered
- **Damage Immunities** fire, poison
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** all, telepathy 120 ft.
- **Challenge** 18

## Traits

***Stench of the Slug.*** Any creature that starts its turn within 10 feet of the avatar must succeed on a DC 19 Constitution saving throw or have the [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned) condition until the start of their next turn. On a successful saving throw, the creature is immune to this stench for 1 hour.

## Actions

***Multiattack.*** The avatar makes four Sickening Claw attacks. It can replace one of the attacks with Insect Gorge (if available).

***Sickening Claw.*** *Melee Weapon Attack:* `dice:1d20+11|noform|text(+11)` to hit, reach 5 ft., one target. *Hit:* `dice:1d8+5|noform|avg|text(9)` (`1d8 + 5`) slashing damage plus `dice:3d8|noform|avg|text(13)` (`3d8`) acid damage. The target's hit point maximum is reduced by the acid damage taken. The reduction lasts until the target finishes a long rest. The target dies if this effect reduces its hit point maximum to 0.

***Insect Gorge (Recharge 4-6).*** The avatar disgorges a swarm of biting flies at a point it can see within 300 feet of itself. Each creature within a 20-foot-radius sphere centered on that point must make a DC 19 Constitution saving throw. A creature takes `dice:10d10|noform|avg|text(55)` (`10d10`) piercing damage on a failed save, or half as much damage on a successful one. The biting flies persist for 1 minute or until the avatar is slain. A creature must also make this saving throw when it enters the insects' area for the first time on a turn or ends its turn there.

***Caustic Slimepool (1/Day).*** The avatar causes caustic slime to emanate from itself, covering a 15-foot-radius circle. Each creature within the slime must succeed on a DC 19 Dexterity saving throw or have the [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) condition (escape DC 17). A [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) creature takes `dice:6d6|noform|avg|text(21)` (`6d6`) acid damage at the start of its turn.
```
^statblock