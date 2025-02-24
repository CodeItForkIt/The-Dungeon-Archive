---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/mabjov
- monster/cr/2
- monster/size/medium
- monster/type/fey
aliases: ["Hamadryad"]
---
# Hamadryad
*Source: Minsc and Boo's Journal of Villainy p. 143*  

> [!quote] A quote from Hamadryad  
> 
> I cannot drink the water. My roots grow black and rotten. I cannot drink the water. My leaves wither and die. I cannot drink...

> [!quote] A quote from Volo  
> 
> It is a sad thing when one of nature's most beautiful fey is corrupted into a hamadryad. Be careful about feeling too much sympathy for them, for they are fearsome when someone trespasses into their territory.

These fey come into being when the home tree of a dryad is destroyed or becomes corrupted by foul magic. If the dryad isn't killed she slowly wastes away and over the course of several months becomes a hamadryad. Hamadryads are mad creatures that seek vengeance against any non-fey that wanders into the deep places of the wood that is their home.

## Beauty Lost

Hamadryads do not retain the beauty that they had before whatever tragedy befell them. Their mouths have vanished and their laughter is forever gone. The beautiful feminine forms dryads are famed for have become twisted. Their emerald skin is grey and sickly and their very touch is corrupt and poisonous.

## Madness

Hamadryads rarely behave in a manner that seems rational. They might viciously attack an intruder and then vanish, only to return later when their mood changes. Sometimes they might help a group of adventurers against evil creatures only to turn on the adventurers once their mutual foe is vanquished.

## Statblock

```ad-statblock
title: Hamadryad
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/MaBJoV/Hamadryad.webp#token)
*Medium fey, Chaotic Neutral*

- **Armor Class** 13 (16 with [barkskin](2-Mechanics/CLI/spells/barkskin.md))
- **Hit Points** 32 (`5d8 + 10`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|10 (+0)|16 (+3)|14 (+2)|14 (+2)|10 (+0)|15 (+2)|

- **Proficiency Bonus** +2
- **Saving Throws** ⏤
- **Skills** Perception +2, Stealth +6
- **Senses** darkvision 60ft., passive Perception 12
- **Languages** Sylvan
- **Challenge** 2

## Traits

***Magic Resistance.*** The hamadryad has advantage on saving throws against spells and other magical effects.

***Speak with Beasts and Plants.*** The hamadryad can communicate with Beasts and Plants as if they shared a language.

***Tree Stride.*** Once on her turn, the hamadryad can use 10 feet of her movement to step magically into one living tree within her reach and emerge from a second living tree within 60 feet of the first tree, appearing in an unoccupied space within 5 feet of the second tree. Both trees must be Large in size or bigger.

***Spellcasting.*** The hamadryad casts one of the following spells, requiring no material components and using Charisma as the spellcasting ability (spell save DC 12):

**1/day each**: [barkskin](2-Mechanics/CLI/spells/barkskin.md), [grasping vine](2-Mechanics/CLI/spells/grasping-vine.md), [pass without trace](2-Mechanics/CLI/spells/pass-without-trace.md)

**2/day**: [entangle](2-Mechanics/CLI/spells/entangle.md)

## Actions

***Multiattack.*** The hamadryad makes two Claw attacks.

***Claw.*** *Melee Weapon Attack:* `dice:1d20+5|noform|text(+5)` to hit, range 5 ft., one target. *Hit:* `dice:1d4+3|noform|avg|text(5)` (`1d4 + 3`) plus `dice:3d6|noform|avg|text(10)` (`3d6`) poison damage.
```
^statblock