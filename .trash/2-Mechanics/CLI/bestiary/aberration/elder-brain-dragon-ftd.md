---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/ftd
- monster/cr/22
- monster/size/gargantuan
- monster/type/aberration
aliases: ["Elder Brain Dragon"]
---
# Elder Brain Dragon
*Source: Fizban's Treasury of Dragons p. 194*  

One of the few consolations available to those who must contend with a mind flayer colony is the limit of its reach, which spreads only as far as the influence of the colony's elder brain. But this small solace withers away when a colony manages to capture a dragon. Teams of mind flayers bind the dragon, which is subject to a gruesome transformation as the elder brain latches onto the dragon's back and digs its tentacles into the dragon's brain. An elder brain dragon is the nightmarish result.

Using the mobility of the dragon's body, the elder brain can now serve as a powerful general to illithid armies, free from the confines of its brine pool. The elder brain dragon becomes a psychic threat in addition to a physical one, its body rife with aberrant influence and pulsing with psionic power. Even the elder brain dragon's breath weapon mutates during its transformation, becoming a stream of briny liquid roiling with illithid tadpoles. These tadpoles can swiftly slay victims and transform them into mind flayers, allowing the elder brain dragon to grow its own roving colony.

```ad-statblock
title: Elder Brain Dragon
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/FTD/Elder%20Brain%20Dragon.webp#token)
*Gargantuan aberration, typically  Lawful Evil*

- **Armor Class** 17 (natural armor)
- **Hit Points** 350 (`20d20 + 140`)
- **Speed** 40 ft., fly 80 ft. (hover)

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|27 (+8)|13 (+1)|25 (+7)|21 (+5)|19 (+4)|24 (+7)|

- **Proficiency Bonus** +7
- **Saving Throws** Constitution +14, Intelligence +12, Wisdom +11, Charisma +14
- **Skills** Arcana +12, Insight +18, Perception +18
- **Senses** blindsight 120 ft., passive Perception 28
- **Damage Immunities** psychic
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened)
- **Languages** Deep Speech, Draconic, telepathy 5 miles
- **Challenge** 22

## Traits

***Legendary Resistance (4/Day).*** If the dragon fails a saving throw, it can choose to succeed instead.

***Siege Monster.*** The dragon deals double damage to objects and structures.

***Unusual Nature.*** The dragon doesn't require air or sleep.

## Actions

***Multiattack.*** The dragon makes one Bite attack, two Claw attacks, and one Tentacle attack.

***Bite.*** *Melee Weapon Attack:* `dice:1d20+15|noform|text(+15)` to hit, reach 15 ft., one target. *Hit:* `dice:2d10+8|noform|avg|text(19)` (`2d10 + 8`) piercing damage plus `dice:2d10|noform|avg|text(11)` (`2d10`) psychic damage.

***Claw.*** *Melee Weapon Attack:* `dice:1d20+15|noform|text(+15)` to hit, reach 10 ft., one target. *Hit:* `dice:1d6+8|noform|avg|text(11)` (`1d6 + 8`) slashing damage.

***Tentacle.*** *Melee Weapon Attack:* `dice:1d20+15|noform|text(+15)` to hit, reach 15 ft., one creature. *Hit:* `dice:1d8+8|noform|avg|text(12)` (`1d8 + 8`) psychic damage. If the target is Huge or smaller, it is [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) (escape DC 18). The dragon can have up to four targets [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) at a time.

***Tadpole Brine Breath (Recharge 5-6).*** The dragon exhales brine in a 120-foot line that is 15 feet wide. Each creature in that area must make a DC 22 Constitution saving throw, taking `dice:10d10|noform|avg|text(55)` (`10d10`) psychic damage on a failed save, or half as much damage on a successful one. On a success or failure, if the creature isn't a Construct or an Undead, it becomes infested with illithid tadpoles.

While infested, the creature takes `dice:3d10|noform|avg|text(16)` (`3d10`) psychic damage at the start of each of its turns. The creature can repeat the saving throw at the end of each of its turns, ending the effect on itself after it succeeds on three of these saves. If the creature is targeted by magic that ends a curse or restores 40 hit points or more, the tadpoles infesting the creature are killed instantly, ending the effect on the creature.

If a Humanoid is reduced to 0 hit points while infested, the creature is stable but remains [unconscious](2-Mechanics/CLI/rules/conditions.md#Unconscious) for `dice:6d12|noform|avg` (`6d12`) hours. When the period of unconsciousness ends, the creature transforms into a [mind flayer](2-Mechanics/CLI/bestiary/aberration/mind-flayer.md) (see the Monster Manual) with all its hit points. Casting a [wish](2-Mechanics/CLI/spells/wish.md) spell on the [unconscious](2-Mechanics/CLI/rules/conditions.md#Unconscious) creature rids it of the infestation and prevents it from turning into a mind flayer.

## Legendary Actions

***Tentacle.*** The dragon makes one Tentacle attack.

***Shatter Concentration (Costs 2 Actions).*** The dragon targets a creature it is grappling. The target's [concentration](2-Mechanics/CLI/rules/conditions.md#Concentration) on a spell it has cast or an ability it is maintaining ends, and the target takes `dice:3d12|noform|avg|text(19)` (`3d12`) psychic damage.
```
^statblock