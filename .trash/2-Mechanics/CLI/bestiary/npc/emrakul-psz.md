---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/psz
- monster/cr/30
- monster/size/gargantuan
- monster/type/monstrosity/titan
aliases: ["Emrakul"]
---
# Emrakul
*Source: Plane Shift: Zendikar p. 38*  

```ad-statblock
title: Emrakul
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/PSZ/Emrakul.webp#token)
*Gargantuan monstrosity (titan), Unaligned*

- **Armor Class** 25 (natural armor)
- **Hit Points** 676 (`33d20 + 330`)
- **Speed** 40 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|30 (+10)|11 (+0)|30 (+10)| 3 (-4)|11 (+0)|11 (+0)|

- **Proficiency Bonus** +9
- **Saving Throws** Intelligence +5, Wisdom +9, Charisma +9
- **Skills** ⏤
- **Senses** blindsight 120 ft., passive Perception 10
- **Damage Immunities** fire; poison; bludgeoning, piercing, slashing from nonmagical attacks; psychic
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened), [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** —
- **Challenge** 30

## Traits

***Legendary Resistance (3/Day).*** If Emrakul fails a saving throw, it can choose to succeed instead.

***Magic Resistance.*** Emrakul has advantage on saving throws against spells and other magical effects.

***Reflective Carapace.*** Any time Emrakul is targeted by a [magic missile](2-Mechanics/CLI/spells/magic-missile.md) spell, a line spell, or a spell that requires a ranged attack roll, roll a `dice:d6|noform|avg` (`d6`). On a 1 to 5, Emrakul is unaffected. On a 6, Emrakul is unaffected, and the effect is reflected back at the caster as though it originated from Emrakul, turning the caster into the target.

***Siege Monster.*** Emrakul deals double damage to objects and structures.

## Actions

***Multiattack.*** Emrakul can use its Frightful Presence. It then makes five attacks: one with its bite, two with its claws, one with its horns, and one with its tail. It can use its Swallow instead of its bite.

***Bite.*** *Melee Weapon Attack:* `dice:1d20+19|noform|text(+19)` to hit, reach 10 ft., one target. *Hit:* `dice:4d12+10|noform|avg|text(36)` (`4d12 + 10`) piercing damage. If the target is a creature, it is [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) (escape DC 20). Until this grapple ends, the target is [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained), and Emrakul can't bite another target.

***Claw.*** *Melee Weapon Attack:* `dice:1d20+19|noform|text(+19)` to hit, reach 15 ft., one target. *Hit:* `dice:4d8+10|noform|avg|text(28)` (`4d8 + 10`) slashing damage.

***Horns.*** *Melee Weapon Attack:* `dice:1d20+19|noform|text(+19)` to hit, reach 10 ft., one target. *Hit:* `dice:4d10+10|noform|avg|text(32)` (`4d10 + 10`) piercing damage.

***Tail.*** *Melee Weapon Attack:* `dice:1d20+19|noform|text(+19)` to hit, reach 20 ft., one target. *Hit:* `dice:4d6+10|noform|avg|text(24)` (`4d6 + 10`) bludgeoning damage. If the target is a creature, it must succeed on a DC 20 Strength saving throw or be knocked [prone](2-Mechanics/CLI/rules/conditions.md#Prone).

***Frightful Presence.*** Each creature of Emrakul's choice within 120 feet of it and aware of it must succeed on a DC 17 Wisdom saving throw or become [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened) for 1 minute. A creature can repeat the saving throw at the end of each of its turns, with disadvantage if Emrakul is within line of sight, ending the effect on itself on a success. If a creature's saving throw is successful or the effect ends for it, the creature is immune to Emrakul's Frightful Presence for the next 24 hours.

***Swallow.*** Emrakul makes one bite attack against a Large or smaller creature it is grappling. If the attack hits, the target takes the bite's damage, the target is swallowed, and the grapple ends. While swallowed, the creature is [blinded](2-Mechanics/CLI/rules/conditions.md#Blinded) and [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained), it has total cover against attacks and other effects outside Emrakul, and it takes `dice:16d6|noform|avg|text(56)` (`16d6`) acid damage at the start of each of Emrakul's turns.

If Emrakul takes 60 damage or more on a single turn from a creature inside it, Emrakul must succeed on a DC 20 Constitution saving throw at the end of that turn or regurgitate all swallowed creatures, which fall [prone](2-Mechanics/CLI/rules/conditions.md#Prone) in a space within 10 feet of Emrakul. If Emrakul dies, a swallowed creature is no longer [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained) by it and can escape from the corpse by using 30 feet of movement, exiting [prone](2-Mechanics/CLI/rules/conditions.md#Prone).

## Legendary Actions

***Attack.*** Emrakul makes one claw attack or tail attack.

***Move.*** Emrakul moves up to half its speed.

***Chomp (Costs 2 Actions).*** Emrakul makes one bite attack or uses its Swallow.
```
^statblock