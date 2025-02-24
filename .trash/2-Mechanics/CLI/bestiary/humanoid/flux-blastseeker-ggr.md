---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/ggr
- monster/cr/5
- monster/size/medium
- monster/type/humanoid/any-race
aliases: ["Flux Blastseeker"]
---
# Flux Blastseeker
*Source: Guildmasters' Guide to Ravnica p. 242*  

While chemisters focus on inventing new tools, weapons, and other devices for the guild to use, the role of a blastseeker is to put those devices to work. Despite the name, not all such devices produce explosions, but all the most interesting ones (from the Izzet perspective) do.

```ad-statblock
title: Flux Blastseeker
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/GGR/Flux%20Blastseeker.webp#token)
*Medium humanoid (any race), Chaotic Neutral*

- **Armor Class** 12 (15 with [mage armor](2-Mechanics/CLI/spells/mage-armor.md))
- **Hit Points** 55 (`10d8 + 10`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|10 (+0)|15 (+2)|12 (+1)|20 (+5)| 9 (-1)|14 (+2)|

- **Proficiency Bonus** +3
- **Saving Throws** Dexterity +5, Intelligence +8
- **Skills** Arcana +8, Perception +2
- **Senses** passive Perception 12
- **Languages** Common plus any one language
- **Challenge** 5

## Traits

***Fluxbending Overcast (Recharge 5-6).*** The blastseeker can create an additional effect immediately after casting a spell. Roll a `dice:d6|noform|avg` (`d6`) to determine the effect: 1-3. The blastseeker teleports, swapping places with a creature it can see within 30 feet of it. 4-6. The blastseeker and each creature within 10 feet of it must succeed on a DC 16 Constitution saving throw or take `dice:2d10|noform|avg|text(11)` (`2d10`) thunder damage.

***Innate Spellcasting.*** The blastseeker's innate spellcasting ability is Intelligence (spell save DC 16, `dice:1d20+8|noform|text(+8)` to hit with spell attacks). The blastseeker can innately cast the following spells, requiring no components other than its Izzet gear, which doesn't function for others:

**1/day each**: [banishment](2-Mechanics/CLI/spells/banishment.md), [cone of cold](2-Mechanics/CLI/spells/cone-of-cold.md), [dimension door](2-Mechanics/CLI/spells/dimension-door.md), [fireball](2-Mechanics/CLI/spells/fireball.md), [ice storm](2-Mechanics/CLI/spells/ice-storm.md)

**3/day each**: [mage armor](2-Mechanics/CLI/spells/mage-armor.md) (self only), [scorching ray](2-Mechanics/CLI/spells/scorching-ray.md)

## Actions

***Quarterstaff.*** *Melee Weapon Attack:* `dice:1d20+3|noform|text(+3)` to hit, reach 5 ft., one target. *Hit:* `dice:1d6|noform|avg|text(3)` (`1d6`) bludgeoning damage, or `dice:1d8|noform|avg|text(4)` (`1d8`) bludgeoning damage if used with two hands.
```
^statblock