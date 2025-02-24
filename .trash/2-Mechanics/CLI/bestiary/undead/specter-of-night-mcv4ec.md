---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/mcv4ec
- monster/cr/12
- monster/size/huge
- monster/type/undead
aliases: ["Specter of Night"]
---
# Specter of Night
*Source: Monstrous Compendium Volume 3: 4: Eldraine Creatures*  

Like dark mirrors of Eldraine's archons (see " Archon of Boundaries "), specters appear as shrouded figures mounted on horrific flying beasts. It is easy to look at a specter and imagine the rider in command of the mount, but the truth is the opposite; the flying horror is an Undead monster that scours the wilds for a knightly corpse. On finding one, the horror binds its essence to the dead body, giving the corpse the semblance of life as a rider. The two function as a single creature, more powerful for their unnatural union.

Humans of Eldraine view specters as heralds of death. Specters are said to utter a keening wail, mournful beyond all other sounds and audible only to those who are about to die.

```ad-statblock
title: Specter of Night
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/MCV4EC/Specter%20of%20Night.webp#token)
*Huge undead, typically  Neutral Evil*

- **Armor Class** 15 (natural armor)
- **Hit Points** 142 (`15d12 + 45`)
- **Speed** 60 ft., fly 60 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|22 (+6)|18 (+4)|17 (+3)|12 (+1)|13 (+1)|12 (+1)|

- **Proficiency Bonus** +4
- **Saving Throws** Dexterity +8, Wisdom +5
- **Skills** Perception +5
- **Senses** darkvision 120 ft., passive Perception 15
- **Damage Resistances** necrotic
- **Damage Immunities** poison
- **Condition Immunities** [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** understands Common but can't speak
- **Challenge** 12

## Traits

***Legendary Resistance (3/Day).*** If the specter fails a saving throw, it can choose to succeed instead.

***Magic Resistance.*** The specter has advantage on saving throws against spells and other magical effects.

## Actions

***Multiattack.*** The specter uses Mournful Keening if available, then makes one Hooves attack and one Reaping Scythe attack.

***Hooves.*** *Melee Weapon Attack:* `dice:1d20+10|noform|text(+10)` to hit, reach 10 ft., one target. *Hit:* `dice:3d6+6|noform|avg|text(16)` (`3d6 + 6`) bludgeoning damage plus `dice:8d6|noform|avg|text(28)` (`8d6`) necrotic damage. If the target is a Medium or smaller creature, it must succeed on a DC 18 Strength saving throw or have the [prone](2-Mechanics/CLI/rules/conditions.md#Prone) condition.

***Mournful Keening (Recharge 6).*** The specter utters a keening wail, calling to those close to death. Each non-Undead creature within 120 feet of the specter must make a DC 15 Constitution saving throw. On a failure, the creature hears the wail and is marked for death.

A creature marked for death can't regain hit points, has disadvantage on death saving throws, and all attack rolls against it are made with advantage. This effect lasts for 1 minute or until the creature is targeted by a [remove curse](2-Mechanics/CLI/spells/remove-curse.md) spell or similar magic.

***Reaping Scythe.*** *Melee Weapon Attack:* `dice:1d20+10|noform|text(+10)` to hit, reach 10 ft., one target. *Hit:* `dice:1d12+6|noform|avg|text(12)` (`1d12 + 6`) slashing damage plus `dice:8d6|noform|avg|text(28)` (`8d6`) necrotic damage. If the target is a creature, it must succeed on a DC 15 Constitution saving throw or gain a level of [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion).
```
^statblock