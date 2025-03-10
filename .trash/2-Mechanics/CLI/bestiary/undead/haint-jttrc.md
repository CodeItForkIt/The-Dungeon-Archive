---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/jttrc
- monster/cr/7
- monster/size/medium
- monster/type/undead
aliases: ["Haint"]
---
# Haint
*Source: Journeys through the Radiant Citadel p. 185*  

Rising from the sorrowful dead, haints are spirits that change their shape in tragic imitation of what they once were. A haint can shift from its spectral form to appear as the corporeal Humanoid it was in life, passing as a living creature. These spirits might mistakenly view innocents as those who killed them or entreat mortals to exact revenge on their behalf.

```ad-statblock
title: Haint
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/JttRC/Haint.webp#token)
*Medium undead, typically  Neutral*

- **Armor Class** 12
- **Hit Points** 75 (`10d8 + 30`)
- **Speed** 30 ft., fly 30 ft. (hover)

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
| 7 (-2)|15 (+2)|17 (+3)|10 (+0)|13 (+1)|17 (+3)|

- **Proficiency Bonus** +3
- **Saving Throws** ⏤
- **Skills** Deception +6, Stealth +8
- **Senses** darkvision 60 ft., passive Perception 11
- **Damage Resistances** acid; fire; thunder; bludgeoning, piercing, slashing from nonmagical attacks
- **Damage Immunities** cold, necrotic, poison
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened), [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled), [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed), [petrified](2-Mechanics/CLI/rules/conditions.md#Petrified), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned), [prone](2-Mechanics/CLI/rules/conditions.md#Prone), [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained)
- **Languages** any languages it knew in life
- **Challenge** 7

## Traits

***Incorporeal Movement.*** The haint can move through other creatures and objects as if they were difficult terrain. It takes `dice:1d10|noform|avg|text(5)` (`1d10`) force damage if it ends its turn inside an object.

***Unusual Nature.*** The haint doesn't require air, food, drink, or sleep.

## Actions

***Multiattack.*** The haint makes two Sorrowful Touch attacks.

***Sorrowful Touch.*** *Melee Spell Attack:* `dice:1d20+6|noform|text(+6)` to hit, reach 5 ft., one creature. *Hit:* `dice:4d8+3|noform|avg|text(21)` (`4d8 + 3`) psychic damage.

***Change Shape.*** The haint magically assumes the appearance of the Humanoid it was in life, while retaining its game statistics. The assumed appearance ends if the haint is reduced to 0 hit points or uses an action to end it.

## Bonus Actions

***Shared Sorrow.*** The haint targets one creature it can see within 60 feet of itself that is missing any hit points, sharing its own torment with this pained soul. The target must succeed on a DC 14 Wisdom saving throw or be [incapacitated](2-Mechanics/CLI/rules/conditions.md#Incapacitated).

A creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success. If a creature's saving throw is successful or the effect ends for it, the creature is immune to the haint's Shared Sorrow for the next 24 hours.
```
^statblock