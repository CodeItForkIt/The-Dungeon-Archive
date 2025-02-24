---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/ghloe
- monster/cr/1
- monster/size/tiny
- monster/type/fiend
statblock: inline
aliases: ["Malikirian Imp"]
---
# [Malikirian Imp](Mechanics\bestiary\fiend/malikirian-imp-ghloe.md)
*Source: Grim Hollow: Lairs of Etharis p. 109*  

> [!quote]  
> 
> I can give you anything, mortal. Riches? Accolades? To be important, for once? Whisper your secrets to me. I will tell you the secrets of your rivals. They all dance with me.

## Salvage

If caught alone with a hostile foe, the imp pleads for its life and pledges to serve its new master. It gives its name, which a caster can use when casting find familiar to summon and bind the imp as their familiar.

An imp's scales and bones can be used to create a potion of fire resistance with a DC 15 Intelligence ([Arcana](Mechanics/Rules/skills.md#Arcana)) ability check from a character proficient in alchemist's supplies. This takes 2 hours and 10 gp of materials. However, there's a 10% chance that the person taking the potion will be vulnerable to all other damage.

Eating the Malikirian imp's heart grants the ability to cast suggestion once without using a spell slot. The DC to resist this spell is 10.

## Lore

- **DC 10 Intelligence ([Religion](Mechanics/Rules/skills.md#Religion)).** Beware the multitudinous throngs of Malikir's progeny, for they can corrupt even the most pure-hearted and spur them to acts of sin and moral decay.  
- **DC 15 Intelligence ([History](Mechanics/Rules/skills.md#History)).** Many a foolish warlock thought they had the upper hand when they received such a pathetic creature as their familiar, but they underestimated the imp at their peril.  
- **DC 20 Intelligence ([Arcana](Mechanics/Rules/skills.md#Arcana)).** Despite archmages' divinations, no one quite knows how the Angel of Empyreus came to hold the chains of a Malikirian imp. This cannot be good news.  

```statblock
"name": "Malikirian Imp (GHLoE)"
"size": "Tiny"
"type": "fiend"
"alignment": "Lawful Evil"
"ac": !!int "11"
"hp": !!int "15"
"hit_dice": "6d4"
"stats":
- !!int "7"
- !!int "13"
- !!int "10"
- !!int "11"
- !!int "12"
- !!int "14"
"speed": "20 ft., fly 40 ft."
"saves":
  "Charisma": !!int "4"
  "Wisdom": !!int "3"
"skillsaves":
  "Deception": !!int "4"
  "Stealth": !!int "3"
  "Insight": !!int "3"
"damage_resistances": "cold; bludgeoning, piercing, slashing from nonmagical attacks"
"damage_immunities": "fire, poison"
"condition_immunities": "[poisoned](Mechanics/Rules/conditions.md#Poisoned)"
"senses": "darkvision 120 ft., passive Perception 11"
"languages": "Infernal and 2 other languages"
"cr": "1"
"traits":
- "desc": "The Malikirian imp's spellcasting ability is Charisma (spell save DC 12).\
    \ It can innately cast the following spells without material components:\n\nAt\
    \ will: [minor illusion](Mechanics/spells/minor-illusion.md)\n\n1/day each:\
    \ [detect thoughts](Mechanics/spells/detect-thoughts.md), [sleep](Mechanics/spells/sleep.md),\
    \ [suggestion](Mechanics/spells/suggestion.md)"
  "name": "Innate Spellcasting"
- "desc": "Creatures within 30 ft. that the Malikirian imp can see must make a DC\
    \ 12 Charisma saving throw at the start of their turn. On a failure, the creature\
    \ acts in accordance with its most selfish, venal, and ruthless impulses to the\
    \ best of its ability. After 24 hours, the creature must make another Charisma\
    \ saving throw, ending the compulsion on a success. Failure indicates the compulsion\
    \ lasts indefinitely until the affected is subject to remove curse or similar\
    \ magic. Creatures that cannot be [charmed](Mechanics/Rules/conditions.md#Charmed)\
    \ are immune to this effect."
  "name": "Creeping Corruption"
- "desc": "The Malikirian imp has advantage on saving throws against spells and other\
    \ magical effects."
  "name": "Magic Resistance"
"actions":
- "desc": "Melee Weapon Attack: -1 to hit, reach 0 ft., one target. Hit: 1 (1d4\
    \ - 2) piercing damage and the target must succeed on a DC 10 Constitution saving\
    \ throw or take 7 (2d6) poison damage."
  "name": "Bite"
- "desc": "The Malikirian imp becomes [invisible](Mechanics/Rules/conditions.md#Invisible)\
    \ until its [concentration](Mechanics/Rules/conditions.md#Concentration) ends\
    \ or it makes an attack."
  "name": "Invisibility"
"source":
- "GHLoE"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/GHLoE/Malikirian%20Imp.webp"
```
^statblock