---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/mpp
- monster/cr/14
- monster/size/medium
- monster/type/fiend/yugoloth
aliases: ["Shemeshka"]
---
# Shemeshka
*Source: Morte's Planar Parade p. 46, Sigil and the Outlands, Turn of Fortune's Wheel*  

Shemeshka the arcanaloth is one of Sigil's most ambitious and notorious crime bosses. From her multiplanar casino, Fortune's Wheel, she manipulates secrets and fates across the planes. Shemeshka and her plots are further detailed in the adventure*Turn of Fortune's Wheel*.

```ad-statblock
title: Shemeshka
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/MPP/Shemeshka.webp#token)
*Medium fiend (yugoloth), Neutral Evil*

- **Armor Class** 17 (natural armor)
- **Hit Points** 162 (`25d8 + 50`)
- **Speed** 30 ft., fly 30 ft. (hover)

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|20 (+5)|14 (+2)|14 (+2)|21 (+5)|16 (+3)|18 (+4)|

- **Proficiency Bonus** +5
- **Saving Throws** Dexterity +7, Intelligence +10, Wisdom +8, Charisma +9
- **Skills** Deception +9, Insight +8, Perception +8
- **Senses** truesight 120 ft., passive Perception 18
- **Damage Resistances** cold; fire; lightning; bludgeoning, piercing, slashing from nonmagical attacks
- **Damage Immunities** acid, poison
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** all, telepathy 120 ft.
- **Challenge** 14

## Traits

***Legendary Resistance (4/Day).*** If Shemeshka fails a saving throw, she can choose to succeed instead.

***Magic Resistance.*** Shemeshka has advantage on saving throws against spells and other magical effects.

***Special Equipment.*** Shemeshka carries a magic crown called the Razorvine Tiara. In the hands of anyone other than Shemeshka, the Razorvine Tiara functions as a [tentacle rod](2-Mechanics/CLI/items/tentacle-rod.md) that deals slashing damage instead of bludgeoning damage.

***Spellcasting.*** Shemeshka casts one of the following spells, requiring no material components and using Intelligence as the spellcasting ability (spell save DC 18):

**At will**: [alter self](2-Mechanics/CLI/spells/alter-self.md), [darkness](2-Mechanics/CLI/spells/darkness.md), [invisibility](2-Mechanics/CLI/spells/invisibility.md) (self only), [mage hand](2-Mechanics/CLI/spells/mage-hand.md), [prestidigitation](2-Mechanics/CLI/spells/prestidigitation.md)

**1/day each**: [banishment](2-Mechanics/CLI/spells/banishment.md), [contact other plane](2-Mechanics/CLI/spells/contact-other-plane.md) (as an action), [mind blank](2-Mechanics/CLI/spells/mind-blank.md)

**2/day each**: [detect thoughts](2-Mechanics/CLI/spells/detect-thoughts.md), [dimension door](2-Mechanics/CLI/spells/dimension-door.md), [suggestion](2-Mechanics/CLI/spells/suggestion.md)

## Actions

***Multiattack.*** Shemeshka uses Arcane Flux or Spellcasting. She then makes one Claw attack or one attack with her Razorvine Tiara.

***Arcane Flux.*** Shemeshka causes a surge of arcane energy to burst around one creature she can see within 120 feet of herself. The target must make a DC 18 Dexterity saving throw. On a failed save, the target takes `dice:7d12|noform|avg|text(45)` (`7d12`) force damage and has the [incapacitated](2-Mechanics/CLI/rules/conditions.md#Incapacitated) condition until the end of its next turn. On a successful save, the target takes half as much damage only.

***Claw.*** *Melee Weapon Attack:* `dice:1d20+10|noform|text(+10)` to hit, reach 5 ft., one target. *Hit:* `dice:2d4+5|noform|avg|text(10)` (`2d4 + 5`) slashing damage plus `dice:4d6|noform|avg|text(14)` (`4d6`) poison damage.

***Razorvine Tiara.*** *Melee Weapon Attack:* `dice:1d20+10|noform|text(+10)` to hit, reach 15 ft., one target. *Hit:* `dice:3d6|noform|avg|text(10)` (`3d6`) slashing damage plus `dice:2d8|noform|avg|text(9)` (`2d8`) necrotic damage. If the target is a creature, it must succeed on a DC 15 Constitution saving throw, or its speed is halved and it has disadvantage on attack rolls and saving throws until the end of its next turn.

## Bonus Actions

***Teleport.*** Shemeshka teleports, along with any equipment she is wearing or carrying, up to 60 feet to an unoccupied space she can see.

## Reactions

***Fell Counterspell (3/Day).*** Shemeshka utters a magical word to interrupt a creature she can see that is casting a spell. If the spell is 5th level or lower, it fails and has no effect. If the spell is 6th level or higher, Shemeshka makes an Intelligence check (DC 10 + the spell's level). On a success, the spell fails and has no effect. Whatever the spell's level, the caster gains the [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned) condition until the end of its next turn.
```
^statblock