---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/psk
- monster/cr/17
- monster/size/huge
- monster/type/dragon
aliases: ["Dragon"]
---
# Dragon
*Source: Plane Shift: Kaladesh p. 29*  

Dragons are the apex predators of the skies. They are usually found in rural areas, avoiding the crowds of air ships and thopters found above the cities of Kaladesh. Their favorite prey are the sky whales that drift through the aethersphere, but they also hunt leviathans, wurms, hydras, drakes, giants—and airships.

Dragons typically hunt by perching on a promontory or hilltop, remaining perfectly still as they wait for prey to come into view. With a single snap of its powerful wings, a dragon can launch itself into the air with lightning speed, hurtling toward its target like a deadly arrow.

Dragons resemble a cross between a lizard and a tiger, with powerful feline bodies covered in striped fur, reptilian heads crowned with long horns, and enormous leathery wings that propel them through the sky at tremendous speed. Their chests are adorned with elaborate patterns resembling fine filigree.

The [red dragon](2-Mechanics/CLI/bestiary/dragon/adult-red-dragon.md) statistics work well for the dragons of Kaladesh, though dragons rarely reach ancient age on that plane. They can spew great blasts of flame, but a dragon's preferred method of assault is to hold flame in its mouth as it attacks. This counts as a use of the dragon's breath weapon, but the dragon makes a special bite attack. On a hit, the bite attack deals its normal piercing damage plus the fire damage from the dragon's breath weapon, with no saving throw.

```ad-statblock
title: Dragon
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/PSK/Dragon.webp#token)
*Huge dragon, Chaotic Evil*

- **Armor Class** 19 (natural armor)
- **Hit Points** 256 (`19d12 + 133`)
- **Speed** 40 ft., climb 40 ft., fly 80 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|27 (+8)|10 (+0)|25 (+7)|16 (+3)|13 (+1)|21 (+5)|

- **Proficiency Bonus** +6
- **Saving Throws** Dexterity +6, Constitution +13, Wisdom +7, Charisma +11
- **Skills** Perception +13, Stealth +6
- **Senses** blindsight 60 ft., darkvision 120 ft., passive Perception 23
- **Damage Immunities** fire
- **Languages** Common, Draconic
- **Challenge** 17

## Traits

***Legendary Resistance (3/Day).*** If the dragon fails a saving throw, it can choose to succeed instead.

## Actions

***Multiattack.*** The dragon can use its Frightful Presence. It then makes three attacks: one with its bite and two with its claws.

***Bite.*** *Melee Weapon Attack:* `dice:1d20+14|noform|text(+14)` to hit, reach 10 ft., one target. *Hit:* `dice:2d10+8|noform|avg|text(19)` (`2d10 + 8`) piercing damage plus `dice:2d6|noform|avg|text(7)` (`2d6`) fire damage.

***Claw.*** *Melee Weapon Attack:* `dice:1d20+14|noform|text(+14)` to hit, reach 5 ft., one target. *Hit:* `dice:2d6+8|noform|avg|text(15)` (`2d6 + 8`) slashing damage.

***Tail.*** *Melee Weapon Attack:* `dice:1d20+14|noform|text(+14)` to hit, reach 15 ft., one target. *Hit:* `dice:2d8+8|noform|avg|text(17)` (`2d8 + 8`) bludgeoning damage.

***Frightful Presence.*** Each creature of the dragon's choice that is within 120 feet of the dragon and aware of it must succeed on a DC 19 Wisdom saving throw or become [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened) for 1 minute. A creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success. If a creature's saving throw is successful or the effect ends for it, the creature is immune to the dragon's Frightful Presence for the next 24 hours.

***Fire Breath (Recharge 5-6).*** The dragon exhales fire in a 60-foot cone. Each creature in that area must make a DC 21 Dexterity saving throw, taking `dice:18d6|noform|avg|text(63)` (`18d6`) fire damage on a failed save, or half as much damage on a successful one.

***Fiery Bite (Recharge 5-6).*** *Melee Weapon Attack:* `dice:1d20+14|noform|text(+14)` to hit, reach 10 ft., one target. *Hit:* `dice:2d10+8|noform|avg|text(19)` (`2d10 + 8`) piercing damage plus `dice:18d6|noform|avg|text(63)` (`18d6`) fire damage. This counts as a use of the dragon's breath weapon.

## Legendary Actions

***Detect.*** The dragon makes a Wisdom ([Perception](2-Mechanics/CLI/rules/skills.md#Perception)) check.

***Tail Attack.*** The dragon makes a tail attack.

***Wing Attack (Costs 2 Actions).*** The dragon beats its wings. Each creature within 10 feet of the dragon must succeed on a DC 22 Dexterity saving throw or take `dice:2d6+8|noform|avg|text(15)` (`2d6 + 8`) bludgeoning damage and be knocked [prone](2-Mechanics/CLI/rules/conditions.md#Prone). The dragon can then fly up to half its flying speed.

![Red Dragon](2-Mechanics/CLI/bestiary/legendary-group/red-dragon.md)
```
^statblock