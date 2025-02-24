---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/tftyp
- monster/cr/5
- monster/size/medium
- monster/type/construct
aliases: ["Reduced-Threat Flesh Golem"]
---
# Reduced-Threat Flesh Golem
*Source: Tales from the Yawning Portal p. 113*  

```ad-statblock
title: Reduced-Threat Flesh Golem
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/TftYP/Reduced-Threat%20Flesh%20Golem.webp#token)
*Medium construct, Neutral*

- **Armor Class** 9
- **Hit Points** 46 (`11d8 + 44`)
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

***Reduced Threat.*** A reduced-threat monster takes a −2 penalty on attack rolls (included in the stat block), ability checks (included in the stat block for skill proficiencies), saving throws (included in the stat block for saving throw proficiencies), and saving throw DCs (included in the stat block).

***Berserk.*** Whenever the golem starts its turn with 40 hit points or fewer, roll a `dice:d6|noform|avg` (`d6`). On a 6, the golem goes berserk. On each of its turns while berserk, the golem attacks the nearest creature it can see. If no creature is near enough to move to and attack, the golem attacks an object, with preference for an object smaller than itself. Once the golem goes berserk, it continues to do so until it is destroyed or regains all its hit points.

The golem's creator, if within 60 feet of the berserk golem, can try to calm it by speaking firmly and persuasively. The golem must be able to hear its creator, who must take an action to make a DC 13 Charisma ([Persuasion](2-Mechanics/CLI/rules/skills.md#Persuasion)) check. If the check succeeds, the golem ceases being berserk. If it takes damage while still at 40 hit points or fewer, the golem might go berserk again.

***Aversion of Fire.*** If the golem takes fire damage, it has disadvantage on attack rolls and ability checks until the end of its next turn.

***Immutable Form.*** The golem is immune to any spell or effect that would alter its form.

***Lightning Absorption.*** Whenever the golem is subjected to lightning damage, it takes no damage and instead regains a number of hit points equal to the lightning damage dealt.

***Magic Resistance.*** The golem has advantage on saving throws against spells and other magical effects.

***Magic Weapons.*** The golem's weapon attacks are magical.

## Actions

***Multiattack.*** The golem makes two slam attacks.

***Slam.*** *Melee Weapon Attack:* `dice:1d20+5|noform|text(+5)` to hit, reach 5 ft., one target. *Hit:* `dice:2d8+4|noform|avg|text(13)` (`2d8 + 4`) bludgeoning damage.
```
^statblock