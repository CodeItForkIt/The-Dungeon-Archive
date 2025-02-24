---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/psi
- monster/cr/2
- monster/size/tiny
- monster/type/construct
aliases: ["Creepy Doll"]
---
# Creepy Doll
*Source: Plane Shift: Innistrad p. 25*  

Many of the evils that plague humanity on Innistrad arise from within humanity itself, and among the most terrible of these are creatures built by human hands. Some of these are animated by the magic of [necro-alchemists](2-Mechanics/CLI/bestiary/humanoid/necro-alchemist-psi.md) or witches, but others are inhabited and given life by hostile spirits or other malign forces. These include [gargoyles](2-Mechanics/CLI/bestiary/elemental/gargoyle.md) and [scarecrows](2-Mechanics/CLI/bestiary/construct/scarecrow.md), haunted dolls and suits of [animated armor](2-Mechanics/CLI/bestiary/construct/animated-armor.md), [stone golems](2-Mechanics/CLI/bestiary/construct/stone-golem.md) formed of gravestones and mausoleums, and [homunculi](2-Mechanics/CLI/bestiary/construct/homunculus.md) created by stitchers and [necro-alchemists](2-Mechanics/CLI/bestiary/humanoid/necro-alchemist-psi.md).

```ad-statblock
title: Creepy Doll
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/PSI/Creepy%20Doll.webp#token)
*Tiny construct, Lawful Evil*

- **Armor Class** 12
- **Hit Points** 21 (`6d4 + 6`)
- **Speed** 40 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
| 6 (-2)|14 (+2)|13 (+1)|12 (+1)|11 (+0)|10 (+0)|

- **Proficiency Bonus** +2
- **Saving Throws** ⏤
- **Skills** Stealth +4
- **Senses** darkvision 60 ft., passive Perception 10
- **Damage Resistances** bludgeoning, piercing, slashing from nonmagical attacks
- **Damage Immunities** poison
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened), [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed)
- **Languages** speaks and understands the languages known by its creator
- **Challenge** 2

## Traits

***False Appearance.*** While the creepy doll remains motionless, it is indistinguishable from an ordinary, inanimate doll.

## Actions

***Multiattack.*** The creepy doll makes one attack with its scissors and uses Psychic Assault.

***Scissors.*** *Melee Weapon Attack:* `dice:1d20+4|noform|text(+4)` to hit, reach 5 ft., one target. *Hit:* `dice:2d4+2|noform|avg|text(7)` (`2d4 + 2`) slashing damage.

***Psychic Assault.*** The creepy doll targets one creature it can see within 10 feet of it that has a brain. The target must succeed on a DC 12 Intelligence saving throw or take `dice:2d10|noform|avg|text(11)` (`2d10`) psychic damage. Also on a failure, roll `dice:3d6|noform|avg` (`3d6`). If the total equals or exceeds the target's Intelligence score, that score is reduced to 0. The target is [stunned](2-Mechanics/CLI/rules/conditions.md#Stunned) until it regains at least one point of Intelligence, as from the [greater restoration](2-Mechanics/CLI/spells/greater-restoration.md) spell or similar magic.

***Body Exchange.*** The creepy doll initiates an Intelligence contest with an [incapacitated](2-Mechanics/CLI/rules/conditions.md#Incapacitated) humanoid within 5 feet of it. If it wins the contest, the creepy doll's spirit inhabits the target's body while the target's spirit is placed into the creepy doll's body. The creepy doll controls the target's body completely. It retains its alignment, Intelligence, Wisdom, Charisma, and immunity to being [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed) and [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened). It otherwise uses the possessed target's statistics, but doesn't gain access to the target's knowledge, class features, or proficiencies. The target retains its alignment, Intelligence, Wisdom, and Charisma while inhabiting the creepy doll's body.

The body exchange lasts until the doll's spirit is forced out by magic. (The [dispel evil and good](2-Mechanics/CLI/spells/dispel-evil-and-good.md) spell will accomplish this, though the doll is not one of the creature types whose possession that spell normally ends.) The body and the doll must be within 5 feet of each other for such an effect to work. The target is immune to this doll's Body Exchange for 24 hours after winning the Intelligence contest or after the exchange ends.
```
^statblock