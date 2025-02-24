---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/idrotf
- monster/cr/5
- monster/size/large
- monster/type/giant
aliases: ["Verbeeg Longstrider"]
---
# Verbeeg Longstrider
*Source: Icewind Dale: Rime of the Frostmaiden p. 311*  

Verbeeg are giants that resemble oversized humans with gangly limbs and elongated faces. Some have other features that give them a fearsome aspect.

Verbeeg craft their own armor and weapons. They prefer thrown spears above all other weapons, and a verbeeg usually has several spears for that purpose.

## Longstriders

Some verbeeg worship gods of nature and help defend the natural world. These even-tempered verbeeg are called longstriders and are blessed with innate spellcasting abilities.

## Statblock

```ad-statblock
title: Verbeeg Longstrider
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/IDRotF/Verbeeg%20Longstrider.webp#token)
*Large giant, Neutral*

- **Armor Class** 14 ([hide armor](2-Mechanics/CLI/items/hide-armor.md))
- **Hit Points** 119 (`14d10 + 42`)
- **Speed** 50 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|19 (+4)|15 (+2)|16 (+3)|13 (+1)|14 (+2)|10 (+0)|

- **Proficiency Bonus** +3
- **Saving Throws** Dexterity +5, Constitution +6, Wisdom +5
- **Skills** Animal Handling +5, Athletics +7, Stealth +5
- **Senses** passive Perception 12
- **Languages** Common, Giant
- **Challenge** 5

## Traits

***Simple Weapon Wielder.*** A simple weapon deals one extra die of its damage when the verbeeg hits with it (included in the attack).

***Innate Spellcasting.*** The verbeeg's innate spellcasting ability is Wisdom. It can innately cast the following spells, requiring no components:

**1/day each**: [animal messenger](2-Mechanics/CLI/spells/animal-messenger.md), [fog cloud](2-Mechanics/CLI/spells/fog-cloud.md), [freedom of movement](2-Mechanics/CLI/spells/freedom-of-movement.md), [pass without trace](2-Mechanics/CLI/spells/pass-without-trace.md), [silence](2-Mechanics/CLI/spells/silence.md), [water walk](2-Mechanics/CLI/spells/water-walk.md)

## Actions

***Multiattack.*** The verbeeg makes two melee attacks.

***Spear.*** *Melee or Ranged Weapon Attack:* `dice:1d20+7|noform|text(+7)` to hit, reach 5 ft. or range 20/60 ft., one target. *Hit:* `dice:3d6+4|noform|avg|text(14)` (`3d6 + 4`) piercing damage, or `dice:3d8+4|noform|avg|text(17)` (`3d8 + 4`) piercing damage if used to make a ranged attack or used with two hands to make a melee attack.

***Sling.*** *Ranged Weapon Attack:* `dice:1d20+5|noform|text(+5)` to hit, range 30/120 ft., one target. *Hit:* `dice:3d4+2|noform|avg|text(9)` (`3d4 + 2`) bludgeoning damage. If the target is a creature, it must succeed on a DC 15 Constitution saving throw or be [stunned](2-Mechanics/CLI/rules/conditions.md#Stunned) until the end of its next turn.
```
^statblock