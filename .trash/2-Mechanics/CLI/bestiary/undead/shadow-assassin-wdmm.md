---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/wdmm
- monster/cr/9
- monster/size/medium
- monster/type/undead
aliases: ["Shadow Assassin"]
---
# Shadow Assassin
*Source: Waterdeep: Dungeon of the Mad Mage p. 316*  

A shadow assassin looks like an undead shadow (as described in the *Monster Manual*) that wields shortswords also made of shadow. It exists only to slay the living.

```ad-statblock
title: Shadow Assassin
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/WDMM/Shadow%20Assassin.webp#token)
*Medium undead, Chaotic Evil*

- **Armor Class** 14
- **Hit Points** 78 (`12d8 + 24`)
- **Speed** 40 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
| 6 (-2)|19 (+4)|14 (+2)|13 (+1)|12 (+1)|14 (+2)|

- **Proficiency Bonus** +4
- **Saving Throws** Dexterity +8, Intelligence +5
- **Skills** Perception +9, Stealth +12
- **Senses** darkvision 60 ft., passive Perception 19
- **Damage Vulnerabilities** radiant
- **Damage Resistances** acid; cold; fire; lightning; thunder; bludgeoning, piercing, slashing from nonmagical attacks
- **Damage Immunities** necrotic, poison
- **Condition Immunities** [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened), [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled), [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed), [petrified](2-Mechanics/CLI/rules/conditions.md#Petrified), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned), [prone](2-Mechanics/CLI/rules/conditions.md#Prone), [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained)
- **Languages** understands the languages it knew in life but can't speak
- **Challenge** 9

## Traits

***Amorphous.*** The assassin can move through a space as narrow as 1 inch wide without squeezing.

***Shadow Stealth.*** While in dim light or darkness, the assassin can take the Hide action as a bonus action.

***Sunlight Weakness.*** While in sunlight, the assassin has disadvantage on attack rolls, ability checks, and saving throws.

## Actions

***Multiattack.*** The assassin makes two Shadow Blade attacks.

***Shadow Blade.*** *Melee Weapon Attack:* `dice:1d20+8|noform|text(+8)` to hit, reach 5 ft., one target. *Hit:* `dice:1d6+4|noform|avg|text(7)` (`1d6 + 4`) piercing damage plus `dice:3d6|noform|avg|text(10)` (`3d6`) necrotic damage. Unless the target is immune to necrotic damage, the target's Strength score is reduced by `dice:1d4|noform|avg` (`1d4`) each time it is hit by this attack. The target dies if its Strength is reduced to 0. The reduction lasts until the target finishes a short or long rest. If a non-evil humanoid dies from this attack, a shadow (see the Monster Manual) rises from the corpse `dice:1d4|noform|avg` (`1d4`) hours later.
```
^statblock