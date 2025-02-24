---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/tob1-2023
- monster/cr/4
- monster/environment/arctic
- monster/size/medium
- monster/type/plant
aliases: ["Frostveil"]
---
# Frostveil
*Source: Tome of Beasts 1 (2023 Edition) p. 193*  

*"They took the sled dogs first, and later the seal-skinner set to guard them. We'd hear a confused, muffled cry in the wind and then we'd find them—a raven harvest, cold and stiff on the ice. Next time, we hid ourselves and watched, and we saw them floating through the air like kites. A wisp of blowing snow that never dispersed, a billowing, snowflake sail moving with sinister purpose. The 'cloak of death' our guide called it."*

Whipped through the air by snowstorms and resembling a spider's web dangling with delicate ice crystals, these silently gliding, beautiful killers are semi-sentient plants adapted to the merciless cold of the north.

## Cloak of Death

Flat nodes shaped like large snowflakes connect the frostveil's netlike body and trailing tails of transparent fibers. Gossamer tendrils stream behind and between the flying snowflakes, ready to grab and entangle any warm-blooded creature the frostveil detects.

## Seek Warmth

Each starlike node contains crude sensory organs, able to detect warmth as meager as a living creature's breath and steer the gliding web toward it.

## Spirit Spores

Northern shamans say the dance of the frostveils is beautiful when lit by the northern lights and a powerful omen. With great care, shamans sometimes harvest frostveils for their frozen spore-shards, which grant potent visions of the spirit world when melted on the tongue.

## Statblock

```ad-statblock
title: Frostveil
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ToB1-2023/Frostveil.webp#token)
*Medium plant, Unaligned*

- **Armor Class** 16 (natural armor)
- **Hit Points** 67 (`9d8 + 27`)
- **Speed** 10 ft., fly 15 ft. (hover)

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|20 (+5)|20 (+5)|16 (+3)| 1 (-5)|11 (+0)| 1 (-5)|

- **Proficiency Bonus** +2
- **Saving Throws** ⏤
- **Skills** Stealth +7
- **Senses** blindsight 120 ft., passive Perception 10
- **Damage Vulnerabilities** fire
- **Damage Resistances** bludgeoning, piercing, slashing from nonmagical attacks
- **Damage Immunities** cold
- **Condition Immunities** [blinded](2-Mechanics/CLI/rules/conditions.md#Blinded), [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [deafened](2-Mechanics/CLI/rules/conditions.md#Deafened), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened), [prone](2-Mechanics/CLI/rules/conditions.md#Prone)
- **Languages** —
- **Challenge** 4

## Traits

***Chilling Acidic Body.*** A creature that touches the frostveil or hits it with a melee attack while within 5 feet of it takes `dice:1d8|noform|avg|text(4)` (`1d8`) acid damage.

***Damage Transfer.*** While engulfing a creature, the frostveil takes only half the damage dealt to it (rounded down), and the engulfed creature takes the other half.

***False Appearance.*** While the frostveil remains motionless, it is indistinguishable from a formation of frost and ice.

***Windborne.*** In windy conditions, the frostveil's flying speed increases to 30 feet. In a wind of moderate or greater speed (at least 10 miles per hour), its flying speed increases to 60 feet.

## Actions

***Multiattack.*** The frostveil makes two Frozen Tendril attacks. If both attacks hit a Medium or smaller target, the target is [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) (escape DC 15), and the frostveil uses Snowy Engulf on it.

***Frozen Tendril.*** *Melee Weapon Attack:* `dice:1d20+7|noform|text(+7)` to hit, reach 10 ft., one target. *Hit:* `dice:1d8+5|noform|avg|text(9)` (`1d8 + 5`) bludgeoning damage plus `dice:1d6|noform|avg|text(3)` (`1d6`) cold damage.

***Snowy Engulf.*** The frostveil engulfs a Medium or smaller creature [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) by it. The engulfed target is [blinded](2-Mechanics/CLI/rules/conditions.md#Blinded) and [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained), and it must succeed on a DC 15 Constitution saving throw at the start of each of the frostveil's turns or take `dice:1d8|noform|avg|text(4)` (`1d8`) acid damage and `dice:1d6|noform|avg|text(3)` (`1d6`) cold damage. If the frostveil moves, the engulfed target moves with it. The frostveil can have only one creature engulfed at a time.

***Spirit Spores (Recharge 6).*** The frostveil releases a puff of psychotropic spores around itself. Each creature within 10 feet of the frostveil must make a DC 15 Constitution saving throw. On a failure, a creature takes `dice:6d6|noform|avg|text(21)` (`6d6`) cold damage and is [incapacitated](2-Mechanics/CLI/rules/conditions.md#Incapacitated) for 1 minute. On a success, a creature takes half the damage and isn't [incapacitated](2-Mechanics/CLI/rules/conditions.md#Incapacitated). When an [incapacitated](2-Mechanics/CLI/rules/conditions.md#Incapacitated) creature moves, it moves in a random direction. An [incapacitated](2-Mechanics/CLI/rules/conditions.md#Incapacitated) creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.
```
^statblock

## Environment

arctic