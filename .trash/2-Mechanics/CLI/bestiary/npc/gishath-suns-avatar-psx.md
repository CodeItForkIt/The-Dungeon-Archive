---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/psx
- monster/cr/10
- monster/size/gargantuan
- monster/type/beast
aliases: ["Gishath, Sun's Avatar"]
---
# Gishath, Sun's Avatar
*Source: Plane Shift: Ixalan p. 32*  

The opening of Orazca, the golden city—which marks the turn between the Ixalan set and Rivals of Ixalan—reveals the existence of six huge and ancient elder dinosaurs, apparently preserved for centuries. Compared to their smaller cousins, they have less brightly-colored plumage and more grayish scales, but their feathers are a bright gold that matches the city around them. They are strong-willed and ferocious, and thus are hard to control. But the power of the Immortal Sun gives the Sun Empire warriors who wield it the ability to bring these elder dinosaurs under their command.

```ad-statblock
title: Gishath, Sun's Avatar
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/PSX/Gishath%2C%20Sun%27s%20Avatar.webp#token)
*Gargantuan beast, Unaligned*

- **Armor Class** 16 (natural armor)
- **Hit Points** 203 (`14d20 + 56`)
- **Speed** 40 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|24 (+7)|12 (+1)|18 (+4)|12 (+1)|16 (+3)| 6 (-2)|

- **Proficiency Bonus** +4
- **Saving Throws** Strength +11, Constitution +8, Wisdom +7, Charisma +2
- **Skills** Perception +7
- **Senses** passive Perception 17
- **Languages** —
- **Challenge** 10

## Traits

***Legendary Resistance (3/Day).*** If Gishath fails a saving throw, it can choose to succeed instead.

## Actions

***Multiattack.*** Gishath makes two attacks: one with its bite and one with its stomp or tail. It can't make both attacks against the same target.

***Bite.*** *Melee Weapon Attack:* `dice:1d20+11|noform|text(+11)` to hit, reach 15 ft., one target. *Hit:* `dice:5d12+7|noform|avg|text(39)` (`5d12 + 7`) piercing damage. If the target is a Large or smaller creature, it must succeed on a DC 19 Dexterity saving throw or it is [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) (escape DC 19). Until this grapple ends, the target is [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained), and Gishath can't bite another target.

***Swallow.*** Gishath makes one bite attack against a Large or smaller creature it is grappling. If the attack hits, that creature takes the bite's damage and is swallowed, and the grapple ends. While swallowed, the creature is [blinded](2-Mechanics/CLI/rules/conditions.md#Blinded) and [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained), it has total cover against attacks and other effects outside Gishath, and it takes `dice:6d6|noform|avg|text(21)` (`6d6`) acid damage at the start of each of Gishath's turns.

If Gishath takes 30 damage or more on a single turn from a creature inside it, it must succeed on a DC 18 Constitution saving throw at the end of that turn or regurgitate all swallowed creatures, which fall [prone](2-Mechanics/CLI/rules/conditions.md#Prone) in a space within 10 feet of it. If Gishath dies, a swallowed creature is no longer [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained) by it and can escape from the corpse by using 20 feet of movement, exiting [prone](2-Mechanics/CLI/rules/conditions.md#Prone).

***Stomp.*** *Melee Weapon Attack:* `dice:1d20+11|noform|text(+11)` to hit, reach 10 ft., one target. *Hit:* `dice:5d8+7|noform|avg|text(29)` (`5d8 + 7`) bludgeoning damage, and the target must succeed on a DC 19 Strength saving throw or be knocked [prone](2-Mechanics/CLI/rules/conditions.md#Prone).

***Tail.*** *Melee Weapon Attack:* `dice:1d20+11|noform|text(+11)` to hit, reach 15 ft., one target. *Hit:* `dice:4d8+7|noform|avg|text(25)` (`4d8 + 7`) bludgeoning damage.

## Legendary Actions

***Attack.*** Gishath makes one stomp or tail attack.

***Roar (Costs 2 Actions).*** Each creature that is within 120 feet of Gishath and can hear it must succeed on a DC 19 Wisdom saving throw or become [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened) for 1 minute. A creature can repeat the saving throw at the end of each of its turns, ending the effect on tself on a success. If a creature's saving throw is successful or the effect ends for it, the creature is immune to Gishath's Roar for the next 24 hours.
```
^statblock