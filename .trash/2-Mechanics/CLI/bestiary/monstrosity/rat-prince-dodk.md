---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/dodk
- monster/cr/3
- monster/size/medium
- monster/type/monstrosity
aliases: ["Rat Prince"]
---
# Rat Prince
*Source: Dungeons of Drakkenheim p. 213*  

This ratling stands head-and-shoulders over the others, and has black-brown fur and a wicked grin - some of his frontmost teeth are delerium crystals. He wears scavenged bits of light armour, tattered dark blue rags, and a gold crown which is slightly too small for his head.

```ad-statblock
title: Rat Prince
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/DoDk/Rat%20Prince.webp#token)
*Medium monstrosity, Chaotic Evil*

- **Armor Class** 15 ([leather armor](2-Mechanics/CLI/items/leather-armor.md))
- **Hit Points** 66 (`12d8 + 12`)
- **Speed** 30 ft., climb 30 ft., swim 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|12 (+1)|19 (+4)|13 (+1)| 9 (-1)|15 (+2)| 9 (-1)|

- **Proficiency Bonus** +2
- **Saving Throws** ⏤
- **Skills** Acrobatics +6, Athletics +3, Perception +6, Stealth +8
- **Senses** darkvision 60 ft., passive Perception 15
- **Languages** Common
- **Challenge** 3

## Traits

***Cunning Action.*** The Rat Prince can take the Dash, Disengage, or Hide action as a bonus action on each of its turns.

***Keen Smell.*** The Rat Prince has advantage on Wisdom ([Perception](2-Mechanics/CLI/rules/skills.md#Perception)) checks that rely on smell.

***Pack Tactics.*** The Rat Prince has advantage on an attack roll against a creature if at least one of his allies is within 5 feet of the creature and the ally isn't [incapacitated](2-Mechanics/CLI/rules/conditions.md#Incapacitated).

***Contaminated Ammunition.*** The Rat Prince carries `dice:2d6|noform|avg` (`2d6`) pieces of ammunition laced with delerium fragments. These projectiles cause `dice:1d6|noform|avg` (`1d6`) extra damage on a hit, and the target must succeed on a DC 10 Constitution saving throw or gain one level of contamination.

## Actions

***Multiattack.*** The Rat Prince makes three attacks: two with his short swords, and one with his contaminated bite.

***Short Sword.*** *Melee Weapon Attack:* `dice:1d20+6|noform|text(+6)` to hit, reach 5 ft., one target. *Hit:* `dice:1d6+4|noform|avg|text(7)` (`1d6 + 4`) piercing damage.

***Contaminated Bite.*** *Melee Weapon Attack:* `dice:1d20+6|noform|text(+6)` to hit, reach 5 ft., one target. *Hit:* `dice:1d4+4|noform|avg|text(4)` (`1d4 + 4`) piercing damage, plus an extra `dice:3d6|noform|avg|text(10)` (`3d6`) necrotic damage, and the creature must succeed on a DC 11 Constitution saving throw or gain one level of contamination.

***Hand Crossbow.*** *Ranged Weapon Attack:* `dice:1d20+6|noform|text(+6)` to hit, range 30/120 ft., one target. *Hit:* `dice:1d6+4|noform|avg|text(7)` (`1d6 + 4`) piercing damage.
```
^statblock