---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/bgdia
- monster/cr/5
- monster/size/large
- monster/type/fiend
aliases: ["Hellwasp"]
---
# Hellwasp
*Source: Baldur's Gate: Descent Into Avernus p. 236*  

A hellwasp is an intelligent, malevolent insect native to the Nine Hells. It has a thick protective carapace, thin metallic wings, and strong legs ending in swordlike talons. It uses its stinger to inject a chemical admixture similar to alchemist's fire into its victims. This same solution carries a paralytic enzyme that renders the victim helpless long enough for the hellwasp to grab its prey and flee.

Hellwasps thrive in hot weather, but extreme cold causes their shells to crack and their metabolisms to shut down. Consequently, they avoid the icy layers of the Nine Hells (Stygia and Cania).

## Nests

Hellwasps spew a golden bile similar to amber, which they use to craft enormous nests riddled with chambers and passages. The hellwasps use these nests as communal shelters and food storage. A typical nest is large enough to support a commune of `dice:1d10+10|noform|avg` (`1d10 + 10`) hellwasps, with each hellwasp having an equal voice and role in the society.

## Hellwasp Telepathy

Hellwasps communicate with one another via a form of telepathy perceptible only to their kind.

## Statblock

```ad-statblock
title: Hellwasp
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/BGDIA/Hellwasp.webp#token)
*Large fiend, Lawful Evil*

- **Armor Class** 19 (natural armor)
- **Hit Points** 52 (`8d10 + 8`)
- **Speed** 10 ft., fly 60 ft. (hover)

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|18 (+4)|15 (+2)|12 (+1)|10 (+0)|10 (+0)| 7 (-2)|

- **Proficiency Bonus** +3
- **Saving Throws** Dexterity +5, Wisdom +3
- **Skills** ⏤
- **Senses** darkvision 60 ft., passive Perception 10
- **Damage Vulnerabilities** cold
- **Damage Immunities** fire
- **Languages** Infernal, telepathy 300 ft. (with other hellwasps only)
- **Challenge** 5

## Traits

***Magic Weapons.*** The hellwasp's weapon attacks are magical.

## Actions

***Multiattack.*** The hellwasp makes two attacks: one with its sting and one with its sword talons.

***Sting.*** *Melee Weapon Attack:* `dice:1d20+7|noform|text(+7)` to hit, reach 5 ft., one creature. *Hit:* `dice:1d8+4|noform|avg|text(8)` (`1d8 + 4`) piercing damage plus `dice:2d6|noform|avg|text(7)` (`2d6`) fire damage, and the target must succeed on a DC 12 Constitution saving throw or be [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned) for 1 minute. While [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned) in this way, the target is also [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed). The target can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.

***Sword Talons.*** *Melee Weapon Attack:* `dice:1d20+7|noform|text(+7)` to hit, reach 5 ft., one target. *Hit:* `dice:2d6+4|noform|avg|text(11)` (`2d6 + 4`) piercing damage.
```
^statblock