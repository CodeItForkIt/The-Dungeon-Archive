---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/erlw
- monster/cr/11
- monster/size/large
- monster/type/celestial
aliases: ["Radiant Idol"]
---
# Radiant Idol
*Source: Eberron: Rising from the Last War p. 308*  

A radiant idol was an angel that was banished from the celestial realm of Syrania and cast down to the Material Plane. One sin led to their fall: the desire to be worshiped by mortals. Now in the mortal realm, most radiant idols gather cults of devoted followers.

## Fallen Angels

The insatiable hunger to be adored can transform a fallen angel, physically and mentally. In its true form, a radiant idol appears to be a warped angel. It might have bloody stumps in place of its wings, or its wings could be weighted down with chains representing its pride. A radiant idol uses [disguise self](2-Mechanics/CLI/spells/disguise-self.md) to hide its corruption, presenting an image of celestial glory.

## The Weight of Corruption

When a radiant idol achieves a sizable following through silvered words and demonstrations of power, its facade begins to crack, and a downward spiral ensues. As the radiant idol sinks deeper into the realm of material power, it begins twisting its followers, leading them ever deeper into ominous ritualism, hedonistic folly, and fanatical doom.

## Immortal Nature

A radiant idol doesn't require food, drink, or sleep.

## Statblock

```ad-statblock
title: Radiant Idol
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ERLW/Radiant%20Idol.webp#token)
*Large celestial, Lawful Evil*

- **Armor Class** 18 (natural armor)
- **Hit Points** 142 (`15d10 + 60`)
- **Speed** 40 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|23 (+6)|18 (+4)|19 (+4)|17 (+3)|20 (+5)|21 (+5)|

- **Proficiency Bonus** +4
- **Saving Throws** Wisdom +9, Charisma +9
- **Skills** Deception +9, Insight +9, Perception +9, Persuasion +9
- **Senses** darkvision 120 ft., passive Perception 19
- **Damage Resistances** radiant; bludgeoning, piercing, slashing from nonmagical attacks
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened)
- **Languages** all, telepathy 120 ft.
- **Challenge** 11

## Traits

***Aura of False Divinity.*** A creature that starts its turn within 30 feet of the radiant idol must make a DC 17 Wisdom saving throw, provided the radiant idol isn't [incapacitated](2-Mechanics/CLI/rules/conditions.md#Incapacitated). On a failed save, the creature is [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed) by the radiant idol. A creature [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed) in this way can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success. Once it succeeds on the saving throw, a creature is immune to this radiant idol's Aura of False Divinity for 24 hours.

***Magic Resistance.*** The radiant idol has advantage on saving throws against spells and other magical effects.

***Innate Spellcasting.*** The radiant idol's spellcasting ability is Charisma (spell save DC 17). The radiant idol can innately cast the following spells, requiring no material components:

**At will**: [charm person](2-Mechanics/CLI/spells/charm-person.md), [cure wounds](2-Mechanics/CLI/spells/cure-wounds.md), [disguise self](2-Mechanics/CLI/spells/disguise-self.md), [thaumaturgy](2-Mechanics/CLI/spells/thaumaturgy.md)

**1/day each**: [commune](2-Mechanics/CLI/spells/commune.md), [dominate person](2-Mechanics/CLI/spells/dominate-person.md), [insect plague](2-Mechanics/CLI/spells/insect-plague.md), [mass suggestion](2-Mechanics/CLI/spells/mass-suggestion.md), [raise dead](2-Mechanics/CLI/spells/raise-dead.md)

## Actions

***Multiattack.*** The radiant idol makes two melee attacks.

***Flail.*** *Melee Weapon Attack:* `dice:1d20+10|noform|text(+10)` to hit, reach 5 ft., one target. *Hit:* `dice:1d8+6|noform|avg|text(10)` (`1d8 + 6`) bludgeoning damage plus `dice:4d8|noform|avg|text(18)` (`4d8`) radiant damage.

***Radiant Strike (1/Day).*** The radiant idol chooses a point on the ground it can see within 60 feet of it. A 30-foot-radius, 40-foot-high cylinder of bright light appears there until the start of the radiant idol's next turn. Each creature in the cylinder when it appears or that ends its turn there must make a DC 17 Constitution saving throw, taking `dice:8d8|noform|avg|text(36)` (`8d8`) radiant damage on a failed save, or half as much damage on a successful one.
```
^statblock