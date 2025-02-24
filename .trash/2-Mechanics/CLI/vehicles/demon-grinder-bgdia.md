---
obsidianUIMode: preview
cssclasses: json5e-vehicle
tags:
- compendium/src/5e/bgdia
- vehicle/size/gargantuan
- vehicle/terrain/land
- vehicle/type/infernal-war-machine
aliases: ["Demon Grinder"]
---
# Demon Grinder
%%-- Embedded content starts on the next line. --%%
*Source: Baldur's Gate: Descent Into Avernus p. 219*  

A Demon Grinder is a bulky, armored coach that rumbles loudly as it crushes obstacles and enemies in its path with the help of a swinging wrecking ball. Iron jaws are mounted on the front of the vehicle, which handles like a garbage truck.

```ad-statblock
title: Demon Grinder
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/vehicles/tokens/BGDIA/Demon%20Grinder.webp#token)
*Gargantuan vehicle (6 tons); land*

- **Cargo Capacity** 1 ton
- **Armor Class** 19
- **Hit Points** 200 (damage threshold 10, mishap threshold 20)
- **Speed** 100 ft.
- *Travel Pace* 10 miles per hour (240 miles per day) ^[Based on _Special Travel Pace_, DMG p242]

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|18 (+4)|10 (+0)|18 (+4)| 0 (-5)| 0 (-5)| 0 (-5)|

- **Damage Immunities** fire, poison, psychic
- **Condition Immunities** [blinded](2-Mechanics/CLI/rules/conditions.md#Blinded), [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [deafened](2-Mechanics/CLI/rules/conditions.md#Deafened), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened), [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed), [petrified](2-Mechanics/CLI/rules/conditions.md#Petrified), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned), [stunned](2-Mechanics/CLI/rules/conditions.md#Stunned), [unconscious](2-Mechanics/CLI/rules/conditions.md#Unconscious)

## Traits

**Crushing Wheels** The Demon Grinder can move through the space of any Large or smaller creature. When it does, the creature must succeed on a DC 11 Dexterity saving throw or take `dice:4d10|noform|avg|text(22)` (`4d10`) bludgeoning damage and be knocked [prone](2-Mechanics/CLI/rules/conditions.md#Prone). If the creature was already [prone](2-Mechanics/CLI/rules/conditions.md#Prone), it takes an extra `dice:4d10|noform|avg|text(22)` (`4d10`) bludgeoning damage. This trait can't be used against a particular creature more than once each turn.

**Magic Weapons** The Demon Grinder's weapon attacks are magical.

**Prone Deficiency** If the Demon Grinder rolls over and falls [prone](2-Mechanics/CLI/rules/conditions.md#Prone), it can't right itself and is [incapacitated](2-Mechanics/CLI/rules/conditions.md#Incapacitated) until flipped upright.

## Action Stations

**Helm (Requires 1 Crew and Grants Three-Quarters Cover)** Drive and steer the Demon Grinder.

**Chomper (Requires 1 Crew and Grants Half Cover)** *Melee Weapon Attack:* `dice:1d20+9|noform|text(+9)` to hit, reach 5 ft., one target. *Hit:* `dice:6d6+4|noform|avg|text(25)` (`6d6 + 4`) piercing damage. A target reduced to 0 hit points by this damage is ground to bits and spit out through pipes on both sides of the Demon Grinder. Any nonmagical items the target was holding or carrying are destroyed as well.

**Wrecking Ball (Requires 1 Crew and Grants Half Cover)** *Melee Weapon Attack:* `dice:1d20+9|noform|text(+9)` to hit, reach 15 ft., one target. *Hit:* `dice:8d8+4|noform|avg|text(40)` (`8d8 + 4`) bludgeoning damage. Double the damage if the target is an object or a structure.

**2 Harpoon Flingers (Each Station Requires 1 Crew and Grants Half Cover)** *Ranged Weapon Attack:* `dice:1d20+5|noform|text(+5)` to hit, range 120 ft., one target. *Hit:* `dice:2d8|noform|avg|text(9)` (`2d8`) piercing damage.
```
^statblock