---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/ghloe
- monster/cr/4
- monster/size/large
- monster/type/dragon
aliases: ["Sky Drake"]
---
# Sky Drake
*Source: Grim Hollow: Lairs of Etharis p. 63*  

> [!quote]  
> 
> Descendants of the great dragons of the mythic past still roam Etharis. They have little of the majesty of their ancestors, but they're still frightening.

## Salvage

Dragons are rare on Etharis, so materials from their corpses fetch a good price. A dragon's corpse can be sold for at least 100 gp times the Challenge of the monster.

## Lore

- **DC 15 Intelligence ([Nature](2-Mechanics/CLI/rules/skills.md#Nature)).** Sea drakes are cunning grapplers resistant to cold, sky drakes are adept fliers and have a bite charged with lightning, and blight drakes collect diseases that don't kill them but make for a toxic bite.  

## Statblock

```ad-statblock
title: Sky Drake
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/GHLoE/Sky%20Drake.webp#token)
*Large dragon, Neutral Evil*

- **Armor Class** 14 (natural armor)
- **Hit Points** 85 (`10d10 + 30`)
- **Speed** 20 ft., fly 60 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|18 (+4)|11 (+0)|17 (+3)| 8 (-1)|14 (+2)|11 (+0)|

- **Proficiency Bonus** +2
- **Saving Throws** ⏤
- **Skills** Athletics +6, Perception +4, Survival +4
- **Senses** darkvision 120 ft., passive Perception 14
- **Languages** Draconic and one other language
- **Challenge** 4

## Traits

***Flyby.*** The sky drake doesn't provoke opportunity attacks when it flies out of an enemy's reach.

***Keen Sight.*** The sky drake has advantage on Wisdom ([Perception](2-Mechanics/CLI/rules/skills.md#Perception)) checks that rely on sight.

## Actions

***Multiattack.*** The sky drake makes one bite attack and one attack with its claws.

***Bite.*** *Melee Weapon Attack:* `dice:1d20+6|noform|text(+6)` to hit, reach 10 ft., one target. *Hit:* `dice:2d6+4|noform|avg|text(11)` (`2d6 + 4`) piercing damage and `dice:2d4|noform|avg|text(5)` (`2d4`) lightning damage.

***Claws.*** *Melee Weapon Attack:* `dice:1d20+6|noform|text(+6)` to hit, reach 5 ft., one target. *Hit:* `dice:2d8+4|noform|avg|text(13)` (`2d8 + 4`) slashing damage.
```
^statblock