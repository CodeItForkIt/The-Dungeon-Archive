---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/psk
- monster/cr/4
- monster/size/huge
- monster/type/construct
aliases: ["Lifecraft Elephant"]
---
# Lifecraft Elephant
*Source: Plane Shift: Kaladesh p. 33*  

Many inventors—particularly elves, but members of the other races as well—view nature as the greatest artificer and strive to imitate it as closely as possible. The Greenwheel Lifecrafters are an inventor society dedicated to this kind of work, and they are responsible for coining the term "lifecrafting" to describe it. Lifecraft creatures are automatons that mimic the forms of natural animals in intricate detail. More than merely artistic endeavors, these creatures often serve practical purposes, just as domesticated animals would. A lifecraft elephant hauling a cart or carrying passengers through the streets of Ghirapur is just as effective in that work as a natural elephant, but it can't be spooked and it leaves no messy waste in its path.

The work of elf lifecrafters is particularly notable. Like most elf inventions, it incorporates living wood and foliage into its design, creating striking hybrids of plant life and animal form united as a perfect aesthetic whole.

Inventors can create lifecraft versions of virtually any creature. A lifecraft creature's type changes to construct, and it gains immunity to poison damage and to the [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed) and [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned) conditions. Its other statistics are typically unchanged.

```ad-statblock
title: Lifecraft Elephant
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/PSK/Lifecraft%20Elephant.webp#token)
*Huge construct, Unaligned*

- **Armor Class** 12 (natural armor)
- **Hit Points** 76 (`8d12 + 24`)
- **Speed** 40 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|22 (+6)| 9 (-1)|17 (+3)| 3 (-4)|11 (+0)| 6 (-2)|

- **Proficiency Bonus** +2
- **Saving Throws** ⏤
- **Skills** ⏤
- **Senses** passive Perception 10
- **Damage Immunities** poison
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** —
- **Challenge** 4

## Traits

***Trampling Charge.*** If the elephant moves at least 20 feet straight toward a creature and then hits it with a gore attack on the same turn, that target must succeed on a DC 12 Strength saving throw or be knocked [prone](2-Mechanics/CLI/rules/conditions.md#Prone). If the target is [prone](2-Mechanics/CLI/rules/conditions.md#Prone), the elephant can make one stomp attack against it as a bonus action.

## Actions

***Gore.*** *Melee Weapon Attack:* `dice:1d20+8|noform|text(+8)` to hit, reach 5 ft., one target. *Hit:* `dice:3d8+6|noform|avg|text(19)` (`3d8 + 6`) piercing damage.

***Stomp.*** *Melee Weapon Attack:* `dice:1d20+8|noform|text(+8)` to hit, reach 5 ft., one [prone](2-Mechanics/CLI/rules/conditions.md#Prone) creature. *Hit:* `dice:3d10+6|noform|avg|text(22)` (`3d10 + 6`) bludgeoning damage.
```
^statblock