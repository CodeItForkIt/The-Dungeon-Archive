---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/tob1-2023
- monster/cr/16
- monster/environment/grassland
- monster/environment/mountain
- monster/size/huge
- monster/type/dragon
aliases: ["Adult Wind Dragon"]
---
# Adult Wind Dragon
*Source: Tome of Beasts 1 (2023 Edition) p. 134*  

*Howling wind encircles the dragon, filling and pushing its wings without the need for them to beat.*

Wind dragons view anywhere touched by air as their property, and mortals point to them as the epitome of arrogance. Their narcissism is not without reason, for awe‑inspiring power supports their claims of rightful control. To the dragons of the shifting gales, strength is the ultimate arbiter.

## Braggarts and Bullies

Wind dragons number among the greatest bullies and worst tyrants of mortal creatures. The sometimes-foolhardy creatures take offense at any perceived challenge and pleasure in humiliating rivals. They claim great swathes of territory but care little for its governance—they perceive mortals in that territory as possessions. Vassals receive only dubious protection in exchange for their loyalty. A wind dragon might seek bloody vengeance for the murder of a follower, but it's unlikely to go to any length to prevent the loss of that life in the first place.

## Lords of the Far Horizons

Some believe that the dragons of the winds claim much more than they are capable of controlling or patrolling. Because they so love altitude, they prefer to rule and meet with earth-bound supplicants at the highest point available: the summit of a great mountain or atop a towering monument erected by fearful slaves. But these dragons are also driven by wanderlust and roam far from their thrones. They return eventually, ready to subjugate new generations and press a tyrannical claw on the neck of anyone who questions their right to rule.

## Perpetual Infighting

These wandering tyrants are even more territorial among their own kind than they are among groundlings. Simple trespass by one wind dragon into the territory of another can lead to a battle to the death. Thus, their numbers never grow large, and the weakest among them are frequently culled.

## Portable Hoards

Wind dragons' hoards typically consist of only a few truly valuable relics. Other dragons might sleep on a bed of coins, but common things bore wind dragons. While all true dragons desire and display great wealth, wind dragons concentrate their riches in a small number of notable trophies or unique historic items—often quite portable.

## A Wind Dragon's Lair

Wind dragons make their lairs where they can overlook and dominate their claims, but the location must be remote enough that inhabitants can't pester them with requests for protection or justice. As they have little to fear from the elements, a shallow cave high on an exposed mountain face is ideal. Wind dragons enjoy heights dotted with rock spires and tall, sheer cliffs. They perch in the howling wind and catch updrafts and downdrafts sweeping through canyons and tearing across crags.

## Statblock

```ad-statblock
title: Adult Wind Dragon
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ToB1-2023/Adult%20Wind%20Dragon.webp#token)
*Huge dragon, Chaotic Neutral*

- **Armor Class** 17 (natural armor)
- **Hit Points** 187 (`15d12 + 90`)
- **Speed** 30 ft., fly 90 ft. (hover)

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|24 (+7)|16 (+3)|22 (+6)|16 (+3)|15 (+2)|18 (+4)|

- **Proficiency Bonus** +5
- **Saving Throws** Dexterity +8, Constitution +11, Wisdom +7, Charisma +9
- **Skills** Acrobatics +13, Intimidation +9, Perception +12, Stealth +8
- **Senses** blindsight 60 ft., darkvision 120 ft., passive Perception 22
- **Damage Resistances** cold
- **Damage Immunities** lightning
- **Languages** Common, Draconic, Primordial
- **Challenge** 16

## Traits

***Freedom of Movement.*** The dragon ignores difficult terrain, and magical effects can't reduce its speed or cause it to be [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained). It can spend 5 feet of movement to escape from nonmagical restraints or being [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled).

***Legendary Resistance (3/Day).*** If the dragon fails a saving throw, it can choose to succeed instead.

***Storm Sight.*** The dragon can see through areas obscured by fog, mist, clouds, or precipitation.

***Whirling Winds.*** Gale force winds rage around the dragon's body. Ranged weapon attack rolls against the dragon have disadvantage.

## Actions

***Multiattack.*** The wind dragon uses its Frightful Presence. It then makes one Bite attack and two Claw attacks.

***Bite.*** *Melee Weapon Attack:* `dice:1d20+12|noform|text(+12)` to hit, reach 10 ft., one target. *Hit:* `dice:2d10+7|noform|avg|text(18)` (`2d10 + 7`) piercing damage.

***Claw.*** *Melee Weapon Attack:* `dice:1d20+12|noform|text(+12)` to hit, reach 5 ft., one target. *Hit:* `dice:2d6+7|noform|avg|text(14)` (`2d6 + 7`) slashing damage.

***Tail.*** *Melee Weapon Attack:* `dice:1d20+12|noform|text(+12)` to hit, reach 15 ft., one target. *Hit:* `dice:2d8+7|noform|avg|text(16)` (`2d8 + 7`) bludgeoning damage.

***Frightful Presence.*** Each creature of the dragon's choice that is within 120 feet of the dragon and aware of it must succeed on a DC 17 Wisdom saving throw or become [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened) for 1 minute. A creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success. If a creature's saving throw is successful or the effect ends for it, the creature is immune to the dragon's Frightful Presence for the next 24 hours.

***Tempest Breath (Recharge 5-6).*** The dragon exhales a blast of stormy wind in a 60-foot cone. Each creature in that area must make a DC 19 Strength saving throw. On a failure, a creature takes `dice:6d8|noform|avg|text(27)` (`6d8`) bludgeoning damage and `dice:6d8|noform|avg|text(27)` (`6d8`) lightning damage and is pushed up to 30 feet away from the dragon and knocked [prone](2-Mechanics/CLI/rules/conditions.md#Prone). On a success, a creature takes half the damage and isn't pushed or knocked [prone](2-Mechanics/CLI/rules/conditions.md#Prone). Unprotected flames, such as torches, in the area are extinguished, and protected flames, such as those in lanterns, have a 75 percent chance of being extinguished.

## Legendary Actions

***Detect.*** The dragon makes a Wisdom ([Perception](2-Mechanics/CLI/rules/skills.md#Perception)) check.

***Tail Attack.*** The dragon makes a Tail attack.

***Wing Attack (Costs 2 Actions).*** The dragon beats its wings. Each creature within 10 feet of the dragon must succeed on a DC 20 Dexterity saving throw or take `dice:2d6+7|noform|avg|text(14)` (`2d6 + 7`) bludgeoning damage and be knocked [prone](2-Mechanics/CLI/rules/conditions.md#Prone). The dragon can then fly up to half its flying speed.

![Wind Dragon](2-Mechanics/CLI/bestiary/legendary-group/wind-dragon-tob1-2023.md)
```
^statblock

## Environment

grassland, mountain