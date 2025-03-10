---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/mpmm
- monster/cr/6
- monster/environment/arctic
- monster/environment/hill
- monster/environment/mountain
- monster/environment/underdark
- monster/environment/urban
- monster/size/medium
- monster/type/humanoid
aliases: ["Warlock of the Great Old One"]
---
# Warlock of the Great Old One
*Source: Mordenkainen Presents: Monsters of the Multiverse p. 256*  

Warlocks of the Great Old One gain their powers through magical pacts forged with eldritch entities from strange and distant realms of existence. Some of these warlocks associate with cultists devoted to these entities, as well as Aberrations that share their goals, yet other warlocks of the Great Old One are experts at rooting out the chaos and wickedness inspired by bizarre beings from beyond the stars.

## Warlocks

Warlocks gain arcane might through magical pacts with mysterious entities. While some use their abilities to serve the sources of their power, others use them to undermine or even destroy these entities.

## Statblock

```ad-statblock
title: Warlock of the Great Old One
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/MPMM/Warlock%20of%20the%20Great%20Old%20One.webp#token)
*Medium humanoid, Any alignment*

- **Armor Class** 13 (16 with [mage armor](2-Mechanics/CLI/spells/mage-armor.md))
- **Hit Points** 91 (`14d8 + 28`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
| 9 (-1)|16 (+3)|15 (+2)|12 (+1)|12 (+1)|18 (+4)|

- **Proficiency Bonus** +3
- **Saving Throws** Wisdom +4, Charisma +7
- **Skills** Arcana +4, History +4
- **Senses** darkvision 60 ft., passive Perception 11
- **Damage Resistances** psychic
- **Languages** any two languages, telepathy 30 ft.
- **Challenge** 6

## Traits

***Whispering Aura.*** At the start of each of the warlock's turns, each creature of its choice within 10 feet of it must succeed on a DC 15 Wisdom saving throw or take `dice:3d6|noform|avg|text(10)` (`3d6`) psychic damage, provided that the warlock isn't [incapacitated](2-Mechanics/CLI/rules/conditions.md#Incapacitated).

***Spellcasting.*** The warlock casts one of the following spells, using Charisma as the spellcasting ability (spell save DC 15): 

**At will**: [detect magic](2-Mechanics/CLI/spells/detect-magic.md), [guidance](2-Mechanics/CLI/spells/guidance.md), [levitate](2-Mechanics/CLI/spells/levitate.md), [mage armor](2-Mechanics/CLI/spells/mage-armor.md) (self only), [mage hand](2-Mechanics/CLI/spells/mage-hand.md), [minor illusion](2-Mechanics/CLI/spells/minor-illusion.md), [prestidigitation](2-Mechanics/CLI/spells/prestidigitation.md)

**1/day each**: [arcane gate](2-Mechanics/CLI/spells/arcane-gate.md), [detect thoughts](2-Mechanics/CLI/spells/detect-thoughts.md), [true seeing](2-Mechanics/CLI/spells/true-seeing.md)

## Actions

***Multiattack.*** The warlock makes two Dagger attacks.

***Dagger.*** *Melee or Ranged Weapon Attack:* `dice:1d20+6|noform|text(+6)` to hit, reach 5 ft. or range 20/60 ft., one target. *Hit:* `dice:1d4+3|noform|avg|text(5)` (`1d4 + 3`) piercing damage plus `dice:3d6|noform|avg|text(10)` (`3d6`) psychic damage.

***Howling Void.*** The warlock opens a momentary extraplanar rift within 60 feet of it. The rift is a scream-filled, 20-foot cube. Each creature in that area must make a DC 15 Wisdom saving throw. On a failed save, a creature takes `dice:2d8|noform|avg|text(9)` (`2d8`) psychic damage and is [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened) of the warlock until the start of the warlock's next turn. On a successful save, a creature takes half as much damage and isn't [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened).
```
^statblock

## Environment

arctic, hill, mountain, underdark, urban