---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/wdmm
- monster/cr/1
- monster/size/medium
- monster/type/humanoid/dwarf
aliases: ["Deformed Duergar"]
---
# Deformed Duergar
*Source: Waterdeep: Dungeon of the Mad Mage p. 180*  

This creature used to be two separate duergar, a male named Blork and a female named Muatha. Arcturia fused them together into a single creature by using magic that only a [wish](2-Mechanics/CLI/spells/wish.md) spell can undo. Both skulls merged into one bulbous head that has three ears, three eyes, two noses, and two mouths. It has a third arm on the right side of its body, and its left leg splits into two at the knee, giving it three feet. The transformation drove the poor creature insane, and it regards all other creatures as threats that must be destroyed.

```ad-statblock
title: Deformed Duergar
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/WDMM/Deformed%20Duergar.webp#token)
*Medium humanoid (dwarf), Lawful Evil*

- **Armor Class** 16 ([scale mail](2-Mechanics/CLI/items/scale-mail.md), [shield](2-Mechanics/CLI/items/shield.md))
- **Hit Points** 40 (`4d8 + 4`)
- **Speed** 25 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|14 (+2)|11 (+0)|14 (+2)|11 (+0)|10 (+0)| 9 (-1)|

- **Proficiency Bonus** +2
- **Saving Throws** ⏤
- **Skills** ⏤
- **Senses** darkvision 120 ft., passive Perception 10
- **Damage Resistances** poison
- **Languages** Dwarvish, Undercommon
- **Challenge** 1

## Traits

***Third Arm.*** The duergar can make an attack with its javelin as a bonus action.

***Merged Heads.*** The duergar has advantage on Wisdom ([Perception](2-Mechanics/CLI/rules/skills.md#Perception)) checks and on saving throws against being [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened), [stunned](2-Mechanics/CLI/rules/conditions.md#Stunned), and knocked [unconscious](2-Mechanics/CLI/rules/conditions.md#Unconscious).

***Duergar Resilience.*** The duergar has advantage on saving throws against poison, spells, and illusions, as well as to resist being [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed) or [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed).

***Sunlight Sensitivity.*** While in sunlight, the duergar has disadvantage on attack rolls, as well as on Wisdom ([Perception](2-Mechanics/CLI/rules/skills.md#Perception)) checks that rely on sight.

## Actions

***Enlarge (Recharges after a Short or Long Rest).*** For 1 minute, the duergar magically increases in size, along with anything it is wearing or carrying. While enlarged, the duergar is Large, doubles its damage dice on Strength-based weapon attacks (included in the attacks), and makes Strength checks and Strength saving throws with advantage. If the duergar lacks the room to become Large, it attains the maximum size possible in the space available.

***War Pick.*** *Melee Weapon Attack:* `dice:1d20+4|noform|text(+4)` to hit, reach 5 ft., one target. *Hit:* `dice:1d8+2|noform|avg|text(6)` (`1d8 + 2`) piercing damage, or `dice:2d8+2|noform|avg|text(11)` (`2d8 + 2`) piercing damage while enlarged.

***Javelin.*** *Melee or Ranged Weapon Attack:* `dice:1d20+4|noform|text(+4)` to hit, reach 5 ft. or range 30/120 ft., one target. *Hit:* `dice:1d6+2|noform|avg|text(5)` (`1d6 + 2`) piercing damage, or `dice:2d6+2|noform|avg|text(9)` (`2d6 + 2`) piercing damage while enlarged.

***Invisibility (Recharges after a Short or Long Rest).*** The duergar magically turns [invisible](2-Mechanics/CLI/rules/conditions.md#Invisible) until it attacks, casts a spell, or uses its Enlarge, or until its [concentration](2-Mechanics/CLI/rules/conditions.md#Concentration) is broken, up to 1 hour (as if concentrating on a spell). Any equipment the duergar wears or carries is [invisible](2-Mechanics/CLI/rules/conditions.md#Invisible) with it.
```
^statblock