---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/crcotn
- monster/cr/10
- monster/size/small-or-medium
- monster/type/humanoid/monk
- monster/type/humanoid/wizard
aliases: ["Monastic High Curator"]
---
# Monastic High Curator
*Source: Critical Role: Call of the Netherdeep p. 201*  

High curators collect knowledge and disseminate truth. They tackle puzzling mysteries and spy on members of other power structures to manipulate or destabilize them, and provide the oppressed with opportunities to escape their plight. High curators are privy to their organizations' deepest secrets and the activities of lesser agents. Their expertise enables them to manipulate energy to defend themselves and disrupt enemies' ability to act.

## Monastics of the Cobalt Soul

Scholars, priests, and ascetics who have been drawn to the cause of truth and knowledge spend their lives in support of the Library of the Cobalt Soul, united by the teachings of Ioun the Knowing Mentor. The Cobalt Soul is guided by a central belief that true strength comes from understanding the world around you. Beyond its efforts in knowledge-seeking, each branch of the Cobalt Soul strives to expose lies, unveil propaganda, and fight corruption in whatever society their chapter, referred to as an archive, calls home.

The Library of the Cobalt Soul is headquartered in Rexxentrum, the capital of the Dwendalian Empire on the continent of Wildemount. The organization has archives across Exandria. The Ank'Hareli branch of the Cobalt Soul is based in the Temple of the Mentor. Like many of the archives, the Temple of the Mentor is both a vast library and a shrine to Ioun. This Marquesian archive is led by High Curator Jamil A'alithiya.

## Statblock

```ad-statblock
title: Monastic High Curator
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/CRCotN/Monastic%20High%20Curator.webp#token)
*Small or Medium humanoid (monk, wizard), Any alignment*

- **Armor Class** 19 (Unarmored Defense)
- **Hit Points** 130 (`20d8 + 40`)
- **Speed** 60 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|12 (+1)|16 (+3)|14 (+2)|18 (+4)|22 (+6)|17 (+3)|

- **Proficiency Bonus** +4
- **Saving Throws** Dexterity +7, Wisdom +10
- **Skills** Arcana +8, History +8, Investigation +8, Perception +10
- **Senses** blindsight 30 ft., passive Perception 20
- **Damage Resistances** psychic
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed)
- **Languages** Common plus four other languages
- **Challenge** 10

## Traits

***Unarmored Defense.*** While the high curator is wearing no armor and wielding no shield, its AC includes its Wisdom modifier.

***Spellcasting.*** The high curator casts one of the following spells, requiring no material components and using Wisdom as the spellcasting ability (spell save DC 18):

**At will**: [detect magic](2-Mechanics/CLI/spells/detect-magic.md)

**2/day each**: [detect thoughts](2-Mechanics/CLI/spells/detect-thoughts.md), [identify](2-Mechanics/CLI/spells/identify.md) (as an action), [scrying](2-Mechanics/CLI/spells/scrying.md) (as an action)

## Actions

***Multiattack.*** The high curator makes three Force Strike attacks and uses Brain Burn (if available).

***Force Strike.*** *Melee or Ranged Spell Attack:* `dice:1d20+10|noform|text(+10)` to hit, reach 5 ft. or range 10 ft., one target. *Hit:* `dice:2d10+6|noform|avg|text(17)` (`2d10 + 6`) force damage.

***Brain Burn (Recharge 4-6).*** The high curator targets up to two creatures it can see within 30 feet of itself. Each target must make a DC 18 Constitution saving throw. On a failed saving throw, the target takes `dice:8d6|noform|avg|text(28)` (`8d6`) psychic damage and can't take reactions until the start of its next turn. On a successful save, the target takes half as much damage and suffers no other effect.
```
^statblock