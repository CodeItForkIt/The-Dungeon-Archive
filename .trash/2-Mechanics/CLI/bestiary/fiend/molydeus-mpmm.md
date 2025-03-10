---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/mpmm
- monster/cr/21
- monster/size/huge
- monster/type/fiend/demon
aliases: ["Molydeus"]
---
# Molydeus
*Source: Mordenkainen Presents: Monsters of the Multiverse p. 184, Mordenkainen's Tome of Foes p. 134*  

The fearsome molydeus speaks for the demon lord it serves and enforces its master's will. This demon is 12 feet tall, and its bipedal body has a slavering wolfs head and a fanged serpent's head. Its demon lord can speak and see through the serpent head; this master also uses the molydeus to guard treasures, slay foes, and terrify troops into obedience.

A molydeus's demon lord bestows on it a powerful weapon that dissolves if the molydeus dies. The weapon's form varies depending on the creator, but that doesn't affect the weapon's capabilities.

```ad-statblock
title: Molydeus
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/MPMM/Molydeus.webp#token)
*Huge fiend (demon), Typically  Chaotic Evil*

- **Armor Class** 19 (natural armor)
- **Hit Points** 216 (`16d12 + 112`)
- **Speed** 40 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|28 (+9)|22 (+6)|25 (+7)|21 (+5)|24 (+7)|24 (+7)|

- **Proficiency Bonus** +7
- **Saving Throws** Strength +16, Constitution +14, Wisdom +14, Charisma +14
- **Skills** Perception +21
- **Senses** truesight 120 ft., passive Perception 31
- **Damage Resistances** cold; fire; lightning; bludgeoning, piercing, slashing from nonmagical attacks
- **Damage Immunities** poison
- **Condition Immunities** [blinded](2-Mechanics/CLI/rules/conditions.md#Blinded), [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [deafened](2-Mechanics/CLI/rules/conditions.md#Deafened), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned), [stunned](2-Mechanics/CLI/rules/conditions.md#Stunned)
- **Languages** Abyssal, telepathy 120 ft.
- **Challenge** 21

## Traits

***Legendary Resistance (3/Day).*** If the molydeus fails a saving throw, it can choose to succeed instead.

***Magic Resistance.*** The molydeus has advantage on saving throws against spells and other magical effects.

***Spellcasting.*** The molydeus casts one of the following spells, requiring no material components and using Charisma as the spellcasting ability (spell save DC 22):

**At will**: [dispel magic](2-Mechanics/CLI/spells/dispel-magic.md), [polymorph](2-Mechanics/CLI/spells/polymorph.md), [telekinesis](2-Mechanics/CLI/spells/telekinesis.md), [teleport](2-Mechanics/CLI/spells/teleport.md)

**3/day**: [lightning bolt](2-Mechanics/CLI/spells/lightning-bolt.md)

## Actions

***Multiattack.*** The molydeus makes one Demonic Weapon attack, one Snakebite attack, and one Wolf Bite attack.

***Demonic Weapon.*** *Melee Weapon Attack:* `dice:1d20+16|noform|text(+16)` to hit, reach 15 ft., one target. *Hit:* `dice:4d12+9|noform|avg|text(35)` (`4d12 + 9`) force damage. If the target has at least one head and the molydeus rolled a 20 on the attack roll, the target is decapitated and dies if it can't survive without that head. A target is immune to this effect if it takes none of the damage, has legendary actions, or is Huge or larger. Such a creature takes an extra `dice:6d8|noform|avg|text(27)` (`6d8`) force damage from the hit.

***Snakebite.*** *Melee Weapon Attack:* `dice:1d20+16|noform|text(+16)` to hit, reach 15 ft., one creature. *Hit:* `dice:2d6+9|noform|avg|text(16)` (`2d6 + 9`) poison damage. The target must succeed on a DC 22 Constitution saving throw, or its hit point maximum is reduced by an amount equal to the damage taken. This reduction lasts until the target finishes a long rest. The target transforms into a [manes](2-Mechanics/CLI/bestiary/fiend/manes.md) if this reduces its hit point maximum to 0. This transformation can be ended only by a [wish](2-Mechanics/CLI/spells/wish.md) spell.

***Wolf Bite.*** *Melee Weapon Attack:* `dice:1d20+16|noform|text(+16)` to hit, reach 10 ft., one target. *Hit:* `dice:3d10+9|noform|avg|text(25)` (`3d10 + 9`) necrotic damage.

## Legendary Actions

***Attack.*** The molydeus makes one Demonic Weapon or Snakebite attack.

***Move.*** The molydeus moves without provoking opportunity attacks.

***Cast a Spell (Costs 2 Actions).*** The molydeus uses Spellcasting.
```
^statblock