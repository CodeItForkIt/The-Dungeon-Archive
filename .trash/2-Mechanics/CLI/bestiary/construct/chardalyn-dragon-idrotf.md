---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/idrotf
- monster/cr/11
- monster/size/huge
- monster/type/construct
aliases: ["Chardalyn Dragon"]
---
# Chardalyn Dragon
*Source: Icewind Dale: Rime of the Frostmaiden p. 281*  

This construct is fashioned from pieces of chardalyn (see the sidebar on Chardalyn) that have been assembled in the form of a dragon. The only parts of the dragon not forged from chardalyn are its wing flaps, which are made of an oily film as tough as rubber, and its heart, which is an orb of pulsating, radiant energy. Demonic magic suffusing the chardalyn imbues the construct with malevolence, allowing it to enjoy the terror it causes. This effect extends outward from it, corrupting other creatures who get too close to the dragon. Those affected by the dragon's presence turn their efforts to helping the dragon inflict suffering on others.

A chardalyn dragon serves the tyrannical will of its evil creator—a tireless drive devotion that exceeds its own instinct of self-preservation. Thus, the dragon will destroy itself in pursuit of its master's desires if necessary. The dragon likes to tear foes apart, as well as knock down doors and other structures. Against enemies it can't reach, it fires a beam of destructive radiance from its grill-like maw.

```ad-statblock
title: Chardalyn Dragon
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/IDRotF/Chardalyn%20Dragon.webp#token)
*Huge construct, Chaotic Evil*

- **Armor Class** 17 (natural armor)
- **Hit Points** 147 (`14d12 + 56`)
- **Speed** 30 ft., fly 90 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|24 (+7)|11 (+0)|19 (+4)|10 (+0)|10 (+0)| 3 (-4)|

- **Proficiency Bonus** +4
- **Saving Throws** Strength +11, Constitution +8
- **Skills** ⏤
- **Senses** darkvision 120 ft., passive Perception 10
- **Damage Resistances** radiant; bludgeoning, piercing, slashing from nonmagical attacks
- **Damage Immunities** cold, poison
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened), [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed), [petrified](2-Mechanics/CLI/rules/conditions.md#Petrified), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** the languages known by its creator
- **Challenge** 11

## Traits

***Immutable Form.*** The dragon is immune to any spell or effect that would alter its form.

***Magic Resistance.*** The dragon has advantage on saving throws against spells and other magical effects.

***Siege Monster.*** The dragon deals double damage to objects and structures.

***Unusual Nature.*** The dragon doesn't require air, food, drink, or sleep, and it gains no benefit from finishing a short or long rest.

## Actions

***Multiattack.*** The dragon uses its Malevolent Presence. It then makes three attacks: two with its claws and one with its tail. If the dragon isn't flying, it can also make one attack with its wings.

***Claw.*** *Melee Weapon Attack:* `dice:1d20+11|noform|text(+11)` to hit, reach 5 ft., one target. *Hit:* `dice:2d6+7|noform|avg|text(14)` (`2d6 + 7`) slashing damage.

***Tail.*** *Melee Weapon Attack:* `dice:1d20+11|noform|text(+11)` to hit, reach 10 ft., one target. *Hit:* `dice:2d10+7|noform|avg|text(18)` (`2d10 + 7`) bludgeoning damage.

***Wings.*** *Melee Weapon Attack:* `dice:1d20+11|noform|text(+11)` to hit, reach 10 ft., one target. *Hit:* `dice:2d4+7|noform|avg|text(12)` (`2d4 + 7`) bludgeoning damage.

***Malevolent Presence.*** Any creature with an Intelligence of 4 or more that is within 30 feet of the dragon must succeed on a DC 16 Wisdom saving throw or be [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed) by it for 1 minute. A creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success. If a creature's saving throw is successful or the effect ends for it, the creature is immune to the dragon's Malevolent Presence for the next 24 hours. A creature [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed) in this way fixates on another creature or object that the dragon mentally chooses and must, on each of its turns, move as close as it can to that target and use its action to make a melee attack against it. If the dragon doesn't choose a target, the [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed) creature can act normally on its turn.

***Radiant Breath (Recharge 5-6).*** The dragon exhales a ray of radiant energy in a 120-foot line that is 5 feet wide. Each creature in that line must make a DC 16 Dexterity saving throw, taking `dice:7d8|noform|avg|text(31)` (`7d8`) radiant damage on a failed save, or half as much damage on a successful one.
```
^statblock