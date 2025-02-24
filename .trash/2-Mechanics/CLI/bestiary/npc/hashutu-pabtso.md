---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/pabtso
- monster/cr/11
- monster/size/medium
- monster/type/aberration
aliases: ["Hashutu"]
---
# Hashutu
*Source: Phandelver and Below: The Shattered Obelisk p. 194*  

```ad-statblock
title: Hashutu
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/PaBTSO/Hashutu.webp#token)
*Medium aberration, typically  Lawful Evil*

- **Armor Class** 15 ([breastplate](2-Mechanics/CLI/items/breastplate.md))
- **Hit Points** 156 (`24d8 + 48`)
- **Speed** 30 ft., fly 60 ft. (hover)

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|11 (+0)|12 (+1)|15 (+2)|21 (+5)|17 (+3)|18 (+4)|

- **Proficiency Bonus** +4
- **Saving Throws** Intelligence +9, Wisdom +7, Charisma +8
- **Skills** Arcana +9, Insight +7, Perception +7, Stealth +5
- **Senses** blindsight 60 ft., darkvision 120 ft., truesight 15 ft., passive Perception 17
- **Damage Resistances** psychic
- **Condition Immunities** [blinded](2-Mechanics/CLI/rules/conditions.md#Blinded), [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened)
- **Languages** Deep Speech, telepathy 120 ft., Undercommon
- **Challenge** 11

## Traits

***Legendary Resistance (3/Day).*** If Hashutu fails a saving throw, it can choose to succeed instead.

***Magic Resistance.*** Hashutu has advantage on saving throws against spells and other magical effects.

***Spellcasting (Psionics).*** Hashutu casts one of the following spells, requiring no spell components and using Intelligence as the spellcasting ability (spell save DC 17):

**At will**: [detect magic](2-Mechanics/CLI/spells/detect-magic.md), [detect thoughts](2-Mechanics/CLI/spells/detect-thoughts.md), [mage hand](2-Mechanics/CLI/spells/mage-hand.md) (the hand is invisible)

**1/day**: [plane shift](2-Mechanics/CLI/spells/plane-shift.md) (self only)

**3/day each**: [clairvoyance](2-Mechanics/CLI/spells/clairvoyance.md) (as an action), [dispel magic](2-Mechanics/CLI/spells/dispel-magic.md)

## Actions

***Multiattack.*** Hashutu makes two Tentacle attacks.

***Tentacle.*** *Melee Weapon Attack:* `dice:1d20+9|noform|text(+9)` to hit, reach 5 ft., one creature. *Hit:* `dice:3d10+5|noform|avg|text(21)` (`3d10 + 5`) psychic damage. If the target is Medium or smaller, it has the [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) condition (escape DC 17) and must succeed on a DC 17 Intelligence saving throw or have the [incapacitated](2-Mechanics/CLI/rules/conditions.md#Incapacitated) condition until the grapple ends.

***Extract Brain.*** *Melee Weapon Attack:* `dice:1d20+9|noform|text(+9)` to hit, reach 5 ft., one [incapacitated](2-Mechanics/CLI/rules/conditions.md#Incapacitated) Humanoid [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) by Hashutu. *Hit:* `dice:10d10|noform|avg|text(55)` (`10d10`) piercing damage. If this damage reduces the target to 0 hit points, Hashutu kills it by extracting and devouring its brain.

***Unleash Void (Recharge 5-6).*** Hashutu opens a rift into the Far Realm, centered on a point Hashutu can see within 60 feet of itself, and a tentacle lashes across creatures near the rift. Each creature other than mind flayers within 30 feet of the rift must make a DC 17 Intelligence saving throw, after which the tentacle disappears and the rift closes. On a failed save, a creature takes `dice:4d8|noform|avg|text(18)` (`4d8`) cold damage from the rift plus `dice:4d8|noform|avg|text(18)` (`4d8`) psychic damage from the tentacle and has the [stunned](2-Mechanics/CLI/rules/conditions.md#Stunned) condition for 1 minute. On a successful save, a creature takes half as much damage only. A [stunned](2-Mechanics/CLI/rules/conditions.md#Stunned) creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.

## Reactions

***Warp Reality.*** When hit by an attack roll, Hashutu gains a +4 bonus to its AC against that attack roll, potentially causing it to miss. Then Hashutu, along with any equipment it is wearing or carrying, magically teleports up to 60 feet to an unoccupied space it can see.
```
^statblock