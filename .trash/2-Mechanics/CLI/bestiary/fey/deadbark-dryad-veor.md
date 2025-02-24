---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/veor
- monster/cr/13
- monster/size/medium
- monster/type/fey
aliases: ["Deadbark Dryad"]
---
# Deadbark Dryad
*Source: Vecna: Eve of Ruin p. 216*  

When a dryad fails to protect its wilderness home from a great evil and is unable to forgive itself, the dryad might transform into a wicked Fey monster called a deadbark dryad. Such dryads relinquish any compassion they once felt for living beings and instead harbor hatred for anyone who dares to invade their rotted demesne.

The wilds around a deadbark dryad become malignant, souring into a swampy morass of stinging nettles and noxious muck. Deadbark dryads are immune to this toxic bog's deleterious effects.

A deadbark dryad is typically bound to the spot where it failed to protect its charge. When a dryad transforms into a deadbark dryad, it becomes stronger and more violent, and it typically gains a renewed dedication to protecting its now-fetid domain. Most deadbark dryads would rather fight to the death than allow any intrusion into their homes.

Deadbark dryads are most often found on Krynn, but occasionally they are found on other worlds where magic and trees are plentiful.

```ad-statblock
title: Deadbark Dryad
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/VEoR/Deadbark%20Dryad.webp#token)
*Medium fey, typically  Chaotic Evil*

- **Armor Class** 16 (natural armor)
- **Hit Points** 187 (`22d8 + 88`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|17 (+3)|16 (+3)|18 (+4)|11 (+0)|16 (+3)|18 (+4)|

- **Proficiency Bonus** +5
- **Saving Throws** Constitution +9, Charisma +9
- **Skills** Perception +8, Stealth +8
- **Senses** darkvision 60 ft., passive Perception 18
- **Damage Resistances** bludgeoning, piercing, slashing from nonmagical attacks
- **Damage Immunities** poison
- **Condition Immunities** [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** Elvish, Sylvan
- **Challenge** 13

## Traits

***Bramble Walk.*** Difficult terrain composed of vegetation, such as foliage or thorns, doesn't cost the dryad extra movement.

***Magic Resistance.*** The dryad has advantage on saving throws against spells and other magical effects.

***Speak with Beasts and Plants.*** The dryad can communicate with Beasts and Plants as if they shared a language.

***Spellcasting.*** The dryad casts one of the following spells, requiring no material components and using Charisma as the spellcasting ability (spell save DC 17):

**At will**: [Druidcraft](2-Mechanics/CLI/spells/druidcraft.md)

**1/day**: [Dispel Magic](2-Mechanics/CLI/spells/dispel-magic.md)

**2/day each**: [Pass without Trace](2-Mechanics/CLI/spells/pass-without-trace.md), [Spike Growth](2-Mechanics/CLI/spells/spike-growth.md)

## Actions

***Multiattack.*** The dryad makes two Poisonous Thorn attacks and one Sapping Vine attack.

***Poisonous Thorn.*** *Melee or Ranged Weapon Attack:* `dice:1d20+8|noform|text(+8)` to hit, reach 5 ft. or range 120 ft., one target. *Hit:* `dice:4d4+3|noform|avg|text(13)` (`4d4 + 3`) piercing damage plus `dice:3d6|noform|avg|text(10)` (`3d6`) poison damage. If the target is a creature, it must succeed on a DC 17 Constitution saving throw or have the [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned) condition until the start of the dryad's next turn.

***Sapping Vine.*** *Melee Weapon Attack:* `dice:1d20+8|noform|text(+8)` to hit, reach 30 ft., one target. *Hit:* The target has the [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) condition (escape DC 16). Until the grapple ends, the target has the [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained) condition, and the dryad can't use the same vine on another target. A creature [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained) in this way takes `dice:3d8|noform|avg|text(13)` (`3d8`) necrotic damage at the start of its turn.

The dryad has six vines. Each vine can be attacked (AC 20; 10 hit points; immunity to poison and psychic damage). Destroying a vine deals no damage to the dryad, but any creature [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) by that vine no longer has the [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) condition. All vines immediately wither and disappear when the dryad is reduced to 0 hit points.
```
^statblock