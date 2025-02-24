---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/wdmm
- monster/cr/14
- monster/size/gargantuan
- monster/type/construct
aliases: ["Shockerstomper"]
---
# Shockerstomper
*Source: Waterdeep: Dungeon of the Mad Mage p. 174*  

```ad-statblock
title: Shockerstomper
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/WDMM/Shockerstomper.webp#token)
*Gargantuan construct, Unaligned*

- **Armor Class** 18
- **Hit Points** 300 (`300d1`)
- **Speed** 40 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|23 (+6)|10 (+0)|20 (+5)| 1 (-5)| 1 (-5)| 1 (-5)|

- **Proficiency Bonus** +5
- **Saving Throws** ⏤
- **Skills** ⏤
- **Senses** blindsight 60 ft. (blind beyond this radius), passive Perception 5
- **Damage Immunities** poison, psychic
- **Condition Immunities** [blinded](2-Mechanics/CLI/rules/conditions.md#Blinded), [deafened](2-Mechanics/CLI/rules/conditions.md#Deafened), [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened), [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** —
- **Challenge** 14

## Traits

***Disable.*** When a leg drops to 0 hit points, it is disabled, and Shockerstomper can use a reaction to detach it from its main body. Whenever one of its legs is disabled, Shockerstomper's walking speed is reduced by 10 feet. The whole contraption topples over and shuts down if four of its seven legs are disabled.

***Electrified Surface.*** A creature that ends its turn in contact with Shockerstomper's body (saucer or turrets) must make a DC 15 Constitution saving throw, taking `dice:4d10|noform|avg|text(22)` (`4d10`) lightning damage on a failed save, or half as much damage on a successful one.

***Immutable Form.*** Shockerstomper is immune to any spell or effect that would alter its form.

***Control Module.*** A creature atop or above Shockerstomper's platform can locate its control module with a successful DC 15 Intelligence ([Investigation](2-Mechanics/CLI/rules/skills.md#Investigation)) check or Wisdom ([Perception](2-Mechanics/CLI/rules/skills.md#Perception)) check. As an action, a character can try to open the control module's access panel, either by tearing it off with a successful DC 25 Strength ([Athletics](2-Mechanics/CLI/rules/skills.md#Athletics)) check or by dislodging it with thieves' tools and a successful DC 25 Dexterity check. Behind the panel, embedded in the floor of the control module, is a 5-foot-diameter pulsating crystal hemisphere with AC 10, 25 hit points, and immunity to poison and psychic damage. Destroying the crystal hemisphere shuts down Shockerstomper.

***Lightning Turret.*** A character can try to plug the nozzle of a lightning turret with a 10-pound rock or similar object, doing so with a successful DC 15 Strength ([Athletics](2-Mechanics/CLI/rules/skills.md#Athletics)) check. A plugged turret can't shoot lightning until a creature uses an action to try to clear the obstruction, which requires another successful DC 15 Strength ([Athletics](2-Mechanics/CLI/rules/skills.md#Athletics)) check. Shockerstomper has no ability to clear an obstruction itself.

## Actions

***Multiattack.*** Shockerstomper makes three Lightning Turret attacks and two Stomp attacks.

***Lightning Turret.*** The turret shoots a magical lightning bolt at one creature within 60 feet of Shockerstomper. The target must make a DC 15 Dexterity saving throw, taking `dice:8d10|noform|avg|text(44)` (`8d10`) lightning damage on a failed save, or half as much damage on a successful one.

***Stomp.*** *Melee Weapon Attack:* `dice:1d20+8|noform|text(+8)` to hit, reach 10 ft., one creature. *Hit:* `dice:3d10+6|noform|avg|text(22)` (`3d10 + 6`) bludgeoning damage.
```
^statblock