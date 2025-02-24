---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/dsotdq
- monster/cr/3
- monster/size/medium
- monster/type/humanoid
aliases: ["Dragon Army Officer"]
---
# Dragon Army Officer
*Source: Dragonlance: Shadow of the Dragon Queen p. 200*  

The Dragon Armies gather fanatical followers to their ranks. Recruits are indoctrinated to revere the Dragon Queen and view dragons as her favored servants. Troops in the Dragon Army wield weapons blessed by Takhisis to strike with the power of the dragons they fight alongside.

## Dragon Army Weapons

The weapons of Dragon Army troops are blessed with an infusion of dragon breath. The type of damage these weapons deal depends on the specific army. The stat blocks presented here represent Red Dragon Army troops with weapons infused by the fire of red dragons. You can represent followers of other chromatic dragons by changing the fire damage to match the damage type associated with those dragons' breath weapons.

## Statblock

```ad-statblock
title: Dragon Army Officer
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/DSotDQ/Dragon%20Army%20Officer.webp#token)
*Medium humanoid, typically  Lawful Evil*

- **Armor Class** 19 ([splint](2-Mechanics/CLI/items/splint-armor.md), [shield](2-Mechanics/CLI/items/shield.md))
- **Hit Points** 65 (`10d8 + 20`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|16 (+3)|14 (+2)|15 (+2)|12 (+1)|14 (+2)|12 (+1)|

- **Proficiency Bonus** +2
- **Saving Throws** Dexterity +4, Wisdom +4
- **Skills** Athletics +5, Perception +4
- **Senses** passive Perception 14
- **Languages** Common, Draconic
- **Challenge** 3

## Traits

***Draconic Devotion.*** While the officer can see a Dragon that isn't hostile to it, the officer has advantage on attack rolls.

## Actions

***Multiattack.*** The officer makes two Vicious Lance attacks and uses Assault Orders if it's available.

***Vicious Lance.*** *Melee Weapon Attack:* `dice:1d20+5|noform|text(+5)` to hit, reach 10 ft., one target. *Hit:* `dice:1d10+3|noform|avg|text(8)` (`1d10 + 3`) piercing damage plus `dice:1d4|noform|avg|text(2)` (`1d4`) fire damage.

***Heavy Crossbow.*** *Ranged Weapon Attack:* `dice:1d20+4|noform|text(+4)` to hit, range 100/400 ft., one target. *Hit:* `dice:1d10+2|noform|avg|text(7)` (`1d10 + 2`) piercing damage plus `dice:1d10|noform|avg|text(5)` (`1d10`) fire damage.

***Assault Orders (Recharge 5-6).*** The officer shouts orders and targets up to two other creatures within 60 feet of itself. If a target has the Draconic Devotion trait and can hear the officer, the target can use its reaction to make one melee attack.
```
^statblock