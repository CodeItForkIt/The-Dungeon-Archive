---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/erlw
- monster/cr/19
- monster/size/medium
- monster/type/aberration
aliases: ["Kalaraq Quori"]
---
# Kalaraq Quori
*Source: Eberron: Rising from the Last War p. 306*  

The most powerful quori are the kalaraqs, also known as eyebinders—entities formed of pure shadow that is outlined by a nimbus of energy. A host of disembodied eyes whirl around a kalaraq, each reflecting a consciousness the creature has consumed.

Kalaraq quori guide the quori race, and the Devourer of Dreams—the personal emissary of the Dreaming Dark—is of this order. Although the kalaraqs never fight one another overtly, each has its own agenda, and each hopes to someday seize the throne of the Devourer of Dreams. Because of this internal conflict, it is unusual for a kalaraq to leave Dal Quor to inhabit a mortal vessel and become one of the Inspired.

Dal Quor is the plane of dreams and is currently dominated by a dark power known as il-Lashtavar, or the Dreaming Dark. Il-Lashtavar is served by a host of aberrations that are the embodiments of dreams and nightmares—the quori. Because it is difficult for anything to physically travel to or from Dal Quor, quori in Eberron are typically encountered while possessing a host body. The Inspired are the most common type of willing host for the quori and are described earlier in this chapter.

```ad-statblock
title: Kalaraq Quori
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ERLW/Kalaraq%20Quori.webp#token)
*Medium aberration, Lawful Evil*

- **Armor Class** 18 (natural armor)
- **Hit Points** 161 (`19d8 + 76`)
- **Speed** 30 ft., fly 60 ft. (hover)

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|12 (+1)|21 (+5)|18 (+4)|23 (+6)|24 (+7)|25 (+7)|

- **Proficiency Bonus** +6
- **Saving Throws** Intelligence +12, Wisdom +13, Charisma +13
- **Skills** Deception +13, Perception +13, Persuasion +13
- **Senses** truesight 120 ft., passive Perception 23
- **Damage Resistances** cold; necrotic; poison; psychic; bludgeoning, piercing, slashing from nonmagical attacks
- **Condition Immunities** [blinded](2-Mechanics/CLI/rules/conditions.md#Blinded), [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened), [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled), [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed), [petrified](2-Mechanics/CLI/rules/conditions.md#Petrified), [prone](2-Mechanics/CLI/rules/conditions.md#Prone), [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained)
- **Languages** all, telepathy 120 ft.
- **Challenge** 19

## Traits

***All-Around Vision.*** The quori can't be [surprised](2-Mechanics/CLI/rules/conditions.md#Surprised) while it isn't [incapacitated](2-Mechanics/CLI/rules/conditions.md#Incapacitated).

***Incorporeal Movement.*** The quori can move through other creatures and objects as if they were difficult terrain. It takes `dice:1d10|noform|avg|text(5)` (`1d10`) force damage if it ends its turn inside an object.

***Magic Resistance.*** The quori has advantage on saving throws against spells and other magical effects.

***Innate Spellcasting (Psionics).*** The quori's spellcasting ability is Charisma (spell save DC 21, `dice:1d20+13|noform|text(+13)` to hit with spell attacks). It can innately cast the following spells, requiring no components:

**At will**: [arcane eye](2-Mechanics/CLI/spells/arcane-eye.md)

**3/day each**: [clairvoyance](2-Mechanics/CLI/spells/clairvoyance.md), [confusion](2-Mechanics/CLI/spells/confusion.md), [dream](2-Mechanics/CLI/spells/dream.md), [eyebite](2-Mechanics/CLI/spells/eyebite.md)

## Actions

***Multiattack.*** The quori makes two Soul Binding attacks. Alternatively, it can make four attacks with Arcane Blast.

***Arcane Blast.*** *Ranged Spell Attack:* `dice:1d20+13|noform|text(+13)` to hit, range 120 ft., one target. *Hit:* `dice:1d10+7|noform|avg|text(12)` (`1d10 + 7`) force damage.

***Soul Binding.*** *Melee Spell Attack:* `dice:1d20+13|noform|text(+13)` to hit, reach 5 ft., one target. *Hit:* `dice:4d10+7|noform|avg|text(29)` (`4d10 + 7`) necrotic damage. A creature reduced to 0 hit points from this attack dies and has its soul imprisoned in one of the quori's eyes. The target can't be revived by any means short of a [wish](2-Mechanics/CLI/spells/wish.md) spell until the quori is destroyed.

***Mind Seed (1/Day).*** The quori touches one humanoid, which must succeed on a DC 21 Intelligence saving throw or be cursed. The curse lasts until it's removed by a remove curse or [greater restoration](2-Mechanics/CLI/spells/greater-restoration.md) spell.

The cursed target suffers 1 level of [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion) every 24 hours, and finishing a long rest doesn't reduce its [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion). If the cursed target reaches [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion) level 6, it doesn't die; it instead becomes a thrall under the quori's control, and all its [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion) is removed. Only the [wish](2-Mechanics/CLI/spells/wish.md) spell can free the thrall from this control.

***Swarm of Eyes (Recharge 6).*** The quori creates a swarm of spectral eyes that fills a 30-foot-radius sphere centered on a point it can see within 60 feet of it. Each creature in that area must make a DC 21 Wisdom saving throw. On a failure, a creature takes `dice:10d8|noform|avg|text(45)` (`10d8`) psychic damage, and it is [blinded](2-Mechanics/CLI/rules/conditions.md#Blinded) for 1 minute. On a success, a creature takes half as much damage and isn't [blinded](2-Mechanics/CLI/rules/conditions.md#Blinded). A [blinded](2-Mechanics/CLI/rules/conditions.md#Blinded) creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.

***Possession (Recharge 6).*** One humanoid that the quori can see within 5 feet of it must succeed on a DC 21 Charisma saving throw or be possessed by the quori; the quori then disappears, and the target is [incapacitated](2-Mechanics/CLI/rules/conditions.md#Incapacitated) and loses control of its body. The quori now controls the body but doesn't deprive the target of awareness. The quori can't be targeted by any attack, spell, or other effect, and it retains its alignment, Intelligence, Wisdom, Charisma, and immunity to being [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed) and [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened). It otherwise uses the possessed target's statistics, but doesn't gain access to the target's knowledge, class features, or proficiencies.

The possession lasts until the body drops to 0 hit points, the quori ends it as a bonus action, or the quori is forced out by an effect like the [dispel evil and good](2-Mechanics/CLI/spells/dispel-evil-and-good.md) spell. When the possession ends, the quori reappears in an unoccupied space within 5 feet of the body. The target is immune to this quori's Possession for 24 hours after succeeding on the saving throw or after the possession ends.
```
^statblock