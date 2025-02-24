---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/tob1-2023
- monster/cr/19
- monster/environment/mountain
- monster/size/huge
- monster/type/giant/shapechanger
- monster/type/giant/titan
aliases: ["Hraesvelgr"]
---
# Hraesvelgr
*Source: Tome of Beasts 1 (2023 Edition) p. 207*  

*The giant stands braced in the midst of powerful wind. With a baleful stare, he shakes his fist and bellows a war cry. The cry becomes an avian shriek, and the giant's form melts into that of a massive bird whose wings blot out the sky*.

A giant with divine blood in his veins, Hraesvelgr the Corpse Swallower is powerfully muscled. His skin is a pale bronze, his eyes are violet, and his hair is the color of storm clouds.

## Roc Form

When he takes his alternate form, Hraesvelgr becomes a tremendous roc, with massive wings that stir the wind across the sky. His eyes remain the same violet and these roc-form feathers match the color of his hair, sparkling with specks of color here and there, like jewels set in steel.

## Birth of the Wind

Hraesvelgr dwells on the fringe of the world itself. From atop the peak of his home, he creates the wind and sends it across the globe. As befits a creature of such primal power, Hraesvelgr doesn't take kindly to intruders. He gluts himself on the bodies of fools who test his might in search of the fabled riches in his home.

## Hraesvelgr's Lair

Hraesvelgr's lair is a windswept crag of gray stone at the edge of the world. At the highest pinnacle rests a massive cottage hewn from the mountainside. A great nest made from the splintered trunks of immense trees rests on the flat roof of the cottage, and the wind constantly howls.

## Statblock

```ad-statblock
title: Hraesvelgr
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ToB1-2023/Hraesvelgr.webp#token)
*Huge giant (shapechanger, titan), Neutral*

- **Armor Class** 19 (natural armor)
- **Hit Points** 241 (`21d12 + 105`)
- **Speed** 50 ft. (20 ft. fly 120 ft. in roc form)

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|25 (+7)|10 (+0)|20 (+5)|16 (+3)|17 (+3)|20 (+5)|

- **Proficiency Bonus** +6
- **Saving Throws** Dexterity +6, Intelligence +9, Wisdom +9, Charisma +11
- **Skills** Athletics +13, Perception +9, Survival +9
- **Senses** passive Perception 19
- **Damage Resistances** lightning, thunder
- **Damage Immunities** cold; bludgeoning, piercing, slashing from nonmagical attacks
- **Condition Immunities** [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion)
- **Languages** Auran, Common, Giant (can't speak in roc form)
- **Challenge** 19

## Traits

***Keen Sight (Roc Form Only).*** Hraesvelgr has advantage on Wisdom ([Perception](2-Mechanics/CLI/rules/skills.md#Perception)) checks that rely on sight.

***Influence Weather.*** Nearby weather responds to Hraesvelgr's desires. At the start of each minute, Hraesvelgr can choose to change the precipitation and wind within 3 miles of him by one stage, up or down (no action required). This effect works like the changing weather conditions aspect of the [control weather](2-Mechanics/CLI/spells/control-weather.md) spell, except Hraesvelgr can't change the temperature and the conditions change immediately.

***Legendary Resistance (3/Day).*** If Hraesvelgr fails a saving throw, he can choose to succeed instead.

## Actions

***Multiattack.*** Hraesvelgr makes one Beak attack and two Talon attacks, or he makes three Fist attacks. Alternatively, he can make three Gale Blast attacks. If two Fist attacks hit one creature, the target must succeed on a DC 19 Constitution saving throw or be [stunned](2-Mechanics/CLI/rules/conditions.md#Stunned) until the end of its next turn.

***Beak (Roc Form Only).*** *Melee Weapon Attack:* `dice:1d20+13|noform|text(+13)` to hit, reach 10 ft., one target. *Hit:* `dice:4d8+7|noform|avg|text(25)` (`4d8 + 7`) piercing damage.

***Fist (Giant Form Only).*** *Melee Weapon Attack:* `dice:1d20+13|noform|text(+13)` to hit, reach 10 ft., one target. *Hit:* `dice:3d8+7|noform|avg|text(20)` (`3d8 + 7`) bludgeoning damage.

***Talons (Roc Form Only).*** *Melee Weapon Attack:* `dice:1d20+13|noform|text(+13)` to hit, reach 5 ft., one target. *Hit:* `dice:3d6+7|noform|avg|text(17)` (`3d6 + 7`) slashing damage, and the target is [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) (escape DC 17). Until this grapple ends, the target is [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained). Hraesvelgr has two talons, each of which can grapple only one target.

***Gale Blast.*** *Ranged Spell Attack:* `dice:1d20+11|noform|text(+11)` to hit, range 120 ft., one target. *Hit:* `dice:2d8+5|noform|avg|text(14)` (`2d8 + 5`) bludgeoning damage plus `dice:2d6|noform|avg|text(7)` (`2d6`) cold damage.

***Swallow (Roc Form Only).*** Hraesvelgr makes one Beak attack against a Large or smaller creature he is grappling. If the attack hits, the target is also swallowed, and the grapple ends. While swallowed, the creature is [blinded](2-Mechanics/CLI/rules/conditions.md#Blinded) and [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained), it has total cover against attacks and other effects outside Hraesvelgr, and it takes `dice:5d6|noform|avg|text(17)` (`5d6`) acid damage at the start of each of Hraesvelgr's turns. Hraesvelgr can have only one creature swallowed at a time.

If Hraesvelgr takes 40 damage or more on a single turn from the swallowed creature, Hraesvelgr must succeed on a DC 15 Constitution saving throw at the end of that turn or regurgitate the creature, which falls [prone](2-Mechanics/CLI/rules/conditions.md#Prone) in a space within 10 feet of Hraesvelgr. Hraesvelgr has disadvantage on this saving throw if he isn't in his roc form. If Hraesvelgr dies, a swallowed creature is no longer [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained) by him and can escape from the corpse by using 15 feet of movement, exiting [prone](2-Mechanics/CLI/rules/conditions.md#Prone).

***Sudden Gust (Recharge 5-6).*** Hraesvelgr unleashes a powerful gust of wind in a 60- foot line that is 10 feet wide. Each creature in the line must make a DC 19 Strength saving throw. On a failure, a creature takes `dice:18d6|noform|avg|text(63)` (`18d6`) bludgeoning damage and is pushed up to 15 feet away from Hraesvelgr. On a success, a creature takes half the damage and isn't pushed.

## Bonus Actions

***Change Shape.*** Hraesvelgr transforms into a roc or back into his true form, which is a Giant. His statistics, other than his speed, are the same in each form. Any equipment he is wearing or carrying isn't transformed. He reverts to his true form if he dies.

## Legendary Actions

***Attack.*** Hraesvelgr makes a Fist or Talons attack.

***Move.*** Hraesvelgr moves up to his speed, or flies up to half his flying speed if in roc form, without provoking opportunity attacks.

***Ear-Splitting Screech (Costs 2 Actions; Roc Form Only).*** Hraesvelgr lets out an ear-splitting screech. Each creature within 30 feet of Hraesvelgr must succeed on a DC 19 Constitution saving throw or take `dice:4d6|noform|avg|text(14)` (`4d6`) thunder damage and be [deafened](2-Mechanics/CLI/rules/conditions.md#Deafened) until the end of its next turn.

![Hraesvelgr](2-Mechanics/CLI/bestiary/legendary-group/hraesvelgr-tob1-2023.md)
```
^statblock

## Environment

mountain