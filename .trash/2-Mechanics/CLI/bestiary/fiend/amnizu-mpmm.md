---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/mpmm
- monster/cr/18
- monster/size/medium
- monster/type/fiend/devil
aliases: ["Amnizu"]
---
# Amnizu
*Source: Mordenkainen Presents: Monsters of the Multiverse p. 46, Mordenkainen's Tome of Foes p. 164*  

Amnizus lead infernal legions into battle and command guardians at the gateways to the Hells. Amnizus are arrogant, bullying, and ruthless, but they're also highly intelligent tacticians and unfailingly loyal—qualities the hellish archdukes value.

Some amnizus perform the critical task of watching over the River Styx from fortresses along the river's blighted banks, where it flows through Dis and Stygia. They collect the souls arriving in the form of [lemures](2-Mechanics/CLI/bestiary/fiend/lemure.md). Lemures have no personalities or memories; they're driven only by the desire to commit evil. The amnizus that patrol here drill the rules of the Nine Hells into the new arrivals' minds and marshal them into legions.

```ad-statblock
title: Amnizu
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/MPMM/Amnizu.webp#token)
*Medium fiend (devil), Typically  Lawful Evil*

- **Armor Class** 21 (natural armor)
- **Hit Points** 202 (`27d8 + 81`)
- **Speed** 30 ft., fly 40 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|11 (+0)|13 (+1)|16 (+3)|20 (+5)|12 (+1)|18 (+4)|

- **Proficiency Bonus** +6
- **Saving Throws** Dexterity +7, Constitution +9, Wisdom +7, Charisma +10
- **Skills** Perception +7
- **Senses** darkvision 120 ft., passive Perception 17
- **Damage Resistances** cold; bludgeoning, piercing, slashing from nonmagical attacks that aren't silvered
- **Damage Immunities** fire, poison
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** Common, Infernal, telepathy 1,000 ft.
- **Challenge** 18

## Traits

***Devil's Sight.*** Magical darkness doesn't impede the amnizu's [darkvision](2-Mechanics/CLI/rules/senses.md#Darkvision).

***Magic Resistance.*** The amnizu has advantage on saving throws against spells and other magical effects.

***Spellcasting.*** The amnizu casts one of the following spells, requiring no material components and using Intelligence as the spellcasting ability (spell save DC 19):

**At will**: [command](2-Mechanics/CLI/spells/command.md)

**1/day**: [feeblemind](2-Mechanics/CLI/spells/feeblemind.md)

**3/day**: [dominate monster](2-Mechanics/CLI/spells/dominate-monster.md)

## Actions

***Multiattack.*** The amnizu uses Blinding Rot or Forgetfulness, if available. It also makes two Taskmaster Whip attacks.

***Taskmaster Whip.*** *Melee Weapon Attack:* `dice:1d20+11|noform|text(+11)` to hit, reach 10 ft., one target. *Hit:* `dice:1d8+5|noform|avg|text(9)` (`1d8 + 5`) slashing damage plus `dice:3d10|noform|avg|text(16)` (`3d10`) force damage.

***Blinding Rot.*** The amnizu targets one or two creatures that it can see within 60 feet of it. Each target must succeed on a DC 19 Wisdom saving throw or take `dice:4d12|noform|avg|text(26)` (`4d12`) necrotic damage and be [blinded](2-Mechanics/CLI/rules/conditions.md#Blinded) until the start of the amnizu's next turn.

***Forgetfulness (Recharge 6).*** The amnizu targets one creature it can see within 60 feet of it. That creature must succeed on a DC 18 Intelligence saving throw or take `dice:4d12|noform|avg|text(26)` (`4d12`) psychic damage and become [stunned](2-Mechanics/CLI/rules/conditions.md#Stunned) for 1 minute. A [stunned](2-Mechanics/CLI/rules/conditions.md#Stunned) creature repeats the saving throw at the end of each of its turns, ending the effect on itself on a success. If the target is [stunned](2-Mechanics/CLI/rules/conditions.md#Stunned) for the full minute, it forgets everything it sensed, experienced, and learned during the last 5 hours.

## Reactions

***Instinctive Charm.*** When a creature within 60 feet of the amnizu makes an attack roll against it, and another creature is within the attack's range, the attacker must make a DC 19 Wisdom saving throw. On a failed save, the attacker must target the creature that is closest to it, not including the amnizu or itself. If multiple creatures are closest, the attacker chooses which one to target. If the saving throw is successful, the attacker is immune to the amnizu's Instinctive Charm for 24 hours.
```
^statblock