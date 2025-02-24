---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/tob1-2023
- monster/cr/1-4
- monster/environment/forest
- monster/size/tiny
- monster/type/ooze
aliases: ["Dipsa"]
---
# Dipsa
*Source: Tome of Beasts 1 (2023 Edition) p. 105*  

*Except for a pair of tiny fangs, the entire body of this yellowishgreen worm looks like a ropy tangle of slime-covered tubes and puddles of mucus.*

## Anesthetic Ooze

Many jungle clans believe the dipsa is an eyeless snake, but it is a tubular ooze with a lethal, poisonous bite. The dipsa's venom has an anesthetic quality that allows the ooze to cling to creatures and slowly turn their innards to jelly without being noticed until the victim falls down dead. Once the poison's numbing property wears off, however, victims report an agonizing sense of burning from the inside out.

## Tiny Fangs

A dipsa's undulating movement evokes that of a snake as much as its serpentine form, but close examination reveals that it has neither bones nor internal organs, only tiny fangs of the same color and substance as the rest of its body. A dipsa never exceeds 1 foot in length. Its coloration oscillates between sickly hues of yellow or green.

## Gelatinous Eggs

Dipsas are hermaphroditic. When two dipsas breed, they leave behind a hundred gelatinous eggs in a small puddle of highly acidic milt. A dozen become fertilized and survive long enough to hatch, after which they immediately devour the others.

## Statblock

```ad-statblock
title: Dipsa
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ToB1-2023/Dipsa.webp#token)
*Tiny ooze, Unaligned*

- **Armor Class** 15 (natural armor)
- **Hit Points** 27 (`6d4 + 12`)
- **Speed** 20 ft., climb 20 ft., swim 20 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
| 3 (-4)|17 (+3)|14 (+2)| 1 (-5)| 6 (-2)| 1 (-5)|

- **Proficiency Bonus** +2
- **Saving Throws** ⏤
- **Skills** Stealth +5
- **Senses** blindsight 60 ft. (blind beyond this radius), passive Perception 8
- **Damage Resistances** acid
- **Condition Immunities** [blinded](2-Mechanics/CLI/rules/conditions.md#Blinded), [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [deafened](2-Mechanics/CLI/rules/conditions.md#Deafened), [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened), [prone](2-Mechanics/CLI/rules/conditions.md#Prone)
- **Languages** —
- **Challenge** 1/4

## Traits

***Amorphous.*** The dipsa can move through a space as narrow as 1 inch wide without squeezing.

***Discreet Bite.*** The bite of a dipsa is barely perceptible and the wound is quickly anesthetized. When the dipsa hits with a Bite attack, the target must succeed on a DC 15 Wisdom ([Perception](2-Mechanics/CLI/rules/skills.md#Perception)) check to notice the dipsa and its attack. Each time the creature takes acid damage from an attached dipsa, it can repeat this check, noticing the dipsa on a success. A creature that takes acid damage from the dipsa while below half its hp maximum automatically succeeds on this check.

***Ooze Nature.*** The dipsa doesn't require sleep.

***Swamp Camouflage.*** The dipsa has advantage on Dexterity ([Stealth](2-Mechanics/CLI/rules/skills.md#Stealth)) checks made to hide in swampy terrain.

## Actions

***Bite.*** *Melee Weapon Attack:* `dice:1d20+5|noform|text(+5)` to hit, reach 5 ft., one creature. *Hit:* 1 piercing damage, and the dipsa attaches to the target. While attached, the dipsa can't attack, and at the start of each of the dipsa's turns, the target takes `dice:1d6|noform|avg|text(3)` (`1d6`) acid damage and must succeed on a DC 12 Constitution saving throw or have its hp maximum reduced by an amount equal to the damage taken. This reduction lasts until the target finishes a long rest. The target dies if this effect reduces its hp maximum to 0.

The attached dipsa moves with the target whenever the target moves, requiring none of the dipsa's movement. It can detach itself by spending 5 feet of its movement on its turn. A creature, including the target, can use its action to detach the dipsa.

## Bonus Actions

***Translucent.*** The dipsa takes the Hide action.
```
^statblock

## Environment

forest