---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/bam
- monster/cr/4
- monster/size/large
- monster/type/aberration
aliases: ["Neh-thalggu"]
---
# Neh-thalggu
*Source: Boo's Astral Menagerie p. 39, Light of Xaryxis*  

Known throughout the multiverse as brain collectors, neh-thalggu consume the brains of Humanoids and use them as receptacles to enhance their magical abilities.

Neh-thalggu are born in the nightmarish Far Realm, but they spread across the Astral Plane and find their way onto the various worlds of the Material Plane, where brains are much more abundant. A neh-thalggu has a bulbous body and six legs resembling those of a crustacean. Four bulging eyes and a tooth-filled maw dominate its hideous visage. Behind and above these features, one or more lumps protrude from its body, each one containing a brain the neh-thalggu has consumed.

After a neh-thalggu kills a victim, it uses its pincers to cut open the victim's head and remove the brain. It then swallows the brain whole. The collected brain is stored inside one of several pockets in the neh-thalggu's head. Once it has collected twelve brains in this fashion, it is overcome by an urge to return to the Far Realm and begins devoting all its energy to finding a way home.

In an encounter with a neh-thalggu, roll a `dice:d12|noform|avg` (`d12`) to determine how many brains it has already collected.

```ad-statblock
title: Neh-thalggu
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/BAM/Neh-thalggu.webp#token)
*Large aberration, typically  Chaotic Neutral*

- **Armor Class** 14 (natural armor)
- **Hit Points** 95 (`10d10 + 40`)
- **Speed** 40 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|15 (+2)| 8 (-1)|18 (+4)|12 (+1)|11 (+0)| 7 (-2)|

- **Proficiency Bonus** +2
- **Saving Throws** ⏤
- **Skills** ⏤
- **Senses** darkvision 120 ft., passive Perception 10
- **Languages** Deep Speech; see also Brain Dump
- **Challenge** 4

## Traits

***Brain Dump.*** Whenever the neh-thalggu consumes a brain, it gains the magical ability to speak and understand languages known by the brain's previous owner.

***Unusual Nature.*** The neh-thalggu doesn't require air.

***Spellcasting (Psionics).*** The neh-thalggu casts one of the following spells, requiring no spell components and using Intelligence as the spellcasting ability (spell save DC 11). It must have consumed the requisite number of brains to cast the spell, as indicated:

**1/day each**: [arms of Hadar](2-Mechanics/CLI/spells/arms-of-hadar.md) (1 brain), [detect magic](2-Mechanics/CLI/spells/detect-magic.md) (2 brains), [magic missile](2-Mechanics/CLI/spells/magic-missile.md) (3 brains), [Tenser's floating disk](2-Mechanics/CLI/spells/tensers-floating-disk.md) (4 brains), [darkness](2-Mechanics/CLI/spells/darkness.md) (5 brains), [hold person](2-Mechanics/CLI/spells/hold-person.md) (6 brains), [invisibility](2-Mechanics/CLI/spells/invisibility.md) (7 brains), [spider climb](2-Mechanics/CLI/spells/spider-climb.md) (8 brains), [fear](2-Mechanics/CLI/spells/fear.md) (9 brains), [hypnotic pattern](2-Mechanics/CLI/spells/hypnotic-pattern.md) (10 brains), [major image](2-Mechanics/CLI/spells/major-image.md) (11 brains), [stinking cloud](2-Mechanics/CLI/spells/stinking-cloud.md) (12 brains)

## Actions

***Multiattack.*** The neh-thalggu makes one Bite attack and two Claw attacks.

***Bite.*** *Melee Weapon Attack:* `dice:1d20+4|noform|text(+4)` to hit, reach 5 ft., one target. *Hit:* `dice:2d8+2|noform|avg|text(11)` (`2d8 + 2`) piercing damage.

***Claw.*** *Melee Weapon Attack:* `dice:1d20+4|noform|text(+4)` to hit, reach 5 ft., one target. *Hit:* `dice:1d4+2|noform|avg|text(4)` (`1d4 + 2`) slashing damage.

***Extract Brain.*** *Melee Weapon Attack:* `dice:1d20+4|noform|text(+4)` to hit, reach 5 ft., one [incapacitated](2-Mechanics/CLI/rules/conditions.md#Incapacitated) Humanoid. *Hit:* `dice:10d6|noform|avg|text(35)` (`10d6`) piercing damage. If this damage reduces the target to 0 hit points, the neh-thalggu kills the target by extracting and consuming its brain.

***Mind Blast (Recharge 5-6).*** The neh-thalggu magically emits psychic energy at one Humanoid it can see within 10 feet of itself. The target must make a DC 14 Wisdom saving throw. On a failed save, the target takes `dice:2d8|noform|avg|text(9)` (`2d8`) psychic damage and is [incapacitated](2-Mechanics/CLI/rules/conditions.md#Incapacitated) until the end of its next turn. On a successful save, the target takes half as much damage and isn't [incapacitated](2-Mechanics/CLI/rules/conditions.md#Incapacitated).
```
^statblock