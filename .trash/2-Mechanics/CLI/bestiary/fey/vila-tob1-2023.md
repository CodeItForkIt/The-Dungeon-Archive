---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/tob1-2023
- monster/cr/5
- monster/environment/forest
- monster/size/medium
- monster/type/fey
aliases: ["Vila"]
---
# Vila
*Source: Tome of Beasts 1 (2023 Edition) p. 386*  

*A woman with hair the color of spring grass, skin like polished wood, and eyes as gray as a storm rides through the forest on the back of a large deer.*

## Dryad Cousins

The vila are kin to the dryads, and like their cousins, they serve as protectors of the deepest forests.

## Demand Oaths

Where dryads beguile to accomplish their goals, the vila coerce and threaten. They demand oaths from interlopers and enforce the oaths fiercely. Vila delight in testing the virtue of travelers and in tormenting the uncharitable and cruel with misfortune.

## Hunt with a Pack

Vila rarely travel or fight alone; they are often seen in the company of alseid, wolves, wampus cats, or deer. In combat, they sometimes ride fleet-footed deer, the better to harry opponents or escape if events turn against them.

## Statblock

```ad-statblock
title: Vila
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ToB1-2023/Vila.webp#token)
*Medium fey, Lawful Neutral*

- **Armor Class** 15
- **Hit Points** 77 (`14d8 + 14`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|12 (+1)|20 (+5)|13 (+1)|11 (+0)|14 (+2)|16 (+3)|

- **Proficiency Bonus** +3
- **Saving Throws** Constitution +4, Wisdom +5, Charisma +6
- **Skills** Animal Handling +8, Insight +5, Intimidation +6, Perception +8, Stealth +8
- **Senses** darkvision 60 ft., passive Perception 18
- **Damage Resistances** bludgeoning, piercing, slashing from nonmagical attacks
- **Languages** Common, Sylvan
- **Challenge** 5

## Traits

***Forest's Defender.*** Difficult terrain composed of nonmagical plants doesn't cost the vila extra movement, and it can pass through nonmagical plants without being slowed by them and without taking damage from them if they have thorns, spines, or a similar hazard. In addition, while in forested terrain, the vila has advantage on initiative rolls.

***Poisoned Weapons.*** The vila's weapons are coated with a magical poison harvest from the forest. When the vila hits with any weapon, the weapon deals an extra `dice:2d6|noform|avg` (`2d6`) poison damage (included in the attack).

***Speak with Beasts.*** The vila can communicate with Beasts as if they shared a language.

## Actions

***Multiattack.*** The vila can use its Song of the Forest. It then makes two Shortsword or Shortbow attacks.

***Shortsword.*** *Melee Weapon Attack:* `dice:1d20+8|noform|text(+8)` to hit, reach 5 ft., one target. *Hit:* `dice:1d6+5|noform|avg|text(8)` (`1d6 + 5`) piercing damage plus `dice:2d6|noform|avg|text(7)` (`2d6`) poison damage.

***Shortbow.*** *Ranged Weapon Attack:* `dice:1d20+8|noform|text(+8)` to hit, range 80/320 ft., one target. *Hit:* `dice:1d6+5|noform|avg|text(8)` (`1d6 + 5`) piercing damage plus `dice:2d6|noform|avg|text(7)` (`2d6`) poison damage.

***Song of the Forest.*** The vila sings one of the following songs at up to three creatures it can see within 30 feet of it. Each target that can hear the song must succeed on a DC 14 Wisdom saving throw or suffer the song's effect.

- **Ancient Lullaby.** Each creature that fails the saving throw falls [unconscious](2-Mechanics/CLI/rules/conditions.md#Unconscious) for 1 minute. The [unconscious](2-Mechanics/CLI/rules/conditions.md#Unconscious) creature wakes up if it takes damage or if another creature takes an action to shake it awake.  
- **Fascinating Melody.** Each creature that fails the saving throw is [stunned](2-Mechanics/CLI/rules/conditions.md#Stunned) until the end of its next turn.  
- **Luckless Tune.** Each creature that fails the saving throw has disadvantage on attack rolls and ability checks until the end of its next turn.  

***Denizens of the Wilds (1/Day).*** The vila magically calls `dice:1d4|noform|avg` (`1d4`) wolves or 1 wampus cat. The called creatures arrive in `dice:1d4|noform|avg` (`1d4`) rounds, acting as allies of the vila and obeying its spoken commands. The creatures remain for 1 hour, until the vila dies, or until the vila dismisses them as a bonus action.
```
^statblock

## Environment

forest