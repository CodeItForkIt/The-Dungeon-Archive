---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/psk
- monster/cr/7
- monster/size/huge
- monster/type/giant
aliases: ["Giant"]
---
# Giant
*Source: Plane Shift: Kaladesh p. 30*  

Standing twenty to thirty feet tall, giants are towering bipedal creatures that follow the flow of aether on regular migratory routes. Once they start moving, they build both momentum and a single-mindedness that makes them nearly impossible to stop. Anything in their path, whether it's a building or a force of soldiers, is crushed without thought.

Giants eat whatever they happen across in the course of their migrations, which includes many other creatures drawn to the aether flow. They are beings of pure aggressive instinct, but without a hint of malice. In all likelihood, giants aren't intelligent enough to wish harm on anyone or anything. Still, the combination of their regular migrations and their sheer destructive power makes these creatures a menace.

Any structure built along one of their migratory paths is sure to be destroyed unless special accommodations are made. The zone of Giant's Walk in Ghirapur was designed by the city's engineers and edificers to include such accommodations, including rotating platforms, shifting bridges, and adjustable canal locks that provide the giants a clear and easy pathway during their biannual migration through the city.

The [stone giant](2-Mechanics/CLI/bestiary/giant/stone-giant.md) statistics in the Monster Manual work well for the giants of Kaladesh.

```ad-statblock
title: Giant
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/PSK/Giant.webp#token)
*Huge giant, Neutral*

- **Armor Class** 17 (natural armor)
- **Hit Points** 126 (`11d12 + 55`)
- **Speed** 40 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|23 (+6)|15 (+2)|20 (+5)|10 (+0)|12 (+1)| 9 (-1)|

- **Proficiency Bonus** +3
- **Saving Throws** Dexterity +5, Constitution +8, Wisdom +4
- **Skills** Athletics +12, Perception +4
- **Senses** darkvision 60 ft., passive Perception 14
- **Languages** Giant
- **Challenge** 7

## Traits

***Stone Camouflage.*** The giant has advantage on Dexterity ([Stealth](2-Mechanics/CLI/rules/skills.md#Stealth)) checks made to hide in rocky terrain.

## Actions

***Multiattack.*** The giant makes two greatclub attacks.

***Greatclub.*** *Melee Weapon Attack:* `dice:1d20+9|noform|text(+9)` to hit, reach 15 ft., one target. *Hit:* `dice:3d8+6|noform|avg|text(19)` (`3d8 + 6`) bludgeoning damage.

***Rock.*** *Ranged Weapon Attack:* `dice:1d20+9|noform|text(+9)` to hit, range 60/240 ft., one target. *Hit:* `dice:4d10+6|noform|avg|text(28)` (`4d10 + 6`) bludgeoning damage. If the target is a creature, it must succeed on a DC 17 Strength saving throw or be knocked [prone](2-Mechanics/CLI/rules/conditions.md#Prone).

## Reactions

***Rock Catching.*** If a rock or similar object is hurled at the giant, the giant can, with a successful DC 10 Dexterity saving throw, catch the missile and take no bludgeoning damage from it.
```
^statblock