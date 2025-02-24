---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/pabtso
- monster/cr/4
- monster/size/medium
- monster/type/aberration
aliases: ["Grell Psychic"]
---
# Grell Psychic
*Source: Phandelver and Below: The Shattered Obelisk p. 145*  

```ad-statblock
title: Grell Psychic
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/PaBTSO/Grell%20Psychic.webp#token)
*Medium aberration, Chaotic Evil*

- **Armor Class** 12 (15 with [mage armor](2-Mechanics/CLI/spells/mage-armor.md))
- **Hit Points** 66 (`12d8 + 12`)
- **Speed** 10 ft., fly 30 ft. (hover)

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|17 (+3)|14 (+2)|13 (+1)|12 (+1)|11 (+0)|14 (+2)|

- **Proficiency Bonus** +2
- **Saving Throws** ⏤
- **Skills** Perception +4, Stealth +6
- **Senses** blindsight 60 ft. (blind beyond this radius), passive Perception 14
- **Damage Immunities** lightning
- **Condition Immunities** [blinded](2-Mechanics/CLI/rules/conditions.md#Blinded), [prone](2-Mechanics/CLI/rules/conditions.md#Prone)
- **Languages** Deep Speech, Grell
- **Challenge** 4

***Spellcasting (Psionics).*** The grell psychic casts one of the following spells, requiring no spell components and using Charisma as the spellcasting ability (spell save DC 12):

**At will**: [detect thoughts](2-Mechanics/CLI/spells/detect-thoughts.md), [mage armor](2-Mechanics/CLI/spells/mage-armor.md), [mage hand](2-Mechanics/CLI/spells/mage-hand.md) (the hand is invisible)

**1/day each**: [confusion](2-Mechanics/CLI/spells/confusion.md), [fear](2-Mechanics/CLI/spells/fear.md)

## Actions

***Multiattack.*** The grell psychic makes one Tentacle attack and one Beak attack.

***Beak.*** *Melee Weapon Attack:* `dice:1d20+5|noform|text(+5)` to hit, reach 5 ft., one target. *Hit:* `dice:3d4+3|noform|avg|text(10)` (`3d4 + 3`) piercing damage.

***Tentacle.*** *Melee Weapon Attack:* `dice:1d20+5|noform|text(+5)` to hit, reach 10 ft., one target. *Hit:* `dice:1d10+3|noform|avg|text(8)` (`1d10 + 3`) piercing damage, and the target must succeed on a DC 11 Constitution saving throw or have the [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned) condition for 1 minute. While the target is [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned), it also has the [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed) condition. The target can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success. The target also has the [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) condition (escape DC 16). While grappling the target, the grell can't make Tentacle attacks against other targets. When the grell moves, any Medium or smaller target it is grappling moves with it.
```
^statblock