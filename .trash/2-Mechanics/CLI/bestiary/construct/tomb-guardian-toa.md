---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/toa
- monster/cr/5
- monster/size/medium
- monster/type/construct
aliases: ["Tomb Guardian"]
---
# Tomb Guardian
*Source: Tomb of Annihilation p. 127*  

Adventurers who have perished inside the tomb are stitched together by tomb dwarves and bolted into suits of armor. Once complete, these shambling golems are released into the tomb to hunt intruders.

A tomb guardian is a flesh golem clad in plate armor, giving it AC 17

```ad-statblock
title: Tomb Guardian
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ToA/Tomb%20Guardian.webp#token)
*Medium construct, Neutral*

- **Armor Class** 17
- **Hit Points** 93 (`11d8 + 44`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|19 (+4)| 9 (-1)|18 (+4)| 6 (-2)|10 (+0)| 5 (-3)|

- **Proficiency Bonus** +3
- **Saving Throws** ⏤
- **Skills** ⏤
- **Senses** darkvision 60 ft., passive Perception 10
- **Damage Immunities** lightning; poison; bludgeoning, piercing, slashing from nonmagical attacks that aren't adamantine
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened), [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed), [petrified](2-Mechanics/CLI/rules/conditions.md#Petrified), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** understands the languages of its creator but can't speak
- **Challenge** 5

## Traits

***Berserk.*** Whenever the tomb guardian starts its turn with 40 hit points or fewer, roll a `dice:d6|noform|avg` (`d6`). On a 6, the tomb guardian goes berserk. On each of its turns while berserk, the tomb guardian attacks the nearest creature it can see. If no creature is near enough to move to and attack, the tomb guardian attacks an object, with preference for an object smaller than itself. Once the tomb guardian goes berserk, it continues to do so until it is destroyed or regains all its hit points. The golem's creator, if within 60 feet of the berserk tomb guardian, can try to calm it by speaking firmly and persuasively. The tomb guardian must be able to hear its creator, who must take an action to make a DC 15 Charisma ([Persuasion](2-Mechanics/CLI/rules/skills.md#Persuasion)) check. If the check succeeds, the tomb guardian ceases being berserk. If it takes damage while still at 40 hit points or fewer, the tomb guardian might go berserk again.

***Aversion of Fire.*** If the tomb guardian takes fire damage, it has disadvantage on attack rolls and ability checks until the end of its next turn.

***Immutable Form.*** The tomb guardian is immune to any spell or effect that would alter its form.

***Lightning Absorption.*** Whenever the tomb guardian is subjected to lightning damage, it takes no damage and instead regains a number of hit points equal to the lightning damage dealt.

***Magic Resistance.*** The tomb guardian has advantage on saving throws against spells and other magical effects.

***Magic Weapons.*** The golem's weapon attacks are magical.

## Actions

***Multiattack.*** The tomb guardian makes two slam attacks.

***Slam.*** *Melee Weapon Attack:* `dice:1d20+7|noform|text(+7)` to hit, reach 5 ft., one target. *Hit:* `dice:2d8+4|noform|avg|text(13)` (`2d8 + 4`) bludgeoning damage.
```
^statblock