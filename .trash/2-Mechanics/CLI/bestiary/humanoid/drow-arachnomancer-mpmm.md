---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/mpmm
- monster/cr/13
- monster/environment/underdark
- monster/size/medium
- monster/type/humanoid/elf
aliases: ["Drow Arachnomancer"]
---
# Drow Arachnomancer
*Source: Mordenkainen Presents: Monsters of the Multiverse p. 99, Mordenkainen's Tome of Foes p. 182*  

Drow spellcasters who seek to devote themselves wholly to Lolth, the Spider Queen, sometimes walk the sinister path of the arachnomancer. By offering up body and soul to Lolth, they gain tremendous power and a supernatural connection to the ancient spiders of the Demonweb Pits, channeling magic from that dread place.

```ad-statblock
title: Drow Arachnomancer
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/MPMM/Drow%20Arachnomancer.webp#token)
*Medium humanoid (elf), Typically  Chaotic Evil*

- **Armor Class** 15 ([studded leather](2-Mechanics/CLI/items/studded-leather-armor.md))
- **Hit Points** 162 (`25d8 + 50`)
- **Speed** 30 ft., climb 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|11 (+0)|17 (+3)|14 (+2)|19 (+4)|14 (+2)|16 (+3)|

- **Proficiency Bonus** +5
- **Saving Throws** Constitution +7, Intelligence +9, Charisma +8
- **Skills** Arcana +9, Nature +9, Perception +7, Stealth +8
- **Senses** blindsight 10 ft., darkvision 120 ft., passive Perception 17
- **Damage Resistances** poison
- **Languages** Elvish, Undercommon, can speak with spiders
- **Challenge** 13

## Traits

***Fey Ancestry.*** The drow has advantage on saving throws against being [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), and magic can't put the drow to sleep.

***Spider Climb.*** The drow can climb difficult surfaces, including upside down on ceilings, without needing to make an ability check.

***Sunlight Sensitivity.*** While in sunlight, the drow has disadvantage on attack rolls, as well as on Wisdom ([Perception](2-Mechanics/CLI/rules/skills.md#Perception)) checks that rely on sight.

***Web Walker.*** The drow ignores movement restrictions caused by webbing.

***Spellcasting.*** The drow casts one of the following spells, requiring no material components and using Intelligence as the spellcasting ability (spell save DC 17):

**At will**: [dancing lights](2-Mechanics/CLI/spells/dancing-lights.md), [mage hand](2-Mechanics/CLI/spells/mage-hand.md)

**1/day each**: [darkness](2-Mechanics/CLI/spells/darkness.md), [dispel magic](2-Mechanics/CLI/spells/dispel-magic.md), [etherealness](2-Mechanics/CLI/spells/etherealness.md), [faerie fire](2-Mechanics/CLI/spells/faerie-fire.md), [fly](2-Mechanics/CLI/spells/fly.md), [insect plague](2-Mechanics/CLI/spells/insect-plague.md), [invisibility](2-Mechanics/CLI/spells/invisibility.md)

## Actions

***Multiattack.*** The drow makes three attacks, using Bite, Poisonous Touch, Web, or a combination of them. One attack can be replaced by a use of Spellcasting.

***Bite (Spider Form Only).*** *Melee Weapon Attack:* `dice:1d20+8|noform|text(+8)` to hit, reach 5 ft., one target. *Hit:* `dice:2d8+3|noform|avg|text(12)` (`2d8 + 3`) piercing damage, and the target must make a DC 15 Constitution saving throw, taking `dice:7d8|noform|avg|text(31)` (`7d8`) poison damage on a failed save, or half as much damage on a successful one. If the poison damage reduces the target to 0 hit points, the target is stable but [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned) for 1 hour, even after regaining hit points, and is [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed) while [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned) in this way.

***Poisonous Touch (Humanoid Form Only).*** *Melee Weapon Attack:* `dice:1d20+8|noform|text(+8)` to hit, reach 5 ft., one target. *Hit:* `dice:10d6|noform|avg|text(35)` (`10d6`) poison damage.

***Web (Spider Form Only; (Recharge 5-6)).*** *Ranged Weapon Attack:* `dice:1d20+8|noform|text(+8)` to hit, range 30/60 ft., one target. *Hit:* The target is [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained) by webbing. As an action, the [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained) target can make a DC 15 Strength check, bursting the webbing on a success. The webbing can also be attacked and destroyed (AC 10; hp 5; vulnerability to fire damage; immunity to bludgeoning, poison, and psychic damage).

## Bonus Actions

***Change Shape (Recharges after a Short or Long Rest).*** The drow magically transforms into a Large spider, remaining in that form for up to 1 hour, or back into its true form. Its statistics, other than its size, are the same in each form. It can speak and cast spells while in spider form. Any equipment it is wearing or carrying in Humanoid form melds into the spider form. It can't activate, use, wield, or otherwise benefit from any of its equipment. It reverts to its Humanoid form if it dies.
```
^statblock

## Environment

underdark