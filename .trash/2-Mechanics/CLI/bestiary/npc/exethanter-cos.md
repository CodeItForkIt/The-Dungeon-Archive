---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/cos
- monster/cr/10
- monster/size/medium
- monster/type/undead
aliases: ["Exethanter"]
---
# Exethanter
*Source: Curse of Strahd p. 189*  

```ad-statblock
title: Exethanter
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/CoS/Exethanter.webp#token)
*Medium undead, Any Evil alignment*

- **Armor Class** 17 (natural armor)
- **Hit Points** 99 (`18d8 + 54`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|11 (+0)|16 (+3)|16 (+3)|20 (+5)|14 (+2)|16 (+3)|

- **Proficiency Bonus** +4
- **Saving Throws** Constitution +10, Intelligence +12, Wisdom +9
- **Skills** Arcana +19, History +12, Insight +9, Perception +9
- **Senses** truesight 120 ft., passive Perception 19
- **Damage Resistances** cold, lightning, necrotic
- **Damage Immunities** poison; bludgeoning, piercing, slashing from nonmagical attacks
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened), [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** Common plus up to five other languages
- **Challenge** 10

## Traits

***Legendary Resistance (3/Day).*** If Exethanter fails a saving throw, it can choose to succeed instead.

***Rejuvenation.*** If it has a phylactery, a destroyed lich gains a new body in `dice:1d10|noform|avg` (`1d10`) days, regaining all its hit points and becoming active again. The new body appears within 5 feet of the phylactery.

***Turn Resistance.*** Exethanter has advantage on saving throws against any effect that turns undead.

***Spellcasting.*** Exethanter is an 18th-level spellcaster. Its spellcasting ability is Intelligence (spell save DC 20, `dice:1d20+12|noform|text(+12)` to hit with spell attacks). Exethanter has the following wizard spells prepared:

**Cantrips (at will)**: [mage hand](2-Mechanics/CLI/spells/mage-hand.md), [prestidigitation](2-Mechanics/CLI/spells/prestidigitation.md), [ray of frost](2-Mechanics/CLI/spells/ray-of-frost.md)

## Actions

***Paralyzing Touch.*** *Melee Spell Attack:* `dice:1d20+12|noform|text(+12)` to hit, reach 5 ft., one creature. *Hit:* `dice:3d6|noform|avg|text(10)` (`3d6`) cold damage. The target must succeed on a DC 18 Constitution saving throw or be [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed) for 1 minute. The target can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.

## Legendary Actions

***Cantrip.*** Exethanter casts a cantrip.

***Paralyzing Touch (Costs 2 Actions).*** Exethanter uses its Paralyzing Touch.

***Frightening Gaze (Costs 2 Actions).*** Exethanter fixes its gaze on one creature it can see within 10 feet of it. The target must succeed on a DC 18 Wisdom saving throw against this magic or become [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened) for 1 minute. The [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened) target can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success. If a target's saving throw is successful or the effect ends for it, the target is immune to Exethanter's gaze for the next 24 hours.

***Disrupt Life (Costs 3 Actions).*** Each non-undead creature within 20 feet of Exethanter must make a DC 18 Constitution saving throw against this magic, taking `dice:6d6|noform|avg|text(21)` (`6d6`) necrotic damage on a failed save, or half as much damage on a successful one.
```
^statblock