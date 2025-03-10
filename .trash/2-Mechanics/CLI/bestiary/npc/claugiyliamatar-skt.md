---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/skt
- monster/cr/22
- monster/size/gargantuan
- monster/type/dragon
aliases: ["Claugiyliamatar"]
---
# Claugiyliamatar
*Source: Storm King's Thunder p. 96, Divine Contention, Storm Lord's Wrath, Sleeping Dragon's Wake*  

```ad-statblock
title: Claugiyliamatar
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/SKT/Claugiyliamatar.webp#token)
*Gargantuan dragon, Lawful Evil*

- **Armor Class** 21 (natural armor)
- **Hit Points** 385 (`22d20 + 154`)
- **Speed** 40 ft., fly 80 ft., swim 40 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|27 (+8)|12 (+1)|25 (+7)|20 (+5)|17 (+3)|19 (+4)|

- **Proficiency Bonus** +7
- **Saving Throws** Dexterity +8, Constitution +14, Wisdom +10, Charisma +11
- **Skills** Deception +11, Insight +10, Perception +17, Persuasion +11, Stealth +8
- **Senses** blindsight 60 ft., darkvision 120 ft., passive Perception 27
- **Damage Immunities** poison
- **Condition Immunities** [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** Common, Draconic
- **Challenge** 22

## Traits

***Amphibious.*** The dragon can breathe air and water.

***Legendary Resistance (3/Day).*** If the dragon fails a saving throw, it can choose to succeed instead.

***Spellcasting.*** Claugiyliamatar casts one of the following spells, requiring no material components and using Charisma as the spellcasting ability (spell save DC 19):

**At will**: [detect magic](2-Mechanics/CLI/spells/detect-magic.md), [druidcraft](2-Mechanics/CLI/spells/druidcraft.md), [speak with animals](2-Mechanics/CLI/spells/speak-with-animals.md)

**1/day each**: [blight](2-Mechanics/CLI/spells/blight.md), [legend lore](2-Mechanics/CLI/spells/legend-lore.md) (cast as 1 action), [locate creature](2-Mechanics/CLI/spells/locate-creature.md), [pass without trace](2-Mechanics/CLI/spells/pass-without-trace.md), [protection from energy](2-Mechanics/CLI/spells/protection-from-energy.md), [true seeing](2-Mechanics/CLI/spells/true-seeing.md)

**2/day each**: [animal messenger](2-Mechanics/CLI/spells/animal-messenger.md), [cure wounds](2-Mechanics/CLI/spells/cure-wounds.md), [dispel magic](2-Mechanics/CLI/spells/dispel-magic.md), [entangle](2-Mechanics/CLI/spells/entangle.md), [invisibility](2-Mechanics/CLI/spells/invisibility.md)

## Actions

***Multiattack.*** The dragon can use its Frightful Presence. It then makes three attacks: one with its bite and two with its claws.

***Bite.*** *Melee Weapon Attack:* `dice:1d20+15|noform|text(+15)` to hit, reach 15 ft., one target. *Hit:* `dice:2d10+8|noform|avg|text(19)` (`2d10 + 8`) piercing damage plus `dice:3d6|noform|avg|text(10)` (`3d6`) poison damage.

***Claw.*** *Melee Weapon Attack:* `dice:1d20+15|noform|text(+15)` to hit, reach 10 ft., one target. *Hit:* `dice:4d6+8|noform|avg|text(22)` (`4d6 + 8`) slashing damage.

***Tail.*** *Melee Weapon Attack:* `dice:1d20+15|noform|text(+15)` to hit, reach 20 ft., one target. *Hit:* `dice:2d8+8|noform|avg|text(17)` (`2d8 + 8`) bludgeoning damage.

***Frightful Presence.*** Each creature of the dragon's choice that is within 120 feet of the dragon and aware of it must succeed on a DC 19 Wisdom saving throw or become [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened) for 1 minute. A creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success. If a creature's saving throw is successful or the effect ends for it, the creature is immune to the dragon's Frightful Presence for the next 24 hours.

***Poison Breath (Recharge 5-6).*** The dragon exhales poisonous gas in a 90-foot cone. Each creature in that area must make a DC 22 Constitution saving throw, taking `dice:22d6|noform|avg|text(77)` (`22d6`) poison damage on a failed save, or half as much damage on a successful one.

## Legendary Actions

***Detect.*** The dragon makes a Wisdom ([Perception](2-Mechanics/CLI/rules/skills.md#Perception)) check.

***Tail Attack.*** The dragon makes a tail attack.

***Wing Attack (Costs 2 Actions).*** The dragon beats its wings. Each creature within 15 feet of the dragon must succeed on a DC 23 Dexterity saving throw or take `dice:2d6+8|noform|avg|text(15)` (`2d6 + 8`) bludgeoning damage and be knocked [prone](2-Mechanics/CLI/rules/conditions.md#Prone). The dragon can then fly up to half its flying speed.
```
^statblock