---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/psz
- monster/cr/1-8
- monster/size/tiny
- monster/type/beast
aliases: ["Heartstabber Mosquito"]
---
# Heartstabber Mosquito
*Source: Plane Shift: Zendikar p. 27*  

The black mana that brews and festers in Zendikar's swamps infuses a wide variety of natural animals, creating large, deadly vermin—rats, bats, insects, scorpions, and spiders that spread death and decay with their bites, stings, or caustic saliva. The swamps of Guul Draz are home to many such creatures, from the enormous heartstabber mosquitoes (best represented with [stirge](2-Mechanics/CLI/bestiary/beast/stirge.md) statistics) to giant scorpions large enough to hold a struggling vampire in one claw. The gigantic, ant-like caustic crawlers (similar to [ankhegs](2-Mechanics/CLI/bestiary/monstrosity/ankheg.md)) shape burrows from stone with their acidic saliva, creating strangely smooth walls easily mistaken for ancient construction. Gloomhunter bats the size of griffins have reservoirs of vaporous mana in their heads, causing their bite to tear at the spirit as well as the flesh. These and other creatures can be built from the offerings in "appendix A of the Monster Manual".

```ad-statblock
title: Heartstabber Mosquito
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/PSZ/Heartstabber%20Mosquito.webp#token)
*Tiny beast, Unaligned*

- **Armor Class** 14 (natural armor)
- **Hit Points** 2 (`1d4`)
- **Speed** 10 ft., fly 40 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
| 4 (-3)|16 (+3)|11 (+0)| 2 (-4)| 8 (-1)| 6 (-2)|

- **Proficiency Bonus** +2
- **Saving Throws** ⏤
- **Skills** ⏤
- **Senses** darkvision 60 ft., passive Perception 9
- **Languages** —
- **Challenge** 1/8

## Actions

***Blood Drain.*** *Melee Weapon Attack:* `dice:1d20+5|noform|text(+5)` to hit, reach 5 ft., one creature. *Hit:* `dice:1d4+3|noform|avg|text(5)` (`1d4 + 3`) piercing damage, and the mosquito attaches to the target. While attached, the mosquito doesn't attack. Instead, at the start of each of the mosquito's turns, the target loses `dice:1d4+3|noform|avg|text(5)` (`1d4 + 3`) hit points due to blood loss.

The mosquito can detach itself by spending 5 feet of its movement. It does so after it drains 10 hit points of blood from the target or the target dies. A creature, including the target, can use its action to detach the mosquito.
```
^statblock