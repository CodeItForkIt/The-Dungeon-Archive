---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/bgg
- monster/cr/4
- monster/size/medium
- monster/type/humanoid/druid
aliases: ["Firbolg Primeval Warden"]
---
# Firbolg Primeval Warden
*Source: Bigby Presents: Glory of the Giants p. 136*  

Like giant priests of Hiatea, firbolgs who serve her fall into two distinct roles that parallel Hiatea's dual nature. At home, primeval wardens tend the hearths and tutor the young. Primeval wardens who patrol the borders of firbolg communities are fierce hunters who guard against external threats and incursions.

## Firbolgs

Distant cousins of giants, the first firbolgs wandered the primeval forests of the multiverse, and the magic of those forests entwined itself with the firbolgs' souls. Ages later, that magic still thrums inside firbolgs.

Firbolgs are often drawn to the service or emulation of the gods Diancastra and Hiatea. Firbolgs' innate magic of obscurement and trickery resonates with Diancastra's wily resourcefulness. A traditional emphasis on community and harmony leads many firbolgs to pledge themselves to Hiatea's service.

## Statblock

```ad-statblock
title: Firbolg Primeval Warden
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/BGG/Firbolg%20Primeval%20Warden.webp#token)
*Medium humanoid (druid), Any alignment*

- **Armor Class** 16 ([hide armor](2-Mechanics/CLI/items/hide-armor.md), [shield](2-Mechanics/CLI/items/shield.md))
- **Hit Points** 65 (`10d8 + 20`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|16 (+3)|14 (+2)|14 (+2)|12 (+1)|16 (+3)|11 (+0)|

- **Proficiency Bonus** +2
- **Saving Throws** Intelligence +3, Wisdom +5
- **Skills** Medicine +5, Nature +3, Perception +7
- **Senses** passive Perception 17
- **Languages** Common, Druidic, Giant
- **Challenge** 4

***Spellcasting.*** The firbolg casts one of the following spells, using Wisdom as the spellcasting ability (spell save DC 13):

**At will**: [entangle](2-Mechanics/CLI/spells/entangle.md), [speak with animals](2-Mechanics/CLI/spells/speak-with-animals.md), [speak with plants](2-Mechanics/CLI/spells/speak-with-plants.md)

**1/day each**: [commune with nature](2-Mechanics/CLI/spells/commune-with-nature.md) (as an action), [detect magic](2-Mechanics/CLI/spells/detect-magic.md), [disguise self](2-Mechanics/CLI/spells/disguise-self.md)

## Actions

***Multiattack.*** The firbolg makes two Spear or Fire Lance attacks.

***Spear.*** *Melee or Ranged Weapon Attack:* `dice:1d20+5|noform|text(+5)` to hit, reach 5 ft. or range 20/60 ft., one target. *Hit:* `dice:1d6+3|noform|avg|text(6)` (`1d6 + 3`) piercing damage plus `dice:2d8|noform|avg|text(9)` (`2d8`) fire damage.

***Fire Lance.*** *Ranged Spell Attack:* `dice:1d20+5|noform|text(+5)` to hit, range 120 ft., one target. *Hit:* `dice:2d10+3|noform|avg|text(14)` (`2d10 + 3`) fire damage.

## Bonus Actions

***Hidden Step (2/Day).*** The firbolg magically turns [invisible](2-Mechanics/CLI/rules/conditions.md#Invisible) until the start of its next turn, until it makes an attack roll, or until it forces someone to make a saving throw.
```
^statblock