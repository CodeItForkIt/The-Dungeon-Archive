---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/tob1-2023
- monster/cr/4
- monster/environment/farmland
- monster/environment/forest
- monster/size/small
- monster/type/ooze
aliases: ["Sap Demon"]
---
# Sap Demon
*Source: Tome of Beasts 1 (2023 Edition) p. 315*  

*The axe mark in the tree oozes with viscous sap that forms into a small, vaguely humanoid shape at the tree's roots. It half walks and half flows forward.*

## Tree Oozes

Despite the name, sap demons aren't true demons. They are sentient oozes that form when an enchanted tree is cut or injured. A few hours after the injury, they pool into a shape that vaguely resembles their tree's attacker; if the tree cutter had a beard, the sap demon's human-like head drips in the vague shape of a beard. After dispatching the tree's attacker, most sap demons return to the tree, though some remain curious or malevolent enough to continue exploring the world.

## Reckless Possessors

A sap demon earns its name from its ability to possess another creature by oozing down its throat. Once inside, the sap demon makes the host bleed as the tree bled and is reckless with the body. However, no matter how the body is bandaged or cured, the host perpetually bleeds.

## Statblock

```ad-statblock
title: Sap Demon
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ToB1-2023/Sap%20Demon.webp#token)
*Small ooze, Chaotic Evil*

- **Armor Class** 13 (natural armor)
- **Hit Points** 81 (`18d6 + 18`)
- **Speed** 20 ft., climb 20 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|14 (+2)| 6 (-2)|12 (+1)| 7 (-2)|14 (+2)| 7 (-2)|

- **Proficiency Bonus** +2
- **Saving Throws** ⏤
- **Skills** ⏤
- **Senses** blindsight 90 ft. (blind beyond this radius), passive Perception 12
- **Damage Resistances** bludgeoning
- **Damage Immunities** acid
- **Condition Immunities** [blinded](2-Mechanics/CLI/rules/conditions.md#Blinded), [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [deafened](2-Mechanics/CLI/rules/conditions.md#Deafened), [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened), [prone](2-Mechanics/CLI/rules/conditions.md#Prone)
- **Languages** —
- **Challenge** 4

## Traits

***Amorphous.*** The sap demon can move through a space as narrow as 1 inch wide without squeezing.

***Ooze Nature.*** The sap demon doesn't require sleep.

***Season's Change.*** If the sap demon takes fire damage, its speed is increased by 10 feet until the end of its next turn. If it takes cold damage, its speed is reduced by 10 feet until the end of its next turn.

## Actions

***Multiattack.*** The sap demon makes two Slam or Lob Sap attacks. If both Slam attacks hit a Medium or smaller creature, the creature is [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) (escape DC 12).

***Slam.*** *Melee Weapon Attack:* `dice:1d20+4|noform|text(+4)` to hit, reach 5 ft., one target. *Hit:* `dice:2d4+2|noform|avg|text(7)` (`2d4 + 2`) bludgeoning damage plus `dice:2d6|noform|avg|text(7)` (`2d6`) acid damage.

***Lob Sap.*** *Ranged Weapon Attack:* `dice:1d20+4|noform|text(+4)` to hit, range 20/60 ft., one target. *Hit:* `dice:3d6+2|noform|avg|text(12)` (`3d6 + 2`) bludgeoning damage, and the target's speed is reduced by 10 feet until the end of its next turn.

***Soul Sap (Recharge 6).*** One humanoid the sap demon is grappling or that is [incapacitated](2-Mechanics/CLI/rules/conditions.md#Incapacitated) within 5 feet of the sap demon must succeed on a DC 12 Constitution saving throw or be possessed by the sap demon. The sap demon then disappears, and the target is [incapacitated](2-Mechanics/CLI/rules/conditions.md#Incapacitated) and loses control of its body. The sap demon now controls the body but doesn't deprive the target of awareness. The ooze can't be targeted by any attack, spell, or other effect, except ones that restore a creature's hp maximum. The ooze retains its Intelligence, Wisdom, and Charisma and condition immunities. It otherwise uses the possessed target's statistics, but doesn't gain access to the target's knowledge, class features, or proficiencies.

While possessed, the target's body seeps blood out of its ears, nose, and eyes, and the target takes `dice:1d4|noform|avg|text(2)` (`1d4`) acid damage at the end of each hour. Its hp maximum is also reduced by that amount. This reduction lasts until the target finishes a long rest after the possession ends. The possession lasts until the body drops to 0 hp, the ooze ends it as a bonus action, or the ooze is forced out by an effect like the [greater restoration](2-Mechanics/CLI/spells/greater-restoration.md) spell. When the possession ends, the ooze reappears in an unoccupied space within 5 feet of the body. The target is immune to this sap demon's Soul Sap for 24 hours after succeeding on the saving throw or after the possession ends.
```
^statblock

## Environment

farmland, forest