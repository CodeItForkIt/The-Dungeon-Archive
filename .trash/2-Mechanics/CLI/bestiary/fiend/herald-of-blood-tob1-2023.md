---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/tob1-2023
- monster/cr/12
- monster/environment/any
- monster/size/huge
- monster/type/fiend
aliases: ["Herald of Blood"]
---
# Herald of Blood
*Source: Tome of Beasts 1 (2023 Edition) p. 232*  

*The giant has bruised, purple skin and wart-like blood blisters that deform its features. It wears cowled robes, and its staff is ebony and mithral embedded with precious stones.*

As powerful sorcerers and blood mages, heralds of blood are without peer. They enjoy enslaving ogres and giants whenever possible, though they make do with lesser slaves when they must.

## Dark Prophets

Their stirring speeches proclaim that the end times are fast approaching and that all must prepare for a bloody reckoning. Their charismatic preaching serves various elder earthly gods, who demand blood sacrifices, and dark druid orders devoted to hunting and murdering innocents. They have the power to grant strength, lust, and vitality—or to wither those who cross them.

## Blood Magic Vortexes

Beneath their giant-like veneer, heralds of blood are swirling vortexes of blood, bone, and raw magical power. They feed on ley line magic and the black blood of the earth as much as on flesh and blood.

## Statblock

```ad-statblock
title: Herald of Blood
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ToB1-2023/Herald%20of%20Blood.webp#token)
*Huge fiend, Neutral Evil*

- **Armor Class** 15 (natural armor)
- **Hit Points** 184 (`16d12 + 80`)
- **Speed** 30 ft., fly 50 ft., swim 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|22 (+6)|12 (+1)|20 (+5)|14 (+2)|17 (+3)|16 (+3)|

- **Proficiency Bonus** +4
- **Saving Throws** Strength +10, Constitution +9, Wisdom +7
- **Skills** Arcana +10, Perception +7
- **Senses** darkvision 240 ft., passive Perception 17
- **Damage Resistances** cold, fire, lightning
- **Damage Immunities** necrotic, poison
- **Condition Immunities** [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened), [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed), [petrified](2-Mechanics/CLI/rules/conditions.md#Petrified), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** Common, Draconic, Infernal, Void Speech
- **Challenge** 12

## Traits

***Blood Armor.*** Each time a creature with blood hits the herald with a melee attack while within 10 feet of the herald, the creature takes `dice:1d8|noform|avg|text(4)` (`1d8`) necrotic damage, and the herald's AC increases by 1 until the end of its next turn. The herald's AC can't be increased to more than 20 from this trait.

## Actions

***Multiattack.*** The herald makes three Herald's Staff or Blood Bolt attacks, or it makes two Herald's Staff attacks and one Grasping Slam attack.

***Herald's Staff.*** *Melee Weapon Attack:* `dice:1d20+10|noform|text(+10)` to hit, reach 10 ft., one target. *Hit:* `dice:2d6+6|noform|avg|text(13)` (`2d6 + 6`) bludgeoning damage plus `dice:3d8|noform|avg|text(13)` (`3d8`) necrotic damage.

***Grasping Slam.*** *Melee Weapon Attack:* `dice:1d20+10|noform|text(+10)` to hit, reach 10 ft., one target. *Hit:* `dice:2d10+6|noform|avg|text(17)` (`2d10 + 6`) bludgeoning damage, and the target is [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) (escape DC 17) if it is a Large or smaller creature. Until this grapple ends, the target is [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained) and takes `dice:2d8|noform|avg|text(9)` (`2d8`) necrotic damage at the start of each of its turns, and the herald can't use its Grasping Slam on another target.

***Blood Bolt.*** *Ranged Spell Attack:* `dice:1d20+7|noform|text(+7)` to hit, range 120 ft., one target. *Hit:* `dice:5d8+3|noform|avg|text(25)` (`5d8 + 3`) necrotic damage. If the target is a creature with blood, it must succeed on a DC 17 Constitution saving throw or be [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned) until the end of its next turn.

***Call Blood (Recharge 5-6).*** Each creature with blood within 10 feet of the herald must make a DC 17 Constitution saving throw, taking `dice:10d8|noform|avg|text(45)` (`10d8`) necrotic damage on a failed save, or half as much damage on a successful one. The herald then gains temporary hp equal to the single highest amount of necrotic damage dealt. A creature that fails the saving throw by 5 or more also suffers one level of [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion).

## Bonus Actions

***Grant Blood Rage.*** The herald of blood infuses reckless rage in one creature it can see within 60 feet of it that isn't a Construct or Undead. The target must succeed on a DC 17 Constitution saving throw or be enraged for a number of rounds equal to the target's Constitution modifier. While enraged, the target has advantage on all melee attack rolls, and attack rolls against it have advantage. When the rage ends, the target takes `dice:3d8|noform|avg|text(13)` (`3d8`) necrotic damage and suffers one level of [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion). A creature with any levels of [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion) automatically succeeds on this saving throw.
```
^statblock

## Environment

any