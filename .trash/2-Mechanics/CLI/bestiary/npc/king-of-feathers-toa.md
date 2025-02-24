---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/toa
- monster/cr/8
- monster/size/huge
- monster/type/monstrosity
aliases: ["King of Feathers"]
---
# King of Feathers
*Source: Tomb of Annihilation p. 106*  

The monstrous tyrannosaurus known as the King of Feathers is the undisputed lord of Omu. Most other dwellers of the Forbidden City live in fear of its thunderous approach and steer well clear of the amphitheater, its lair.

```ad-statblock
title: King of Feathers
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ToA/King%20of%20Feathers.webp#token)
*Huge monstrosity, Unaligned*

- **Armor Class** 13 (natural armor)
- **Hit Points** 200 (`19d12 + 52`)
- **Speed** 50 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|25 (+7)|10 (+0)|19 (+4)| 2 (-4)|12 (+1)| 9 (-1)|

- **Proficiency Bonus** +3
- **Saving Throws** ⏤
- **Skills** Perception +4
- **Senses** passive Perception 14
- **Languages** —
- **Challenge** 8

## Traits

***Detect Invisibility.*** The King of Feathers can see [invisible](2-Mechanics/CLI/rules/conditions.md#Invisible) creatures and objects as if they were visible.

***Legendary Resistance (3/Day).*** If the King of Feathers fails a saving throw, it can choose to succeed instead.

***Innate Spellcasting.*** The King of Feathers's innate spellcasting ability is Wisdom. It can innately cast the following spell, requiring no material components:

**At will**: [misty step](2-Mechanics/CLI/spells/misty-step.md)

## Actions

***Multiattack.*** The King of Feathers makes two attacks: one with its bite and one with its tail. It can't make both attacks against the same target.

***Bite.*** *Melee Weapon Attack:* `dice:1d20+10|noform|text(+10)` to hit, reach 10 ft., one target. *Hit:* `dice:4d12+7|noform|avg|text(33)` (`4d12 + 7`) piercing damage. If the target is a Medium or smaller creature, it is [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) (escape DC 17). Until this grapple ends, the target is [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained), and the tyrannosaurus can't bite another target.

***Tail.*** *Melee Weapon Attack:* `dice:1d20+10|noform|text(+10)` to hit, reach 10 ft., one target. *Hit:* `dice:3d8+7|noform|avg|text(20)` (`3d8 + 7`) bludgeoning damage.

***Summon Swarm (Recharge 5-6).*** The King of Feathers exhales a [swarm of insects (wasps)](2-Mechanics/CLI/bestiary/beast/swarm-of-wasps.md) that forms in a space within 20 feet of it. The swarm acts as an ally of the King of Feathers and takes its turn immediately after it. The swarm disperses after 1 minute. It can't use the Summon Swarm action while it is grappling a creature with its jaws.
```
^statblock