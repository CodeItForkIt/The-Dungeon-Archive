---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/cm
- monster/cr/18
- monster/size/medium
- monster/type/undead
aliases: ["Lichen Lich"]
---
# Lichen Lich
*Source: Candlekeep Mysteries p. 223*  

Lichen liches are undead remnants of powerful druids.

A lichen lich looks like a skeleton covered with fungi and bark-like lichen. A lichen lich has vines within its chest cavity. These vines exude viscid and poisonous black fluid.

```ad-statblock
title: Lichen Lich
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/CM/Lichen%20Lich.webp#token)
*Medium undead, Unaligned*

- **Armor Class** 20 (natural armor)
- **Hit Points** 225 (`30d8 + 90`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|11 (+0)|16 (+3)|16 (+3)|14 (+2)|20 (+5)|16 (+3)|

- **Proficiency Bonus** +6
- **Saving Throws** Constitution +9, Intelligence +8, Wisdom +11, Charisma +9
- **Skills** Medicine +11, Nature +14, Perception +11, Survival +11
- **Senses** truesight 120 ft., passive Perception 21
- **Damage Resistances** cold, necrotic
- **Damage Immunities** poison
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened), [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned), [stunned](2-Mechanics/CLI/rules/conditions.md#Stunned)
- **Languages** Common, Druidic, Sylvan
- **Challenge** 18

## Traits

***Legendary Resistance (3/Day).*** If the lich fails a saving throw, it can choose to succeed instead.

***Rejuvenation.*** If it has a phylactery, a destroyed lich gains a new body in `dice:1d10|noform|avg` (`1d10`) days, regaining all its hit points and becoming active again. The new body appears within 5 feet of the phylactery.

***Spellcasting.*** The lich casts one of the following spells using Wisdom as the spellcasting ability (save DC 19):

**At will**: [druidcraft](2-Mechanics/CLI/spells/druidcraft.md)

**1/day each**: [antilife shell](2-Mechanics/CLI/spells/antilife-shell.md), [dispel magic](2-Mechanics/CLI/spells/dispel-magic.md), [speak with plants](2-Mechanics/CLI/spells/speak-with-plants.md), [transport via plants](2-Mechanics/CLI/spells/transport-via-plants.md), 

**3/day each**: [detect magic](2-Mechanics/CLI/spells/detect-magic.md), [fog cloud](2-Mechanics/CLI/spells/fog-cloud.md), [pass without trace](2-Mechanics/CLI/spells/pass-without-trace.md)

## Actions

***Multiattack.*** The lich makes four attacks.

***Poisonous Touch.*** *Melee Weapon Attack:* `dice:1d20+9|noform|text(+9)` to hit, reach 10 ft., one creature. *Hit:* `dice:5d6|noform|avg|text(17)` (`5d6`) poison damage, and the target must succeed on a DC 19 Constitution saving throw or be [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned) for 1 minute. The target can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.

***Wither.*** *Ranged Spell Attack:* `dice:1d20+9|noform|text(+9)` to hit, range 60 ft., one target. *Hit:* `dice:4d6|noform|avg|text(14)` (`4d6`) necrotic damage.

***Fire Storm (7th-Level Spell; 1/Day).*** The lich fills up to ten 10-foot cubes with fire. Every cube must be within 150 feet of the lich and occupy a space the lich can see, and each cube must have at least one face adjacent to the face of another cube. Each creature in the area must make a DC 19 Dexterity saving throw, taking `dice:7d10|noform|avg|text(38)` (`7d10`) fire damage on a failed save, or half as much damage on a successful one. The fire ignites flammable objects in the area that aren't being worn or carried. If the lich chooses, plant life in the area is unaffected by the spell.

## Legendary Actions

***Attack.*** The lich makes an attack.

***Poison Prick (Cost 2 Actions).*** The lich targets one [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned) creature it can see within 30 feet of it. The target must succeed on a DC 19 Constitution saving throw or fall [unconscious](2-Mechanics/CLI/rules/conditions.md#Unconscious) until the [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned) condition ends on it.

***Sap Life (Costs 2 Actions).*** The lich targets one creature it can see within 30 feet of it. The target must succeed on a DC 19 Constitution saving throw or take `dice:2d10|noform|avg|text(11)` (`2d10`) necrotic damage. The lich regains a number of hit points equal to the amount of damage that the creature takes.

![Lichen Lich](2-Mechanics/CLI/bestiary/legendary-group/lichen-lich-cm.md)
```
^statblock