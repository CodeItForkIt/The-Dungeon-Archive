---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/mcv3mc
- monster/cr/5
- monster/size/medium
- monster/type/elemental
aliases: ["Blaze"]
---
# Blaze
*Source: Monstrous Compendium Volume 3: Minecraft Creatures p. 3, Lightning Keep*  

Blazes are elemental beings that congregate at Nether fortresses. They float a short distance above the ground, and each one is orbited by three sets of glowing rods. When a blaze is destroyed, it sometimes leaves one of these rods behind. Blaze rods are a source of great energy that, when carefully crushed into powder, can be used to brew potions and craft other magic items.

A blaze attacks by launching three fireballs from its fiery core. This fire ignites creatures and flammable objects. If necessary, a blaze levitates into the air to better see and more easily target its enemies.

```ad-statblock
title: Blaze
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/MCV3MC/Blaze.webp#token)
*Medium elemental, typically  Neutral Evil*

- **Armor Class** 13
- **Hit Points** 75 (`10d8 + 30`)
- **Speed** 20 ft., fly 20 ft. (vertical movement only; hover)

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|16 (+3)|17 (+3)|16 (+3)| 6 (-2)|10 (+0)| 7 (-2)|

- **Proficiency Bonus** +3
- **Saving Throws** ⏤
- **Skills** ⏤
- **Senses** darkvision 60 ft., passive Perception 10
- **Damage Resistances** bludgeoning, piercing, slashing from nonmagical attacks
- **Damage Immunities** fire
- **Condition Immunities** [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled), [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed), [petrified](2-Mechanics/CLI/rules/conditions.md#Petrified), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned), [prone](2-Mechanics/CLI/rules/conditions.md#Prone), [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained)
- **Languages** —
- **Challenge** 5

## Traits

***Blaze Rod.*** When the blaze drops to 0 hit points, it disappears in a cloud of smoke and has a 50 percent chance of leaving behind a glowing rod worth 100 gp. The rod sheds dim light in a 5-foot radius. As an action, a creature can try to snap the rod, doing so with a successful DC 14 Strength check. The snapped rod releases its fiery energy in a 5-foot-radius sphere centered on itself. Each creature in that area must make a DC 14 Dexterity saving throw, taking `dice:1d12|noform|avg|text(6)` (`1d12`) fire damage on a failed save, or half as much damage on a successful one.

***Heat Aura.*** Any creature that starts its turn within 5 feet of the blaze takes `dice:1d6|noform|avg|text(3)` (`1d6`) fire damage.

***Illumination.*** The blaze sheds bright light in a 20-foot radius and dim light for an additional 20 feet.

***Water Susceptibility.*** The blaze takes 1 cold damage for every 5 feet it moves in water, for every gallon of water splashed on it, or whenever it starts its turn in the rain.

## Actions

***Multiattack.*** The blaze makes three Fiery Doom attacks.

***Fiery Doom.*** *Melee or Ranged Spell Attack:* `dice:1d20+6|noform|text(+6)` to hit; reach 5 ft. or ranged 60 ft., one target. *Hit:* `dice:1d10+3|noform|avg|text(8)` (`1d10 + 3`) fire damage, and the target catches fire if it's a creature or a flammable object. Until a creature takes an action to extinguish the fire, the burning target takes `dice:1d6|noform|avg|text(3)` (`1d6`) fire damage at the end of each of its turns.
```
^statblock