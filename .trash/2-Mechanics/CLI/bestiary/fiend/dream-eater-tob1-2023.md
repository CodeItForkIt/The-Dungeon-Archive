---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/tob1-2023
- monster/cr/5
- monster/environment/urban
- monster/size/medium
- monster/type/fiend
aliases: ["Dream Eater"]
---
# Dream Eater
*Source: Tome of Beasts 1 (2023 Edition) p. 148*  

*This tattered skeletal humanoid resembles a monster from a nightmare with vestigial skeletal wings with a few feathers, small horns, sharp teeth, and cloven hooves.*

## Drawn to Sin

Dream eaters are dedicated to lust, gluttony, and greed. They make their lairs in casinos, brothels, thieves' dens, and other locations where gambling, food, and other pleasures are readily available. Sometimes dream eaters work together to create such a place, especially near large towns or cities. Some band together to create traveling shows, offering all the oddities, whimsies, and flights of fantasy customary for such entertainers.

## Devouring Hopes

Dream eaters lure people into their lairs, enticing them with promises of pleasure or wealth. Of course, they make sure the odds are stacked in their favor. Eventually, their victims are left with nothing. Worse than the loss of physical treasures, dream eaters leave their victims stripped of hopes and aspirations. Dream eaters feed on emotions, leaving helpless thralls willing to sell their souls for their vices.

## Statblock

```ad-statblock
title: Dream Eater
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ToB1-2023/Dream%20Eater.webp#token)
*Medium fiend, Lawful Evil*

- **Armor Class** 15 (natural armor)
- **Hit Points** 75 (`10d8 + 30`)
- **Speed** 30 ft., fly 20 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|15 (+2)|18 (+4)|17 (+3)|16 (+3)|13 (+1)|20 (+5)|

- **Proficiency Bonus** +3
- **Saving Throws** ⏤
- **Skills** Deception +8, Insight +4, Persuasion +8
- **Senses** darkvision 60 ft., passive Perception 11
- **Damage Resistances** cold; fire; lightning; bludgeoning, piercing, slashing from nonmagical attacks
- **Damage Immunities** poison
- **Condition Immunities** [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** Abyssal, Celestial, Common, Infernal, telepathy 120 ft.
- **Challenge** 5

## Traits

***Dream Eater's Caress.*** A creature that starts its turn [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) by the dream eater must succeed on a DC 14 Charisma saving throw or take `dice:2d4|noform|avg|text(5)` (`2d4`) psychic damage. The dream eater gains temporary hp equal to the psychic damage dealt.

## Actions

***Multiattack.*** The dream eater uses its Lotus Scent. It then makes one Bite attack and one Claw attack.

***Bite.*** *Melee Weapon Attack:* `dice:1d20+7|noform|text(+7)` to hit, reach 5 ft., one target. *Hit:* `dice:2d10+4|noform|avg|text(15)` (`2d10 + 4`) piercing damage.

***Claw.*** *Melee Weapon Attack:* `dice:1d20+7|noform|text(+7)` to hit, reach 5 ft., one target. *Hit:* `dice:2d8+4|noform|avg|text(13)` (`2d8 + 4`) slashing damage, and the target is [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) (escape DC 14) if it is a Large or smaller creature. Until this grapple ends, the creature is [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained). The dream eater has two claws, each of which can grapple only one target.

***Lotus Scent.*** The dream eater secretes an oily chemical that most creatures find intoxicating. Each creature that isn't a Construct or Undead within 15 feet of the dream eater must succeed on a DC 14 Constitution saving throw or be [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned) for 1 minute. While [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned), the creature is [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed) by the fiend. A [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned) creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success. If a creature's saving throw is successful or the effect ends for it, the creature is immune to the dream eater's Lotus Scent for the next 24 hours.

***Waking Dreams (Recharge 5-6).*** Each creature within 20 feet of the dream eater must make a DC 14 Charisma saving throw. On a failure, a creature takes `dice:6d6|noform|avg|text(21)` (`6d6`) psychic damage and is [incapacitated](2-Mechanics/CLI/rules/conditions.md#Incapacitated) for 1 minute. When it moves, an [incapacitated](2-Mechanics/CLI/rules/conditions.md#Incapacitated) creature moves in a random direction. On a success, a creature takes half the damage and isn't [incapacitated](2-Mechanics/CLI/rules/conditions.md#Incapacitated). A creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.

## Bonus Actions

***Change Shape.*** The dream eater magically transforms into a Small or Medium humanoid it has seen, or back into its true form, which is a Fiend. Its statistics, other than its size, are the same in each form. Any equipment it is wearing or carrying transforms with it. It reverts to its true form if it dies.
```
^statblock

## Environment

urban