---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/qftis
- monster/cr/2
- monster/size/medium
- monster/type/humanoid
aliases: ["Champion of Gorm"]
---
# Champion of Gorm
*Source: Quests from the Infinite Staircase p. 203*  

Champions are blessed by Gorm to lead their fellow guardians. In battle, they channel auras of ghostly lightning to protect Gorm's servants.

## Guardians of Gorm

The Guardians of Gorm are stalwart Cynidiceans who worship Gorm, an ancient god of justice, storms, and war. Members of the order wear brass masks bearing the face of their god, who is depicted as a long-haired, bearded man with a stern gaze. Each fully initiated guardian has a small blue lightning bolt tattooed on their right shoulder.

Guardians follow a strict code of decorum that values bravery, honesty, and justice tempered with mercy. Still, they are quick to chastise blasphemers, criminals, and cultists who oppose their cause, buffeting these foes with their shocking implements.

## Statblock

```ad-statblock
title: Champion of Gorm
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/QftIS/Champion%20of%20Gorm.webp#token)
*Medium humanoid, typically  Lawful Good*

- **Armor Class** 19 ([splint armor](2-Mechanics/CLI/items/splint-armor.md), [shield](2-Mechanics/CLI/items/shield.md))
- **Hit Points** 33 (`6d8 + 6`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|17 (+3)|10 (+0)|12 (+1)|12 (+1)|15 (+2)|16 (+3)|

- **Proficiency Bonus** +2
- **Saving Throws** Strength +5, Wisdom +4
- **Skills** Athletics +5, Insight +4, Religion +3
- **Senses** passive Perception 12
- **Languages** Common
- **Challenge** 2

## Traits

***Brave.*** The champion has advantage on saving throws against the [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened) condition.

## Actions

***Multiattack.*** The champion makes two Lightning Mace attacks or three Handaxe attacks.

***Lightning Mace.*** *Melee Weapon Attack:* `dice:1d20+5|noform|text(+5)` to hit, reach 5 ft., one target. *Hit:* `dice:1d6+3|noform|avg|text(6)` (`1d6 + 3`) piercing damage plus `dice:2d4|noform|avg|text(5)` (`2d4`) lightning damage.

***Handaxe.*** *Melee or Ranged Weapon Attack:* `dice:1d20+5|noform|text(+5)` to hit, reach 5 ft. or range 20/60 ft., one target. *Hit:* `dice:1d6+3|noform|avg|text(6)` (`1d6 + 3`) slashing damage.

## Bonus Actions

***Aura of Resilience (1/Day).*** The champion exudes an aura of ghostly lightning that fills a 10-foot-radius sphere centered on itself. While this aura is active, the champion and each creature of its choice within the aura have advantage on saving throws. The aura moves with the champion and lasts for 1 minute, until the champion has the [incapacitated](2-Mechanics/CLI/rules/conditions.md#Incapacitated) condition, or until the champion uses another bonus action to end the aura.
```
^statblock