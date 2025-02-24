---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/mot
- monster/cr/2
- monster/size/medium
- monster/type/humanoid/triton
aliases: ["Triton Shorestalker"]
---
# Triton Shorestalker
*Source: Mythic Odysseys of Theros p. 244*  

Some insults don't wash away with the tides. When surface dwellers threaten the safety of triton communities, impede upon Thassa's holiest depths, or steal the treasures of the deep, triton shorestalkers seek vengeance. Using speed and poison harvested from deadly sea beasts, these triton assassins slip into shallow waters and strike when least expected. Often, surface dwellers don't even realize they've been attacked by shorestalkers, chalking disappearances and deaths up to the innumerable dangers of the sea.

Clever, far-ranging people of the sea, tritons live rich lives unknown to most land-dwelling individuals. While the waves separate most tritons from land-dwellers, occasionally the inhabitants of the surface and the deep come into conflict. In such cases, tritons prove skilled at sabotaging ocean-going vessels, employing water-based magic, and otherwise whipping up the fury of the sea. Few dare insult tritons in their home environment, but those who do and survive often learn that the tritons' wrath doesn't end at the shore.

```ad-statblock
title: Triton Shorestalker
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/MOT/Triton%20Shorestalker.webp#token)
*Medium humanoid (triton), Neutral Evil*

- **Armor Class** 13
- **Hit Points** 32 (`5d8 + 10`)
- **Speed** 30 ft., swim 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|11 (+0)|16 (+3)|14 (+2)|10 (+0)|15 (+2)|11 (+0)|

- **Proficiency Bonus** +2
- **Saving Throws** ⏤
- **Skills** Nature +4, Perception +4, Stealth +5
- **Senses** darkvision 60 ft., passive Perception 14
- **Damage Resistances** cold
- **Languages** Common, Primordial
- **Challenge** 2

## Traits

***Amphibious.*** The triton can breathe air and water.

***Nimble Escape.*** The triton can take the Disengage or Hide actions as a bonus action on each of its turns.

***Innate Spellcasting.*** The triton's spellcasting ability is Wisdom (spell save DC 12). It can innately cast the following spells, requiring no material components:

**1/day each**: [fog cloud](2-Mechanics/CLI/spells/fog-cloud.md), [gust of wind](2-Mechanics/CLI/spells/gust-of-wind.md)

## Actions

***Multiattack.*** The triton makes two urchin-spine shortsword attacks.

***Urchin-Spine Shortsword.*** *Melee Weapon Attack:* `dice:1d20+5|noform|text(+5)` to hit, reach 5 ft., one target. *Hit:* `dice:1d6+3|noform|avg|text(6)` (`1d6 + 3`) piercing damage plus `dice:3d6|noform|avg|text(10)` (`3d6`) poison damage. If the damage reduces a creature to 0 hit points, that creature is stable but [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned) for 1 hour, even after regaining hit points, and is [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed) while [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned) in this way.

***Poisoned Spine.*** *Ranged Weapon Attack:* `dice:1d20+5|noform|text(+5)` to hit, range 30/60 ft., one target. *Hit:* `dice:1d4+3|noform|avg|text(5)` (`1d4 + 3`) piercing damage plus `dice:3d6|noform|avg|text(10)` (`3d6`) poison damage.
```
^statblock