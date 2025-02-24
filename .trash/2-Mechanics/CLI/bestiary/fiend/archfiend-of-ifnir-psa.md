---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/psa
- monster/cr/13
- monster/size/large
- monster/type/fiend/demon
aliases: ["Archfiend of Ifnir"]
---
# Archfiend of Ifnir
*Source: Plane Shift: Amonkhet p. 30*  

## Demons

Deep in the desert, far from the protection of the Hekma and the safety of Naktamun, lies a place called Ifnir, the Demons' Nest. The people of Amonkhet believe that the God-Pharaoh banished all the demons of this plane to the desolation of Ifnir as punishment when they rose up in rebellion against him. Some say that the angels carry the worst dissenters into the heart of Ifnir, which is a fate far worse than merely being abandoned amid the scouring sands.

The demons of Ifnir bear some resemblance to Bolas, with long limbs and tails, huge wings, and gaunt bodies adorned with horns and blades. Other demonic creatures have more bestial features, including [ammits](2-Mechanics/CLI/bestiary/beast/ammit-psa.md)—crocodilian demons sometimes used as challenges within the trials of the five gods—and the scorpion demons called [soulstingers](2-Mechanics/CLI/bestiary/fiend/soulstinger-demon-psa.md), whose venom causes excruciating pain in its victims.

Use the statistics of a [nalfeshnee](2-Mechanics/CLI/bestiary/fiend/nalfeshnee.md) for a demon such as an [Archfiend of Ifnir](2-Mechanics/CLI/bestiary/fiend/archfiend-of-ifnir-psa.md). The statistics of a [giant crocodile](2-Mechanics/CLI/bestiary/beast/giant-crocodile.md) can model an [ammit](2-Mechanics/CLI/bestiary/beast/ammit-psa.md), and those of a [bone devil](2-Mechanics/CLI/bestiary/fiend/bone-devil.md) work well for a [soulstinger demon](2-Mechanics/CLI/bestiary/fiend/soulstinger-demon-psa.md).

```ad-statblock
title: Archfiend of Ifnir
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/PSA/Archfiend%20of%20Ifnir.webp#token)
*Large fiend (demon), Chaotic Evil*

- **Armor Class** 18 (natural armor)
- **Hit Points** 184 (`16d10 + 96`)
- **Speed** 20 ft., fly 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|21 (+5)|10 (+0)|22 (+6)|19 (+4)|12 (+1)|15 (+2)|

- **Proficiency Bonus** +5
- **Saving Throws** Constitution +11, Intelligence +9, Wisdom +6, Charisma +7
- **Skills** ⏤
- **Senses** truesight 120 ft., passive Perception 11
- **Damage Resistances** cold; fire; lightning; bludgeoning, piercing, slashing from nonmagical attacks
- **Damage Immunities** poison
- **Condition Immunities** [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** Abyssal, telepathy 120 ft.
- **Challenge** 13

## Traits

***Magic Resistance.*** The archfiend has advantage on saving throws against spells and other magical effects.

## Actions

***Multiattack.*** The archfiend uses Horror Nimbus if it can. It then makes three attacks: one with its bite and two with its claws.

***Bite.*** *Melee Weapon Attack:* `dice:1d20+10|noform|text(+10)` to hit, reach 5 ft., one target. *Hit:* `dice:5d10+5|noform|avg|text(32)` (`5d10 + 5`) piercing damage.

***Claw.*** *Melee Weapon Attack:* `dice:1d20+10|noform|text(+10)` to hit, reach 10 ft., one target. *Hit:* `dice:3d6+5|noform|avg|text(15)` (`3d6 + 5`) slashing damage.

***Horror Nimbus (Recharge 5-6).*** The archfiend magically emits scintillating, multicolored light. Each creature within 15 feet of the archfiend that can see the light must succeed on a DC 15 Wisdom saving throw or be [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened) for 1 minute. A creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success. If a creature's saving throw is successful or the effect ends for it, the creature is immune to the archfiend's Horror Nimbus for the next 24 hours.

***Teleport.*** The archfiend magically teleports, along with any equipment it is wearing or carrying, up to 120 feet to an unoccupied space it can see.
```
^statblock