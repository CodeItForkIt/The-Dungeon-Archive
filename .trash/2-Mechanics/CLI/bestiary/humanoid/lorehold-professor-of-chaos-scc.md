---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/scc
- monster/cr/7
- monster/size/small-or-medium
- monster/type/humanoid/wizard
aliases: ["Lorehold Professor of Chaos"]
---
# Lorehold Professor of Chaos
*Source: Strixhaven: A Curriculum of Chaos p. 198*  

Professors of chaos wield magic inspired by the ebb and flow of chance. They study the course history has taken, looking for breaking points in the flow of events, and focus their magic into creating breaks that are to their advantage. Whether those breaks are in a series of events, in obstacles, or in enemies depends on the needs in the moment. They crush enemies' plans under the weight of time and lash out with magical energy that often takes the appearance of books, scrolls, and sheets of parchment.

## Lorehold Scholars

The archaeomancers of Lorehold College draw their magical might from the flow of time and fate and the way those forces shape the course of history. Scholars of this broad mystical study divide between those who see history as an unpredictable jumble of chance and those who believe events form a perfect—and predictable—pattern.

## Statblock

```ad-statblock
title: Lorehold Professor of Chaos
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/SCC/Lorehold%20Professor%20of%20Chaos.webp#token)
*Small or Medium humanoid (wizard), Any alignment*

- **Armor Class** 12
- **Hit Points** 110 (`17d8 + 34`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|11 (+0)|14 (+2)|14 (+2)|19 (+4)|15 (+2)|13 (+1)|

- **Proficiency Bonus** +3
- **Saving Throws** Constitution +5, Intelligence +7, Wisdom +5, Charisma +4
- **Skills** Arcana +7, History +7, Perception +5
- **Senses** passive Perception 15
- **Languages** Common plus any four languages
- **Challenge** 7

## Traits

***Voice from the Past (1/Day).*** The professor can cast the [contact other plane](2-Mechanics/CLI/spells/contact-other-plane.md) spell to contact a long-dead spirit, using Intelligence as the spellcasting ability.

***Spellcasting.*** The professor casts one of the following spells, requiring no material components and using Intelligence as the spellcasting ability:

**At will**: [comprehend languages](2-Mechanics/CLI/spells/comprehend-languages.md), [dancing lights](2-Mechanics/CLI/spells/dancing-lights.md), [guidance](2-Mechanics/CLI/spells/guidance.md)

**2/day each**: [locate object](2-Mechanics/CLI/spells/locate-object.md), [mage armor](2-Mechanics/CLI/spells/mage-armor.md), [passwall](2-Mechanics/CLI/spells/passwall.md)

## Actions

***Multiattack.*** The professor makes two Spectral Scroll attacks. It can also use Weight of [History](2-Mechanics/CLI/rules/skills.md#History), if available.

***Spectral Scroll.*** *Melee Spell Attack:* `dice:1d20+7|noform|text(+7)` to hit, reach 30 ft., one target. *Hit:* `dice:2d10+4|noform|avg|text(15)` (`2d10 + 4`) force damage. If the target is a creature, it must succeed on a DC 15 Strength saving throw or be knocked [prone](2-Mechanics/CLI/rules/conditions.md#Prone).

***Weight of History (Recharge 5-6).*** The professor magically compresses time around up to six creatures of its choice that it can see within 30 feet of itself. Each target must succeed on a DC 15 Wisdom saving throw or be [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained) for 1 minute, but the [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained) target's speed is halved instead of being reduced to 0. At the start of each of its turns, the [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained) target takes `dice:1d8|noform|avg|text(4)` (`1d8`) force damage. A [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained) target can repeat the save at the end of each of its turns, ending the effect on itself on a success.
```
^statblock