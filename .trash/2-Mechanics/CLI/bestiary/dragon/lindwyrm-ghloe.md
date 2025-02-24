---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/ghloe
- monster/cr/14
- monster/size/gargantuan
- monster/type/dragon
aliases: ["Lindwyrm"]
---
# Lindwyrm
*Source: Grim Hollow: Lairs of Etharis p. 58*  

> [!quote]  
> 
> My great grandfather spoke of the lindwyrm terrorizing the countryside and devouring whole villages. But it's been so long since anyone has seen the beast, it's likely the creature is long dead. Thank Miklas!

## Salvage

A dose of [lindwyrm venom](2-Mechanics/CLI/items/lindwyrm-venom-ghloe.md) (see Appendix A of Lairs of Etharis) can be harvested by someone proficient with a poisoner's kit and succeeds on a DC 18 Dexterity ([Sleight of Hand](2-Mechanics/CLI/rules/skills.md#Sleight%20of%20Hand)) check, but this must be done within 1 hour of the lindwyrm's death. If the check fails by 5 or more, the harvester instead poisons themselves. This injury poison is worth 1,000 gp.

## Lore

- **DC 10 Intelligence ([History](2-Mechanics/CLI/rules/skills.md#History)).** Lindwyrms sleep for 100 years and when they waken are devastating to communities in its hunting area.  
- **DC 15 Intelligence ([Nature](2-Mechanics/CLI/rules/skills.md#Nature)).** Lindwyrms have a poisonous bite and may swallow creatures they bite.  
- **DC 20 Intelligence ([Nature](2-Mechanics/CLI/rules/skills.md#Nature)).** Lindwyrms can sense vibrations in the ground from as far away as 120 ft.  

> [!note] GM Advice
> 
> One exciting adventure seed could find a powerful enemy of the adventurers looking to waken and control a lindwyrm. Whether that plot succeeds or not is up to you, but a three-way battle between involving a lindwyrm and other foes should be memorable as the action ebbs and flows.
^gm-advice

## Statblock

```ad-statblock
title: Lindwyrm
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/GHLoE/Lindwyrm.webp#token)
*Gargantuan dragon, Chaotic Neutral*

- **Armor Class** 16 (natural armor)
- **Hit Points** 186 (`12d20 + 60`)
- **Speed** 40 ft., burrow 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|23 (+6)|15 (+2)|21 (+5)| 8 (-1)|14 (+2)|12 (+1)|

- **Proficiency Bonus** +5
- **Saving Throws** Strength +11, Dexterity +7, Constitution +10
- **Skills** Perception +7, Stealth +7
- **Senses** darkvision 120 ft., tremorsense 120 ft., passive Perception 17
- **Damage Resistances** bludgeoning, piercing, slashing from nonmagical attacks
- **Damage Immunities** poison
- **Condition Immunities** [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** Draconic
- **Challenge** 14

## Traits

***Disease Immunity.*** The lindwyrm is immune to all nonmagical diseases.

***Legendary Resistance (3/Day).*** If the lindwyrm fails a saving throw, it can choose to succeed instead.

## Actions

***Multiattack.*** The lindwyrm makes three attacks: one with its bite and two with its claws. The lindwyrm can substitute a swallow attack for one of its claw attacks.

***Bite.*** *Melee Weapon Attack:* `dice:1d20+11|noform|text(+11)` to hit, reach 15 ft., one target. *Hit:* `dice:3d10+6|noform|avg|text(22)` (`3d10 + 6`) piercing damage and the target must make a DC 18 Constitution saving throw, taking 18 (`dice:4d8|noform|avg` (`4d8`)) poison damage on a failed save, or half as much damage on a successful one. On a hit, the target is also [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) (escape DC 18). Until this grapple ends, the target is [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained), and the lindwyrm can't bite another target.

***Claw.*** *Melee Weapon Attack:* `dice:1d20+11|noform|text(+11)` to hit, reach 10 ft., one target. *Hit:* `dice:2d8+6|noform|avg|text(15)` (`2d8 + 6`) slashing damage.

***Swallow.*** *Melee Weapon Attack:* `dice:1d20+11|noform|text(+11)` to hit, reach 5 ft., one Huge or smaller creature the lindwyrm is grappling. *Hit:* `dice:3d10+6|noform|avg|text(22)` (`3d10 + 6`) piercing damage, the target is swallowed, and the grapple ends. The swallowed target is [blinded](2-Mechanics/CLI/rules/conditions.md#Blinded) and [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained), it has total cover against attacks and other effects outside the lindwyrm, and it takes `dice:6d8|noform|avg|text(27)` (`6d8`) acid damage at the start of each of the lindwyrm's turns. The lindwyrm can have only one target swallowed at a time.

If the lindwyrm takes 40 damage or more on a single turn from the swallowed creature, the lindwyrm must succeed on a DC 18 Constitution saving throw at the end of that turn or regurgitate the creature, which falls [prone](2-Mechanics/CLI/rules/conditions.md#Prone) in a space within 10 feet of the lindwyrm. If the lindwyrm dies, a swallowed creature is no longer [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained) by it and can escape from the corpse using 5 feet of movement, exiting [prone](2-Mechanics/CLI/rules/conditions.md#Prone).

## Legendary Actions

***Claw Attack.*** The lindwyrm makes a claw attack.

***Burrowing Rush (Costs 2 Actions).*** The lindwyrm burrows its speed and comes up beneath a target touching the ground, making a bite attack. This movement does not provoke opportunity attacks.
```
^statblock