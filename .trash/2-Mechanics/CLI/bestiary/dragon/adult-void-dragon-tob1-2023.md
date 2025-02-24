---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/tob1-2023
- monster/cr/16
- monster/environment/planar
- monster/size/huge
- monster/type/dragon
aliases: ["Adult Void Dragon"]
---
# Adult Void Dragon
*Source: Tome of Beasts 1 (2023 Edition) p. 129*  

*A dragon seemingly formed of the night sky has bright white stars for eyes. Lesser stars twinkle in the firmament of the dragon's body.*

## Children of the Stars

Void dragons drift through the empty spaces beyond the boundaries of the mortal world and wander between the stars. They are aloof, mingling only with the otherworldly beings that live above and beyond the earth, including the incarnate forms of the stars themselves.

## Witnesses to the Void

Void dragons are intensely knowledgeable creatures, but they have seen too much, lingering at the edge of the Void itself. They carry a piece of that nothing with them, and it flows out of them to break the minds of lesser beings when the dragons fly into a rage.

## Voracious Scholars

Despite their removed existence and strange quirks, Void dragons still hoard treasure. Gems that glitter like the stars of their home are particularly prized. Their crowning piece, however, is knowledge. Void dragons jealously hoard scraps of forbidden and forgotten lore of any kind and spend most of their time at home poring over these treasures.

## A Void Dragon's Lair

Void dragons make their lairs deep in the freezing, airless space between the stars. When a Void dragon claims a home elsewhere, it prefers towering mountain peaks, valleys, or ruins at high elevation with a clear view of the sky. When encountered in its lair, an adult Void dragon has a challenge rating of 17 (18,000 XP), and an ancient Void dragon has a challenge rating of 25 (75,000 XP).

## Statblock

```ad-statblock
title: Adult Void Dragon
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ToB1-2023/Adult%20Void%20Dragon.webp#token)
*Huge dragon, Chaotic Neutral*

- **Armor Class** 19 (natural armor)
- **Hit Points** 229 (`17d12 + 119`)
- **Speed** 40 ft., fly 80 ft. (hover)

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|24 (+7)|10 (+0)|25 (+7)|16 (+3)|13 (+1)|21 (+5)|

- **Proficiency Bonus** +5
- **Saving Throws** Dexterity +5, Constitution +12, Wisdom +6, Charisma +10
- **Skills** Arcana +13, History +13, Perception +11, Stealth +5
- **Senses** blindsight 60 ft., darkvision 120 ft., passive Perception 21
- **Damage Immunities** cold
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened)
- **Languages** Common, Draconic, Void Speech
- **Challenge** 16

## Traits

***Chill of the Void.*** Creatures with resistance to cold damage don't have resistance to the cold damage dealt by the Void dragon. A creature with immunity to cold damage is still immune to the dragon's cold damage.

***Expert Void Traveler.*** The Void dragon doesn't require air, food, drink, sleep, or ambient pressure. While traveling in the Void, the dragon magically glides on solar winds, covering immense distances in short times.

***Legendary Resistance (3/Day).*** If the dragon fails a saving throw, it can choose to succeed instead.

## Actions

***Multiattack.*** The dragon uses its Aura of Madness. It then makes one Bite attack and two Claw attacks.

***Bite.*** *Melee Weapon Attack:* `dice:1d20+12|noform|text(+12)` to hit, reach 10 ft., one target. *Hit:* `dice:2d10+7|noform|avg|text(18)` (`2d10 + 7`) piercing damage plus `dice:3d6|noform|avg|text(10)` (`3d6`) cold damage.

***Claw.*** *Melee Weapon Attack:* `dice:1d20+12|noform|text(+12)` to hit, reach 5 ft., one target. *Hit:* `dice:2d6+7|noform|avg|text(14)` (`2d6 + 7`) slashing damage.

***Tail.*** *Melee Weapon Attack:* `dice:1d20+12|noform|text(+12)` to hit, reach 15 ft., one target. *Hit:* `dice:2d8+7|noform|avg|text(16)` (`2d8 + 7`) bludgeoning damage.

***Aura of Madness.*** Each creature of the dragon's choice that is within 120 feet of the dragon and aware of it must succeed on a DC 18 Wisdom saving throw or suffer short-term madness for 1 minute. A creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success. If a creature's saving throw is successful or the effect ends for it, the creature is immune to the dragon's Aura of Madness for the next 24 hours.

***Breath Weapons (Recharge 5-6).*** The dragon uses one of the following breath weapons.

- **Gravitic Breath.** The dragon exhales localized gravity in a 60‑foot cube, originating from the dragon. When a creature ends a fall in the cube, it takes `dice:1d10|noform|avg` (`1d10`) bludgeoning damage for every 10 feet it fell, to a maximum of `dice:20d10|noform|avg` (`20d10`). A creature that enters the cube for the first time on a turn or starts its turn there must make a DC 20 Dexterity saving throw. On a failure, the creature is [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained). On a success, the creature's speed is halved as long as it remains in the cube. A creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success. The cube lasts until the dragon's breath weapon recharges.  
- **Stellar Breath.** The dragon exhales star fire in a 60-foot cone. Each creature in that area must make a DC 20 Dexterity saving throw, taking `dice:9d6|noform|avg|text(31)` (`9d6`) fire damage and `dice:9d6|noform|avg|text(31)` (`9d6`) radiant damage on a failed save, or half as much damage on a successful one.  

## Reactions

***Void Twist.*** The dragon adds 5 to its AC against one attack that would hit it, as it twists reality to open a small rift in space to protect itself. To do so, the dragon must be able to see the attacker. If the attack misses by 5 or more, the dragon can choose to open a second, connected rift next to another creature it can see within 30 feet of it to direct the attack at that creature instead, using the original attack roll result against the new target's AC.

## Legendary Actions

***Detect.*** The dragon makes a Wisdom ([Perception](2-Mechanics/CLI/rules/skills.md#Perception)) check.

***Tail Attack.*** The dragon makes a Tail attack.

***Void Slip (Costs 2 Actions).*** The dragon twists the fabric of space around it, disappearing and reappearing in an unoccupied space it can see within 120 feet of it. Each creature within 10 feet of the dragon must succeed on a DC 20 Constitution saving throw or take `dice:4d6|noform|avg|text(14)` (`4d6`) cold damage and be knocked [prone](2-Mechanics/CLI/rules/conditions.md#Prone).

![Void Dragon](2-Mechanics/CLI/bestiary/legendary-group/void-dragon-tob1-2023.md)
```
^statblock

## Environment

planar