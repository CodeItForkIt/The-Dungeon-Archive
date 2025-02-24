---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/mpp
- monster/cr/3
- monster/size/small-or-medium
- monster/type/humanoid
aliases: ["Society of Sensation Muse"]
---
# Society of Sensation Muse
*Source: Morte's Planar Parade p. 61, Sigil and the Outlands, Turn of Fortune's Wheel*  

The muses of the Society of Sensation are performers who enthrall crowds with spectacle and minor sensory experiences. When threatened, they beguile their foes, placating their enemies with magical displays.

```ad-statblock
title: Society of Sensation Muse
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/MPP/Society%20of%20Sensation%20Muse.webp#token)
*Small or Medium humanoid, Any alignment*

- **Armor Class** 14 ([leather armor](2-Mechanics/CLI/items/leather-armor.md))
- **Hit Points** 44 (`8d8 + 8`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
| 8 (-1)|16 (+3)|12 (+1)|15 (+2)|14 (+2)|17 (+3)|

- **Proficiency Bonus** +2
- **Saving Throws** Dexterity +5, Charisma +5
- **Skills** Insight +4, Perception +4, Performance +7, Stealth +5
- **Senses** passive Perception 14
- **Languages** Common plus two more languages
- **Challenge** 3

***Spellcasting.*** The muse casts one of the following spells, using Charisma as the spellcasting ability (spell save DC 13):

**At will**: [dancing lights](2-Mechanics/CLI/spells/dancing-lights.md)

**1/day each**: [comprehend languages](2-Mechanics/CLI/spells/comprehend-languages.md), [hypnotic pattern](2-Mechanics/CLI/spells/hypnotic-pattern.md)

## Actions

***Multiattack.*** The muse makes two Beguiling Resonance attacks.

***Beguiling Resonance.*** *Melee or Ranged Spell Attack:* `dice:1d20+5|noform|text(+5)` to hit, reach 5 ft. or range 90 ft., one target. *Hit:* `dice:2d8|noform|avg|text(9)` (`2d8`) psychic damage. If the target is a creature, it must succeed on a DC 13 Charisma saving throw or have disadvantage on the next attack roll it makes until the end of its next turn.

## Bonus Actions

***Enchanting Presence.*** Each creature within 30 feet of the muse must make a DC 13 Wisdom saving throw. On a failed save, the creature has the [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed) condition for 1 minute. On a successful save, the creature becomes immune to any muse's Enchanting Presence for 24 hours.

Whenever the muse deals damage to the [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed) creature, the [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed) creature can repeat the saving throw, ending the effect on itself on a success.
```
^statblock