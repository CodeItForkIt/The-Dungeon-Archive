---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/psz
- monster/cr/5
- monster/size/medium
- monster/type/undead
aliases: ["Wraith"]
---
# Wraith
*Source: Plane Shift: Zendikar p. 28*  

Magic fueled by black mana can alter the natural cycle of life and death. Whether wielded by mortal wizards or demons, or simply an environmental manifestation of black mana's flow through the land, such magic can trap spirits between the realm of the living and the mysterious fate of the dead. These ghostly undead are as destructive and hateful as the magic that calls them into being. Zendikar's shades and wraiths can be represented by the [shadows](2-Mechanics/CLI/bestiary/undead/shadow.md) and [wraiths](2-Mechanics/CLI/bestiary/undead/wraith.md) in the Monster Manual.

Not all spirits are created with black mana, however, and not all are malevolent. The spirits of the dead sometimes linger in the world to protect their kin or communities, or to stand guard over sacred or important sites. These spirits can be dangerous, but they are not usually malicious. Both the kor and the Mul Daya elves remain in communion with the spirits of their dead kindred, entreating them for wisdom and protection. Such spirits are best described as the [ghosts](2-Mechanics/CLI/bestiary/undead/ghost.md) in the Monster Manual.

```ad-statblock
title: Wraith
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/PSZ/Wraith.webp#token)
*Medium undead, Neutral Evil*

- **Armor Class** 13
- **Hit Points** 67 (`9d8 + 27`)
- **Speed** 0 ft., fly 60 ft. (hover)

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
| 6 (-2)|16 (+3)|16 (+3)|12 (+1)|14 (+2)|15 (+2)|

- **Proficiency Bonus** +3
- **Saving Throws** ⏤
- **Skills** ⏤
- **Senses** darkvision 60 ft., passive Perception 12
- **Damage Resistances** acid; cold; fire; lightning; thunder; bludgeoning, piercing, slashing from nonmagical attacks that aren't silvered
- **Damage Immunities** necrotic, poison
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled), [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed), [petrified](2-Mechanics/CLI/rules/conditions.md#Petrified), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned), [prone](2-Mechanics/CLI/rules/conditions.md#Prone), [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained)
- **Languages** the languages it knew in life
- **Challenge** 5

## Traits

***Incorporeal Movement.*** The wraith can move through other creatures and objects as if they were difficult terrain. It takes `dice:1d10|noform|avg|text(5)` (`1d10`) force damage if it ends its turn inside an object.

***Sunlight Sensitivity.*** While in sunlight, the wraith has disadvantage on attack rolls, as well as on Wisdom ([Perception](2-Mechanics/CLI/rules/skills.md#Perception)) checks that rely on sight.

## Actions

***Life Drain.*** *Melee Weapon Attack:* `dice:1d20+6|noform|text(+6)` to hit, reach 5 ft., one creature. *Hit:* `dice:4d8+3|noform|avg|text(21)` (`4d8 + 3`) necrotic damage. The target must succeed on a DC 14 Constitution saving throw or its hit point maximum is reduced by an amount equal to the damage taken. This reduction lasts until the target finishes a long rest. The target dies if this effect reduces its hit point maximum to 0.

***Create Specter.*** The wraith targets a humanoid within 10 feet of it that has been dead for no longer than 1 minute and died violently. The target's spirit rises as a [specter](2-Mechanics/CLI/bestiary/undead/specter.md) in the space of its corpse or in the nearest unoccupied space. The [specter](2-Mechanics/CLI/bestiary/undead/specter.md) is under the wraith's control. The wraith can have no more than seven specters under its control at one time.
```
^statblock