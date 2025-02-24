---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/dsotdq
- monster/cr/14
- monster/size/medium
- monster/type/undead
aliases: ["Wersten Kern"]
---
# Wersten Kern
*Source: Dragonlance: Shadow of the Dragon Queen p. 209*  

Wersten Kern is Lord Soth's standard bearer and champion. As with many of Soth's knights, she died alongside her liege during the Cataclysm and was cursed with undeath. In battle, she wields a wicked pike that flies Soth's black rose standard, and her cries can stop mighty warriors' hearts. Wersten staunchly follows Soth's commands, and she will serve him until she faces a second doom.

```ad-statblock
title: Wersten Kern
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/DSotDQ/Wersten%20Kern.webp#token)
*Medium undead, Lawful Evil*

- **Armor Class** 18 ([plate](2-Mechanics/CLI/items/plate-armor.md))
- **Hit Points** 178 (`21d8 + 84`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|21 (+5)|10 (+0)|18 (+4)|13 (+1)|14 (+2)|16 (+3)|

- **Proficiency Bonus** +5
- **Saving Throws** Constitution +9, Wisdom +7
- **Skills** ⏤
- **Senses** darkvision 60 ft., passive Perception 12
- **Damage Immunities** poison
- **Condition Immunities** [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** Common, Infernal, Solamnic
- **Challenge** 14

## Traits

***Undead Fortitude.*** If damage reduces Wersten to 0 hit points, she must make a Constitution saving throw with a DC of 5 + the damage taken, unless the damage is bludgeoning or from a critical hit. On a success, Wersten drops to 1 hit point instead.

***Unusual Nature.*** Wersten doesn't require air, food, drink, or sleep.

***Spellcasting.*** Wersten casts one of the following spells, requiring no material components and using Charisma as the spellcasting ability (spell save DC 16):

**1/day each**: [dispel magic](2-Mechanics/CLI/spells/dispel-magic.md), [wall of stone](2-Mechanics/CLI/spells/wall-of-stone.md)

## Actions

***Multiattack.*** Wersten makes three Banner Pike attacks and uses Terrifying Litany if it's available.

***Banner Pike.*** *Melee Weapon Attack:* `dice:1d20+10|noform|text(+10)` to hit, reach 5 ft., one target. *Hit:* `dice:1d10+5|noform|avg|text(10)` (`1d10 + 5`) piercing damage plus `dice:3d8|noform|avg|text(13)` (`3d8`) necrotic damage. If the target is a Humanoid, it must succeed on a DC 16 Charisma saving throw or be cursed. The curse lasts until it is lifted by remove curse or similar magic. Black, thorny rose stems sprout from the creature's body while it is cursed, imposing disadvantage on the creature's ability checks and attack rolls and halving its speed. A creature that succeeds on the saving throw against the curse is immune to it for 24 hours.

***Terrifying Litany (Recharge 5-6).*** Wersten recites names of souls slain by Soth and his company, channeling their mortal terror. Each creature that isn't an Undead within 30 feet of her must make a DC 16 Wisdom saving throw. On a failed save, the creature takes `dice:4d10|noform|avg|text(22)` (`4d10`) psychic damage and is [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened) of Wersten for 1 minute. On a successful save, the creature takes half as much damage and isn't [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened). At the end of each of its turns, a [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened) creature can repeat the saving throw, ending the effect on itself on a success.
```
^statblock