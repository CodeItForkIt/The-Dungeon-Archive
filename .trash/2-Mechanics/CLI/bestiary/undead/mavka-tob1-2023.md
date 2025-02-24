---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/tob1-2023
- monster/cr/12
- monster/environment/forest
- monster/size/medium
- monster/type/undead
aliases: ["Mavka"]
---
# Mavka
*Source: Tome of Beasts 1 (2023 Edition) p. 265*  

*With burnt and blackened skin, burnt twigs for hair, and clawed hands and feet that resemble burnt and twisted roots, this creature appears scorched and even frail. Pupilless red eyes gleam in its sockets with a hellish green flame.*

Mavkas are twisted dryads created by undead warlocks and vampiric experiments.

## Death Riders

Mavkas ride nightmares and are fearsome raiders, snatching victims up into the saddle, never to be seen again. They despise and trample foot soldiers as peasants unworthy of attention.

## Hag Killers

Mavkas are the mortal enemies of red hags, who call these undead horrors "greenbanes." When red hag covens discover vampires and other undead turning local dryads into mavkas, they go on a rampage, destroying all undead they encounter.

> [!note] Mavkas in Midgard
> 
> There were once three dryad sisters named Mica, Anthelia, and Saramantha. After his conquest of Morgau, the Black Prince Lucan had the dryads and their trees killed and then raised them as powerful undead—mavkas. His warlocks bonded the new undead with nightmares instead of trees to complete their corruption.
> 
> These three sisters have since spawned many more such undead fey. Some serve the Black Prince as generals or concubines, while others pursue their own ends, destroying vampires, laying waste to villages, and seeking power in the Shadow Realm.
^mavkas-in-midgard

## Statblock

```ad-statblock
title: Mavka
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ToB1-2023/Mavka.webp#token)
*Medium undead, Chaotic Evil*

- **Armor Class** 17 (natural armor)
- **Hit Points** 170 (`20d8 + 80`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|20 (+5)|15 (+2)|18 (+4)|13 (+1)|13 (+1)|18 (+4)|

- **Proficiency Bonus** +4
- **Saving Throws** Strength +9, Dexterity +6, Constitution +8, Charisma +8
- **Skills** Athletics +9, Nature +5, Perception +5
- **Senses** darkvision 90 ft., passive Perception 15
- **Damage Resistances** fire; bludgeoning, piercing, slashing from nonmagical attacks
- **Damage Immunities** necrotic, poison
- **Condition Immunities** [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** Abyssal, Common, Infernal, Sylvan
- **Challenge** 12

## Traits

***Mounted Warrior.*** While the mavka is mounted, her mount can't be [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed) or [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened).

***Nightmare Mount.*** The mavka has formed a bond with a nightmare. The nightmare acts as a controlled mount while carrying the mavka, obeying the mavka's spoken commands. Mounting and dismounting the nightmare costs the mavka only 5 feet of movement.

***Sunlight Hypersensitivity.*** The mavka takes 20 radiant damage when she starts her turn in sunlight. While in sunlight, she has disadvantage on attack rolls and ability checks.

***Undead Nature.*** The mavka doesn't require air, food, drink, or sleep.

***Spellcasting.*** The mavka casts one of the following spells, requiring no material components and using Charisma as the spellcasting ability (spell save DC 16):

**At will**: [create or destroy water](2-Mechanics/CLI/spells/create-or-destroy-water.md), [dancing lights](2-Mechanics/CLI/spells/dancing-lights.md)

**1/day each**: [bestow curse](2-Mechanics/CLI/spells/bestow-curse.md), [dispel magic](2-Mechanics/CLI/spells/dispel-magic.md)

**3/day each**: [darkness](2-Mechanics/CLI/spells/darkness.md), [hold person](2-Mechanics/CLI/spells/hold-person.md), [silence](2-Mechanics/CLI/spells/silence.md)

## Actions

***Multiattack.*** The mavka makes two Enervating Slam attacks or three Necrotic Bolt attacks. If she is riding a nightmare, the nightmare can then make one Hooves attack. If both Enervating Slam attacks hit one creature, the mavka regains hp equal to the total necrotic damage dealt by both attacks.

***Enervating Slam.*** *Melee Weapon Attack:* `dice:1d20+9|noform|text(+9)` to hit, reach 5 ft., one target. *Hit:* `dice:4d8+5|noform|avg|text(23)` (`4d8 + 5`) bludgeoning damage plus `dice:3d10|noform|avg|text(16)` (`3d10`) necrotic damage.

***Necrotic Bolt.*** *Ranged Spell Attack:* `dice:1d20+8|noform|text(+8)` to hit, range 60 ft., one target. *Hit:* `dice:4d10+4|noform|avg|text(26)` (`4d10 + 4`) necrotic damage.

***Flame Burst (Recharge 5-6).*** While riding a nightmare, the mavka channels her power into her mount, causing its fiery light to burn those nearby. Each creature within 20 feet of the mavka must make a DC 16 Dexterity saving throw, taking `dice:12d8|noform|avg|text(54)` (`12d8`) fire damage on a failed save, or half as much damage on a successful one.
```
^statblock

## Environment

forest