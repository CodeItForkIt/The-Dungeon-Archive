---
obsidianUIMode: preview
cssclasses: json5e-vehicle
tags:
- compendium/src/5e/bgdia
- vehicle/size/huge
- vehicle/terrain/land
- vehicle/type/infernal-war-machine
aliases: ["Tormentor"]
---
# Tormentor
%%-- Embedded content starts on the next line. --%%
*Source: Baldur's Gate: Descent Into Avernus p. 218*  

The Tormentor handles like a dune buggy and is designed for raiding and scouting. Bladed iron wheels drive the vehicle forward.

```ad-statblock
title: Tormentor
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/vehicles/tokens/BGDIA/Tormentor.webp#token)
*Huge vehicle (1 ton 1000 lb.); land*

- **Cargo Capacity**  500 lb.
- **Armor Class** 19
- **Hit Points** 60 (damage threshold 10, mishap threshold 20)
- **Speed** 100 ft.
- *Travel Pace* 10 miles per hour (240 miles per day) ^[Based on _Special Travel Pace_, DMG p242]

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|16 (+3)|14 (+2)|14 (+2)| 0 (-5)| 0 (-5)| 0 (-5)|

- **Damage Immunities** fire, poison, psychic
- **Condition Immunities** [blinded](2-Mechanics/CLI/rules/conditions.md#Blinded), [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [deafened](2-Mechanics/CLI/rules/conditions.md#Deafened), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened), [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed), [petrified](2-Mechanics/CLI/rules/conditions.md#Petrified), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned), [stunned](2-Mechanics/CLI/rules/conditions.md#Stunned), [unconscious](2-Mechanics/CLI/rules/conditions.md#Unconscious)

## Traits

**Crushing Wheels** The Tormentor can move through the space of any Medium or smaller creature. When it does, the creature must succeed on a DC 13 Dexterity saving throw or take `dice:2d10|noform|avg|text(11)` (`2d10`) bludgeoning damage and be knocked [prone](2-Mechanics/CLI/rules/conditions.md#Prone).If the creature was already [prone](2-Mechanics/CLI/rules/conditions.md#Prone), it takes an extra `dice:2d10|noform|avg|text(11)` (`2d10`) bludgeoning damage.This trait can't be used against a particular creature more than once each turn.

**Magic Weapons** The Tormentor's weapon attacks are magical.

**Prone Deficiency** If the Tormentor rolls over and falls [prone](2-Mechanics/CLI/rules/conditions.md#Prone), it can't right itself and is [incapacitated](2-Mechanics/CLI/rules/conditions.md#Incapacitated) until flipped upright.

**Raking Scythes** When the Tormentor moves within 5 feet of a creature that isn't [prone](2-Mechanics/CLI/rules/conditions.md#Prone) or another vehicle for the first time on a turn, it can rake the creature or vehicle with its protruding blades for `dice:2d10+2|noform|avg|text(13)` (`2d10 + 2`) slashing damage. A creature moves out of the way and takes no damage if it succeeds on a DC 13 Dexterity saving throw.A vehicle moves out of the way and takes no damage if its driver succeeds on the saving throw.

## Action Stations

**Helm (Requires 1 Crew and Grants Three-Quarters Cover)** Drive and steer the Tormentor

**Harpoon Flinger (Requires 1 Crew and Grants Half Cover)** *Ranged Weapon Attack:* `dice:1d20+7|noform|text(+7)` to hit, range 120 ft., one target. *Hit:* `dice:2d8+2|noform|avg|text(11)` (`2d8 + 2`) piercing damage.

## Reactions

**Juke** If the Tormentor is able to move, the driver can use its reaction to grant the Tormentor advantage on a Dexterity saving throw.
```
^statblock