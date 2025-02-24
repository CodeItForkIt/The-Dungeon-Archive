---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/mpmm
- monster/cr/23
- monster/environment/arctic
- monster/environment/coastal
- monster/environment/grassland
- monster/environment/hill
- monster/environment/mountain
- monster/size/gargantuan
- monster/type/elemental
aliases: ["Elder Tempest"]
---
# Elder Tempest
*Source: Mordenkainen Presents: Monsters of the Multiverse p. 121, Mordenkainen's Tome of Foes p. 200*  

Terrifying storms manifest in the bodies of elder tempests. Beings carved from clouds, wind, rain, and lightning, elder tempests assume the shape of serpents that slither through the sky. They drown the land beneath them with rain and stab the earth with lances of lightning. Punishing winds scream around them as they fly, feeding the chaos they create.

```ad-statblock
title: Elder Tempest
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/MPMM/Elder%20Tempest.webp#token)
*Gargantuan elemental, Typically  Neutral*

- **Armor Class** 19
- **Hit Points** 264 (`16d20 + 96`)
- **Speed** 0 ft., fly 120 ft. (hover)

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|23 (+6)|28 (+9)|23 (+6)| 2 (-4)|21 (+5)|18 (+4)|

- **Proficiency Bonus** +7
- **Saving Throws** Wisdom +12, Charisma +11
- **Skills** ⏤
- **Senses** darkvision 60 ft., passive Perception 15
- **Damage Resistances** bludgeoning, piercing, slashing from nonmagical attacks
- **Damage Immunities** lightning, poison, thunder
- **Condition Immunities** [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled), [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed), [petrified](2-Mechanics/CLI/rules/conditions.md#Petrified), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned), [prone](2-Mechanics/CLI/rules/conditions.md#Prone), [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained), [stunned](2-Mechanics/CLI/rules/conditions.md#Stunned)
- **Languages** —
- **Challenge** 23

## Traits

***Air Form.*** The tempest can enter a hostile creature's space and stop there. It can move through a space as narrow as 1 inch wide without squeezing.

***Flyby.*** The tempest doesn't provoke opportunity attacks when it flies out of an enemy's reach.

***Legendary Resistance (3/Day).*** If the tempest fails a saving throw, it can choose to succeed instead.

***Living Storm.*** The tempest is always at the center of a storm `dice:1d6+4|noform|avg` (`1d6 + 4`) miles in diameter. Heavy precipitation in the form of either rain or snow falls there, causing the area to be lightly obscured. Heavy rain also extinguishes open flames and imposes disadvantage on Wisdom ([Perception](2-Mechanics/CLI/rules/skills.md#Perception)) checks that rely on hearing. In addition, strong winds swirl in the area covered by the storm. The winds impose disadvantage on ranged attack rolls. They also extinguish open flames and disperse fog.

***Siege Monster.*** The tempest deals double damage to objects and structures.

## Actions

***Multiattack.*** The tempest makes two Thunderous Slam attacks.

***Thunderous Slam.*** *Melee Weapon Attack:* `dice:1d20+16|noform|text(+16)` to hit, reach 20 ft., one target. *Hit:* `dice:4d6+9|noform|avg|text(23)` (`4d6 + 9`) thunder damage.

***Lightning Storm (Recharge 6).*** Each creature within 120 feet of the tempest must make a DC 21 Dexterity saving throw, taking `dice:6d8|noform|avg|text(27)` (`6d8`) lightning damage on a failed save, or half as much damage on a successful one. If a target's saving throw fails by 5 or more, the creature is also [stunned](2-Mechanics/CLI/rules/conditions.md#Stunned) until the end of its next turn.

## Legendary Actions

***Move.*** The tempest moves up to its speed.

***Lightning Strike (Costs 2 Actions).*** The tempest can cause a bolt of lightning to strike a point on the ground anywhere under its storm. Each creature within 5 feet of that point must make a DC 21 Dexterity saving throw, taking `dice:3d10|noform|avg|text(16)` (`3d10`) lightning damage on a failed save, or half as much damage on a successful one.

***Screaming Gale (Costs 3 Actions).*** The tempest releases a blast of thunder and wind in a line that is 300 feet long and 20 feet wide. Objects in that area take `dice:4d10|noform|avg|text(22)` (`4d10`) thunder damage. Each creature there must succeed on a DC 21 Dexterity saving throw or take `dice:4d10|noform|avg|text(22)` (`4d10`) thunder damage and be flung up to 60 feet in a direction away from the line. If a thrown target collides with an immovable object (such as a wall or floor) or another creature, the target takes `dice:1d6|noform|avg|text(3)` (`1d6`) bludgeoning damage for every 10 feet it was thrown before impact. If the target collides with another creature, that other creature must succeed on a DC 19 Dexterity saving throw or take the same impact damage and be knocked [prone](2-Mechanics/CLI/rules/conditions.md#Prone).
```
^statblock

## Environment

arctic, coastal, grassland, hill, mountain