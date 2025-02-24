---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/ghloe
- monster/cr/2
- monster/size/medium
- monster/type/dragon
aliases: ["Sea Drake"]
---
# Sea Drake
*Source: Grim Hollow: Lairs of Etharis p. 51*  

> [!quote]  
> 
> Descendants of the great dragons of the mythic past still roam Etharis. They have little of the majesty of their ancestors, but they're still frightening.

## Salvage

Dragons are rare on Etharis, so materials from their corpses fetch a good price. A dragon's corpse can be sold for at least 100 gp times the Challenge of the monster.

Someone who has proficiency with alchemist's supplies can reduce the brain of a prismatic drake into an oil that can be used to fashion one arrow of dragon slaying. Brewing the oil takes 5 days of work, reagents worth 2,000 gp, and a successful DC 17 Intelligence or Wisdom check. Making the arrow is a trivial task, but treating it properly with the oil takes 5 more days of work.

## Lore

- **DC 15 Intelligence ([Nature](2-Mechanics/CLI/rules/skills.md#Nature)).** Sea drakes are cunning grapplers resistant to cold, sky drakes are adept fliers and have a bite charged with lightning, and blight drakes collect diseases that don't kill them but make for a toxic bite.  
- **DC 20 Intelligence ([Arcana](2-Mechanics/CLI/rules/skills.md#Arcana)).** Prismatic drakes are the rarest drakes, rumored to be sorcerers transformed into dragons after they foolishly connected their minds to Gormadraug, the slumbering Prismatic Dragon. These drakes can cast spells.  

## Statblock

```ad-statblock
title: Sea Drake
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/GHLoE/Sea%20Drake.webp#token)
*Medium dragon, Neutral Evil*

- **Armor Class** 14 (natural armor)
- **Hit Points** 58 (`9d8 + 18`)
- **Speed** 20 ft., swim 50 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|15 (+2)|16 (+3)|14 (+2)| 7 (-2)|14 (+2)| 8 (-1)|

- **Proficiency Bonus** +2
- **Saving Throws** ⏤
- **Skills** Perception +4, Stealth +5
- **Senses** darkvision 120 ft., passive Perception 14
- **Damage Resistances** cold
- **Languages** Draconic
- **Challenge** 2

## Traits

***Amphibious.*** The sea drake can breathe air and water.

## Actions

***Multiattack.*** The sea drake makes one bite attack and one tail attack.

***Bite.*** *Melee Weapon Attack:* `dice:1d20+5|noform|text(+5)` to hit, reach 5 ft., one target. *Hit:* `dice:2d6+3|noform|avg|text(10)` (`2d6 + 3`) piercing damage.

***Tail.*** *Melee Weapon Attack:* `dice:1d20+5|noform|text(+5)` to hit, reach 10 ft., one target. *Hit:* `dice:1d6+3|noform|avg|text(6)` (`1d6 + 3`) bludgeoning damage. If the target is a Medium or smaller creature, it is pulled within 5 feet of the sea drake and [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) (escape DC 13). Until this grapple ends, the drake can't use its tail on another target.
```
^statblock