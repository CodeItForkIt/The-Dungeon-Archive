---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/tofw
- monster/cr/22
- monster/size/gargantuan
- monster/type/fiend
aliases: ["Modron Planar Incarnate"]
---
# Modron Planar Incarnate
*Source: Turn of Fortune's Wheel p. 92*  

```ad-statblock
title: Modron Planar Incarnate
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ToFW/Modron%20Planar%20Incarnate.webp#token)
*Gargantuan fiend, Any alignment*

- **Armor Class** 20 (natural armor)
- **Hit Points** 333 (`18d20 + 144`)
- **Speed** 40 ft., fly 40 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|27 (+8)|10 (+0)|26 (+8)|15 (+2)|20 (+5)|20 (+5)|

- **Proficiency Bonus** +7
- **Saving Throws** ⏤
- **Skills** Perception +12
- **Senses** truesight 120 ft., passive Perception 22
- **Damage Immunities** necrotic; poison; radiant; bludgeoning, piercing, slashing from nonmagical attacks
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened), [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled), [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed), [petrified](2-Mechanics/CLI/rules/conditions.md#Petrified), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned), [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained), [stunned](2-Mechanics/CLI/rules/conditions.md#Stunned), [unconscious](2-Mechanics/CLI/rules/conditions.md#Unconscious)
- **Languages** all
- **Challenge** 22

## Traits

***Legendary Resistance (3/Day).*** If the incarnate fails a saving throw, it can choose to succeed instead.

***Magic Resistance.*** The incarnate has advantage on saving throws against spells and other magical effects.

***Siege Monster.*** The incarnate deals double damage to objects and structures.

## Actions

***Multiattack.*** The incarnate makes two Slam or Energy Bolt attacks.

***Slam.*** *Melee Weapon Attack:* `dice:1d20+15|noform|text(+15)` to hit, reach 15 ft., one target. *Hit:* `dice:3d12+8|noform|avg|text(27)` (`3d12 + 8`) force damage.

***Energy Bolt.*** *Ranged Spell Attack:* `dice:1d20+12|noform|text(+12)` to hit, range 120 ft., one target. *Hit:* `dice:5d12|noform|avg|text(32)` (`5d12`) necrotic damage.

***Planar Exhalation (Recharge 5-6).*** The incarnate exhales concentrated energy native to its plane in a 60-foot cone. Each creature in that area must make a DC 23 Constitution saving throw. On a failed save, a creature takes `dice:8d12|noform|avg|text(52)` (`8d12`) necrotic damage, and the creature has the [blinded](2-Mechanics/CLI/rules/conditions.md#Blinded) condition until the end of the incarnate's next turn. On a successful save, a creature takes half as much damage only.

## Reactions

The incarnate can take up to three reactions per round but only one per turn.

***Searing Gaze.*** In response to being hit by an attack roll, the incarnate turns its magical gaze toward one creature it can see within 120 feet of itself and commands it to combust. The target must succeed on a DC 20 Wisdom saving throw or take `dice:3d10|noform|avg|text(16)` (`3d10`) fire damage.

***Teleport.*** Immediately after a creature the incarnate sees ends its turn, the incarnate teleports up to 60 feet to an unoccupied space it can see.
```
^statblock