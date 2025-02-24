---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/dodk
- monster/cr/6
- monster/size/medium
- monster/type/undead
aliases: ["Saint Gresha"]
---
# Saint Gresha
*Source: Dungeons of Drakkenheim p. 124*  

Gresha was called back in spirit by Lucretia Mathias to tend her namesake chapel. If Saint Gresha is destroyed, Lucretia Mathias calls her spirit back again as soon as possible.

```ad-statblock
title: Saint Gresha
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/DoDk/Saint%20Gresha.webp#token)
*Medium undead, Neutral Good*

- **Armor Class** 13
- **Hit Points** 67 (`9d8 + 27`)
- **Speed** 0 ft., fly 60 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
| 6 (-2)|16 (+3)|16 (+3)|12 (+1)|14 (+2)|15 (+2)|

- **Proficiency Bonus** +3
- **Saving Throws** ⏤
- **Skills** ⏤
- **Senses** darkvision 60 ft., passive Perception 12
- **Damage Resistances** acid; cold; fire; lightning; thunder; bludgeoning, piercing, slashing from nonmagical attacks that aren't silvered
- **Damage Immunities** necrotic, poison
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled), [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed), [petrified](2-Mechanics/CLI/rules/conditions.md#Petrified), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned), [prone](2-Mechanics/CLI/rules/conditions.md#Prone), [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained)
- **Languages** The languages it knew in life
- **Challenge** 6

## Traits

***Incorporeal Movement.*** Saint Gresha can move through other creatures and objects as if they were difficult terrain. It takes `dice:1d10|noform|avg|text(5)` (`1d10`) force damage if it ends its turn inside an object.

***Sunlight Sensitivity.*** While in sunlight, Saint Gresha has disadvantage on attack rolls, as well as on Wisdom ([Perception](2-Mechanics/CLI/rules/skills.md#Perception)) checks that rely on sight.

***Spellcasting.*** Saint Gresha is an 8th-level spellcaster. Its spellcasting ability is Charisma (spell save DC 13, `dice:1d20+5|noform|text(+5)` to hit with spell attacks). Saint Gresha knows the following sorcerer spells:

**At will**: [guidance](2-Mechanics/CLI/spells/guidance.md), [light](2-Mechanics/CLI/spells/light.md), [sacred flame](2-Mechanics/CLI/spells/sacred-flame.md), [thaumaturgy](2-Mechanics/CLI/spells/thaumaturgy.md)

**1/day each**: [divine word](2-Mechanics/CLI/spells/divine-word.md), [harm](2-Mechanics/CLI/spells/harm.md), [heal](2-Mechanics/CLI/spells/heal.md), [holy aura](2-Mechanics/CLI/spells/holy-aura.md), [sacrament of the falling fire](2-Mechanics/CLI/spells/sacrament-of-the-falling-fire-dodk.md)*

**3/day each**: [bless](2-Mechanics/CLI/spells/bless.md), [flame strike](2-Mechanics/CLI/spells/flame-strike.md), [guiding bolt](2-Mechanics/CLI/spells/guiding-bolt.md), [healing word](2-Mechanics/CLI/spells/healing-word.md), [prayer of healing](2-Mechanics/CLI/spells/prayer-of-healing.md), [spirit guardians](2-Mechanics/CLI/spells/spirit-guardians.md)

*new spell described in Appendix D of Dungeons of Drakkenheim.

## Actions

***Life Drain.*** *Melee Weapon Attack:* `dice:1d20+6|noform|text(+6)` to hit, reach 5 ft., one creature. *Hit:* `dice:4d8+3|noform|avg|text(21)` (`4d8 + 3`) necrotic damage. The target must succeed on a DC 14 Constitution saving throw or its hit point maximum is reduced by an amount equal to the damage taken. This reduction lasts until the target finishes a long rest. The target dies if this effect reduces its hit point maximum to 0.

***Create Specter.*** Saint Gresha targets a humanoid within 10 feet of it that has been dead for no longer than 1 minute and died violently. The target's spirit rises as a specter in the space of its corpse or in the nearest unoccupied space. The specter is under Saint Gresha's control. Saint Gresha can have no more than seven specters under its control at one time.
```
^statblock