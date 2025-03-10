---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/bam
- monster/cr/11
- monster/size/gargantuan
- monster/type/monstrosity
aliases: ["Megapede"]
---
# Megapede
*Source: Boo's Astral Menagerie p. 36, Light of Xaryxis*  

Megapedes are enormous centipedes that can be as much as 150 feet long, though most specimens top out at between 100 and 120 feet. Their dozens of legs are each 5 feet long and tipped with flexible claws, and they have fur-covered carapaces. A megapede that lives in a sandy environment often buries itself in the sand and waits for prey to wander nearby, but megapedes also nest in cavernous underground chambers.

A megapede's bite is poisonous. In addition, the creature has magical abilities that make it a superior predator. It can exude an invisible aura of life-draining energy, or it can fix its gaze on one creature and implant a psychic bomb in that creature's mind.

After a megapede lays eggs, it attaches the eggs to its body using sticky saliva and carries them on its back until the eggs hatch. Newly hatched megapedes grow to full size within weeks by consuming as much as they can, possibly including one another if food is scarce.

```ad-statblock
title: Megapede
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/BAM/Megapede.webp#token)
*Gargantuan monstrosity, Unaligned*

- **Armor Class** 15 (natural armor)
- **Hit Points** 175 (`13d20 + 39`)
- **Speed** 40 ft., climb 40 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|22 (+6)|10 (+0)|17 (+3)| 1 (-5)|10 (+0)| 3 (-4)|

- **Proficiency Bonus** +4
- **Saving Throws** Constitution +7, Wisdom +4
- **Skills** Perception +8, Stealth +4
- **Senses** darkvision 120 ft., passive Perception 18
- **Languages** —
- **Challenge** 11

## Actions

***Multiattack.*** The megapede makes one Bite attack and uses either Life Drain or Psychic Bomb.

***Bite.*** *Melee Weapon Attack:* `dice:1d20+10|noform|text(+10)` to hit, reach 20 ft., one target. *Hit:* `dice:3d10+6|noform|avg|text(22)` (`3d10 + 6`) piercing damage plus `dice:5d8|noform|avg|text(22)` (`5d8`) poison damage.

***Life Drain.*** The megapede magically drains life energy from other creatures nearby. Each creature within 15 feet of the megapede must make a DC 15 Constitution saving throw, taking `dice:3d10|noform|avg|text(16)` (`3d10`) necrotic damage on a failed save, or half as much damage on a successful one.

***Psychic Bomb.*** The megapede targets one creature it can see within 60 feet of itself. The target must make a DC 15 Wisdom saving throw. On a failed save, the target takes `dice:5d8|noform|avg|text(22)` (`5d8`) psychic damage and is [incapacitated](2-Mechanics/CLI/rules/conditions.md#Incapacitated) until the end of its next turn. On a successful save, the target takes half as much damage and isn't [incapacitated](2-Mechanics/CLI/rules/conditions.md#Incapacitated).
```
^statblock