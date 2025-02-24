---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/ghloe
- monster/cr/1
- monster/size/tiny
- monster/type/fiend
aliases: ["Malikirian Imp"]
---
# Malikirian Imp
*Source: Grim Hollow: Lairs of Etharis p. 109*  

> [!quote]  
> 
> I can give you anything, mortal. Riches? Accolades? To be important, for once? Whisper your secrets to me. I will tell you the secrets of your rivals. They all dance with me.

## Salvage

If caught alone with a hostile foe, the imp pleads for its life and pledges to serve its new master. It gives its name, which a caster can use when casting find familiar to summon and bind the imp as their familiar.

An imp's scales and bones can be used to create a potion of fire resistance with a DC 15 Intelligence ([Arcana](2-Mechanics/CLI/rules/skills.md#Arcana)) ability check from a character proficient in alchemist's supplies. This takes 2 hours and 10 gp of materials. However, there's a 10% chance that the person taking the potion will be vulnerable to all other damage.

Eating the Malikirian imp's heart grants the ability to cast suggestion once without using a spell slot. The DC to resist this spell is 10.

## Lore

- **DC 10 Intelligence ([Religion](2-Mechanics/CLI/rules/skills.md#Religion)).** Beware the multitudinous throngs of Malikir's progeny, for they can corrupt even the most pure-hearted and spur them to acts of sin and moral decay.  
- **DC 15 Intelligence ([History](2-Mechanics/CLI/rules/skills.md#History)).** Many a foolish warlock thought they had the upper hand when they received such a pathetic creature as their familiar, but they underestimated the imp at their peril.  
- **DC 20 Intelligence ([Arcana](2-Mechanics/CLI/rules/skills.md#Arcana)).** Despite archmages' divinations, no one quite knows how the Angel of Empyreus came to hold the chains of a Malikirian imp. This cannot be good news.  

## Statblock

```ad-statblock
title: Malikirian Imp
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/GHLoE/Malikirian%20Imp.webp#token)
*Tiny fiend, Lawful Evil*

- **Armor Class** 11
- **Hit Points** 15 (`6d4`)
- **Speed** 20 ft., fly 40 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
| 7 (-2)|13 (+1)|10 (+0)|11 (+0)|12 (+1)|14 (+2)|

- **Proficiency Bonus** +2
- **Saving Throws** Wisdom +3, Charisma +4
- **Skills** Deception +4, Insight +3, Stealth +3
- **Senses** darkvision 120 ft., passive Perception 11
- **Damage Resistances** cold; bludgeoning, piercing, slashing from nonmagical attacks
- **Damage Immunities** fire, poison
- **Condition Immunities** [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** Infernal and 2 other languages
- **Challenge** 1

## Traits

***Creeping Corruption.*** Creatures within 30 ft. that the Malikirian imp can see must make a DC 12 Charisma saving throw at the start of their turn. On a failure, the creature acts in accordance with its most selfish, venal, and ruthless impulses to the best of its ability. After 24 hours, the creature must make another Charisma saving throw, ending the compulsion on a success. Failure indicates the compulsion lasts indefinitely until the affected is subject to remove curse or similar magic. Creatures that cannot be [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed) are immune to this effect.

***Magic Resistance.*** The Malikirian imp has advantage on saving throws against spells and other magical effects.

***Innate Spellcasting.*** The Malikirian imp's spellcasting ability is Charisma (spell save DC 12). It can innately cast the following spells without material components:

**At will**: [minor illusion](2-Mechanics/CLI/spells/minor-illusion.md)

**1/day each**: [detect thoughts](2-Mechanics/CLI/spells/detect-thoughts.md), [sleep](2-Mechanics/CLI/spells/sleep.md), [suggestion](2-Mechanics/CLI/spells/suggestion.md)

## Actions

***Bite.*** *Melee Weapon Attack:* `dice:1d20-1|noform|text(-1)` to hit, reach 0 ft., one target. *Hit:* `dice:1d4-2|noform|avg|text(1)` (`1d4 - 2`) piercing damage and the target must succeed on a DC 10 Constitution saving throw or take `dice:2d6|noform|avg|text(7)` (`2d6`) poison damage.

***Invisibility.*** The Malikirian imp becomes [invisible](2-Mechanics/CLI/rules/conditions.md#Invisible) until its [concentration](2-Mechanics/CLI/rules/conditions.md#Concentration) ends or it makes an attack.
```
^statblock