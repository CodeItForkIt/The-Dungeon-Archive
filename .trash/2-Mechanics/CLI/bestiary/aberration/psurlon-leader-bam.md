---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/bam
- monster/cr/6
- monster/size/medium
- monster/type/aberration
aliases: ["Psurlon Leader"]
---
# Psurlon Leader
*Source: Boo's Astral Menagerie p. 45*  

One out of every hundred psurlons is a mutant with two heads, one at each end of its body, and a superior intellect. Other psurlons look to the two-headed ones for leadership.

```ad-statblock
title: Psurlon Leader
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/BAM/Psurlon%20Leader.webp#token)
*Medium aberration, typically  Lawful Evil*

- **Armor Class** 15 ([mage armor](2-Mechanics/CLI/spells/mage-armor.md))
- **Hit Points** 127 (`17d8 + 51`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|16 (+3)|14 (+2)|16 (+3)|20 (+5)|11 (+0)| 7 (-2)|

- **Proficiency Bonus** +3
- **Saving Throws** Wisdom +3, Charisma +1
- **Skills** Perception +6
- **Senses** blindsight 120 ft. (blind beyond this radius), passive Perception 16
- **Damage Resistances** psychic
- **Condition Immunities** [blinded](2-Mechanics/CLI/rules/conditions.md#Blinded), [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed)
- **Languages** Deep Speech, telepathy 120 ft.
- **Challenge** 6

## Traits

***Aberrant Mind.*** Magic can't read the psurlon's thoughts or put the psurlon to sleep.

***Two Heads.*** The psurlon has advantage on saving throws it makes to avoid or end the [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened), [stunned](2-Mechanics/CLI/rules/conditions.md#Stunned), or [unconscious](2-Mechanics/CLI/rules/conditions.md#Unconscious) condition on itself. While one of the psurlon's heads is asleep, its other head is awake.

***Spellcasting (Psionics).*** The psurlon casts one of the following spells, requiring no spell components and using Intelligence as the spellcasting ability (spell save DC 16):

**1/day each**: [dimension door](2-Mechanics/CLI/spells/dimension-door.md), [suggestion](2-Mechanics/CLI/spells/suggestion.md)

**2/day each**: [disguise self](2-Mechanics/CLI/spells/disguise-self.md), [mage armor](2-Mechanics/CLI/spells/mage-armor.md) (self only)

## Actions

***Multiattack.*** The psurlon makes two Bite attacks and two Claw attacks. It can also use Pacify (if available) or Psychic Crush.

***Bite.*** *Melee Weapon Attack:* `dice:1d20+6|noform|text(+6)` to hit, reach 5 ft., one creature. *Hit:* `dice:1d8+3|noform|avg|text(7)` (`1d8 + 3`) piercing damage.

***Claw.*** *Melee Weapon Attack:* `dice:1d20+6|noform|text(+6)` to hit, reach 5 ft., one target. *Hit:* `dice:1d4+3|noform|avg|text(5)` (`1d4 + 3`) slashing damage.

***Pacify (Recharge 5-6).*** The psurlon targets one creature it can see within 120 feet of itself. The target must succeed on a DC 16 Wisdom saving throw or fall [unconscious](2-Mechanics/CLI/rules/conditions.md#Unconscious) for 10 minutes. The condition ends if the target takes any damage or if another creature uses its action to shake the target awake.

***Psychic Crush.*** The psurlon targets one creature it can see within 120 feet of itself. The target must make a DC 16 Wisdom saving throw, taking `dice:3d10+5|noform|avg|text(21)` (`3d10 + 5`) psychic damage on a failed save, or half as much damage on a successful one.
```
^statblock