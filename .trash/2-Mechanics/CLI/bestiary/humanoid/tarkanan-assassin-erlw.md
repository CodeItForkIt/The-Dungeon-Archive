---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/erlw
- monster/cr/2
- monster/size/medium
- monster/type/humanoid/any-race
aliases: ["Tarkanan Assassin"]
---
# Tarkanan Assassin
*Source: Eberron: Rising from the Last War p. 320*  

Tarkanan assassins are the elite killers, spies, and thieves who work for House Tarkanan, a criminal organization specializing in theft and assassination. In addition to their deadly skill, a Tarkanan assassin possesses an aberrant dragonmark—a twisted sigil that provides them with magical power. House Tarkanan actively seeks and recruits people with aberrant dragonmarks.

> [!note] Aberrant Dragonmark Innate Spells
> 
> The power granted by an aberrant dragonmark is unpredictable. When running a Tarkanan assassin, you can roll on the Aberrant Dragonmark Innate Spells table to determine the spells gained from that NPC's aberrant mark, replacing the spells in the stat block's Innate Spellcasting trait.
> 
> `dice: [](tarkanan-assassin-erlw.md#^at-will-1-day)`
> 
> | dice: d6 | At Will | 1/Day |
> |----------|---------|-------|
> | 1 | [Fire bolt](2-Mechanics/CLI/spells/fire-bolt.md) (`dice:2d10\\|noform\\|avg` (`2d10`)) | [Burning hands](2-Mechanics/CLI/spells/burning-hands.md) (`dice:3d6\\|noform\\|avg` (`3d6`)) |
> | 2 | [Shocking grasp](2-Mechanics/CLI/spells/shocking-grasp.md) (`dice:2d8\\|noform\\|avg` (`2d8`)) | [Chromatic orb](2-Mechanics/CLI/spells/chromatic-orb.md) (`dice:4d8\\|noform\\|avg` (`4d8`)) |
> | 3 | [Poison spray](2-Mechanics/CLI/spells/poison-spray.md) (`dice:2d12\\|noform\\|avg` (`2d12`)) | [Ray of sickness](2-Mechanics/CLI/spells/ray-of-sickness.md) (`dice:3d8\\|noform\\|avg` (`3d8`)) |
> | 4 | [Friends](2-Mechanics/CLI/spells/friends.md) | [Charm person](2-Mechanics/CLI/spells/charm-person.md) (two creatures) |
> | 5 | [Minor illusion](2-Mechanics/CLI/spells/minor-illusion.md) | [Thunderwave](2-Mechanics/CLI/spells/thunderwave.md) (`dice:2d8\\|noform\\|avg` (`2d8`)) |
> | 6 | [Dancing lights](2-Mechanics/CLI/spells/dancing-lights.md) | [Sleep](2-Mechanics/CLI/spells/sleep.md) (`dice:7d8\\|noform\\|avg` (`7d8`)) |
> ^at-will-1-day
^aberrant-dragonmark-innate-spells

```ad-statblock
title: Tarkanan Assassin
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ERLW/Tarkanan%20Assassin.webp#token)
*Medium humanoid (any race), Any Non-Good alignment*

- **Armor Class** 15 ([studded leather](2-Mechanics/CLI/items/studded-leather-armor.md))
- **Hit Points** 45 (`7d8 + 14`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|12 (+1)|16 (+3)|14 (+2)|10 (+0)|14 (+2)|11 (+0)|

- **Proficiency Bonus** +2
- **Saving Throws** ⏤
- **Skills** Athletics +3, Deception +2, Perception +4, Sleight of Hand +5, Stealth +5
- **Senses** darkvision 60 ft., passive Perception 14
- **Languages** Common, Thieves' cant
- **Challenge** 2

## Traits

***Unstable Mark.*** When the assassin casts an innate spell, each creature within 10 feet of the assassin must make a DC 12 Constitution saving throw, taking `dice:1d8|noform|avg|text(4)` (`1d8`) force damage on a failed save, or half as much damage on a successful one.

***Innate Spellcasting.*** The assassin's spellcasting ability is Constitution (`dice:1d20+4|noform|text(+4)` to hit with spell attacks). It can innately cast the following spells, requiring no material components:

**At will**: [fire bolt](2-Mechanics/CLI/spells/fire-bolt.md)

**1/day**: [chromatic orb](2-Mechanics/CLI/spells/chromatic-orb.md)

## Actions

***Multiattack.*** The assassin makes two shortsword attacks.

***Shortsword.*** *Melee Weapon Attack:* `dice:1d20+5|noform|text(+5)` to hit, reach 5 ft., one target. *Hit:* `dice:1d6+3|noform|avg|text(6)` (`1d6 + 3`) piercing damage plus `dice:2d6|noform|avg|text(7)` (`2d6`) poison damage.

***Fire Bolt (Cantrip).*** *Ranged Spell Attack:* `dice:1d20+4|noform|text(+4)` to hit, range 120 ft., one target. *Hit:* `dice:2d10|noform|avg|text(11)` (`2d10`) fire damage. A flammable object hit by this spell ignites if it isn't being worn or carried.

***Chromatic Orb (1/Day).*** *Ranged Spell Attack:* `dice:1d20+4|noform|text(+4)` to hit, range 90 ft., one creature. *Hit:* `dice:4d8|noform|avg|text(18)` (`4d8`) damage of a type chosen by the assassin: acid, cold, fire, lightning, poison, or thunder.
```
^statblock