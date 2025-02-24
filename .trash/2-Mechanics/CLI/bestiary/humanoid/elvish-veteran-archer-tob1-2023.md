---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/tob1-2023
- monster/cr/3
- monster/environment/forest
- monster/size/medium
- monster/type/humanoid/elf
aliases: ["Elvish Veteran Archer"]
---
# Elvish Veteran Archer
*Source: Tome of Beasts 1 (2023 Edition) p. 410*  

The elvish veteran archer is a stealthy hunter that quietly slips through the wood, watching for game or intruders. While capable with a sword, the elvish archer's true skill lies with the longbow. When unseen, the archer can launch a volley of arrows at its foes with deadly results.

```ad-statblock
title: Elvish Veteran Archer
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ToB1-2023/Elvish%20Veteran%20Archer.webp#token)
*Medium humanoid (elf), Any alignment*

- **Armor Class** 16 ([studded leather](2-Mechanics/CLI/items/studded-leather-armor.md))
- **Hit Points** 66 (`12d8 + 12`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|11 (+0)|18 (+4)|12 (+1)|11 (+0)|13 (+1)|11 (+0)|

- **Proficiency Bonus** +2
- **Saving Throws** ⏤
- **Skills** Nature +2, Perception +5, Stealth +5, Survival +3
- **Senses** passive Perception 15
- **Languages** Common, Elvish
- **Challenge** 3

## Traits

***Beast Hunter.*** The elvish veteran archer has advantage on Wisdom ([Survival](2-Mechanics/CLI/rules/skills.md#Survival)) checks to track Beasts and on Intelligence ([Nature](2-Mechanics/CLI/rules/skills.md#Nature)) checks to recall information about Beasts.

***Fey Ancestry.*** The elvish veteran archer has advantage on saving throws against being [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), and magic can't put the archer to sleep.

***Keen Hearing and Sight.*** The elvish veteran archer has advantage on Wisdom ([Perception](2-Mechanics/CLI/rules/skills.md#Perception)) checks that rely on hearing or sight.

***Point Blank Hunter.*** A longbow deals one extra die of its damage when the archer hits with it (included in the attack). In addition, when the archer makes a ranged attack with a longbow, it doesn't have disadvantage on the attack roll from being within 5 feet of a hostile creature, though it may still have disadvantage from other sources.

## Actions

***Multiattack.*** The elvish veteran archer makes three Shortsword attacks or two Longbow attacks.

***Shortsword.*** *Melee Weapon Attack:* `dice:1d20+6|noform|text(+6)` to hit, reach 5 ft., one target. *Hit:* `dice:1d6+4|noform|avg|text(7)` (`1d6 + 4`) piercing damage.

***Longbow.*** *Ranged Weapon Attack:* `dice:1d20+6|noform|text(+6)` to hit, range 150/600 ft., one target. *Hit:* `dice:2d8+4|noform|avg|text(13)` (`2d8 + 4`) piercing damage. Instead of dealing damage, the archer can pin part of the target's clothing or body to the ground or to a nearby wall or tree. If it does so, the target is [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained). A creature, including the target, can take its action to remove the arrow and free the [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained) target by succeeding on a DC 14 Strength check.

***Arrow Spray (Recharge 5-6).*** The elvish veteran archer fires a flurry of arrows in a 15-foot cone. Each creature in the cone must make a DC 14 Dexterity saving throw, taking `dice:4d8|noform|avg|text(18)` (`4d8`) piercing damage on a failed save, or half as much damage on a successful one.
```
^statblock

## Environment

forest