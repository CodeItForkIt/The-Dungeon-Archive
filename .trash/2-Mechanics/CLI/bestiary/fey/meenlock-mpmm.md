---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/mpmm
- monster/cr/2
- monster/environment/forest
- monster/environment/swamp
- monster/environment/urban
- monster/size/small
- monster/type/fey
aliases: ["Meenlock"]
---
# Meenlock
*Source: Mordenkainen Presents: Monsters of the Multiverse p. 178*  

Meenlocks are Fey that invoke terror and seek to destroy all that is good, innocent, and beautiful. These bipeds have the heads and claws of crustaceans, and they primarily live in forests, although they adapt well to urban and subterranean settings.

Meenlocks are spawned by fear. When terror overwhelms a creature in the Feywild or another location where the Feywild's influence is strong, one or more meenlocks might spontaneously arise in the shadows or darkness nearby. If more than one meenlock is born, a lair also magically forms. The earth creaks and moans as narrow, twisting tunnels open up within it. One of these passageways serves as the lair's only entrance, and a large central chamber serves as the meenlocks' den. Inside the warren, black moss covers every surface, muffling sound.

A meenlock can supernaturally sense areas of darkness and shadow in its vicinity and can teleport from one darkened space to another—enabling it to sneak up on its prey or run away when outmatched. Meenlocks also project a supernatural aura that instills terror in those nearby.

## Telepathic Torment

Up to four meenlocks can telepathically torment one [incapacitated](2-Mechanics/CLI/rules/conditions.md#Incapacitated) creature, filling its mind with disturbing sounds and dreadful imagery. Participating meenlocks can't use their telepathy for any other purpose during this time, though they can move about and take actions and reactions as normal. This torment has no effect on a creature that is immune to the [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened) condition. If the creature is susceptible and remains [incapacitated](2-Mechanics/CLI/rules/conditions.md#Incapacitated) for 1 hour, the creature must make a Wisdom saving throw, taking `dice:3d6|noform|avg|text(10)` (`3d6`) psychic damage on a failed save, or half as much damage on a successful one. The save DC is 10 + the number of meenlocks participating in the torment, considering only those that remain within sight of the victim for the entire hour and aren't [incapacitated](2-Mechanics/CLI/rules/conditions.md#Incapacitated) during it. The process can be repeated. A Humanoid that drops to 0 hit points as a result of this damage instantly transforms into a meenlock at full health and under the DM's control. Only a [wish](2-Mechanics/CLI/spells/wish.md) spell or divine intervention can restore a transformed creature to its former state.

## Statblock

```ad-statblock
title: Meenlock
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/MPMM/Meenlock.webp#token)
*Small fey, Typically  Neutral Evil*

- **Armor Class** 15 (natural armor)
- **Hit Points** 31 (`7d6 + 7`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
| 7 (-2)|15 (+2)|12 (+1)|11 (+0)|10 (+0)| 8 (-1)|

- **Proficiency Bonus** +2
- **Saving Throws** ⏤
- **Skills** Perception +4, Stealth +6, Survival +2
- **Senses** darkvision 120 ft., passive Perception 14
- **Condition Immunities** [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened)
- **Languages** telepathy 120 ft.
- **Challenge** 2

## Traits

***Fear Aura.*** Any Beast or Humanoid that starts its turn within 10 feet of the meenlock must succeed on a DC 11 Wisdom saving throw or be [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened) until the start of the creature's next turn.

***Light Sensitivity.*** While in bright light, the meenlock has disadvantage on attack rolls, as well as on Wisdom ([Perception](2-Mechanics/CLI/rules/skills.md#Perception)) checks that rely on sight.

## Actions

***Claw.*** *Melee Weapon Attack:* `dice:1d20+4|noform|text(+4)` to hit, reach 5 ft., one target. *Hit:* `dice:2d4+2|noform|avg|text(7)` (`2d4 + 2`) slashing damage, and the target must succeed on a DC 11 Constitution saving throw or be [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed) for 1 minute. The target can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.

## Bonus Actions

***Shadow Teleport (Recharge 5-6).*** The meenlock teleports to an unoccupied space within 30 feet of it, provided that both the space it's teleporting from and its destination are in dim light or darkness. The destination need not be within line of sight.
```
^statblock

## Environment

forest, swamp, urban