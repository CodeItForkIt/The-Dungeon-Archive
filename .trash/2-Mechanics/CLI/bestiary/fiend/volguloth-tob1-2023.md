---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/tob1-2023
- monster/cr/4
- monster/environment/any
- monster/environment/planar
- monster/size/medium
- monster/type/fiend
aliases: ["Volguloth"]
---
# Volguloth
*Source: Tome of Beasts 1 (2023 Edition) p. 391*  

*What at first appears to be a humanoid wearing voluminous robes is a thin, fiendish figure whose skin drapes about its form like a wet shroud.*

These minor fiends are often found in the service of more powerful fiends or, occasionally, powerful mortals. Volguloths are quiet, efficient killers and often act as assassins. They are sadistic and cruel, reveling in the deaths they cause, and are loathe to turn their stealthy skills to less violent tasks, such as theft or reconnaissance.

## Skin Shroud

A volguloth's skin behaves more like a sinuous sheet of muscle, contracting and expanding as the volguloth requires. Typically, it drapes the fiend's form like a robe. However, the volguloth can tighten it to a rumpled but close-fitting hide or extend it into long sheets. This allows it to glide short distances or enwrap and smother victims, engulfing them in the folds of its skin and squeezing them until they run out of air.

## Statblock

```ad-statblock
title: Volguloth
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ToB1-2023/Volguloth.webp#token)
*Medium fiend, Neutral Evil*

- **Armor Class** 14 (natural armor)
- **Hit Points** 78 (`12d8 + 24`)
- **Speed** 30 ft., climb 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|16 (+3)|15 (+2)|14 (+2)|12 (+1)|13 (+1)|11 (+0)|

- **Proficiency Bonus** +2
- **Saving Throws** ⏤
- **Skills** Perception +3, Stealth +6
- **Senses** blindsight 30 ft., darkvision 60 ft., passive Perception 13
- **Damage Resistances** cold; fire; lightning; bludgeoning, piercing, slashing from nonmagical attacks
- **Damage Immunities** acid, poison
- **Condition Immunities** [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** Abyssal, Infernal, telepathy 60 ft.
- **Challenge** 4

## Traits

***Glide.*** The volguloth has draping skin that it can expand while falling to slow its rate of descent to 60 feet per round, landing on its feet and taking no falling damage. It can move up to 5 feet horizontally for every 1 foot it falls. The volguloth can't gain height with its expanded skin alone. If subjected to a strong wind or lift of any kind, it can use the updraft to glide farther.

***Magic Resistance.*** The volguloth has advantage on saving throws against spells and other magical effects.

***Poisoned Weapons.*** The volguloth's weapons are coated with a magical poison. When the volguloth hits with any weapon, the weapon deals an extra `dice:2d6|noform|avg` (`2d6`) poison damage (included in the attack).

## Actions

***Multiattack.*** The volguloth makes two Claw attacks. If both Claw attacks hit a Medium or smaller target, the target is [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) (escape DC 13), and the volguloth uses its Enshroud on the target.

***Claw.*** *Melee Weapon Attack:* `dice:1d20+5|noform|text(+5)` to hit, reach 5 ft., one target. *Hit:* `dice:2d4+3|noform|avg|text(8)` (`2d4 + 3`) slashing damage plus `dice:2d6|noform|avg|text(7)` (`2d6`) poison damage.

***Enshroud.*** The volguloth enshrouds a Medium or smaller target [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) by it. The enshrouded target is [blinded](2-Mechanics/CLI/rules/conditions.md#Blinded), [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained), and unable to breathe or speak until the grapple ends. If the volguloth moves, the enshrouded target moves with it. The volguloth can have only one creature enshrouded at a time, and it can't use its Glide trait while enshrouding a creature.

## Bonus Actions

***Strangle.*** A creature enshrouded by the volguloth must succeed on a DC 13 Strength saving throw or take `dice:3d6|noform|avg|text(10)` (`3d6`) bludgeoning damage and begin suffocating, as the air is squeezed from its lungs.
```
^statblock

## Environment

any, planar