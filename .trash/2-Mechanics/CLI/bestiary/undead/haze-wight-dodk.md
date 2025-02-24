---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/dodk
- monster/cr/3
- monster/size/medium
- monster/type/undead
aliases: ["Haze Wight"]
---
# Haze Wight
*Source: Dungeons of Drakkenheim p. 198*  

A haze wight is more sentient than their haze husk minions, but has still been stripped of their former life. Many were former adventurers, military officers, or mighty warriors who died in the Haze. Many still believe themselves to be great heroes rallying the common folk of Drakkenheim against invaders, but in their madness they see all humanoids as monsters.

```ad-statblock
title: Haze Wight
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/DoDk/Haze%20Wight.webp#token)
*Medium undead, Neutral Evil*

- **Armor Class** 14 ([studded leather](2-Mechanics/CLI/items/studded-leather-armor.md))
- **Hit Points** 45 (`6d8 + 18`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|15 (+2)|14 (+2)|16 (+3)|10 (+0)|13 (+1)|15 (+2)|

- **Proficiency Bonus** +2
- **Saving Throws** ⏤
- **Skills** Perception +3, Stealth +4
- **Senses** darkvision 60 ft., passive Perception 13
- **Damage Resistances** necrotic; bludgeoning, piercing, slashing from nonmagical attacks that aren't silvered
- **Damage Immunities** poison
- **Condition Immunities** [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** the languages it knew in life
- **Challenge** 3

## Traits

***Sunlight Sensitivity.*** While in sunlight, the haze wight has disadvantage on attack rolls, as well as on Wisdom ([Perception](2-Mechanics/CLI/rules/skills.md#Perception)) checks that rely on sight.

## Actions

***Multiattack.*** The haze wight makes two longsword attacks or two longbow attacks. It can use its Contaminated Touch or Create Haze Husk in place of one longsword attack.

***Contaminated Touch.*** *Melee Weapon Attack:* `dice:1d20+4|noform|text(+4)` to hit, reach 5 ft., one creature. *Hit:* `dice:3d6|noform|avg|text(10)` (`3d6`) necrotic damage. The target must succeed on a DC 13 Constitution saving throw or gain one level of contamination.

***Create Haze Husk.*** The wight targets a humanoid within 10 feet of it that has been dead for no longer than 1 minute and died violently. It rises as a haze husk in an unoccupied space within 5 feet. The haze husk is under the wight's control. The wight can have no more than 12 haze husks under its control at one time.

***Longsword.*** *Melee Weapon Attack:* `dice:1d20+4|noform|text(+4)` to hit, reach 5 ft., one target. *Hit:* `dice:1d8+2|noform|avg|text(6)` (`1d8 + 2`) slashing damage, or `dice:1d10+2|noform|avg|text(7)` (`1d10 + 2`) slashing damage if used with two hands.

***Longbow.*** *Ranged Weapon Attack:* `dice:1d20+4|noform|text(+4)` to hit, range 150/600 ft., one target. *Hit:* `dice:1d8+2|noform|avg|text(6)` (`1d8 + 2`) piercing damage.
```
^statblock