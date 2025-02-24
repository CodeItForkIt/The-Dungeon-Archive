---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/qftis
- monster/cr/6
- monster/size/medium
- monster/type/construct
aliases: ["Combat Robot"]
---
# Combat Robot
*Source: Quests from the Infinite Staircase p. 214*  

Combat robots are designed for security or military action. They make able sentries and are usually programmed to take intruders prisoner before resorting to lethal force. Combat robots signal their pursuit with built-in sirens and flashing lights, warning nearby creatures of their imminent arrival with an intimidating display. Combat robots display a wide range of voices. Some units are clearly designed to intimidate, while others offer canned, upbeat platitudes in pleasant tones even while subduing opponents.

## Robots

Robots are Constructs created for heavy labor, menial tasks, or routine security. Despite robots' hardy construction, their circuitry is prone to overload if exposed to strong electrical currents. A robot has a pair of small appendages for fine motor control and object manipulation, as well as two larger appendages specialized for its role. Robots are programmed with intelligence, understanding, and usually loyalty to their creators. Despite that, long-operating robots sometimes develop their own personalities and ideas. Robots that endure long stretches of isolation, mistreatment, or neglect are prone to malfunctions. Some robots become despondent or cruel, while others obsessively repeat their last directive or adopt new, peculiar purposes of their own.

## Statblock

```ad-statblock
title: Combat Robot
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/QftIS/Combat%20Robot.webp#token)
*Medium construct, typically  Lawful Neutral*

- **Armor Class** 15 (natural armor)
- **Hit Points** 112 (`15d8 + 45`)
- **Speed** 40 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|20 (+5)|14 (+2)|17 (+3)|10 (+0)|15 (+2)|10 (+0)|

- **Proficiency Bonus** +3
- **Saving Throws** Constitution +6, Charisma +3
- **Skills** Athletics +8, Intimidation +6, Perception +5
- **Senses** darkvision 120 ft., passive Perception 15
- **Damage Resistances** acid, fire
- **Damage Immunities** cold, poison
- **Condition Immunities** [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** Common plus the languages spoken by its creator
- **Challenge** 6

## Traits

***Lightning Overload.*** When the robot takes lightning damage, it must succeed on a DC 10 Constitution saving throw or have the [stunned](2-Mechanics/CLI/rules/conditions.md#Stunned) condition until the start of its next turn.

## Actions

***Multiattack.*** The robot makes two Tentacle attacks or three Laser Beam attacks.

***Tentacle.*** *Melee Weapon Attack:* `dice:1d20+8|noform|text(+8)` to hit, reach 10 ft., one target. *Hit:* `dice:1d10+5|noform|avg|text(10)` (`1d10 + 5`) bludgeoning damage. If the target is a Medium or smaller creature, it has the [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) condition (escape DC 16). While [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled), the target also has the [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained) condition. The robot has two tentacles, each of which can grapple one target.

***Laser Beam.*** *Ranged Weapon Attack:* `dice:1d20+5|noform|text(+5)` to hit, range 120 ft., one target. *Hit:* `dice:4d6+2|noform|avg|text(16)` (`4d6 + 2`) radiant damage.

***Grenade Launcher (Recharge 5-6).*** The robot fires a grenade at a point it can see within 120 feet of itself. The grenade explodes in a 20-foot-radius sphere centered on that point, creating one of the following effects (robot's choice):

***Concussion Grenade.*** Each creature in the sphere must make a DC 15 Dexterity saving throw, taking `dice:6d6|noform|avg|text(21)` (`6d6`) force damage on a failed save or half as much damage on a successful one.

***Sleep Grenade.*** Each creature in the sphere must succeed on a DC 15 Constitution saving throw or have the [unconscious](2-Mechanics/CLI/rules/conditions.md#Unconscious) condition for 1 hour. The condition ends on a creature early if the creature takes damage or if another creature uses an action to shake it awake.

## Bonus Actions

***Emergency Speed (2/Day).*** The robot takes the Dash or Disengage action.
```
^statblock