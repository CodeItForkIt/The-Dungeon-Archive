---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/tob1-2023
- monster/cr/24
- monster/environment/planar
- monster/size/gargantuan
- monster/type/dragon
aliases: ["Ancient Void Dragon"]
---
# Ancient Void Dragon
*Source: Tome of Beasts 1 (2023 Edition) p. 128*  

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
title: Ancient Void Dragon
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ToB1-2023/Ancient%20Void%20Dragon.webp#token)
*Gargantuan dragon, Chaotic Neutral*

- **Armor Class** 22 (natural armor)
- **Hit Points** 429 (`22d20 + 198`)
- **Speed** 40 ft., fly 80 ft. (hover)

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|28 (+9)|10 (+0)|29 (+9)|18 (+4)|15 (+2)|23 (+6)|

- **Proficiency Bonus** +7
- **Saving Throws** Dexterity +7, Constitution +16, Wisdom +9, Charisma +13
- **Skills** Arcana +18, History +18, Perception +16, Stealth +7
- **Senses** blindsight 60 ft., darkvision 120 ft., passive Perception 26
- **Damage Immunities** cold
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened)
- **Languages** Common, Draconic, Void Speech
- **Challenge** 24

## Traits

***Chill of the Void.*** Creatures with resistance to cold damage don't have resistance to the cold damage dealt by the Void dragon. A creature with immunity to cold damage is still immune to the dragon's cold damage.

***Collapsing Star.*** When the void dragon dies, it explodes in a swath of celestial destruction. Each creature within 1,000 feet of the dragon must make a DC 21 Constitution saving throw, taking `dice:10d10|noform|avg|text(55)` (`10d10`) bludgeoning damage and `dice:10d10|noform|avg|text(55)` (`10d10`) cold damage on a failed save, or half as much damage on a successful one. Objects in the area that aren't being worn or carried take half the bludgeoning damage. A creature that fails the saving throw by 5 or more is ejected to a random location on a random plane of existence or `dice:5d100|noform|avg` (`5d100`) miles away from its current location in a random direction (GM's choice).

***Expert Void Traveler.*** The Void dragon doesn't require air, food, drink, sleep, or ambient pressure. While traveling in the Void, the dragon magically glides on solar winds, covering immense distances in short times.

***Legendary Resistance (3/Day).*** If the dragon fails a saving throw, it can choose to succeed instead.

## Actions

***Multiattack.*** The dragon uses its Aura of Madness. It then makes one Bite attack and two Claw attacks.

***Bite.*** *Melee Weapon Attack:* `dice:1d20+16|noform|text(+16)` to hit, reach 15 ft., one target. *Hit:* `dice:2d10+9|noform|avg|text(20)` (`2d10 + 9`) piercing damage plus `dice:4d6|noform|avg|text(14)` (`4d6`) cold damage.

***Claw.*** *Melee Weapon Attack:* `dice:1d20+16|noform|text(+16)` to hit, reach 10 ft., one target. *Hit:* `dice:2d6+9|noform|avg|text(16)` (`2d6 + 9`) slashing damage.

***Tail.*** *Melee Weapon Attack:* `dice:1d20+16|noform|text(+16)` to hit, reach 20 ft., one target. *Hit:* `dice:2d8+9|noform|avg|text(18)` (`2d8 + 9`) bludgeoning damage.

***Aura of Madness.*** Each creature of the dragon's choice that is within 120 feet of the dragon and aware of it must succeed on a DC 18 Wisdom saving throw or suffer short-term madness for 1 minute. A creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success. If a creature's saving throw is successful or the effect ends for it, the creature is immune to the dragon's Aura of Madness for the next 24 hours.

***Breath Weapons (Recharge 5-6).*** The dragon uses one of the following breath weapons.

- **Gravitic Breath.** The dragon exhales localized gravity in a 90‑foot cube, originating from the dragon. When a creature ends a fall in the cube, it takes `dice:1d10|noform|avg` (`1d10`) bludgeoning damage for every 10 feet it fell, to a maximum of `dice:20d10|noform|avg` (`20d10`). A creature that enters the cube for the first time on a turn or starts its turn there must make a DC 24 Dexterity saving throw. On a failure, the creature is [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained). On a success, the creature's speed is halved as long as it remains in the cube. A creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success. The cube lasts for 1 minute.  
- **Stellar Breath.** The dragon exhales star fire in a 90-foot cone. Each creature in that area must make a DC 24 Dexterity saving throw, taking `dice:12d6|noform|avg|text(42)` (`12d6`) fire damage and `dice:12d6|noform|avg|text(42)` (`12d6`) radiant damage on a failed save, or half as much damage on a successful one.  

## Reactions

***Void Twist.*** The dragon adds 7 to its AC against one attack that would hit it, as it twists reality to open a small rift in space to protect itself. To do so, the dragon must be able to see the attacker. If the attack misses by 5 or more, the dragon can choose to open a second, connected rift next to another creature it can see within 30 feet of it to direct the attack at that creature instead, using the original attack roll result against the new target's AC.

## Legendary Actions

***Detect.*** The dragon makes a Wisdom ([Perception](2-Mechanics/CLI/rules/skills.md#Perception)) check.

***Tail Attack.*** The dragon makes a Tail attack.

***Void Slip (Costs 2 Actions).*** The dragon twists the fabric of space around it, disappearing and reappearing in an unoccupied space it can see within 120 feet of it. Each creature within 15 feet of the dragon must succeed on a DC 21 Dexterity saving throw or take `dice:5d6|noform|avg|text(17)` (`5d6`) cold damage and be knocked [prone](2-Mechanics/CLI/rules/conditions.md#Prone).

![Void Dragon](2-Mechanics/CLI/bestiary/legendary-group/void-dragon-tob1-2023.md)
```
^statblock

## Environment

planar