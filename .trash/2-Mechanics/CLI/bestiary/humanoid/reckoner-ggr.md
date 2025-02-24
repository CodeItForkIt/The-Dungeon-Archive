---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/ggr
- monster/cr/4
- monster/size/medium
- monster/type/humanoid/any-race
aliases: ["Reckoner"]
---
# Reckoner
*Source: Guildmasters' Guide to Ravnica p. 231*  

Boros reckoners combine physical power and magical prowess, serving as the shock troops of the legion. They are adept at breaking up mobs and organized lines of defense. Sometimes described as living thunderstorms, reckoners charge their bodies with lightning that bursts forth in their spells and lashes out at enemies who harm them. Many reckoners are minotaurs.

```ad-statblock
title: Reckoner
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/GGR/Reckoner.webp#token)
*Medium humanoid (any race), Lawful Neutral*

- **Armor Class** 18 ([plate armor](2-Mechanics/CLI/items/plate-armor.md))
- **Hit Points** 52 (`8d8 + 16`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|16 (+3)|12 (+1)|15 (+2)|15 (+2)|12 (+1)|10 (+0)|

- **Proficiency Bonus** +2
- **Saving Throws** ⏤
- **Skills** Arcana +4, Intimidation +2, Perception +3
- **Senses** passive Perception 13
- **Languages** Common plus any one language
- **Challenge** 4

## Traits

***First Strike.*** The reckoner has advantage on initiative rolls.

***Spellcasting.*** The reckoner is a 5th-level Boros spellcaster. Its spellcasting ability is Intelligence (spell save DC 12, `dice:1d20+4|noform|text(+4)` to hit with spell attacks). The reckoner has the following wizard spells prepared:

**Cantrips (at will)**: [blade ward](2-Mechanics/CLI/spells/blade-ward.md), [light](2-Mechanics/CLI/spells/light.md), [message](2-Mechanics/CLI/spells/message.md), [shocking grasp](2-Mechanics/CLI/spells/shocking-grasp.md)

**1st level (4 slots)**: [guiding bolt](2-Mechanics/CLI/spells/guiding-bolt.md), [shield](2-Mechanics/CLI/spells/shield.md), [thunderwave](2-Mechanics/CLI/spells/thunderwave.md), [witch bolt](2-Mechanics/CLI/spells/witch-bolt.md)

**2nd level (3 slots)**: [blur](2-Mechanics/CLI/spells/blur.md), [levitate](2-Mechanics/CLI/spells/levitate.md)

**3rd level (2 slots)**: [lightning bolt](2-Mechanics/CLI/spells/lightning-bolt.md)

## Actions

***Longsword.*** *Melee Weapon Attack:* `dice:1d20+5|noform|text(+5)` to hit, reach 5 ft., one target. *Hit:* `dice:1d8+3|noform|avg|text(7)` (`1d8 + 3`) slashing damage, or `dice:1d10+3|noform|avg|text(8)` (`1d10 + 3`) slashing damage if used with two hands.

## Reactions

***Lightning Backlash (Recharge 5-6).*** When a creature hits the reckoner with an attack, the attacker takes lightning damage equal to half the damage dealt by the attack.
```
^statblock