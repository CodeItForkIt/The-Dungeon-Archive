---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/mcv4ec
- monster/cr/11
- monster/size/medium
- monster/type/fey
aliases: ["High Fae Impostor"]
---
# High Fae Impostor
*Source: Monstrous Compendium Volume 3: 4: Eldraine Creatures*  

High fae impostors are sly and mischievous manipulators who delight in disguising themselves with magic to vex other creatures. Their reasons for deception vary, ranging from harmless pranks to malicious infiltration. When a high fae impostor takes on the identity of another creature, the impostor magically gains access to a small portion of that creature's mind—any information that the creature might share with a casual acquaintance. Though not comprehensive, this information helps high fae impostors impersonate their targets effectively.

> [!quote]  
> 
> Though unable to tell outright lies, the high fae of Eldraine have many other means of deception at their disposal.

## High Fae

Ageless and inhuman, high fae are the oldest creatures in Eldraine, embodying the natural splendor and danger of the wilderness. High fae have no regard for mortal values of honor and law, but they nonetheless operate under inviolable rules of their own: gifts must always be repaid, promises must be honored, and outright lies must never be spoken (though misdirection and riddles are always welcome). To amuse themselves over the long centuries of their lives, high fae frequently engage in deceptions and other complex games of wits against one another.

Most high fae remain secluded deep within the wilds of Eldraine. They draw power from motes of light found throughout the wilds, and they use their innate illusory magic to power and embellish their various weapons.

The high fae are ruled by Talion, the Kindly Lord. Talion is as strange, ancient, and fickle as the wilds of Eldraine, and the Kindly Lord demands fealty and respect from followers. Despite having an austere demeanor, the Kindly Lord is also known for following mysterious whims, journeying to the farthest reaches of Eldraine out of an insatiable curiosity.

## Statblock

```ad-statblock
title: High Fae Impostor
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/MCV4EC/High%20Fae%20Impostor.webp#token)
*Medium fey, Any alignment*

- **Armor Class** 15
- **Hit Points** 149 (`23d8 + 46`)
- **Speed** 30 ft., fly 30 ft. (hover)

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|13 (+1)|21 (+5)|15 (+2)|18 (+4)|16 (+3)|23 (+6)|

- **Proficiency Bonus** +4
- **Saving Throws** Dexterity +9, Wisdom +7
- **Skills** Deception +14, Performance +10, Stealth +13
- **Senses** darkvision 60 ft., passive Perception 13
- **Damage Resistances** bludgeoning, piercing, slashing from nonmagical attacks
- **Languages** Common, Sylvan
- **Challenge** 11

## Traits

***Magic Resistance.*** The high fae has advantage on saving throws against spells and other magical effects.

***Spellcasting.*** The high fae casts one of the following spells, requiring no material components and using Charisma as the spellcasting ability (spell save DC 18):

**At will**: [friends](2-Mechanics/CLI/spells/friends.md), [minor illusion](2-Mechanics/CLI/spells/minor-illusion.md)

**1/day each**: [enthrall](2-Mechanics/CLI/spells/enthrall.md), [Nystul's magic aura](2-Mechanics/CLI/spells/nystuls-magic-aura.md)

## Actions

***Multiattack.*** The high fae makes two Fae Blade attacks and uses Vexing Prank once.

***Fae Blade.*** *Melee Weapon Attack:* `dice:1d20+9|noform|text(+9)` to hit, reach 5 ft., one target. *Hit:* `dice:3d8+5|noform|avg|text(18)` (`3d8 + 5`) force damage.

***Vexing Prank.*** The high fae targets one creature it can see within 60 feet of itself with a magical trick. The target must make a DC 18 Wisdom saving throw. On a failed save, the target takes `dice:6d6|noform|avg|text(21)` (`6d6`) psychic damage and has the [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened) condition until the start of the high fae's next turn. On a successful save, the target takes half as much damage only.

## Bonus Actions

***Loot Likeness.*** The high fae magically transforms into a duplicate of a Small or Medium creature it can see. While transformed, the high fae retains its game statistics (other than its size) but gains access to enough general information about the imitated creature, such as background and personality, to reasonably pass itself off as the creature. This transformation ends if the high fae is reduced to 0 hit points, uses this bonus action again, or uses a bonus action to revert to its true form.
```
^statblock