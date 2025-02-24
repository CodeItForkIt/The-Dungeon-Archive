---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/mot
- monster/cr/3
- monster/size/medium
- monster/type/undead
aliases: ["Flitterstep Eidolon"]
---
# Flitterstep Eidolon
*Source: Mythic Odysseys of Theros p. 222*  

When a mortal soul traumatically sacrifices its identity in order to escape the Underworld as a Returned, its identity manifests as a spirit-like eidolon. While eidolons possess many of the skills and details related to their past lives, they're disconnected from those experiences, choosing to wander the world or brood in haunts they're drawn to in death. They care nothing for morbid reunions with their lost bodies or Returned remnants.

Of the various types of eidolons, flitterstep eidolons are the most common and wander without purpose.

```ad-statblock
title: Flitterstep Eidolon
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/MOT/Flitterstep%20Eidolon.webp#token)
*Medium undead, Any alignment*

- **Armor Class** 14
- **Hit Points** 44 (`8d8 + 8`)
- **Speed** 40 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
| 8 (-1)|18 (+4)|13 (+1)|11 (+0)|12 (+1)|10 (+0)|

- **Proficiency Bonus** +2
- **Saving Throws** ⏤
- **Skills** Perception +3, Stealth +8
- **Senses** passive Perception 13
- **Damage Resistances** necrotic; bludgeoning, piercing, slashing from nonmagical attacks
- **Damage Immunities** poison
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened), [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled), [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed), [petrified](2-Mechanics/CLI/rules/conditions.md#Petrified), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned), [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained)
- **Languages** the languages it knew in life
- **Challenge** 3

## Traits

***Blurred Form.*** Attack rolls against the eidolon are made with disadvantage unless the eidolon is [incapacitated](2-Mechanics/CLI/rules/conditions.md#Incapacitated).

***Evasion.*** If the eidolon is subjected to an effect that allows it to make a Dexterity saving throw to take only half damage, the eidolon instead takes no damage if it succeeds on the saving throw, and only half damage if it fails. It can't use this trait if it's [incapacitated](2-Mechanics/CLI/rules/conditions.md#Incapacitated).

***Incorporeal Movement.*** The eidolon can move through other creatures and objects as if they were difficult terrain. It takes `dice:1d10|noform|avg|text(5)` (`1d10`) force damage if it ends its turn inside an object.

***Turn Resistance.*** The eidolon has advantage on saving throws against any effect that turns undead.

## Actions

***Multiattack.*** The eidolon makes two melee attacks. Immediately before or after one of its attacks, it can use Flitterstep if it is available.

***Flickering Dagger.*** *Melee Weapon Attack:* `dice:1d20+6|noform|text(+6)` to hit, reach 5 ft., one target. *Hit:* `dice:1d4+4|noform|avg|text(6)` (`1d4 + 4`) piercing damage plus `dice:1d6|noform|avg|text(3)` (`1d6`) psychic damage.

***Flitterstep (Recharge 5-6).*** The eidolon magically teleports to an unoccupied space it can see within 30 feet of it. If it makes an attack immediately after teleporting, it has advantage on the attack roll.
```
^statblock