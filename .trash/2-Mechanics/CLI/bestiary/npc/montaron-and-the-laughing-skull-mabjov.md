---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/mabjov
- monster/cr/11
- monster/size/small
- monster/type/humanoid/halfling
aliases: ["Montaron and the Laughing Skull"]
---
# Montaron and the Laughing Skull
*Source: Minsc and Boo's Journal of Villainy p. 86*  

Possibly the most ornery halfling in all of Toril, Montaron is aggressive, bloodthirsty, and absolutely ruthless. He puts his natural nimbleness to use as a skilled assassin working for the Shadow Thieves. He used to work for a rival criminal organization known as the Zhentarim until he was killed during a mission. He despises his old organization, but not nearly as much as he does socalled "goody-goodies." He was eventually brought back to life by the Shadow Thieves because of his relationship with his old partner, a necromancer named Xzar.

Xzar was already known for his erratic and bizarre behavior before he decided to attempt the magical ritual that would turn him into a lich. While successful at achieving this goal, once he embraced undeath he quickly descended into insanity. Xzar lost track of his phylactery and thus didn't feed it the souls required to fuel his undead state. Several decades later his body had crumbled to dust and Xzar had devolved into a demilich.

Montaron was brought back by the Shadow Thieves to utilize the demilich. The halfling keeps Xzar's skull in a bag of holding, only bringing it out during a mission. When Xzar is active, he will sometimes affectionately refer to the halfling as "Monty". Most of the time he will just berate Montaron for being an insufferable idiot.

Montaron is motivated by two things: amassing coin and finding outlets for his hot temper. He secretly despises his old partner Xzar, but knows that the demilich makes him a much more effective assassin.

## Montaron as a Contact

Montaron is the primary contact for members of the Shadow Thieves at low levels. Montaron has access to fences in all of the major cities of the Sword Coast. He can exchange magic items of equal value for a small cost.

**Items Available from Montaron**

| Magic Item | Required Trade | Cost |
|------------|----------------|------|
| Armor, +1 of your choice | Armor +1 | 200 gp |
| Ring of jumping, ring of mind shielding, ring of swimming, ring of warmth, ring of water walking | Uncommon magic ring | 100 gp |
| Ring of evasion, ring of feather falling, ring of free action, ring of protection, ring of x-ray vision | Rare magic ring | 300 gp |
| Rod of rulership, staff of the adder, staff of charming, staff of the python, staff of swarming insects | Rare magic rod or staff | 500 gp |
| Wand of magic detection, wand of magic missiles, wand of secrets, wand of web | Uncommon magic wand | 150 gp |
| Wand of binding, wand of enemy detection, wand of fear, wand of paralysis, wand of wonder | Rare magic wand | 300 gp |
| Weapon, +1 of your choice | Weapon +1 | 100 gp |
^items-available-from-montaron

## Statblock

```ad-statblock
title: Montaron and the Laughing Skull
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/MaBJoV/Montaron%20and%20the%20Laughing%20Skull.webp#token)
*Small humanoid (halfling), Neutral Evil*

- **Armor Class** 17 ([studded leather](2-Mechanics/CLI/items/studded-leather-armor.md))
- **Hit Points** 149 (`23d6 + 69`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|12 (+1)|20 (+5)|16 (+3)|13 (+1)|11 (+0)|10 (+0)|

- **Proficiency Bonus** +4
- **Saving Throws** Dexterity +9, Intelligence +5
- **Skills** Acrobatics +9, Deception +4, Perception +4, Stealth +13
- **Senses** passive Perception 14
- **Damage Resistances** poison
- **Languages** Common, Halfling, Thieves' cant
- **Challenge** 11

## Traits

***Assassinate.*** During his first turn, Montaron has advantage on attack rolls against any creature that hasn't taken a turn. Any hit Montaron scores against a surprised creature is a critical hit.

***Evasion.*** If Montaron is subjected to an effect that allows him to make a Dexterity saving throw to take only half damage, Montaron instead takes no damage if he succeeds on the saving throw, and only half damage if he fails.

***Nimbleness.*** Montaron can move through the space of any creature that is of a size larger than his.

***Sneak Attack (1/Turn).*** Montaron deals an extra `dice:6d6|noform|avg|text(21)` (`6d6`) damage when he hits a target with a weapon attack and has advantage on the attack roll, or when the target is within 5 feet of an ally of Montaron that isn't incapacitated and Montaron doesn't have disadvantage on the attack roll.

***Special Equipment.*** Montaron possesses a [bag of holding](2-Mechanics/CLI/items/bag-of-holding.md). He keeps the [demilich](2-Mechanics/CLI/bestiary/undead/demilich.md), Xzar, in the bag. He also possesses a [portable hole](2-Mechanics/CLI/items/portable-hole.md), which he uses to aid in robberies. As a bonus action, Montaron can place his [portable hole](2-Mechanics/CLI/items/portable-hole.md) in his [bag of holding](2-Mechanics/CLI/items/bag-of-holding.md). This instantly destroys both items and opens a gate to the Astral Plane. Montaron and any creature within 10 feet of him is sucked through the gate to a random location on the Astral Plane. The gate then closes.

## Actions

***Multiattack.*** Montaron makes three Shortsword attacks and uses the ability Unleash the Demilich if available.

***Shortsword.*** *Melee Weapon Attack:* `dice:1d20+9|noform|text(+9)` to hit, reach 5 ft., one target. *Hit:* `dice:1d6+5|noform|avg|text(8)` (`1d6 + 5`) piercing damage, and the target must make a DC 15 Constitution saving throw, taking `dice:7d6|noform|avg|text(24)` (`7d6`) poison damage on a failed save, or half as much damage on a successful one.

***Light Crossbow.*** *Ranged Weapon Attack:* `dice:1d20+9|noform|text(+9)` to hit, range 80/320 ft., one target. *Hit:* `dice:1d8+5|noform|avg|text(9)` (`1d8 + 5`) piercing damage.

***Unleash the Demilich (1/Day).*** Montaron reaches inside his bag of holding and releases Xzar. Xzar is a [demilich](2-Mechanics/CLI/bestiary/undead/demilich.md) and appears within 5 feet of Montaron. Xzar rolls for his own initiative. Xzar can't use lair actions or legendary actions. He has a CR of 14.
```
^statblock