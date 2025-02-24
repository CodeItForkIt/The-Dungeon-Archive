---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/wbtw
- monster/cr/13
- monster/size/huge
- monster/type/dragon
aliases: ["Jabberwock"]
---
# Jabberwock
*Source: The Wild Beyond the Witchlight p. 236*  

A jabberwock is a solitary, temperamental predator that haunts pristine forests and ancient ruins. Accurate descriptions of jabberwocks are difficult to come by, because the rare survivors of an encounter with one retain only a confused impression of its parts and not a sense of the whole. Pieced-together accounts describe it as a sinewy, dragon-like creature that can walk on its hind legs as easily as it travels on all four. Its eyes can emit fiery beams.

Once a jabberwock has chosen its target, it concentrates its attacks on that target until the victim is killed (and devoured), until the jabberwock is killed, or until the target escapes using teleportation magic or other means.

If a jabberwock is slain, another one appears `dice:3d8|noform|avg` (`3d8`) years later, materializing within a thousand miles of where the old one perished. No immature jabberwock has ever been sighted, and the creature does not appear to age.

```ad-statblock
title: Jabberwock
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/WBtW/Jabberwock.webp#token)
*Huge dragon, typically  Chaotic Evil*

- **Armor Class** 18 (natural armor)
- **Hit Points** 115 (`10d12 + 50`)
- **Speed** 30 ft., climb 30 ft., fly 60 ft., swim 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|20 (+5)|12 (+1)|20 (+5)| 4 (-3)| 7 (-2)|11 (+0)|

- **Proficiency Bonus** +5
- **Saving Throws** Strength +10, Dexterity +6, Constitution +10, Intelligence +2, Wisdom +3, Charisma +5
- **Skills** Perception +8
- **Senses** truesight 120 ft., passive Perception 18
- **Damage Vulnerabilities** slashing from a vorpal sword
- **Damage Immunities** poison
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** —
- **Challenge** 13

## Traits

***Confusing Burble.*** The jabberwock burbles to itself unless it is [incapacitated](2-Mechanics/CLI/rules/conditions.md#Incapacitated). Any creature that starts its turn within 30 feet of the jabberwock and is able to hear its burbling must make a DC 18 Charisma saving throw. On a failed saving throw, the creature can't take reactions until the start of its next turn, and it rolls a `dice:d4|noform|avg` (`d4`) to determine what it does during its current turn:

- **1-2.** The creature does nothing.  
- **3.** The creature does nothing except use all its movement to move in a random direction.  
- **4.** The creature either makes one melee attack against a random creature it can see or does nothing if no visible creature is within its reach.  

***Legendary Resistance (3/Day).*** If the jabberwock fails a saving throw, it can choose to succeed instead.

***Regeneration.*** The jabberwock regains 10 hit points at the start of its turn. If the jabberwock takes slashing damage, this trait doesn't function at the start of its next turn. The jabberwock dies only if it starts its turn with 0 hit points and doesn't regenerate.

***Uncanny Tracker.*** The jabberwock can unerringly track any creature it has wounded in the last 24 hours, and it knows the distance and direction to its quarry as long as the two of them are on the same plane of existence.

## Actions

***Multiattack.*** The jabberwock makes two Rend attacks.

***Rend.*** *Melee Weapon Attack:* `dice:1d20+10|noform|text(+10)` to hit, reach 10 ft., one target. *Hit:* `dice:3d10+5|noform|avg|text(21)` (`3d10 + 5`) slashing damage.

***Tail.*** *Melee Weapon Attack:* `dice:1d20+10|noform|text(+10)` to hit, reach 15 ft., one target. *Hit:* `dice:1d10+5|noform|avg|text(10)` (`1d10 + 5`) bludgeoning damage.

***Fiery Gaze (Recharge 5-6).*** Unless it is [blinded](2-Mechanics/CLI/rules/conditions.md#Blinded), the jabberwock emits a 120-foot-long, 5-foot-wide line of fire from its eyes. Each creature in that line must make a DC 18 Dexterity saving throw, taking `dice:7d8|noform|avg|text(31)` (`7d8`) fire damage on a failed save, or half as much damage on a successful one.

## Legendary Actions

***Tail Attack.*** The jabberwock makes one Tail attack.

***Rend Attack (2 Actions).*** The jabberwock makes one Rend attack.

***Wing Attack (3 Actions).*** The jabberwock beats its wings. Each creature within 10 feet of the jabberwock must succeed on a DC 18 Dexterity saving throw or take `dice:1d6+5|noform|avg|text(8)` (`1d6 + 5`) bludgeoning damage and be knocked [prone](2-Mechanics/CLI/rules/conditions.md#Prone).
```
^statblock