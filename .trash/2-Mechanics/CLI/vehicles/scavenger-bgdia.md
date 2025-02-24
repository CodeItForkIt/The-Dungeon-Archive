---
obsidianUIMode: preview
cssclasses: json5e-vehicle
tags:
- compendium/src/5e/bgdia
- vehicle/size/huge
- vehicle/terrain/land
- vehicle/type/infernal-war-machine
aliases: ["Scavenger"]
---
# Scavenger
%%-- Embedded content starts on the next line. --%%
*Source: Baldur's Gate: Descent Into Avernus p. 219*  

The Scavenger handles like a small bus and is used to sift through battlefield detritus for scrap metal and other materials worth salvaging. Attached to the back of the vehicle is a swinging crane with an iron grappling claw fastened to the end of a winch and a 50-foot-long chain.

```ad-statblock
title: Scavenger
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/vehicles/tokens/BGDIA/Scavenger.webp#token)
*Huge vehicle (4 tons 1000 lb.); land*

- **Cargo Capacity** 2 tons
- **Armor Class** 19
- **Hit Points** 150 (damage threshold 10, mishap threshold 20)
- **Speed** 100 ft.
- *Travel Pace* 10 miles per hour (240 miles per day) ^[Based on _Special Travel Pace_, DMG p242]

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|20 (+5)|12 (+1)|20 (+5)| 0 (-5)| 0 (-5)| 0 (-5)|

- **Damage Immunities** fire, poison, psychic
- **Condition Immunities** [blinded](2-Mechanics/CLI/rules/conditions.md#Blinded), [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [deafened](2-Mechanics/CLI/rules/conditions.md#Deafened), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened), [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed), [petrified](2-Mechanics/CLI/rules/conditions.md#Petrified), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned), [stunned](2-Mechanics/CLI/rules/conditions.md#Stunned), [unconscious](2-Mechanics/CLI/rules/conditions.md#Unconscious)

## Traits

**Crushing Wheels** The Scavenger can move through the space of any Large or smaller creature. When it does, the creature must succeed on a DC 12 Dexterity saving throw or take `dice:3d10|noform|avg|text(16)` (`3d10`) bludgeoning damage and be knocked [prone](2-Mechanics/CLI/rules/conditions.md#Prone). If the creature was already [prone](2-Mechanics/CLI/rules/conditions.md#Prone), it takes an extra `dice:3d10|noform|avg|text(16)` (`3d10`) bludgeoning damage. This trait can't be used against a particular creature more than once each turn.

**Magic Weapons** The Scavenger's weapon attacks are magical.

**Prone Deficiency** If the Scavenger rolls over and falls [prone](2-Mechanics/CLI/rules/conditions.md#Prone), it can't right itself and is [incapacitated](2-Mechanics/CLI/rules/conditions.md#Incapacitated) until flipped upright.

## Action Stations

**Helm (Requires 1 Crew and Grants Three-Quarters Cover)** Drive and steer the Scavenger.

**Grappling Claw (Requires 1 Crew and Grants Half Cover)** *Melee Weapon Attack:* `dice:1d20+10|noform|text(+10)` to hit, reach 15 ft., one target. *Hit:* The target is [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) (escape DC 12). If the target is a creature, it is [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained) until the grapple ends. The grappling claw can grapple only one target at a time, and the claw's operator can use a bonus action to make the claw release whatever it's holding.

**2 Harpoon Flingers (Each Station Requires 1 Crew and Grants Half Cover)** *Ranged Weapon Attack:* `dice:1d20+6|noform|text(+6)` to hit, range 120 ft., one target. *Hit:* `dice:2d8+1|noform|avg|text(10)` (`2d8 + 1`) piercing damage.
```
^statblock