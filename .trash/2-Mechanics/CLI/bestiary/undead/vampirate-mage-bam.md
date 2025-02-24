---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/bam
- monster/cr/5
- monster/size/medium
- monster/type/undead
aliases: ["Vampirate Mage"]
---
# Vampirate Mage
*Source: Boo's Astral Menagerie p. 63, Light of Xaryxis*  

A ship of vampirates needs a spellcaster to operate the spelljamming helm. A vampirate mage rarely, if ever, leaves the helm.

```ad-statblock
title: Vampirate Mage
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/BAM/Vampirate%20Mage.webp#token)
*Medium undead, typically  Lawful Evil*

- **Armor Class** 14 (natural armor)
- **Hit Points** 68 (`8d8 + 32`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|12 (+1)|14 (+2)|18 (+4)|13 (+1)|14 (+2)|15 (+2)|

- **Proficiency Bonus** +3
- **Saving Throws** Wisdom +5, Charisma +5
- **Skills** ⏤
- **Senses** darkvision 120 ft., passive Perception 12
- **Damage Vulnerabilities** radiant
- **Damage Immunities** cold, necrotic, poison
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** the languages it knew in life
- **Challenge** 5

## Traits

***Explode.*** When the mage is reduced to 0 hit points, it explodes in a cloud of ash. Any creature within 5 feet of it must succeed on a DC 14 Constitution saving throw or take `dice:2d10|noform|avg|text(11)` (`2d10`) necrotic damage.

***Spider Climb.*** The mage can climb difficult surfaces, including upside down on ceilings, without needing to make an ability check.

***Unusual Nature.*** The mage doesn't require air or drink.

***Spellcasting.*** The mage casts one of the following spells, using Charisma as the spellcasting ability (spell save DC 13):

**At will**: [mage hand](2-Mechanics/CLI/spells/mage-hand.md), [message](2-Mechanics/CLI/spells/message.md)

**1/day**: [darkness](2-Mechanics/CLI/spells/darkness.md), [dimension door](2-Mechanics/CLI/spells/dimension-door.md), [fly](2-Mechanics/CLI/spells/fly.md), [hypnotic pattern](2-Mechanics/CLI/spells/hypnotic-pattern.md)

## Actions

***Multiattack.*** The mage makes two Ray of Cold attacks.

***Energy Drain.*** *Melee or Ranged Spell Attack:* `dice:1d20+5|noform|text(+5)` to hit, reach 5 ft. or range 30 ft., one creature. *Hit:* `dice:4d10|noform|avg|text(22)` (`4d10`) necrotic damage. A Humanoid reduced to 0 hit points by this attack dies and instantly transforms into a free-willed shadow under the DM's control.

***Ray of Cold.*** *Ranged Spell Attack:* `dice:1d20+5|noform|text(+5)` to hit, range 120 ft., one target. *Hit:* `dice:2d8+2|noform|avg|text(11)` (`2d8 + 2`) cold damage.
```
^statblock