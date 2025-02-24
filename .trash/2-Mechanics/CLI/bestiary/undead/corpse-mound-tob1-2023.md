---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/tob1-2023
- monster/cr/11
- monster/environment/urban
- monster/size/huge
- monster/type/undead
aliases: ["Corpse Mound"]
---
# Corpse Mound
*Source: Tome of Beasts 1 (2023 Edition) p. 67*  

*The reeking pile of bodies and bones, as large as a giant, lurches forward. Corpses that tumble off it rise moments later as undead and follow the determined hill of corruption.*

## Rise from Mass Graves

In times of plague and war, hundreds of bodies are dumped into mass graves. Without sanctifying rites, necromantic magic can seep into the mound of bodies and animate them as a massive horror hungering for others to join its form.

## Absorb Bodies

A corpse mound is driven by the anger and loneliness of the dead within it to kill and absorb the bodies of its victims. It attacks any living creature larger than a dog, but it is drawn to humans and humanoids. It never tires, no matter how many victims it accumulates. Entire towns have been wiped out by advancing corpse mounds.

## Statblock

```ad-statblock
title: Corpse Mound
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ToB1-2023/Corpse%20Mound.webp#token)
*Huge undead, Neutral Evil*

- **Armor Class** 16 (natural armor)
- **Hit Points** 207 (`18d12 + 90`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|24 (+7)|11 (+0)|21 (+5)| 6 (-2)|10 (+0)| 8 (-1)|

- **Proficiency Bonus** +4
- **Saving Throws** Constitution +9, Intelligence +2, Wisdom +4
- **Skills** ⏤
- **Senses** darkvision 60 ft., passive Perception 10
- **Damage Resistances** necrotic
- **Damage Immunities** poison
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** understands Common but can't speak
- **Challenge** 11

## Traits

***Absorb the Dead.*** Whenever a Large or smaller creature that isn't a Construct or Undead dies within 10 feet of the corpse mound, that creature's remains join with the mound, and the mound regains hp equal to twice the CR or level of the absorbed creature. The absorbed creature can't be returned to life by any spell or effect that requires a body, unless the body is retrieved from the corpse mound.

***Noxious Aura.*** At the end of each of the corpse mound's turns, each creature within 20 feet of it must succeed on a DC 17 Constitution saving throw or become [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned) until the end of its next turn. On a successful saving throw, the creature is immune to the mound's Noxious Aura for 24 hours.

***Undead Nature.*** The corpse mound doesn't require air, food, drink, or sleep.

***Zombie Drop.*** At the start of each of the corpse mound's turns, it can choose to have one corpse fall from it and immediately rise as a zombie under its control. The mound can have no more than ten zombies under its control at one time. Zombies take their turns immediately after the corpse mound's turn.

## Actions

***Multiattack.*** The corpse mound makes two Slam or Bone Shard attacks. If both Slam attacks hit a Large or smaller target, the corpse mound can immediately use Envelop on it.

***Slam.*** *Melee Weapon Attack:* `dice:1d20+11|noform|text(+11)` to hit, reach 5 ft., one target. *Hit:* `dice:2d10+7|noform|avg|text(18)` (`2d10 + 7`) bludgeoning damage plus `dice:3d6|noform|avg|text(10)` (`3d6`) necrotic damage, and the target is [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) (escape DC 17). Until this grapple ends, the target is [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained).

***Bone Shard.*** *Ranged Weapon Attack:* `dice:1d20+11|noform|text(+11)` to hit, range 30/120 ft., one target. *Hit:* `dice:2d6+7|noform|avg|text(14)` (`2d6 + 7`) piercing damage plus `dice:3d6|noform|avg|text(10)` (`3d6`) necrotic damage, and the target must succeed on a DC 17 Strength saving throw or be knocked [prone](2-Mechanics/CLI/rules/conditions.md#Prone) and [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained) as it is pinned to the ground by the shard. A creature, including the [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained) target, can take its action to free the target by succeeding on a DC 17 Strength check.

***Envelop.*** The corpse mound envelops a Large or smaller creature within 5 feet of it that is [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained) by its Bone Shard or a Large or smaller creature [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) by it. The enveloped target is [blinded](2-Mechanics/CLI/rules/conditions.md#Blinded), [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained), and unable to breathe, and it must succeed on a DC 17 Strength saving throw at the start of each of the mound's turns or take `dice:2d10+7|noform|avg|text(18)` (`2d10 + 7`) bludgeoning damage. If the mound moves, the enveloped target moves with it. The mound can have no more than four creatures enveloped at a time.

A creature within 5 feet of the mound, including the enveloped creature, can free the enveloped creature by succeeding on a DC 17 Strength check. Any creature that makes such an attempt takes `dice:3d6|noform|avg|text(10)` (`3d6`) necrotic damage.
```
^statblock

## Environment

urban