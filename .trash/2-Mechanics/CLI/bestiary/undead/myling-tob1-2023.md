---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/tob1-2023
- monster/cr/2
- monster/environment/forest
- monster/size/small
- monster/type/undead
aliases: ["Myling"]
---
# Myling
*Source: Tome of Beasts 1 (2023 Edition) p. 281*  

*Dressed in rags, this small humanoid has cold, blue skin and large, black eyes.*

Mylings are the souls of the unburied, those who died in the forest from abandonment or exposure and can find no peace until their bodies are properly interred. Given the circumstances around their deaths, mylings tend to be solitary, haunting the places where they died. When some tragedy ended in multiple deaths, the resulting mylings stay together and hunt as a pack.

## Attack in a Rage

Mylings prefer to attack lone wanderers. They target a group when desperate or when there's more than one myling in the pack. They shadow a target until after dark, then jump onto the target's back and demand to be carried to their chosen burial ground. They cling tightly to a victim with arms and legs locked around the victim's shoulders and midsection, begging, threatening, and biting until the victim gives in to their demands. Mylings bite victims to death if the victim is unable or unwilling to carry them, or if a victim moves too slowly.

## Ungrateful Rest

While all mylings seek a creature to carry them to their final resting place, even when a "mount" is willing, the creature's body grows immensely heavy as it nears its burial place. Once there, the myling sinks into the earth, taking its bearer with it.

## Urchin Rhymes and Songs

Some mylings maintain traces of the personalities they had while alive—charming, sullen, or sadistic—and can speak touchingly and piteously. Dressed in ragged clothing, their skin blue with cold, they sometimes reach victims who believe they are helping an injured child or young adult. They hide their faces and sing innocent rhymes when they aren't screeching in fury, for they know that their dead eyes and cold blue skin cause fright and alarm.

## Statblock

```ad-statblock
title: Myling
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ToB1-2023/Myling.webp#token)
*Small undead, Chaotic Evil*

- **Armor Class** 13 (natural armor)
- **Hit Points** 45 (`10d6 + 10`)
- **Speed** 30 ft., burrow 10 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|10 (+0)|16 (+3)|12 (+1)|10 (+0)|12 (+1)|10 (+0)|

- **Proficiency Bonus** +2
- **Saving Throws** ⏤
- **Skills** Stealth +5
- **Senses** darkvision 60 ft., passive Perception 11
- **Damage Resistances** bludgeoning, piercing, slashing from nonmagical attacks that aren't silvered
- **Damage Immunities** necrotic, poison
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned), [stunned](2-Mechanics/CLI/rules/conditions.md#Stunned), [unconscious](2-Mechanics/CLI/rules/conditions.md#Unconscious)
- **Languages** the languages it knew in life
- **Challenge** 2

## Traits

***Enfeebling Attacks.*** Each time the myling deals necrotic damage to a creature that is below half its hp maximum, the target's Strength score is reduced by `dice:1d4|noform|avg` (`1d4`). The target dies if this reduces its Strength to 0. Otherwise, the reduction lasts until the target finishes a short or long rest.

***Undead Nature.*** The myling doesn't require air, food, drink, or sleep.

## Actions

***Claw.*** *Melee Weapon Attack:* `dice:1d20+5|noform|text(+5)` to hit, reach 5 ft., one target. *Hit:* `dice:2d6+3|noform|avg|text(10)` (`2d6 + 3`) slashing damage plus `dice:2d6|noform|avg|text(7)` (`2d6`) necrotic damage, and the target must succeed on a DC 13 Dexterity saving throw or the myling attaches to it. While attached, the myling sinks its teeth into the target and can't attack, and at the start of each of the myling's turns, the target takes `dice:5d6|noform|avg|text(17)` (`5d6`) necrotic damage.

The attached myling moves with the target whenever the target moves, requiring none of the myling's movement. It can detach itself by spending 5 feet of its movement on its turn. A creature, including the target, can use its action to detach the myling by succeeding on a DC 13 Strength check.

## Bonus Actions

***Bury Alive (Recharge 6).*** The creature to which the myling is attached is knocked [prone](2-Mechanics/CLI/rules/conditions.md#Prone), dragged into the ground, and buried just below the surface, ending the attachment. The buried creature is [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained) and unable to breathe or stand up. A creature, including the buried creature, can take its action to free the buried creature by succeeding on a DC 13 Strength check.
```
^statblock

## Environment

forest