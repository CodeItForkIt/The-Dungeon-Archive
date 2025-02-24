---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/psa
- monster/cr/24
- monster/size/gargantuan
- monster/type/dragon
aliases: ["Ancient Amonkhet Dragon"]
---
# Ancient Amonkhet Dragon
*Source: Plane Shift: Amonkhet p. 33*  

Dragons are fierce monsters with heavy reptilian bodies, crocodilian heads, and leathery wings, and are dis-tinguished by their ability to breathe fire. Though Nicol Bolas is also a dragon, he feels no kinship for these savage, dim-witted beasts. They live mostly in the remote reaches of the desert, soaring in lazy circles through the sky as they search for prey. Sometimes they are captured and brought inside the Hekma, where they are put to use within the trials of the five gods—especially in the climactic battles of the final Trial of Zeal.

The dragons of Amonkhet are **red dragons**, though they lack the high Intelligence of the red dragons in the "Monster Manual".

```ad-statblock
title: Ancient Amonkhet Dragon
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/PSA/Ancient%20Amonkhet%20Dragon.webp#token)
*Gargantuan dragon, Chaotic Evil*

- **Armor Class** 22 (natural armor)
- **Hit Points** 546 (`28d20 + 252`)
- **Speed** 40 ft., climb 40 ft., fly 80 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|30 (+10)|10 (+0)|29 (+9)|10 (+0)|15 (+2)|23 (+6)|

- **Proficiency Bonus** +7
- **Saving Throws** Dexterity +7, Constitution +16, Wisdom +9, Charisma +13
- **Skills** Perception +16, Stealth +7
- **Senses** blindsight 60 ft., darkvision 120 ft., passive Perception 26
- **Damage Immunities** fire
- **Languages** Common, Draconic
- **Challenge** 24

## Traits

***Legendary Resistance (3/Day).*** If the dragon fails a saving throw, it can choose to succeed instead.

## Actions

***Multiattack.*** The dragon can use its Frightful Presence. It then makes three attacks: one with its bite and two with its claws.

***Bite.*** *Melee Weapon Attack:* `dice:1d20+17|noform|text(+17)` to hit, reach 15 ft., one target. *Hit:* `dice:2d10+10|noform|avg|text(21)` (`2d10 + 10`) piercing damage plus `dice:4d6|noform|avg|text(14)` (`4d6`) fire damage.

***Claw.*** *Melee Weapon Attack:* `dice:1d20+17|noform|text(+17)` to hit, reach 10 ft., one target. *Hit:* `dice:2d6+10|noform|avg|text(17)` (`2d6 + 10`) slashing damage.

***Tail.*** *Melee Weapon Attack:* `dice:1d20+17|noform|text(+17)` to hit, reach 20 ft., one target. *Hit:* `dice:2d8+10|noform|avg|text(19)` (`2d8 + 10`) bludgeoning damage.

***Frightful Presence.*** Each creature of the dragon's choice that is within 120 feet of the dragon and aware of it must succeed on a DC 21 Wisdom saving throw or become [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened) for 1 minute. A creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success. If a creature's saving throw is successful or the effect ends for it, the creature is immune to the dragon's Frightful Presence for the next 24 hours.

***Fire Breath (Recharge 5-6).*** The dragon exhales fire in a 90-foot cone. Each creature in that area must make a DC 24 Dexterity saving throw, taking `dice:26d6|noform|avg|text(91)` (`26d6`) fire damage on a failed save, or half as much damage on a successful one.

## Legendary Actions

***Detect.*** The dragon makes a Wisdom ([Perception](2-Mechanics/CLI/rules/skills.md#Perception)) check.

***Tail Attack.*** The dragon makes a tail attack.

***Wing Attack (Costs 2 Actions).*** The dragon beats its wings. Each creature within 15 feet of the dragon must succeed on a DC 25 Dexterity saving throw or take `dice:2d6+10|noform|avg|text(17)` (`2d6 + 10`) bludgeoning damage and be knocked [prone](2-Mechanics/CLI/rules/conditions.md#Prone). The dragon can then fly up to half its flying speed.
```
^statblock