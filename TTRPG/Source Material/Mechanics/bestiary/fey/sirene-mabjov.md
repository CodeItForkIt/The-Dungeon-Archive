---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/mabjov
- monster/cr/3
- monster/size/medium
- monster/type/fey
statblock: inline
aliases: ["Sirene"]
---
# [Sirene](Mechanics\bestiary\fey/sirene-mabjov.md)
*Source: Minsc and Boo's Journal of Villainy p. 147*  

> [!quote] A quote from Volo  
> 
> Sirenes are seen in only a few places in Faerûn. Obviously, the Sword Coast region is one such place. Sirenes have also been sighted in the Sea of Fallen Stars and the Moonsea lake. There are rumors that sirenes can be found at the courts of storm giant lords.

> [!quote] A quote from Sirene  
> 
> Come no closer, mortal. We sing for our sisters and we sing for the ocean. We sing not for you.

Sirenes are fey creatures that live along the cliffs and jagged rocks of the Sword Coast. Equally comfortable on land or beneath the waves, sirenes prefer to keep close to shore and rarely go out into deep water. They are famed for their beautiful singing that often lures sailors to steer their ships to disaster on the coast.

## Territorial

Sirenes live together in small bands. They are extremely territorial and try to drive out any other humanoid that trespasses in their domain. They initially use non-deadly means to convince intruders to leave, but if that is not successful, they are willing to kill.

## Beautiful Song

Sirenes love to sing and use their music to communicate amongst themselves. Their songs are beautiful and haunting, but usually not magical in nature. Only when they are in danger will they weave magic into their songs.

## Skilled Warriors

Sirenes are deadly warriors who use their skills to hunt for food and to kill those who trespass on their territory. Their wicked daggers are made from bone and are their primary weapon when they travel beneath the water. They store their bows close to shore, ready to be retrieved if needed.

```statblock
"name": "Sirene (MaBJoV)"
"size": "Medium"
"type": "fey"
"alignment": "Chaotic Neutral"
"ac": !!int "14"
"hp": !!int "63"
"hit_dice": "14d8"
"stats":
- !!int "12"
- !!int "18"
- !!int "11"
- !!int "12"
- !!int "10"
- !!int "16"
"speed": "30 ft., swim 30 ft."
"skillsaves":
  "Stealth": !!int "6"
  "Performance": !!int "5"
  "Persuasion": !!int "5"
"senses": "darkvision 60ft., passive Perception 10"
"languages": "Common, Elvish, Sylvan"
"cr": "3"
"traits":
- "desc": "The sirene casts one of the following spells, requiring no material components\
    \ and using Charisma as the spellcasting ability (spell save DC 13):\n\n1/day\
    \ each: [crown of madness](Mechanics/spells/crown-of-madness.md), [fog cloud](Mechanics/spells/fog-cloud.md),\
    \ [invisibility](Mechanics/spells/invisibility.md)"
  "name": "Spellcasting"
- "desc": "The sirene can breathe air and water."
  "name": "Amphibious"
- "desc": "The sirene has advantage on saving throws against spells and other magical\
    \ effects."
  "name": "Magic Resistance"
"actions":
- "desc": "The sirene makes two Dagger attacks or two Shortbow attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +6 to hit, range 5 ft., one target. Hit: 6 (1d4\
    \ + 4) piercing damage plus 3 (1d6) cold damage."
  "name": "Dagger"
- "desc": "Ranged Weapon Attack: +6 to hit, range 80/320 ft., one target. Hit:\
    \ 7 (1d6 + 4) piercing damage."
  "name": "Shortbow"
- "desc": "The sirene casts [suggestion](Mechanics/spells/suggestion.md) with a range\
    \ of 1 mile that affects all creatures of the sirene's choosing in range. Each\
    \ target has disadvantage on the saving throw."
  "name": "Sirene's Song (2/Day)"
"source":
- "MaBJoV"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/MaBJoV/Sirene.webp"
```
^statblock