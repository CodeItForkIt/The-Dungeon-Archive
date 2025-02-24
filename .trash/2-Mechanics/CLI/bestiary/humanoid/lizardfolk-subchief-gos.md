---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/gos
- monster/cr/3
- monster/size/medium
- monster/type/humanoid/lizardfolk
aliases: ["Lizardfolk Subchief"]
---
# Lizardfolk Subchief
*Source: Ghosts of Saltmarsh p. 242, Storm Lord's Wrath*  

The lizardfolk subchief (seen in Danger at Dunwater) is a devout priest of Semuanya, pursuing the worship of its god in a manner similar to a cleric. It wields a dagger crafted of a massive crocodile tooth blessed by Semuanya, representing the subchief's prowess in both battle and piety.

```ad-statblock
title: Lizardfolk Subchief
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/GoS/Lizardfolk%20Subchief.webp#token)
*Medium humanoid (lizardfolk), Neutral*

- **Armor Class** 14 (natural armor)
- **Hit Points** 52 (`8d8 + 16`)
- **Speed** 30 ft., swim 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|14 (+2)|12 (+1)|14 (+2)|10 (+0)|16 (+3)|12 (+1)|

- **Proficiency Bonus** +2
- **Saving Throws** Wisdom +5
- **Skills** Athletics +4, Perception +5, Survival +5
- **Senses** passive Perception 15
- **Languages** Draconic
- **Challenge** 3

## Traits

***Hold Breath.*** The subchief can hold its breath for 15 minutes.

***Spellcasting.*** The subchief is a 5th-level spellcaster. Its spellcasting ability is Wisdom (spell save DC 13, `dice:1d20+5|noform|text(+5)` to hit with spell attacks). It has the following cleric spells prepared:

**Cantrips (at will)**: [light](2-Mechanics/CLI/spells/light.md), [sacred flame](2-Mechanics/CLI/spells/sacred-flame.md), [spare the dying](2-Mechanics/CLI/spells/spare-the-dying.md), [thaumaturgy](2-Mechanics/CLI/spells/thaumaturgy.md)

**1st level (4 slots)**: [command](2-Mechanics/CLI/spells/command.md), [guiding bolt](2-Mechanics/CLI/spells/guiding-bolt.md), [purify food and drink](2-Mechanics/CLI/spells/purify-food-and-drink.md)

**2nd level (3 slots)**: [hold person](2-Mechanics/CLI/spells/hold-person.md), [lesser restoration](2-Mechanics/CLI/spells/lesser-restoration.md), [silence](2-Mechanics/CLI/spells/silence.md)

**3rd level (2 slots)**: [bestow curse](2-Mechanics/CLI/spells/bestow-curse.md), [dispel magic](2-Mechanics/CLI/spells/dispel-magic.md)

## Actions

***Tooth Dagger.*** *Melee Weapon Attack:* `dice:1d20+4|noform|text(+4)` to hit, reach 5 ft., one target. *Hit:* `dice:1d4+2|noform|avg|text(4)` (`1d4 + 2`) piercing damage.

***Jaws of Semuanya (Recharge 5-6).*** The subchief invokes the primal magic of Semuanya, summoning a spectral maw around a target it can see within 60 feet of it. The target must make a DC 13 Dexterity saving throw, taking `dice:5d8|noform|avg|text(22)` (`5d8`) piercing damage on a failed save, or half as much damage on a successful one. A creature that fails this saving throw is also [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened) until the end of its next turn.
```
^statblock