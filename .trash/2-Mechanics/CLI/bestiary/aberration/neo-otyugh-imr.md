---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/imr
- monster/cr/7
- monster/size/huge
- monster/type/aberration
aliases: ["Neo-Otyugh"]
---
# Neo-Otyugh
*Source: Infernal Machine Rebuild p. 75*  

A neo-otyugh is a stronger, more intelligent version of an otyugh—a grotesque aberration sporting three legs, snake-like tentacles, and a perpetually ravenous maw. Like an otyugh, a neo-otyugh buries itself under mounds of offal and carrion to ambush prey. Their improved intellect and innate spellcasting makes them especially effective against humanoid targets, as they use their powers of control to split off a straggler from a party, then attack.

```ad-statblock
title: Neo-Otyugh
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/IMR/Neo-Otyugh.webp#token)
*Huge aberration, Neutral*

- **Armor Class** 16 (natural armor)
- **Hit Points** 150 (`12d12 + 72`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|20 (+5)|11 (+0)|22 (+6)|12 (+1)|13 (+1)| 6 (-2)|

- **Proficiency Bonus** +3
- **Saving Throws** Constitution +9
- **Skills** ⏤
- **Senses** darkvision 120 ft., passive Perception 11
- **Condition Immunities** [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** Otyugh
- **Challenge** 7

## Traits

***Limited Telepathy.*** The otyugh can magically transmit simple messages and images to any creature within 120 feet of it that can understand a language. This form of telepathy doesn't allow the receiving creature to telepathically respond.

***Innate Spellcasting (Psionics).*** The neo-otyugh's innate spellcasting ability is Intelligence (spell save DC 12). It can innately cast the following spells, requiring no components:

**At will**: [detect thoughts](2-Mechanics/CLI/spells/detect-thoughts.md)

**1/day each**: [command](2-Mechanics/CLI/spells/command.md), [hold person](2-Mechanics/CLI/spells/hold-person.md)

## Actions

***Multiattack.*** The neo-otyugh makes three attacks: one with its bite and two with its tentacles.

***Bite.*** *Melee Weapon Attack:* `dice:1d20+8|noform|text(+8)` to hit, reach 10 ft., one target. *Hit:* `dice:2d10+5|noform|avg|text(16)` (`2d10 + 5`) piercing damage. If the target is a creature, it must succeed on a DC 17 Constitution saving throw against disease or become [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned) until the disease is cured. Every 24 hours that elapse, the target must repeat the saving throw, reducing its hit point maximum by `dice:1d10|noform|avg|text(5)` (`1d10`) on a failure. The disease is cured on a success. The target dies if the disease reduces its hit point maximum to 0. This reduction to the target's hit point maximum lasts until the disease is cured.

***Tentacle.*** *Melee Weapon Attack:* `dice:1d20+8|noform|text(+8)` to hit, reach 15 ft., one target. *Hit:* `dice:1d10+5|noform|avg|text(10)` (`1d10 + 5`) bludgeoning damage. If the target is Large or smaller, it is [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) (escape DC 16) and [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained) until the grapple ends. The neo-otyugh has two tentacles, each of which can grapple one target.

***Tentacle Slam.*** The neo-otyugh slams creatures [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) by it into each other or a solid surface. Each creature must succeed on a DC 16 Constitution saving throw or take `dice:3d6+5|noform|avg|text(15)` (`3d6 + 5`) bludgeoning damage and be [stunned](2-Mechanics/CLI/rules/conditions.md#Stunned) until the end of the neo-otyugh's next turn. On a successful save, the target takes half the bludgeoning damage and isn't [stunned](2-Mechanics/CLI/rules/conditions.md#Stunned).
```
^statblock