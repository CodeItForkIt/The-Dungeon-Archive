---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/psz
- monster/cr/2
- monster/size/large
- monster/type/monstrosity
aliases: ["Caustic Crawler"]
---
# Caustic Crawler
*Source: Plane Shift: Zendikar p. 27*  

The black mana that brews and festers in Zendikar's swamps infuses a wide variety of natural animals, creating large, deadly vermin—rats, bats, insects, scorpions, and spiders that spread death and decay with their bites, stings, or caustic saliva. The swamps of Guul Draz are home to many such creatures, from the enormous heartstabber mosquitoes (best represented with [stirge](2-Mechanics/CLI/bestiary/beast/stirge.md) statistics) to giant scorpions large enough to hold a struggling vampire in one claw. The gigantic, ant-like caustic crawlers (similar to [ankhegs](2-Mechanics/CLI/bestiary/monstrosity/ankheg.md)) shape burrows from stone with their acidic saliva, creating strangely smooth walls easily mistaken for ancient construction. Gloomhunter bats the size of griffins have reservoirs of vaporous mana in their heads, causing their bite to tear at the spirit as well as the flesh. These and other creatures can be built from the offerings in "appendix A of the Monster Manual".

```ad-statblock
title: Caustic Crawler
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/PSZ/Caustic%20Crawler.webp#token)
*Large monstrosity, Unaligned*

- **Armor Class** 14 (natural armor; 11 while prone)
- **Hit Points** 39 (`6d10 + 6`)
- **Speed** 30 ft., burrow 10 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|17 (+3)|11 (+0)|13 (+1)| 1 (-5)|13 (+1)| 6 (-2)|

- **Proficiency Bonus** +2
- **Saving Throws** ⏤
- **Skills** ⏤
- **Senses** darkvision 60 ft., tremorsense 60 ft., passive Perception 11
- **Languages** —
- **Challenge** 2

## Actions

***Bite.*** *Melee Weapon Attack:* `dice:1d20+5|noform|text(+5)` to hit, reach 5 ft., one target. *Hit:* `dice:2d6+3|noform|avg|text(10)` (`2d6 + 3`) slashing damage plus `dice:1d6|noform|avg|text(3)` (`1d6`) acid damage. If the target is a Large or smaller creature, it is [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) (escape DC 13). Until this grapple ends, the crawler can bite only the [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) creature and has advantage on attack rolls to do so.

***Acid Spray (Recharge 6).*** The crawler spits acid in a line that is 30 feet long and 5 feet wide, provided that it has no creature [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled). Each creature in that line must make a DC 13 Dexterity saving throw, taking `dice:3d6|noform|avg|text(10)` (`3d6`) acid damage on a failed save, or half as much damage on a successful one.
```
^statblock