---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/tdcsr
- monster/cr/8
- monster/size/large
- monster/type/elemental
aliases: ["Cinderslag Elemental"]
---
# Cinderslag Elemental
*Source: Tal'Dorei Campaign Setting Reborn p. 231*  

Cinderslag elementals are pure manifestations of the hatred and furore of the deceased "Cinder King, Thordak". Even after his death, the fires of that great red dragon continue to ravage "Emon", as places scorched by his corrupting flames are transformed into vitriolic pits of slag and ash that spawn mindless creatures of elemental destruction. Though "Thordak's Crater" in "Emon" has mostly been healed by the Fire Ashari of Pyrah, the terrible fires still churning beneath the city give rise to [cinderslag elementals](2-Mechanics/CLI/bestiary/elemental/cinderslag-elemental-tdcsr.md), as do other areas where the "Cinder King's" elemental devastation has left an indelible mark, including the ruins of "Serpent's Head" in the "Cliffkeep Mountains" and the "Ashen Gorge" in the "Stormcrest Mountains".

## Gaze of Annihilation

A cinderslag elemental's Molten Gaze unleashes incredible power that can melt steel and stone with a glance. If one of these creatures is allowed to focus its gaze for long periods, or if several elementals work in unison, entire cities can easily be leveled in a tide of molten stone. Fortunately for the people of "Emon", "Thordak's" elemental spawn are mindless and incapable of unified action—as long as no one is able to bend these creatures to their will.

## Statblock

```ad-statblock
title: Cinderslag Elemental
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/TDCSR/Cinderslag%20Elemental.webp#token)
*Large elemental, Unaligned*

- **Armor Class** 15 (natural armor)
- **Hit Points** 102 (`12d10 + 36`)
- **Speed** 20 ft., burrow 40 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|15 (+2)|12 (+1)|17 (+3)| 1 (-5)|10 (+0)| 3 (-4)|

- **Proficiency Bonus** +3
- **Saving Throws** ⏤
- **Skills** ⏤
- **Senses** darkvision 60 ft., passive Perception 10
- **Damage Resistances** bludgeoning, piercing, slashing from non-magical attacks
- **Damage Immunities** fire, poison
- **Condition Immunities** [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled), [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed), [petrified](2-Mechanics/CLI/rules/conditions.md#Petrified), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned), [prone](2-Mechanics/CLI/rules/conditions.md#Prone), [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained), [unconscious](2-Mechanics/CLI/rules/conditions.md#Unconscious)
- **Languages** —
- **Challenge** 8

## Traits

***Searing Presence.*** Any creature that starts its turn within 5 feet of the elemental takes `dice:1d10|noform|avg|text(5)` (`1d10`) fire damage.

***Molten Form.*** The elemental can move through a space as narrow as 1 inch wide without squeezing. In addition, the elemental can enter a hostile creature's space and stop there. The first time it enters a creature's space on a turn, that creature takes `dice:1d10|noform|avg|text(5)` (`1d10`) fire damage and must succeed on a DC 14 Strength saving throw or be [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained). A creature that starts its turn [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained) in this way takes `dice:1d10|noform|avg|text(5)` (`1d10`) fire damage. It can repeat the saving throw at the end of each of its turns, freeing itself on a success.

***Water Susceptibility.*** For every 5 feet the elemental moves in water, or for every gallon of water splashed on it, it takes 1 cold damage.

## Actions

***Multiattack.*** The elemental makes two slam attacks.

***Slam.*** *Melee Weapon Attack:* `dice:1d20+5|noform|text(+5)` to hit, reach 5 ft., one target. *Hit:* `dice:3d6+2|noform|avg|text(12)` (`3d6 + 2`) bludgeoning damage plus `dice:1d10|noform|avg|text(5)` (`1d10`) fire damage. If the target is a creature or a flammable object, it ignites. Until a creature takes an action to douse the fire, the target takes `dice:1d10|noform|avg|text(5)` (`1d10`) fire damage at the start of each of its turns.

***Molten Gaze.*** *Ranged Spell Attack:* `dice:1d20+8|noform|text(+8)` to hit, range 30 ft., one target. *Hit:* `dice:6d6|noform|avg|text(21)` (`6d6`) fire damage, and the target must succeed on a DC 14 Constitution saving throw or have one nonmagical item of the elemental's choice that the target is carrying instantly melt or burn to cinders.
```
^statblock