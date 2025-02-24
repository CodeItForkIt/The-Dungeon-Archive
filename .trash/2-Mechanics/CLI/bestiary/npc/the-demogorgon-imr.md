---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/imr
- monster/cr/8
- monster/size/large
- monster/type/giant
aliases: [""The Demogorgon""]
---
# "The Demogorgon"
*Source: Infernal Machine Rebuild p. 53*  

```ad-statblock
title: "The Demogorgon"
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/IMR/The%20Demogorgon.webp#token)
*Large giant, Chaotic Neutral*

- **Armor Class** 15 (natural armor)
- **Hit Points** 123 (`13d12 + 39`)
- **Speed** 40 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|21 (+5)| 8 (-1)|17 (+3)| 6 (-2)|10 (+0)| 8 (-1)|

- **Proficiency Bonus** +3
- **Saving Throws** ⏤
- **Skills** Perception +3
- **Senses** darkvision 60 ft., passive Perception 13
- **Languages** Giant, Orc
- **Challenge** 8

## Traits

***Two Heads.*** The ettin has advantage on Wisdom ([Perception](2-Mechanics/CLI/rules/skills.md#Perception)) checks and on saving throws against being [blinded](2-Mechanics/CLI/rules/conditions.md#Blinded), [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [deafened](2-Mechanics/CLI/rules/conditions.md#Deafened), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened), [stunned](2-Mechanics/CLI/rules/conditions.md#Stunned), and knocked [unconscious](2-Mechanics/CLI/rules/conditions.md#Unconscious).

***Wakeful.*** When one of the ettin's heads is asleep, its other head is awake.

## Actions

***Multiattack.*** The ettin makes two attacks: one with its battleaxe and one with its morningstar.

***Battleaxe.*** *Melee Weapon Attack:* `dice:1d20+8|noform|text(+8)` to hit, reach 5 ft., one target. *Hit:* `dice:2d8+5|noform|avg|text(14)` (`2d8 + 5`) slashing damage.

***Morningstar.*** *Melee Weapon Attack:* `dice:1d20+8|noform|text(+8)` to hit, reach 5 ft., one target. *Hit:* `dice:2d8+5|noform|avg|text(14)` (`2d8 + 5`) piercing damage.

***Fire Breath (Recharge 5-6).*** The ettin's right head exhales fire in a 30-foot cone. Each creature in that area must make a DC 14 Dexterity saving throw, taking `dice:10d8|noform|avg|text(45)` (`10d8`) fire damage on a failed save, or half as much damage on a successful one.

***Cold Breath (Recharge 5-6).*** The ettin's left head exhales an icy blast in a 30-foot cone. Each creature in that area must make a DC 14 Constitution saving throw, taking `dice:10d8|noform|avg|text(45)` (`10d8`) cold damage on a failed save, or half as much damage on a successful one.

***Gaze.*** The ettin turns its magical gaze toward one creature that it can see within 120 feet of it. That target must make a DC 14 Wisdom saving throw. Unless the target is [incapacitated](2-Mechanics/CLI/rules/conditions.md#Incapacitated), it can avert its eyes to avoid the gaze and to automatically succeed on the save. If the target does so, it can't see the ettin until the start of the ettin's next turn. If the target looks at the ettin in the meantime, it must immediately make the save.

If the target fails the save, it suffers one of the following effects of the ettin's choice or at random:

***Beguiling Gaze.*** The target is [stunned](2-Mechanics/CLI/rules/conditions.md#Stunned) until the start of the ettin's next turn or until the ettin is no longer within line of sight.

***Hypnotic Gaze.*** The target is [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed) by the ettin until the start of the ettin's next turn. The ettin chooses how the [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed) target uses its actions, reactions, and movement.

***Insanity Gaze.*** The target suffers the effect of the [confusion](2-Mechanics/CLI/spells/confusion.md) spell without making a saving throw. The effect lasts until the start of the ettin's next turn. The ettin doesn't need to concentrate on the spell.
```
^statblock