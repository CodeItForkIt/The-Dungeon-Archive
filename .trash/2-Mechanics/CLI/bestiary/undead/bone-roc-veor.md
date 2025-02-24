---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/veor
- monster/cr/8
- monster/size/huge
- monster/type/undead
aliases: ["Bone Roc"]
---
# Bone Roc
*Source: Vecna: Eve of Ruin p. 211*  

A bone roc is a birdlike Undead that can incorporate the bones of multiple flying creatures. Despite their name, bone rocs aren't always reanimated skeletons of rocs. You may customize a bone roc by rolling on the Bone Roc Sources table to determine the type of bones used and how that affects its stat block.

`dice: [](bone-roc-veor.md#^bone-source)`

| dice: d6 | Bone Source |
|----------|-------------|
| 1 | Axe Beak. The bone roc's walking speed is 50 feet. |
| 2 | Cockatrice. A creature hit by the bone roc's Beak attack must succeed on a DC 14 Constitution saving throw or have its speed reduced by 10 feet until the start of the bone roc's next turn. |
| 3 | Giant Owl. The bone roc's modifier for Dexterity ([Stealth](2-Mechanics/CLI/rules/skills.md#Stealth)) checks is +8. |
| 4 | Peryton. The bone roc has resistance to slashing damage from nonmagical attacks. |
| 5 | Pteranodon. The bone roc doesn't provoke an opportunity attack when it flies out of an enemy's reach. |
| 6 | Roc. The bone roc's size is Gargantuan, and its flying speed is 120 feet. Its Hit Dice remain unchanged. |
^bone-source

```ad-statblock
title: Bone Roc
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/VEoR/Bone%20Roc.webp#token)
*Huge undead, typically  Neutral Evil*

- **Armor Class** 15
- **Hit Points** 133 (`14d12 + 42`)
- **Speed** 15 ft., fly 90 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|18 (+4)|20 (+5)|16 (+3)| 2 (-4)|17 (+3)|10 (+0)|

- **Proficiency Bonus** +3
- **Saving Throws** Dexterity +8, Wisdom +6
- **Skills** Perception +6
- **Senses** darkvision 120 ft., passive Perception 16
- **Damage Vulnerabilities** bludgeoning
- **Damage Immunities** poison
- **Condition Immunities** [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** —
- **Challenge** 8

## Actions

***Multiattack.*** The bone roc makes one Beak attack and two Talons attacks.

***Beak.*** *Melee Weapon Attack:* `dice:1d20+8|noform|text(+8)` to hit, reach 5 ft., one target. *Hit:* `dice:2d8+5|noform|avg|text(14)` (`2d8 + 5`) piercing damage.

***Talons.*** *Melee Weapon Attack:* `dice:1d20+8|noform|text(+8)` to hit, reach 5 ft., one target. *Hit:* `dice:2d6+5|noform|avg|text(12)` (`2d6 + 5`) slashing damage plus `dice:3d6|noform|avg|text(10)` (`3d6`) necrotic damage.
```
^statblock