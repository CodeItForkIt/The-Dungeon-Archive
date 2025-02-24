---
obsidianUIMode: preview
cssclasses: json5e-vehicle
tags:
- compendium/src/5e/aag
- vehicle/terrain/sea
- vehicle/terrain/space
- vehicle/type/spelljammer
aliases: ["Living Ship"]
---
# Living Ship
%%-- Embedded content starts on the next line. --%%
*Source: Astral Adventurer's Guide p. 36*  

Druids, rangers, and clerics devoted to gods of nature are often found aboard living ships, as are Wildspace explorers who don't want to have to worry about their ship's air envelope becoming fouled during a long voyage.

This ship's main distinctive feature is the fully grown [treant](2-Mechanics/CLI/bestiary/plant/treant.md) on the aft deck. The treant has a speed of 0 because its roots are woven into the deck; it and the ship are inseparable. If the ship is reduced to 0 hit points, the treant dies of shock. The ship can function if its treant dies, but the treant can never be replaced with another.

When the treant finishes a long rest, it repairs the ship's hull, enabling the ship to regain `dice:4d12|noform|avg` (`4d12`) hit points, and refreshes the ship's air envelope (turning deadly air into foul air, or foul air into fresh air).

A living ship can float on water and sail across it, but it can't land safely on the ground (its keel would cause it to roll on its side). Its standard weaponry is an aft-mounted ballista.

```ad-statblock
title: Living Ship
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/vehicles/tokens/AAG/Living%20Ship.webp#token)
*Spelljammer (80 ft. by 20 ft.); space, sea*

- **Armor Class** 15
- **Hit Points** 250
- **Damage Threshold** 15
- **Speed** fly 40 ft. (fly 4½ mph ^[108.0 miles per day])
- **Cargo** 10 tons tons
- **Crew** 5 crew (plus the [treant](2-Mechanics/CLI/bestiary/plant/treant.md))
- **Keel/Beam** 80 ft. by 20 ft.
- **Cost** 25,000 gp

## Weapon: Ballista (Crew: 3)

- **Armor Class** 15
- **Hit Points** 50
- **Cost** 50 gp (ballista), 5 gp (bolt)

It takes 1 action to load the ballista, 1 action to aim it, and 1 action to fire it.

**Bolt** *Ranged Weapon Attack:* +6 to hit, range 120/480 ft., one target. *Hit:* `dice:3d10|noform|avg|text(16)` (`3d10`) piercing damage.
```
^statblock