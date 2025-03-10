---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/erlw
- monster/cr/9
- monster/size/medium
- monster/type/aberration
aliases: ["Hashalaq Quori"]
---
# Hashalaq Quori
*Source: Eberron: Rising from the Last War p. 305*  

Hashalaq quori are loremasters and judges, and are commonly known as dreamstealers. In their natural form, hashalaqs are composed of hundreds of translucent tendrils. They can compress and configure these tendrils to form a wide range of simple shapes. A point of blue light suspended within its tendrils serves as the hashalaq's sensory organ, which can be moved around to suit the creature's current shape.

## The Power of Pleasure

Hashalaq quori have studied their mortal prey for centuries. Inhabiting human bodies as Inspired has granted the hashalaq a deep understanding of the hedonistic urges of humanity. As a result, they have developed numerous ways to control humanoids through pleasure—even as they have developed a taste for such things themselves.

## The Learned of Dal Quor

Hashalaq quori are the loremasters of Dal Quor. Even those hashalaqs who don't make use of Inspired vessels dedicate themselves to studying Eberron and the planes, and they are among the few quori castes whose members understand the ways of magic. In Dal Quor, the hashalaq quori are typically found as advisors to the kalaraq. They also serve as judges, policing the quori and ensuring that the rivalries of the tsucora never threaten the greater plans of the Dreaming Dark.

Dal Quor is the plane of dreams and is currently dominated by a dark power known as il-Lashtavar, or the Dreaming Dark. Il-Lashtavar is served by a host of aberrations that are the embodiments of dreams and nightmares—the quori. Because it is difficult for anything to physically travel to or from Dal Quor, quori in Eberron are typically encountered while possessing a host body. The Inspired are the most common type of willing host for the quori and are described earlier in this chapter.

## Statblock

```ad-statblock
title: Hashalaq Quori
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ERLW/Hashalaq%20Quori.webp#token)
*Medium aberration, Lawful Evil*

- **Armor Class** 17 (natural armor)
- **Hit Points** 99 (`18d8 + 18`)
- **Speed** 40 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|12 (+1)|14 (+2)|13 (+1)|18 (+4)|16 (+3)|18 (+4)|

- **Proficiency Bonus** +4
- **Saving Throws** Wisdom +7, Charisma +8
- **Skills** Arcana +12, History +12, Insight +11, Persuasion +8
- **Senses** darkvision 60 ft., passive Perception 13
- **Damage Resistances** psychic
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened)
- **Languages** Common, Quori
- **Challenge** 9

***Innate Spellcasting (Psionics).*** The quori's spellcasting ability is Intelligence (spell save DC 16). It can innately cast the following spells, requiring no components:

**At will**: [charm person](2-Mechanics/CLI/spells/charm-person.md)

**1/day**: [dominate person](2-Mechanics/CLI/spells/dominate-person.md), [dream](2-Mechanics/CLI/spells/dream.md)

**3/day each**: [detect thoughts](2-Mechanics/CLI/spells/detect-thoughts.md), [disguise self](2-Mechanics/CLI/spells/disguise-self.md), [suggestion](2-Mechanics/CLI/spells/suggestion.md)

## Actions

***Multiattack.*** The quori uses its Mind Thrust twice.

***Idyllic Touch.*** *Melee Spell Attack:* `dice:1d20+8|noform|text(+8)` to hit, reach 5 ft., one target. *Hit:* `dice:1d10+4|noform|avg|text(9)` (`1d10 + 4`) force damage. If the target is a creature, it must succeed on a DC 16 Wisdom saving throw or fall [prone](2-Mechanics/CLI/rules/conditions.md#Prone) in a fit of laughter.

***Mind Thrust.*** The quori targets a creature it can see within 60 feet of it. The target must make a DC 16 Wisdom saving throw, taking `dice:4d8|noform|avg|text(18)` (`4d8`) psychic damage on a failed save, or half as much damage on a successful one.

***Possession (Recharge 6).*** One humanoid that the quori can see within 5 feet of it must succeed on a DC 16 Charisma saving throw or be possessed by the quori; the quori then disappears, and the target is [incapacitated](2-Mechanics/CLI/rules/conditions.md#Incapacitated) and loses control of its body. The quori now controls the body but doesn't deprive the target of awareness. The quori can't be targeted by any attack, spell, or other effect, and it retains its alignment, Intelligence, Wisdom, Charisma, and immunity to being [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed) and [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened). It otherwise uses the possessed target's statistics, but doesn't gain access to the target's knowledge, class features, or proficiencies.

The possession lasts until the body drops to 0 hit points, the quori ends it as a bonus action, or the quori is forced out by an effect like the [dispel evil and good](2-Mechanics/CLI/spells/dispel-evil-and-good.md) spell. When the possession ends, the quori reappears in an unoccupied space within 5 feet of the body. The target is immune to this quori's Possession for 24 hours after succeeding on the saving throw or after the possession ends.

## Reactions

***Empathic Feedback.*** When the quori takes damage from a creature it can see within 60 feet of it, the quori can force that creature to succeed on a DC 16 Intelligence saving throw or take `dice:2d10|noform|avg|text(11)` (`2d10`) psychic damage.
```
^statblock