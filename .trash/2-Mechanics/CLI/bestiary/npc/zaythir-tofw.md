---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/tofw
- monster/cr/7
- monster/size/medium
- monster/type/aberration/gith
aliases: ["Zaythir"]
---
# Zaythir
*Source: Turn of Fortune's Wheel p. 32*  

```ad-statblock
title: Zaythir
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ToFW/Zaythir.webp#token)
*Medium aberration (gith), Neutral*

- **Armor Class** 16 (psychic defense)
- **Hit Points** 123 (`19d8 + 38`)
- **Speed** 40 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|13 (+1)|17 (+3)|15 (+2)|15 (+2)|17 (+3)|16 (+3)|

- **Proficiency Bonus** +3
- **Saving Throws** Strength +4, Dexterity +6, Intelligence +5, Wisdom +6
- **Skills** Insight +6, Perception +6
- **Senses** passive Perception 16
- **Languages** Common, Gith
- **Challenge** 7

## Traits

***Psychic Defense.*** While Zaythir is wearing no armor and wielding no shield, its AC includes its Wisdom modifier.

***Spellcasting (Psionics).*** Zaythir casts one of the following spells, requiring no spell components and using Wisdom as the spellcasting ability (spell save DC 14):

**At will**: [mage hand](2-Mechanics/CLI/spells/mage-hand.md) (the hand is invisible), [see invisibility](2-Mechanics/CLI/spells/see-invisibility.md)

**1/day each**: [plane shift](2-Mechanics/CLI/spells/plane-shift.md) (self only), [telekinesis](2-Mechanics/CLI/spells/telekinesis.md)

## Actions

***Multiattack.*** Zaythir makes three Unarmed Strike or Psychic Bolt attacks. It can replace any of these attacks with one use of its Pacifying Touch.

***Unarmed Strike.*** *Melee Weapon Attack:* `dice:1d20+6|noform|text(+6)` to hit, reach 5 ft., one target. *Hit:* `dice:1d8+3|noform|avg|text(7)` (`1d8 + 3`) bludgeoning damage plus `dice:3d6|noform|avg|text(10)` (`3d6`) psychic damage.

***Psychic Bolt.*** *Ranged Spell Attack:* `dice:1d20+6|noform|text(+6)` to hit, range 60 ft., one creature. *Hit:* `dice:5d6|noform|avg|text(17)` (`5d6`) psychic damage.

***Pacifying Touch.*** Zaythir touches one creature it can see within 5 feet of itself. The target must succeed on a DC 14 Intelligence saving throw, or Zaythir chooses an action for that target: Attack, Cast a Spell, or Dash. The affected target can't take that action for 1 minute. At the end of each of the target's turns, it can repeat the saving throw, ending the effect on itself on a successful save. A target that succeeds on the saving throw becomes immune to this githzerai's Pacifying Touch for 24 hours.
```
^statblock