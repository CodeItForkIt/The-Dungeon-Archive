---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/dsotdq
- monster/cr/7
- monster/size/medium
- monster/type/undead
aliases: ["Skeletal Knight"]
---
# Skeletal Knight
*Source: Dragonlance: Shadow of the Dragon Queen p. 208*  

Skeletal knights are powerful Undead that arise to serve even more wicked beings—often death knights. Those who become skeletal knights were typically virtuous in life but betrayed their oaths and died in disgrace. Unable to rest, they are now unswervingly loyal to the villains they serve. Should a skeletal knight's master be destroyed, the knight regains its will and is free to pursue its own ends.

Skeletal knights are relentless in battle and difficult to destroy. They cling to the sins that curse them, and they fight until their skulls are reduced to shards. Their blades deal lingering wounds that sap their victims' life force and leave blackened scars even after magical healing.

```ad-statblock
title: Skeletal Knight
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/DSotDQ/Skeletal%20Knight.webp#token)
*Medium undead, typically  Lawful Evil*

- **Armor Class** 18 ([plate](2-Mechanics/CLI/items/plate-armor.md))
- **Hit Points** 112 (`15d8 + 45`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|20 (+5)|10 (+0)|16 (+3)|13 (+1)|14 (+2)|10 (+0)|

- **Proficiency Bonus** +3
- **Saving Throws** Constitution +6, Wisdom +5
- **Skills** ⏤
- **Senses** darkvision 60 ft., passive Perception 12
- **Damage Immunities** poison
- **Condition Immunities** [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** understands the languages it knew in life but can't speak
- **Challenge** 7

## Traits

***Undead Fortitude.*** If damage reduces the skeletal knight to 0 hit points, it must make a Constitution saving throw with a DC of 5 + the damage taken, unless the damage is bludgeoning or from a critical hit. On a success, the skeletal knight drops to 1 hit point instead.

***Unusual Nature.*** The skeletal knight doesn't require air, food, drink, or sleep.

## Actions

***Multiattack.*** The skeletal knight makes three Enervating Blade or Throwing Axe attacks in any combination.

***Enervating Blade.*** *Melee Weapon Attack:* `dice:1d20+8|noform|text(+8)` to hit, reach 5 ft., one target. *Hit:* `dice:3d6+5|noform|avg|text(15)` (`3d6 + 5`) necrotic damage, and if the target is a creature, it can't regain hit points until the start of the skeletal knight's next turn.

***Throwing Axe.*** *Melee or Ranged Weapon Attack:* `dice:1d20+8|noform|text(+8)` to hit, reach 5 ft. or range 20/60 ft., one target. *Hit:* `dice:2d8+5|noform|avg|text(14)` (`2d8 + 5`) slashing damage.
```
^statblock