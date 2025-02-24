---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/mot
- monster/cr/15
- monster/size/huge
- monster/type/monstrosity
aliases: ["Typhon"]
---
# Typhon
*Source: Mythic Odysseys of Theros p. 246*  

Titanic horrors of writhing flesh and gnashing maws, typhons slither through the Underworld seeking only to consume. Once the souls of mortal warlords and cruel tyrants, typhons come into being over ages of festering bitterness and rage. Over time, these souls twist into eternally ravenous monstrosities, which rampage through the realm of the dead, consuming souls by the thousands. The Underworld remains their prison, though, and most would relish nothing more than to escape and slaughter the living once more.

```ad-statblock
title: Typhon
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/MOT/Typhon.webp#token)
*Huge monstrosity, Chaotic Evil*

- **Armor Class** 17 (natural armor)
- **Hit Points** 195 (`17d12 + 85`)
- **Speed** 40 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|24 (+7)|10 (+0)|20 (+5)| 7 (-2)|12 (+1)|13 (+1)|

- **Proficiency Bonus** +5
- **Saving Throws** Constitution +10
- **Skills** ⏤
- **Senses** darkvision 60 ft., passive Perception 11
- **Damage Immunities** acid, necrotic
- **Languages** Common
- **Challenge** 15

## Traits

***Keen Smell.*** The typhon has advantage on Wisdom ([Perception](2-Mechanics/CLI/rules/skills.md#Perception)) checks that rely on smell.

***Regeneration.*** The typhon regains 20 hit points at the start of its turn. If it takes radiant damage, this trait doesn't function at the start of its next turn. The typhon dies only if it starts its turn with 0 hit points and doesn't regenerate.

## Actions

***Multiattack.*** The typhon makes three attacks: one with its Flurry of Bites, one to constrict, and one with its maw.

***Flurry of Bites.*** *Melee Weapon Attack:* `dice:1d20+12|noform|text(+12)` to hit, reach 10 ft., one target. *Hit:* `dice:8d6+7|noform|avg|text(35)` (`8d6 + 7`) piercing damage.

***Constrict.*** *Melee Weapon Attack:* `dice:1d20+12|noform|text(+12)` to hit, reach 15 ft., one Large or smaller creature. *Hit:* `dice:3d6+7|noform|avg|text(17)` (`3d6 + 7`) bludgeoning damage, and the target is [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) (escape DC 19). Until this grapple ends, the target is [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained) and takes `dice:3d6+7|noform|avg|text(17)` (`3d6 + 7`) bludgeoning damage at the start of each of its turns. The typhon can have up to two creatures constricted.

***Maw.*** *Melee Weapon Attack:* `dice:1d20+12|noform|text(+12)` to hit, reach 10 ft., one target. *Hit:* `dice:3d12+7|noform|avg|text(26)` (`3d12 + 7`) piercing damage plus `dice:3d12|noform|avg|text(19)` (`3d12`) acid damage.
```
^statblock