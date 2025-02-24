---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/veor
- monster/cr/6
- monster/size/medium
- monster/type/undead
aliases: ["Black Rose Bearer"]
---
# Black Rose Bearer
*Source: Vecna: Eve of Ruin p. 208*  

> [!quote] A quote from Common saying among the Knights of Solamnia  
> 
> Their existence mocks the living. Their roses mock the knights. Suffer not their presence; destroy rose bearers on sight.

A black rose bearer is a rotting corpse animated by necromancers on Krynn to serve as a guardian. Its name derives from the preserved black rose the bearer carries inside a delicate bell jar. The slightest jostle can cause the bearer to lose its grasp on the bell jar, destroying the jar and the flower within.

Normally, a black rose bearer is sluggish and placid. It follows its creator's orders and attacks intruders only languidly. If its rose is disturbed, however, the black rose bearer bursts into furious violence, attacking indiscriminately.

A bearer's black rose is an homage to the tyrannical Lord Soth, the most powerful death knight on Krynn, who was once a Solamnic Knight of the Order of the Rose.

```ad-statblock
title: Black Rose Bearer
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/VEoR/Black%20Rose%20Bearer.webp#token)
*Medium undead, typically  Neutral Evil*

- **Armor Class** 11 (natural armor)
- **Hit Points** 110 (`13d8 + 52`)
- **Speed** 20 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|17 (+3)| 6 (-2)|18 (+4)| 2 (-4)|10 (+0)| 5 (-3)|

- **Proficiency Bonus** +3
- **Saving Throws** ⏤
- **Skills** ⏤
- **Senses** darkvision 60 ft., passive Perception 10
- **Damage Immunities** poison
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** understands the languages it knew in life but can't speak
- **Challenge** 6

## Traits

***Berserk.*** Whenever the bearer takes damage or makes a Strength or Dexterity saving throw, roll a `dice:d6|noform|avg` (`d6`). On a 5 or 6, the bearer goes berserk. On each of its turns while berserk, the bearer has advantage on melee attack rolls, it can Dash as a bonus action, and it must attack the nearest creature it can see. If no creature is near enough to move to and attack, the bearer attacks an object, with preference for an object smaller than itself. Once the bearer goes berserk, it remains berserk until it is destroyed or its creator gives it a pristine black rose.

***Undead Fortitude.*** If damage reduces the bearer to 0 hit points, it must make a Constitution saving throw with a DC of 5 plus the damage taken, unless the damage is radiant or from a critical hit. On a successful save, the bearer drops to 1 hit point instead.

## Actions

***Multiattack.*** The bearer makes two Slam attacks.

***Slam.*** *Melee Weapon Attack:* `dice:1d20+6|noform|text(+6)` to hit, reach 5 ft., one target. *Hit:* `dice:2d8+3|noform|avg|text(12)` (`2d8 + 3`) bludgeoning damage plus `dice:2d10|noform|avg|text(11)` (`2d10`) necrotic damage.
```
^statblock