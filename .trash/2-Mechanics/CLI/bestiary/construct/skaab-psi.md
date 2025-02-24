---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/psi
- monster/cr/5
- monster/size/medium
- monster/type/construct
aliases: ["Skaab"]
---
# Skaab
*Source: Plane Shift: Innistrad p. 20*  

Skaberen, also called stitchers, are scientist-mages who create artificial forms of life. The true goal of a skaberen is to create real life, an undertaking which usually produces a malformed "offspring" for the practitioner. This offspring is a skaab—a constructed zombie.

Skaabs are assembled from disparate body parts and animated through scientific means. Most skaabs are more or less humanlike, but creative stitchers have crafted winged skaabs similar to the drakes of other worlds, towering giant skaabs, and unrecognizable horrors.

Skaberen go through an elaborate process to gather body parts, bind them together, infuse the stitched body with vital fluid, and plant a vital force in its unliving flesh. Some skaberen even use necro-alchemy to fuel their laboratories, leading to even more confusion in terminology.

Skaberen usually ply their trade in remote and inhospitable places, since they are viewed as blasphemers by the church of Avacyn. They often become obsessed hermits who surround themselves with ancient scrolls and books, phials of rare noxious liquids, glass jars full of pickled organs, anatomical charts for both humans and beasts, rune-engraved skeletal remains, and small anvils and hammers for inscribing brass and copper plates.

Some skaberen might be mere [commoners](2-Mechanics/CLI/bestiary/humanoid/commoner.md), or perhaps [cultists](2-Mechanics/CLI/bestiary/humanoid/cultist.md). The most powerful among them might be [mages](2-Mechanics/CLI/bestiary/humanoid/mage.md) (using geist-powered devices), but the true power of most skaberen is in their creations ([flesh golems](2-Mechanics/CLI/bestiary/construct/skaab-psi.md)), not their own magic.

```ad-statblock
title: Skaab
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/PSI/Skaab.webp#token)
*Medium construct, Neutral*

- **Armor Class** 9
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

***Berserk.*** Whenever the skaab starts its turn with 40 hit points or fewer, roll a `dice:d6|noform|avg` (`d6`). On a 6, the skaab goes berserk. On each of its turns while berserk, the skaab attacks the nearest creature it can see. If no creature is near enough to move to and attack, the skaab attacks an object, with preference for an object smaller than itself. Once the skaab goes berserk, it continues to do so until it is destroyed or regains all its hit points.

The skaab's creator, if within 60 feet of the berserk skaab, can try to calm it by speaking firmly and persuasively. The skaab must be able to hear its creator, who must take an action to make a DC 15 Charisma ([Persuasion](2-Mechanics/CLI/rules/skills.md#Persuasion)) check. If the check succeeds, the skaab ceases being berserk. If it takes damage while still at 40 hit points or fewer, the skaab might go berserk again.

***Aversion of Fire.*** If the skaab takes fire damage, it has disadvantage on attack rolls and ability checks until the end of its next turn.

***Immutable Form.*** The skaab is immune to any spell or effect that would alter its form.

***Lightning Absorption.*** Whenever the skaab is subjected to lightning damage, it takes no damage and instead regains a number of hit points equal to the lightning damage dealt.

***Magic Resistance.*** The skaab has advantage on saving throws against spells and other magical effects.

***Magic Weapons.*** The skaab's weapon attacks are magical.

## Actions

***Multiattack.*** The skaab makes two slam attacks.

***Slam.*** *Melee Weapon Attack:* `dice:1d20+7|noform|text(+7)` to hit, reach 5 ft., one target. *Hit:* `dice:2d8+4|noform|avg|text(13)` (`2d8 + 4`) bludgeoning damage.
```
^statblock