---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/psa
- monster/cr/9
- monster/size/large
- monster/type/fiend/demon
aliases: ["Soulstinger Demon"]
---
# Soulstinger Demon
*Source: Plane Shift: Amonkhet p. 30*  

## Demons

Deep in the desert, far from the protection of the Hekma and the safety of Naktamun, lies a place called Ifnir, the Demons' Nest. The people of Amonkhet believe that the God-Pharaoh banished all the demons of this plane to the desolation of Ifnir as punishment when they rose up in rebellion against him. Some say that the angels carry the worst dissenters into the heart of Ifnir, which is a fate far worse than merely being abandoned amid the scouring sands.

The demons of Ifnir bear some resemblance to Bolas, with long limbs and tails, huge wings, and gaunt bodies adorned with horns and blades. Other demonic creatures have more bestial features, including [ammits](2-Mechanics/CLI/bestiary/beast/ammit-psa.md)—crocodilian demons sometimes used as challenges within the trials of the five gods—and the scorpion demons called [soulstingers](2-Mechanics/CLI/bestiary/fiend/soulstinger-demon-psa.md), whose venom causes excruciating pain in its victims.

Use the statistics of a [nalfeshnee](2-Mechanics/CLI/bestiary/fiend/nalfeshnee.md) for a demon such as an [Archfiend of Ifnir](2-Mechanics/CLI/bestiary/fiend/archfiend-of-ifnir-psa.md). The statistics of a [giant crocodile](2-Mechanics/CLI/bestiary/beast/giant-crocodile.md) can model an [ammit](2-Mechanics/CLI/bestiary/beast/ammit-psa.md), and those of a [bone devil](2-Mechanics/CLI/bestiary/fiend/bone-devil.md) work well for a [soulstinger demon](2-Mechanics/CLI/bestiary/fiend/soulstinger-demon-psa.md).

```ad-statblock
title: Soulstinger Demon
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/PSA/Soulstinger%20Demon.webp#token)
*Large fiend (demon), Lawful Evil*

- **Armor Class** 19 (natural armor)
- **Hit Points** 142 (`15d10 + 60`)
- **Speed** 40 ft., fly 40 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|18 (+4)|16 (+3)|18 (+4)|13 (+1)|14 (+2)|16 (+3)|

- **Proficiency Bonus** +4
- **Saving Throws** Intelligence +5, Wisdom +6, Charisma +7
- **Skills** Deception +7, Insight +6
- **Senses** darkvision 120 ft., passive Perception 12
- **Damage Resistances** cold; bludgeoning, piercing, slashing from nonmagical attacks that aren't silvered
- **Damage Immunities** fire, poison
- **Condition Immunities** [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** Infernal, telepathy 120 ft.
- **Challenge** 9

## Traits

***Devil's Sight.*** Magical darkness doesn't impede the demon's darkvision.

***Magic Resistance.*** The demon has advantage on saving throws against spells and other magical effects.

## Actions

***Multiattack.*** The demon makes three attacks: two with its claws and one with its sting.

***Claw.*** *Melee Weapon Attack:* `dice:1d20+8|noform|text(+8)` to hit, reach 10 ft., one target. *Hit:* `dice:1d8+4|noform|avg|text(8)` (`1d8 + 4`) slashing damage.

***Sting.*** *Melee Weapon Attack:* `dice:1d20+8|noform|text(+8)` to hit, reach 10 ft., one target. *Hit:* `dice:2d8+4|noform|avg|text(13)` (`2d8 + 4`) piercing damage plus `dice:5d6|noform|avg|text(17)` (`5d6`) poison damage, and the target must succeed on a DC 14 Constitution saving throw or become [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned) for 1 minute. The target can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.
```
^statblock