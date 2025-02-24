---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/bam
- monster/cr/1-2
- monster/size/medium
- monster/type/monstrosity/lizardfolk
aliases: ["Ssurran Poisoner"]
---
# Ssurran Poisoner
*Source: Boo's Astral Menagerie p. 58, Light of Xaryxis*  

Ssurran poisoners coat their weapons with toxin and hurl bombs that release poisonous gas.

```ad-statblock
title: Ssurran Poisoner
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/BAM/Ssurran%20Poisoner.webp#token)
*Medium monstrosity (lizardfolk), Any alignment*

- **Armor Class** 16 (natural armor, [shield](2-Mechanics/CLI/items/shield.md))
- **Hit Points** 22 (`4d8 + 4`)
- **Speed** 30 ft., swim 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|13 (+1)|12 (+1)|13 (+1)|12 (+1)|12 (+1)| 7 (-2)|

- **Proficiency Bonus** +2
- **Saving Throws** ⏤
- **Skills** Perception +3, Stealth +3, Survival +3
- **Senses** passive Perception 13
- **Languages** Draconic
- **Challenge** 1/2

## Traits

***Hold Breath.*** The ssurran can hold its breath for 15 minutes.

## Actions

***Multiattack.*** The ssurran makes two Claw attacks.

***Claw.*** *Melee Weapon Attack:* `dice:1d20+3|noform|text(+3)` to hit, reach 5 ft., one target. *Hit:* `dice:1d6+1|noform|avg|text(4)` (`1d6 + 1`) slashing damage.

***Javelin.*** *Melee or Ranged Weapon Attack:* `dice:1d20+3|noform|text(+3)` to hit, reach 5 ft. or range 30/120 ft., one target. *Hit:* `dice:1d6+1|noform|avg|text(4)` (`1d6 + 1`) piercing damage plus `dice:1d8|noform|avg|text(4)` (`1d8`) poison damage.

***Poison Bomb.*** The ssurran throws a tangerine-sized bomb at a point up to 60 feet away, where it explodes, releasing a 10-foot-radius sphere of poisonous gas that disperses quickly. Each creature in the sphere must make a DC 11 Constitution saving throw, taking `dice:3d6|noform|avg|text(10)` (`3d6`) poison damage on a failed save, or half as much damage on a successful one. After the ssurran throws a bomb, roll a `dice:d6|noform|avg` (`d6`); on a roll of 4 or lower, the ssurran has no more bombs to throw.
```
^statblock