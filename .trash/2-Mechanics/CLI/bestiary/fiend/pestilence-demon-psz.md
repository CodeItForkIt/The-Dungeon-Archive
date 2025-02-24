---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/psz
- monster/cr/6
- monster/size/large
- monster/type/fiend/demon
aliases: ["Pestilence Demon"]
---
# Pestilence Demon
*Source: Plane Shift: Zendikar p. 27*  

The dark reflections of angels, demons are the incarnation of black mana and all it represents—selfish desire and lust for power. Their forms are roughly humanoid, but distorted and bestial. Their grotesque heads feature elongated ears, spiky protrusions, and large horns. (The size and number of a demon's horns are an indication of its age and power.) Spikes protrude from their backs and arms, and their hands are warped into large, sharp claws. Most demons have large, leathery wings, and a few have long tails. Their skin has an inhuman texture—dry and leathery for some; stony and cold for others. Their eyes are small points of red or blue light that glow as if revealing an inner inferno.

Unlike angels, demons reject any form of society or alliance. They are utterly selfish and hoard power in many different forms, including wealth, magic, territory, and slaves. Drawn to places where black mana flows freely, they often dwell in ancient crypts or in ruins deep in swampy terrain. Their presence defiles any remaining scrap of purity or goodness in an area, and often extends the bounds of a swamp or stirs up the restless spirits of the dead.

Any demon, devil, or yugoloth in the Monster Manual can stand in for a demon of Zendikar. The vile green mist surrounding a pestilence demon suggests it might have poison like a [vrock](2-Mechanics/CLI/bestiary/fiend/vrock.md), for example.

```ad-statblock
title: Pestilence Demon
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/PSZ/Pestilence%20Demon.webp#token)
*Large fiend (demon), Chaotic Evil*

- **Armor Class** 15 (natural armor)
- **Hit Points** 104 (`11d10 + 44`)
- **Speed** 40 ft., fly 60 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|17 (+3)|15 (+2)|18 (+4)| 8 (-1)|13 (+1)| 8 (-1)|

- **Proficiency Bonus** +3
- **Saving Throws** Dexterity +5, Wisdom +4, Charisma +2
- **Skills** ⏤
- **Senses** darkvision 120 ft., passive Perception 11
- **Damage Resistances** cold; fire; lightning; bludgeoning, piercing, slashing from nonmagical attacks
- **Damage Immunities** poison
- **Condition Immunities** [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** Abyssal, telepathy 120 ft.
- **Challenge** 6

## Traits

***Magic Resistance.*** The demon has advantage on saving throws against spells and other magical effects.

## Actions

***Multiattack.*** The demon makes two attacks: one with its beak and one with its talons.

***Beak.*** *Melee Weapon Attack:* `dice:1d20+6|noform|text(+6)` to hit, reach 5 ft., one target. *Hit:* `dice:2d6+3|noform|avg|text(10)` (`2d6 + 3`) piercing damage.

***Talons.*** *Melee Weapon Attack:* `dice:1d20+6|noform|text(+6)` to hit, reach 5 ft., one target. *Hit:* `dice:2d10+3|noform|avg|text(14)` (`2d10 + 3`) slashing damage.

***Spores (Recharge 6).*** A 15-foot-radius cloud of toxic spores extends out from the demon. The spores spread around corners. Each creature in that area must succeed on a DC 14 Constitution saving throw or become [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned). While [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned) in this way, a target takes `dice:1d10|noform|avg|text(5)` (`1d10`) poison damage at the start of each of its turns. A target can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success. Emptying a vial of holy water on the target also ends the effect on it.

***Stunning Screech (1/Day).*** The demon emits a horrific screech. Each creature within 20 feet of it that can hear it and that isn't a demon must succeed on a DC 14 Constitution saving throw or be [stunned](2-Mechanics/CLI/rules/conditions.md#Stunned) until the end of the demon's next turn.
```
^statblock