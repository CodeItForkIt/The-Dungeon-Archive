---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/ftd
- monster/cr/5
- monster/size/medium
- monster/type/humanoid
aliases: ["Dragon Blessed"]
---
# Dragon Blessed
*Source: Fizban's Treasury of Dragons p. 188*  

Dragon blessed are the acolytes of dragons, whom they revere as gods. They wield magic to heal and support those who have earned their dragon masters' favor—and scourge those who incur the dragons' wrath. Dragon blessed view their lives and magical abilities as gifts bestowed by their dragon, and they give life energy to save those they deem important to their masters' work.

## Dragon Followers

Dragons boast many minions, students, employees, acolytes, and thralls. Dragon followers are those servitors whose devotion to a dragon approaches fanatical reverence and who receive magical power from the dragon in return.

Dragon followers might serve and revere any kind of dragon, and their behavior and beliefs reflect the ethos of the dragon they follow. Many dragon followers have personal stories of benevolent dragons sharing great knowledge, protecting their towns, or sparing their lives during some foolhardy adventure. Other followers seek to uncover the mysteries of draconic nature and live a life worthy of their dragon's reward, and they dream of a world where dragons can live among them as their rulers.

## Statblock

```ad-statblock
title: Dragon Blessed
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/FTD/Dragon%20Blessed.webp#token)
*Medium humanoid, Any alignment*

- **Armor Class** 14 ([scale mail](2-Mechanics/CLI/items/scale-mail.md))
- **Hit Points** 75 (`10d8 + 30`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|12 (+1)|10 (+0)|16 (+3)|14 (+2)|17 (+3)|10 (+0)|

- **Proficiency Bonus** +3
- **Saving Throws** Constitution +6, Wisdom +6
- **Skills** Medicine +6, Religion +5
- **Senses** passive Perception 13
- **Condition Immunities** [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened)
- **Languages** Common, Draconic, and any two languages
- **Challenge** 5

***Spellcasting.*** The blessed casts one of the following spells, using Wisdom as the spellcasting ability (spell save DC 14):

**At will**: [light](2-Mechanics/CLI/spells/light.md), [thaumaturgy](2-Mechanics/CLI/spells/thaumaturgy.md)

**1/day each**: [enhance ability](2-Mechanics/CLI/spells/enhance-ability.md), [flame strike](2-Mechanics/CLI/spells/flame-strike.md), [mass cure wounds](2-Mechanics/CLI/spells/mass-cure-wounds.md), [revivify](2-Mechanics/CLI/spells/revivify.md), [tongues](2-Mechanics/CLI/spells/tongues.md)

## Actions

***Multiattack.*** The blessed makes two Mace or Radiant Bolt attacks.

***Mace.*** *Melee Weapon Attack:* `dice:1d20+4|noform|text(+4)` to hit, reach 5 ft., one target. *Hit:* `dice:1d6+1|noform|avg|text(4)` (`1d6 + 1`) bludgeoning damage plus `dice:4d8|noform|avg|text(18)` (`4d8`) radiant damage.

***Radiant Bolt.*** *Ranged Spell Attack:* `dice:1d20+6|noform|text(+6)` to hit, range 120 ft., one target. *Hit:* `dice:5d8|noform|avg|text(22)` (`5d8`) radiant damage, and the blessed regains `dice:1d10|noform|avg|text(5)` (`1d10`) hit points.
```
^statblock