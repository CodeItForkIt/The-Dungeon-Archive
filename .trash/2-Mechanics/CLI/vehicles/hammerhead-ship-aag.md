---
obsidianUIMode: preview
cssclasses: json5e-vehicle
tags:
- compendium/src/5e/aag
- vehicle/terrain/sea
- vehicle/terrain/space
- vehicle/type/spelljammer
aliases: ["Hammerhead Ship"]
---
# Hammerhead Ship
%%-- Embedded content starts on the next line. --%%
*Source: Astral Adventurer's Guide p. 32, Spelljammer Academy*  

Hammerhead ships are popular craft, especially among pirates and merchants carrying heavy cargo. They can float on water and sail across it, but they aren't built to land on the ground (their keels would cause them to tip to one side). Standard weapons on a hammerhead ship include fore and aft mangonels, a ballista, and a reinforced bow for ramming.

```ad-statblock
title: Hammerhead Ship
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/vehicles/tokens/AAG/Hammerhead%20Ship.webp#token)
*Spelljammer (250 ft. by 25 ft.); space, sea*

- **Armor Class** 15
- **Hit Points** 400
- **Damage Threshold** 15
- **Speed** fly 35 ft. (fly 4 mph ^[96.0 miles per day])
- **Cargo** 30 tons tons
- **Crew** 15 crew
- **Keel/Beam** 250 ft. by 25 ft.
- **Cost** 40,000 gp

## Weapon: Ballista (Crew: 3)

- **Armor Class** 15
- **Hit Points** 50
- **Cost** 50 gp (ballista), 5 gp (bolt)

It takes 1 action to load the ballista, 1 action to aim it, and 1 action to fire it.

**Bolt** *Ranged Weapon Attack:* `dice:1d20+6|noform|text(+6)` to hit, range 120/480 ft., one target. *Hit:* `dice:3d10|noform|avg|text(16)` (`3d10`) piercing damage.

## Weapon: 2 Mangonels (Crew: 5 each)

- **Armor Class** 15
- **Hit Points** 100
- **Cost** 100 gp (mangonel), ⏤ (stone)

It takes 2 actions to load a mangonel, 2 actions to aim it, and 1 action to fire it.

**Mangonel Stone** *Ranged Weapon Attack:* `dice:1d20+5|noform|text(+5)` to hit, range 200/800 ft. (can't hit targets within 60 ft. of it), one target. *Hit:* `dice:5d10|noform|avg|text(27)` (`5d10`) bludgeoning damage.

## Weapon: Blunt Ram

- **Cost** ⏤ (included in ship cost)

The ship's spelljammer can make the following attack when the ship runs into another object or into a Gargantuan creature (see "Crashing" in chapter 2 of Astral Adventurer's Guide).

**Blunt Ram** *Melee Weapon Attack:* `dice:1d20+8|noform|text(+8)` to hit, range 0 ft. one object or Gargantuan creature. *Hit:* `dice:16d10|noform|avg|text(88)` (`16d10`) bludgeoning damage. The hammerhead ship takes half as much damage and comes to a dead stop. *Miss:* The attack deals no damage, the target moves into the nearest unoccupied space that isn't in the hammerhead ship's path, and the hammerhead ship can continue moving if it has any movement left.
```
^statblock