---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/mot
- monster/cr/11
- monster/size/large
- monster/type/fiend
aliases: ["Nightmare Shepherd"]
---
# Nightmare Shepherd
*Source: Mythic Odysseys of Theros p. 221*  

A nightmare shepherd is a gaunt, ashen fiend with leathery wings. It carries a shepherd's crook, which it uses to direct a flock of wandering dead that it torments and occasionally feeds upon.

```ad-statblock
title: Nightmare Shepherd
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/MOT/Nightmare%20Shepherd.webp#token)
*Large fiend, Lawful Evil*

- **Armor Class** 18 (natural armor)
- **Hit Points** 133 (`14d10 + 56`)
- **Speed** 30 ft., fly 60 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|19 (+4)|15 (+2)|18 (+4)|14 (+2)|17 (+3)|20 (+5)|

- **Proficiency Bonus** +4
- **Saving Throws** Constitution +8, Wisdom +7
- **Skills** Arcana +6, Deception +9, Perception +7, Persuasion +9
- **Senses** darkvision 120 ft., passive Perception 17
- **Damage Resistances** cold, necrotic
- **Damage Immunities** poison
- **Condition Immunities** [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** Abyssal, Common, Infernal
- **Challenge** 11

## Traits

***Aura of Nightmares.*** Undead creatures within 30 feet of the shepherd gain a +5 bonus to attack and damage rolls. When any other creature that isn't undead or a construct starts its turn within 30 feet of the shepherd, that creature must succeed on a DC 17 Wisdom saving throw or take `dice:2d10|noform|avg|text(11)` (`2d10`) psychic damage.

***Magic Resistance.*** The shepherd has advantage on saving throws against spells and other magical effects.

***Innate Spellcasting.*** The shepherd's spellcasting ability is Charisma (spell save DC 17). It can innately cast the following spells, requiring no material components:

**1/day each**: [confusion](2-Mechanics/CLI/spells/confusion.md), [dispel magic](2-Mechanics/CLI/spells/dispel-magic.md), [hold person](2-Mechanics/CLI/spells/hold-person.md), [suggestion](2-Mechanics/CLI/spells/suggestion.md)

## Actions

***Multiattack.*** The shepherd makes two attacks: one with its claws and one with its staff.

***Claws.*** *Melee Weapon Attack:* `dice:1d20+8|noform|text(+8)` to hit, reach 5 ft., one target. *Hit:* `dice:2d8+4|noform|avg|text(13)` (`2d8 + 4`) slashing damage plus `dice:3d10|noform|avg|text(16)` (`3d10`) necrotic damage.

***Staff.*** *Melee Weapon Attack:* `dice:1d20+8|noform|text(+8)` to hit, reach 5 ft., one target. *Hit:* `dice:2d6+4|noform|avg|text(11)` (`2d6 + 4`) bludgeoning damage, or `dice:2d8+4|noform|avg|text(13)` (`2d8 + 4`) bludgeoning damage if used with two hands, plus `dice:4d12|noform|avg|text(26)` (`4d12`) psychic damage.

***Herd the Underworld (Recharges after a Short or Long Rest).*** The shepherd pulls twisted souls from the Underworld; `dice:1d6|noform|avg` (`1d6`) [shadows](2-Mechanics/CLI/bestiary/undead/shadow.md) (without Sunlight Weakness) arise in unoccupied spaces within 20 feet of the shepherd. The shadows act right after the shepherd on the same initiative count and fight until they're destroyed. They disappear when the shepherd dies.
```
^statblock