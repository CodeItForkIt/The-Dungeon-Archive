---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/ftd
- monster/cr/2
- monster/size/small
- monster/type/humanoid
aliases: ["Dragon Speaker"]
---
# Dragon Speaker
*Source: Fizban's Treasury of Dragons p. 189*  

Dragon speakers are charismatic and persuasive orators who serve as a dragon's ambassadors among other folk. Dragon speakers have loud and authoritative voices, which they use to gain valuable resources, diplomatic connections, and donations of treasure and magic for their dragons—as well as to weave magic both subtle and thundering. They use their commanding presence to instill awe and fear into the hearts of friends and foes alike.

## Dragon Followers

Dragons boast many minions, students, employees, acolytes, and thralls. Dragon followers are those servitors whose devotion to a dragon approaches fanatical reverence and who receive magical power from the dragon in return.

Dragon followers might serve and revere any kind of dragon, and their behavior and beliefs reflect the ethos of the dragon they follow. Many dragon followers have personal stories of benevolent dragons sharing great knowledge, protecting their towns, or sparing their lives during some foolhardy adventure. Other followers seek to uncover the mysteries of draconic nature and live a life worthy of their dragon's reward, and they dream of a world where dragons can live among them as their rulers.

## Statblock

```ad-statblock
title: Dragon Speaker
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/FTD/Dragon%20Speaker.webp#token)
*Small humanoid, Any alignment*

- **Armor Class** 13 ([leather armor](2-Mechanics/CLI/items/leather-armor.md))
- **Hit Points** 36 (`8d6 + 8`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|10 (+0)|14 (+2)|12 (+1)|13 (+1)|11 (+0)|17 (+3)|

- **Proficiency Bonus** +2
- **Saving Throws** Dexterity +4, Charisma +5
- **Skills** Persuasion +5, Religion +3
- **Senses** darkvision 60 ft., passive Perception 10
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened)
- **Languages** Common, Draconic, and any two languages
- **Challenge** 2

***Spellcasting.*** The speaker casts one of the following spells, using Charisma as the spellcasting ability (spell save DC 13):

**At will**: [dancing lights](2-Mechanics/CLI/spells/dancing-lights.md)

**1/day each**: [calm emotions](2-Mechanics/CLI/spells/calm-emotions.md), [charm person](2-Mechanics/CLI/spells/charm-person.md), [command](2-Mechanics/CLI/spells/command.md), [comprehend languages](2-Mechanics/CLI/spells/comprehend-languages.md)

## Actions

***Multiattack.*** The speaker makes two Thunder Bolt attacks.

***Thunder Bolt.*** *Melee or Ranged Spell Attack:* `dice:1d20+5|noform|text(+5)` to hit, reach 5 ft. or range 60 ft., one target. *Hit:* `dice:3d8|noform|avg|text(13)` (`3d8`) thunder damage, and the target is pushed horizontally up to 10 feet away from the speaker.

## Reactions

***Disarming Words (3/Day).*** When a creature the speaker can see within 60 feet of it makes a damage roll, the speaker can roll a `dice:d6|noform|avg` (`d6`) and subtract the number rolled from that damage roll.
```
^statblock