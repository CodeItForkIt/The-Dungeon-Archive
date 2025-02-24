---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/toa
- monster/cr/8
- monster/size/medium
- monster/type/humanoid/half-dragon
aliases: ["Zindar"]
---
# Zindar
*Source: Tomb of Annihilation p. 239*  

This half-gold dragon runs Port Nyanzaru's docks and keeps track of ship manifests. A sorcerer of impressive ability, Zindar is well paid by the merchant princes for his work. He is also a key member of the Ytepka Society and a great source of information about the city. Zindar has a soft spot for adventurers, but he knows the dangers of Chult well enough to understand that most of those who embark on expeditions to explore the jungle never return.

Zindar makes extensive use of spells in his day-today work, casting message to deliver missives to dock workers, detect thoughts for reading ship captains' minds, knock for unsealing containers for inspection, clairvoyance for peering into ship holds, dominate beast to pacify nervous animals, and so forth.

## Zindar's Traits

### Ideal

"I take pride in my work, and I like to keep all my business dealings honest."

### Bond

"Port Nyanzaru is my home. I take a dim view of those who would bring harm to the city and its inhabitants."

### Flaw

"I don't get mad. I get even."

## Statblock

```ad-statblock
title: Zindar
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ToA/Zindar.webp#token)
*Medium humanoid (half-dragon), Lawful Good*

- **Armor Class** 13 (natural armor)
- **Hit Points** 110 (`17d8 + 34`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|14 (+2)|10 (+0)|14 (+2)|16 (+3)|15 (+2)|18 (+4)|

- **Proficiency Bonus** +3
- **Saving Throws** Constitution +5, Wisdom +5
- **Skills** Arcana +6, History +9, Insight +5, Investigation +9
- **Senses** blindsight 10 ft., darkvision 60 ft., passive Perception 12
- **Damage Resistances** fire
- **Languages** Common, Draconic, Dwarvish, Primordial
- **Challenge** 8

## Traits

***Dragon Wings.*** As a bonus action on his turn, Zindar can sprout a pair of dragon wings from his back, gaining a flying speed of 30 feet until he dismisses them as a bonus action.

***Spellcasting.*** Zindar is a 14th-level spellcaster. His spellcasting ability is Charisma (spell save DC 15, `dice:1d20+7|noform|text(+7)` to hit with spell attacks). Zindar knows the following sorcerer spells:

**Cantrips (at will)**: [fire bolt](2-Mechanics/CLI/spells/fire-bolt.md), [friends](2-Mechanics/CLI/spells/friends.md), [light](2-Mechanics/CLI/spells/light.md), [mage hand](2-Mechanics/CLI/spells/mage-hand.md), [mending](2-Mechanics/CLI/spells/mending.md), [message](2-Mechanics/CLI/spells/message.md)

**1st level (6 slots)**: [magic missile](2-Mechanics/CLI/spells/magic-missile.md), [shield](2-Mechanics/CLI/spells/shield.md), [sleep](2-Mechanics/CLI/spells/sleep.md)

**2nd level (4 slots)**: [detect thoughts](2-Mechanics/CLI/spells/detect-thoughts.md), [knock](2-Mechanics/CLI/spells/knock.md)

**3rd level (3 slots)**: [clairvoyance](2-Mechanics/CLI/spells/clairvoyance.md), [tongues](2-Mechanics/CLI/spells/tongues.md)

**4th level (3 slots)**: [dominate beast](2-Mechanics/CLI/spells/dominate-beast.md), [stoneskin](2-Mechanics/CLI/spells/stoneskin.md)

**5th level (3 slots)**: [hold monster](2-Mechanics/CLI/spells/hold-monster.md), [telekinesis](2-Mechanics/CLI/spells/telekinesis.md)

**6th level (1 slots)**: [true seeing](2-Mechanics/CLI/spells/true-seeing.md)

**7th level (1 slots)**: [fire storm](2-Mechanics/CLI/spells/fire-storm.md)

## Actions

***Quarterstaff.*** *Melee Weapon Attack:* `dice:1d20+5|noform|text(+5)` to hit, reach 5 ft., one target. *Hit:* `dice:1d6+2|noform|avg|text(5)` (`1d6 + 2`) bludgeoning damage, or `dice:1d8+2|noform|avg|text(6)` (`1d8 + 2`) bludgeoning damage when used with two hands.

***Breath Weapon (Recharge 5-6).*** Zindar uses one of the following options:

***Fire Breath.*** Zindar exhales fire in a 15-foot cone. Each creature in that area must make a DC 15 Dexterity saving throw, taking `dice:4d10|noform|avg|text(22)` (`4d10`) fire damage on a failed save, or half as much damage on a successful one.

***Weakening Breath.*** Zindar exhales gas in a 15-foot cone. Each creature in that area must succeed on a DC 15 Strength saving throw or have disadvantage on Strength-based attack rolls, Strength checks, and Strength saving throws for 1 minute. A creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.
```
^statblock