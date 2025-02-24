---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/tob1-2023
- monster/cr/18
- monster/environment/mountain
- monster/size/huge
- monster/type/dragon
aliases: ["Adult Mithral Dragon"]
---
# Adult Mithral Dragon
*Source: Tome of Beasts 1 (2023 Edition) p. 122*  

*Light glints off the dragon's glossy scales, shining silver-white. Its tiny wings folded flush against its body open like a fan and expose shimmering, diaphanous membranes. Its narrow head, with bare slits for its eyes and nostrils, sits at the end of a slender neck atop an impossibly thin frame*.

## Rage in Youth

Younger mithral dragons raid and pillage as heavily as any chromatic dragon, driven largely by greed to acquire a worthy hoard, though they are less likely to kill for sport or out of cruelty. In adulthood and old age, however, mithral dragons are less concerned with material wealth and more inclined to value friendship, knowledge, and a peaceful life pursuing interesting goals.

## Peacemakers

Adult and older mithral dragons are diplomats and arbitrators by temperament (some dragons cynically call them referees). They enjoy bringing some peace to warring factions. Among all dragons, their strict neutrality and ability to negate magic make them well suited to these vital roles.

> [!note] Mithral Dragons in Midgard
> 
> Mithral dragons are rebellious dragons who once sought to make peace between chromatic and metallic dragons. Having failed in that, they declared themselves neutral and now seek opportunities to make peace elsewhere. They are the only dragons that advocate against the perpetual war of the Dragon Empire, and occasionally serve as mercenaries against the Mharoti.
^mithral-dragons-in-midgard

## A Mithral Dragon's Lair

Mithral dragons are attracted to lairs near humanoid civilization, where petitioners can reach them if their diplomatic services are needed. Unlike other dragons, mithral dragons forsake lairing upon remote natural caverns or cliffs, preferring to dwell in impressive structures of metal and stone—with a particular fondness for towers. More than once, a mithral dragon has accepted the deed to a fortress, palace, or castle as payment for brokering peace between warring factions.

Curiously, mithral dragons don't hoard coins and precious metals as most dragons do. Other curiosities fill their lair, like fine paintings, marble statues, rare tomes, stained glass, and anything made of mithral—rare treasures procured over a lifetime of interacting with mortal creatures.

## Statblock

```ad-statblock
title: Adult Mithral Dragon
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ToB1-2023/Adult%20Mithral%20Dragon.webp#token)
*Huge dragon, Neutral*

- **Armor Class** 18 (natural armor)
- **Hit Points** 253 (`22d12 + 110`)
- **Speed** 40 ft., fly 80 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|12 (+1)|22 (+6)|21 (+5)|18 (+4)|19 (+4)|18 (+4)|

- **Proficiency Bonus** +6
- **Saving Throws** Dexterity +12, Constitution +11, Wisdom +10, Charisma +10
- **Skills** History +10, Insight +10, Perception +16, Persuasion +10, Stealth +12
- **Senses** blindsight 60 ft., darkvision 120 ft., passive Perception 26
- **Damage Resistances** force
- **Damage Immunities** slashing
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed)
- **Languages** all, telepathy 120 ft.
- **Challenge** 18

## Traits

***Legendary Resistance (3/Day).*** If the dragon fails a saving throw, it can choose to succeed instead.

***Magic Resistance.*** The dragon has advantage on saving throws against spells and other magical effects.

***Mithral Scales.*** If the dragon rolls a 20 on a saving throw against a spell that targets only it, the dragon is unaffected, and the spell is reflected back at the caster as though it originated from the dragon, turning the caster into the target.

## Actions

***Multiattack.*** The dragon uses its Frightful Presence. It then makes one Bite attack and two Claw attacks.

***Bite.*** *Melee Weapon Attack:* `dice:1d20+12|noform|text(+12)` to hit, reach 10 ft., one target. *Hit:* `dice:2d10+6|noform|avg|text(17)` (`2d10 + 6`) piercing damage. Instead of dealing damage, the dragon can end one magical effect of its choice of 5th level or lower on the target.

***Claw.*** *Melee Weapon Attack:* `dice:1d20+12|noform|text(+12)` to hit, reach 5 ft., one target. *Hit:* `dice:2d6+6|noform|avg|text(13)` (`2d6 + 6`) slashing damage, and if the target isn't a Construct or Undead, it must succeed on a DC 19 Constitution saving throw or lose 7 `dice:2d6|noform|avg` (`2d6`) hp at the start of each of its turns as a piece of metallic claw breaks off in the wound. Any creature can take an action to remove the claw with a successful DC 14 Wisdom ([Medicine](2-Mechanics/CLI/rules/skills.md#Medicine)) check. The claw pops out of the wound if the target receives magical healing.

***Tail.*** *Melee Weapon Attack:* `dice:1d20+12|noform|text(+12)` to hit, reach 15 ft., one target. *Hit:* `dice:2d8+6|noform|avg|text(15)` (`2d8 + 6`) bludgeoning damage.

***Frightful Presence.*** Each creature of the dragon's choice that is within 120 feet of the dragon and aware of it must succeed on a DC 18 Wisdom saving throw or become [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened) for 1 minute. A creature can repeat the saving throw at the end of its turns, ending the effect on itself on a success. If a creature's saving throw is successful or the effect ends for it, the creature is immune to the dragon's Frightful Presence for the next 24 hours.

***Shard Breath (Recharge 5-6).*** The mithral dragon spits metallic shards in a 60-foot cone. Each creature in that area must make a DC 19 Constitution saving throw, taking `dice:12d6|noform|avg|text(42)` (`12d6`) slashing damage on a failed save, or half as much on a successful one. The area becomes difficult terrain for 1 minute, then the shards dissolve into wisps of silvery smoke. When a creature moves into or within the area, it takes `dice:2d6|noform|avg|text(7)` (`2d6`) slashing damage for every 5 feet it travels.

## Legendary Actions

***Detect.*** The dragon makes a Wisdom ([Perception](2-Mechanics/CLI/rules/skills.md#Perception)) check.

***Tail Attack.*** The dragon makes a Tail attack.

***Wing Attack (Costs 2 Actions).*** The dragon beats its wings. Each creature within 10 feet of the dragon must succeed on a DC 20 Dexterity saving throw or take `dice:2d6+6|noform|avg|text(13)` (`2d6 + 6`) bludgeoning damage and be knocked [prone](2-Mechanics/CLI/rules/conditions.md#Prone). The dragon can then fly up to half its flying speed.

![Mithral Dragon](2-Mechanics/CLI/bestiary/legendary-group/mithral-dragon-tob1-2023.md)
```
^statblock

## Environment

mountain