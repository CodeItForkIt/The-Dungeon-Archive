---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/pota
- monster/cr/20
- monster/size/gargantuan
- monster/type/elemental
aliases: ["Ogrémoch"]
---
# Ogrémoch
*Source: Princes of the Apocalypse p. 216*  

The Prince of Evil Earth is Ogrémoch (pronounced oh-gray-mock), the Mountain that Walks. His natural form is a shambling, 50-foot-tall colossus of rock, with crystal growths embedded throughout his body. When he bothers to speak, his voice sounds like grinding stones.

Ogrémoch is a miser who regards all the resources and treasures found in the ground as his own. He holds nothing but contempt for mortals (or any other denizens of the Material Plane) and desires nothing more than to crush and subjugate whomever he encounters. What he can't crush, he endures and outlasts.

Ogrémoch especially resents any mortals that dare to remove valuable metal or stone from the earth, and those who shape or build things of stone. He notices each nugget of gold or raw gemstone removed from areas under his influence, seeking to reclaim treasures "stolen" from him-and to punish the thieves. When the Prince of Evil Earth gains access to the Material Plane through an elemental node, he begins to methodically locate and destroy every mine, quarry, town, or fortification in the area. It's not that he needs the wealth, but the principle of the thing-extracting treasure from the earth-is anathema to Ogrémoch.

## Ogrémoch's Lair

Ogrémoch is normally found in the depths of elemental earth, choosing caverns with black crystals and jagged rock spikes to serve as his throne room. He can enter the Material Plane through large and well-established nodes of elemental earth, with a little help from the proper rituals. Within such a node, Ogrémoch wields great power.

## Statblock

```ad-statblock
title: Ogrémoch
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/PotA/Ogremoch.webp#token)
*Gargantuan elemental, Neutral Evil*

- **Armor Class** 20 (natural armor)
- **Hit Points** 526 (`27d20 + 243`)
- **Speed** 50 ft., burrow 50 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|26 (+8)|11 (+0)|28 (+9)|11 (+0)|15 (+2)|22 (+6)|

- **Proficiency Bonus** +6
- **Saving Throws** Strength +14, Constitution +15, Wisdom +8
- **Skills** ⏤
- **Senses** blindsight 120 ft., tremorsense 120 ft., passive Perception 12
- **Damage Resistances** bludgeoning, piercing, slashing from nonmagical attacks
- **Damage Immunities** poison
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened), [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed), [petrified](2-Mechanics/CLI/rules/conditions.md#Petrified), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned), [prone](2-Mechanics/CLI/rules/conditions.md#Prone)
- **Languages** Common, Terran
- **Challenge** 20

## Traits

***Empowered Attacks.*** Ogrémoch's slam attacks are treated as magical and adamantine for the purpose of bypassing resistance and immunity to nonmagical attacks.

***Legendary Resistance (3/Day).*** If Ogrémoch fails a saving throw, he can choose to succeed instead.

***Magic Resistance.*** Ogrémoch has advantage on saving throws against spells and other magical effects.

***Siege Monster.*** Ogrémoch deals double damage to objects and structures with his melee and ranged weapon attacks.

***Innate Spellcasting.*** Ogrémoch's innate spellcasting ability is Charisma (spell save DC 20, `dice:1d20+12|noform|text(+12)` to hit with spell attacks). He can innately cast the following spells, requiring no material components:

**At will**: [meld into stone](2-Mechanics/CLI/spells/meld-into-stone.md), [move earth](2-Mechanics/CLI/spells/move-earth.md), [wall of stone](2-Mechanics/CLI/spells/wall-of-stone.md)

## Actions

***Multiattack.*** Ogrémoch makes two slam attacks.

***Slam.*** *Melee Weapon Attack:* `dice:1d20+14|noform|text(+14)` to hit, reach 15 ft., one target. *Hit:* `dice:4d10+8|noform|avg|text(30)` (`4d10 + 8`) bludgeoning damage.

***Boulder.*** *Ranged Weapon Attack:* `dice:1d20+6|noform|text(+6)` to hit, range 500 ft., one target. *Hit:* `dice:7d10+8|noform|avg|text(46)` (`7d10 + 8`) bludgeoning damage. If the target is a creature, it must succeed on a DC 23 Strength saving throw or be knocked [prone](2-Mechanics/CLI/rules/conditions.md#Prone).

***Summon Elementals (1/Day).*** Ogrémoch summons up to three [earth elementals](2-Mechanics/CLI/bestiary/elemental/earth-elemental.md) and loses 30 hit points for each elemental he summons. Summoned elementals have maximum hit points, appear within 100 feet of Ogrémoch, and disappear if Ogrémoch is reduced to 0 hit points.

## Legendary Actions

***Illuminating Crystals.*** Ogrémoch's crystalline protrusions flare. Each creature within 30 feet of Ogrémoch becomes outlined in orange light, shedding dim light in a 10-foot radius. Any attack roll against an affected creature has advantage if the attacker can see it, and the affected creature can't benefit from being [invisible](2-Mechanics/CLI/rules/conditions.md#Invisible).

***Stomp (Costs 2 Actions).*** Ogrémoch stomps the ground, creating an earth tremor that extends in a 30-foot radius. Other creatures standing on the ground in that radius must succeed on a DC 23 Dexterity saving throw or fall [prone](2-Mechanics/CLI/rules/conditions.md#Prone).

***Create Gargoyle (Costs 3 Actions).*** Ogrémoch's hit points are reduced by 50 as he breaks off a chunk of his body and places it on the ground in an unoccupied space within 15 feet of him. The chunk of rock instantly transforms into a [gargoyle](2-Mechanics/CLI/bestiary/elemental/gargoyle.md) and acts on the same initiative count as Ogrémoch. Ogrémoch can't use this action if he has 50 hit points or fewer. The gargoyle obeys Ogrémoch's commands and fights until destroyed.

![Ogrémoch](2-Mechanics/CLI/bestiary/legendary-group/ogremoch-pota.md)
```
^statblock