---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/tob1-2023
- monster/cr/11
- monster/environment/any
- monster/environment/urban
- monster/size/large
- monster/type/construct
aliases: ["Eye Golem"]
---
# Eye Golem
*Source: Tome of Beasts 1 (2023 Edition) p. 216*  

*Eye-like sigils dot the smooth, marble skin of this statue. One of the eye sigils opens, and a beam of brilliant light shines out.*

## Covered in Arcana

Eye golems stand at least ten feet tall, and their magically durable hide is covered with real eyes as well as arcane sigils that resemble eyes.

## Blinds Victims

An eye golem rarely kills its victims, choosing to steal its victims' eyes instead. The victims are left blinded, wandering, and tormented, seeing only visions of the eye golem flashing through their memories. This drives some mad, while others instead choose to serve the golem, becoming devoted to the one who still holds sight.

## All Eyes Open

When killed, an eye golem does not simply fall down dead. All of its eyes open at once, and a blinding burst of light shines from the body. When the light stops, hundreds of perfectly preserved eyeballs remain where its body fell, still warm, fresh, and without scars or damage. Detectable only by those trained in the arcane arts, each eye emits a barely perceptible beam of light, connecting it to its owner. The creature that holds the golem's central eye after it is slain can use the eye to restore stolen eyes to their victims.

## Statblock

```ad-statblock
title: Eye Golem
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ToB1-2023/Eye%20Golem.webp#token)
*Large construct, Unaligned*

- **Armor Class** 20 (natural armor)
- **Hit Points** 157 (`15d10 + 75`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|22 (+6)| 9 (-1)|20 (+5)| 5 (-3)|11 (+0)| 1 (-5)|

- **Proficiency Bonus** +4
- **Saving Throws** ⏤
- **Skills** Perception +8
- **Senses** truesight 120 ft., passive Perception 18
- **Damage Immunities** poison; psychic; radiant; bludgeoning, piercing, slashing from nonmagical attacks that aren't adamantine
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened), [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed), [petrified](2-Mechanics/CLI/rules/conditions.md#Petrified), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** understands the languages of its creator but can't speak
- **Challenge** 11

## Traits

***Blinding Demise.*** When the golem reduces a creature to 0 hp, it can blind the creature permanently. If it does so, the creature is reduced to 1 hp instead.

***Construct Nature.*** The golem doesn't require air, food, drink, or sleep.

***Immutable Form.*** The golem is immune to any spell or effect that would alter its form.

***Light-Infused Fists.*** The golem's Slam attacks are magical. When the golem hits with a Slam attack, the attack deals an extra `dice:4d8|noform|avg` (`4d8`) radiant damage (included in the attack).

***Magic Resistance.*** The golem has advantage on saving throws against spells and other magical effects.

## Actions

***Multiattack.*** The eye golem can use its Primal Voice of Doom. It then makes two Slam attacks.

***Slam.*** *Melee Weapon Attack:* `dice:1d20+10|noform|text(+10)` to hit, reach 5 ft., one target. *Hit:* `dice:2d10+6|noform|avg|text(17)` (`2d10 + 6`) bludgeoning damage plus `dice:4d8|noform|avg|text(18)` (`4d8`) radiant damage.

***Gaze of Ancient Light (Recharge 5-6).*** The golem opens all of its eyes and emits a burst of blinding light. Each creature within 30 feet of it must make a DC 17 Dexterity saving throw. On a failure, a creature takes `dice:10d6|noform|avg|text(35)` (`10d6`) radiant damage and is [blinded](2-Mechanics/CLI/rules/conditions.md#Blinded) for 1 minute. On a success, a creature takes half the damage and isn't [blinded](2-Mechanics/CLI/rules/conditions.md#Blinded). A creature that fails the saving throw by 5 or more is also [stunned](2-Mechanics/CLI/rules/conditions.md#Stunned) until the end of its next turn. A [blinded](2-Mechanics/CLI/rules/conditions.md#Blinded) creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.

***Primal Voice of Doom.*** The golem intones a disturbing invocation of the sun god at one creature it can see within 30 feet of it. The target must succeed on a DC 17 Wisdom saving throw or be [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened) for 1 minute. The [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened) target can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.
```
^statblock

## Environment

any, urban