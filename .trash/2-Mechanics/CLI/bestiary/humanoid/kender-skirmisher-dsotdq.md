---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/dsotdq
- monster/cr/1-4
- monster/size/small
- monster/type/humanoid
aliases: ["Kender Skirmisher"]
---
# Kender Skirmisher
*Source: Dragonlance: Shadow of the Dragon Queen p. 204*  

Kender skirmishers are fearless fighters who use stealth and wiliness to defend their friends and homes. They excel at disrupting their enemies by sabotaging crucial equipment or by taunting opponents into making rash decisions. They wield the signature kender weapon: the hoopak, a combination spear and sling staff.

## Kender Taunts

Roll on or choose an entry from the Kender Taunts table to determine how a kender skirmisher infuriates an opponent in battle.

`dice: [](kender-skirmisher-dsotdq.md#^taunt)`

| dice: d4 | Taunt |
|----------|-------|
| 1 | "Should I pretend to be scared? You seem like you really need this." |
| 2 | "I wish I could be like you and just not care how I look... or smell... or dress. So brave." |
| 3 | "Did the Cataclysm have a face? Because I think you might be twins!" |
| 4 | Energetically points at their foe with both hands and loudly repeats the word "bonk." |
^taunt

## Statblock

```ad-statblock
title: Kender Skirmisher
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/DSotDQ/Kender%20Skirmisher.webp#token)
*Small humanoid, Any alignment*

- **Armor Class** 14 ([leather armor](2-Mechanics/CLI/items/leather-armor.md))
- **Hit Points** 14 (`4d6`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
| 8 (-1)|16 (+3)|10 (+0)|12 (+1)| 8 (-1)|14 (+2)|

- **Proficiency Bonus** +2
- **Saving Throws** ⏤
- **Skills** Perception +3, Sleight of Hand +7, Stealth +5
- **Senses** passive Perception 13
- **Condition Immunities** [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened)
- **Languages** Common, Kenderspeak
- **Challenge** 1/4

## Actions

***Hoopak.*** *Melee or Ranged Weapon Attack:* `dice:1d20+5|noform|text(+5)` to hit, reach 5 ft. or range 40/160 ft., one target. *Hit:* `dice:1d6+3|noform|avg|text(6)` (`1d6 + 3`) piercing damage, or `dice:1d4+3|noform|avg|text(5)` (`1d4 + 3`) bludgeoning damage if the kender used the hoopak's sling to make a ranged attack.

***Taunt.*** The kender launches a barrage of insults at a creature it can see within 60 feet of itself. If the target can hear the kender, the target must succeed on a DC 12 Wisdom saving throw or have disadvantage on attack rolls until the end of its next turn.

## Bonus Actions

***Elusive.*** The kender takes the Disengage or Hide action.
```
^statblock