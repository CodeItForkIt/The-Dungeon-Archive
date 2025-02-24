---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/hftt
- monster/cr/4
- monster/size/huge
- monster/type/monstrosity
aliases: ["Thessalhydra"]
---
# Thessalhydra
*Source: Hunt for the Thessalhydra p. 41, Infernal Machine Rebuild*  

The thessalhydra is a strange and terrible creature with eight heads surrounding a large, circular mouth rimmed with jagged teeth. Its maw drips with acid, and its tail ends with a pair of sharp pincers. The thessalhydra is gluttonous and damaging to any environment.

```ad-statblock
title: Thessalhydra
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/HftT/Thessalhydra.webp#token)
*Huge monstrosity, Unaligned*

- **Armor Class** 14 (natural armor)
- **Hit Points** 69 (`6d12 + 30`)
- **Speed** 30 ft., swim 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|19 (+4)|12 (+1)|20 (+5)| 5 (-3)|10 (+0)| 7 (-2)|

- **Proficiency Bonus** +2
- **Saving Throws** ⏤
- **Skills** Perception +4
- **Senses** darkvision 60 ft., passive Perception 14
- **Damage Immunities** acid
- **Condition Immunities** [blinded](2-Mechanics/CLI/rules/conditions.md#Blinded), [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [deafened](2-Mechanics/CLI/rules/conditions.md#Deafened), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened), [stunned](2-Mechanics/CLI/rules/conditions.md#Stunned)
- **Languages** —
- **Challenge** 4

## Actions

***Multiattack.*** The thessalhydra makes one maw attack and one Flurry of Bites.

***Flurry of Bites.*** *Melee Weapon Attack:* `dice:1d20+7|noform|text(+7)` to hit, reach 10 ft., one target. *Hit:* `dice:1d6+4|noform|avg|text(7)` (`1d6 + 4`) piercing damage plus `dice:4d4|noform|avg|text(10)` (`4d4`) poison damage.

***Maw.*** *Melee Weapon Attack:* `dice:1d20+7|noform|text(+7)` to hit, reach 5 ft., one target. *Hit:* `dice:1d10+4|noform|avg|text(9)` (`1d10 + 4`) piercing damage plus `dice:1d10|noform|avg|text(5)` (`1d10`) acid damage.

***Tail Pincer.*** *Melee Weapon Attack:* `dice:1d20+7|noform|text(+7)` to hit, reach 10 ft., one target. *Hit:* `dice:1d12+4|noform|avg|text(10)` (`1d12 + 4`) slashing damage, and the target is [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled). As an action, the target can escape the grapple by succeeding on a DC 14 Strength ([Athletics](2-Mechanics/CLI/rules/skills.md#Athletics)) or Dexterity ([Acrobatics](2-Mechanics/CLI/rules/skills.md#Acrobatics)) check (its choice). Until this grapple ends, the thessalhydra can't use its tail pincer.

***Acid Saliva (Recharge 5-6).*** The thessalhydra spits a glob of acid at a point it can see within 30 feet of it. Each creature within 10 feet of that point must make a DC 15 Dexterity saving throw, taking `dice:4d8|noform|avg|text(18)` (`4d8`) acid damage on a failed save, or half as much damage on a successful one.

## Legendary Actions

***Detect.*** The thessalhydra makes a Wisdom ([Perception](2-Mechanics/CLI/rules/skills.md#Perception)) check with advantage.

***Tail Swipe.*** The thessalhydra makes a tail pincer attack.
```
^statblock