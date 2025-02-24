---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/dodk
- monster/cr/4
- monster/size/medium
- monster/type/undead
aliases: ["Warp Witch"]
---
# Warp Witch
*Source: Dungeons of Drakkenheim p. 198*  

These ethereal phantoms haunt the places where they died, grasping for any memory of their former identities. Their mental anguish breaks the minds of those who hear their wails, and they induce rapid mutations when they possess humanoid bodies.

```ad-statblock
title: Warp Witch
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/DoDk/Warp%20Witch.webp#token)
*Medium undead, Any alignment*

- **Armor Class** 11
- **Hit Points** 45 (`10d8`)
- **Speed** 0 ft., fly 40 ft. (hover)

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
| 7 (-2)|13 (+1)|10 (+0)|10 (+0)|12 (+1)|17 (+3)|

- **Proficiency Bonus** +2
- **Saving Throws** ⏤
- **Skills** ⏤
- **Senses** darkvision 60 ft., passive Perception 11
- **Damage Resistances** acid; fire; lightning; thunder; bludgeoning, piercing, slashing from nonmagical attacks
- **Damage Immunities** cold, necrotic, poison
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened), [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled), [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed), [petrified](2-Mechanics/CLI/rules/conditions.md#Petrified), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned), [prone](2-Mechanics/CLI/rules/conditions.md#Prone), [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained)
- **Languages** any languages it knew in life
- **Challenge** 4

## Traits

***Ethereal Sight.*** The warp witch can see 60 feet into the Ethereal Plane when it is on the Material Plane, and vice versa.

***Incorporeal Movement.*** The warp witch can move through other creatures and objects as if they were difficult terrain. It takes `dice:1d10|noform|avg|text(5)` (`1d10`) force damage if it ends its turn inside an object.

## Actions

***Withering Touch.*** *Melee Weapon Attack:* `dice:1d20+5|noform|text(+5)` to hit, reach 5 ft., one target. *Hit:* `dice:4d6+3|noform|avg|text(17)` (`4d6 + 3`) necrotic damage.

***Etherealness.*** The warp witch enters the Ethereal Plane from the Material Plane, or vice versa. It is visible on the Material Plane while it is in the Border Ethereal, and vice versa, yet it can't affect or be affected by anything on the other plane.

***Psychic Wail (Recharge 5-6).*** Every creature within 30 feet of the warp witch must succeed on a DC 13 Intelligence saving throw or take `dice:3d6|noform|avg|text(10)` (`3d6`) psychic damage and become [incapacitated](2-Mechanics/CLI/rules/conditions.md#Incapacitated) until the end of the warp witches next turn.

***Mutate Host.*** The warp witch can use a bonus action while it is possessing a creature to force mutations upon its host. The possessed creature must succeed on a DC 13 Charisma saving throw or gain one level of contamination. Rather than rolling to determine if a mutation occurs, the warp witch automatically causes a random mutation.

***Possession (Recharge 6).*** One humanoid that the warp witch can see within 5 feet of it must succeed on a DC 13 Charisma saving throw or be possessed by the warp witch; the warp witch then disappears, and the target is [incapacitated](2-Mechanics/CLI/rules/conditions.md#Incapacitated) and loses control of its body. The warp witch now controls the body but doesn't deprive the target of awareness. The warp witch can't be targeted by any attack, spell, or other effect, except ones that turn undead, and it retains its alignment, Intelligence, Wisdom, Charisma, and immunity to being [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed) and [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened). It otherwise uses the possessed target's statistics, but doesn't gain access to the target's knowledge, class features, or proficiencies.

The possession lasts until the body drops to 0 hit points, the warp witch ends it as a bonus action, or the warp witch is turned or forced out by an effect like the [dispel evil and good](2-Mechanics/CLI/spells/dispel-evil-and-good.md) spell. When the possession ends, the warp witch reappears in an unoccupied space within 5 feet of the body. The target is immune to this warp witch's Possession for 24 hours after succeeding on the saving throw or after the possession ends.
```
^statblock