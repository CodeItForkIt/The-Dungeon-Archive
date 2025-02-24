---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/tob1-2023
- monster/cr/7
- monster/environment/planar
- monster/size/large
- monster/type/aberration
aliases: ["Spider of Leng"]
---
# Spider of Leng
*Source: Tome of Beasts 1 (2023 Edition) p. 341*  

*These bloated purple spiders have small claws on their front legs that serve as handlike manipulators. Their abdomens are a sickly purple-white.*

## Hate Humanoids

The nefarious spiders of Leng are highly intelligent. They are a very ancient people, steeped in evil lore and hideous malice, with an abiding hatred for all humanoid races. They sometimes keep ghostwalk spiders as guardians or soldiers.

## Dangerous Blood

Their blood is poisonous and corrosive to most creatures native to the Material Plane. The folk of Leng prize it in the making of etheric harpoons and enchanted nets.

## Statblock

```ad-statblock
title: Spider of Leng
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ToB1-2023/Spider%20of%20Leng.webp#token)
*Large aberration, Chaotic Evil*

- **Armor Class** 15 (natural armor)
- **Hit Points** 144 (`17d10 + 51`)
- **Speed** 30 ft., climb 20 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|14 (+2)|16 (+3)|16 (+3)|18 (+4)|10 (+0)|10 (+0)|

- **Proficiency Bonus** +3
- **Saving Throws** Dexterity +6, Constitution +6, Intelligence +7
- **Skills** Athletics +5, Perception +3, Stealth +6
- **Senses** darkvision 240 ft., passive Perception 13
- **Damage Immunities** poison
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned), [unconscious](2-Mechanics/CLI/rules/conditions.md#Unconscious)
- **Languages** Common, Void Speech
- **Challenge** 7

## Traits

***Eldritch Understanding.*** The spider of Leng can read and use any spell scroll or magic item, ignoring all class, race, and level requirements.

***Poisonous Blood.*** A creature that hits the spider of Leng with a melee attack while within 5 feet of it takes `dice:1d8|noform|avg|text(4)` (`1d8`) poison damage.

***Poisonous Death.*** When the spider of Leng dies, the poisonous blood in its body vaporizes, forming a cloud in the spider's space until initiative count 20 on the next round. Each creature within 5 feet of the spider and each creature that enters the cloud for the first time on a turn must make a DC 15 Constitution saving throw, taking `dice:2d8|noform|avg|text(9)` (`2d8`) poison damage on a failed save, or half as much damage on a successful one.

***Spellcasting.*** The spider of Leng casts one of the following spells, requiring no material components and using Intelligence as the spellcasting ability (spell save DC 15):

**At will**: [comprehend languages](2-Mechanics/CLI/spells/comprehend-languages.md), [detect magic](2-Mechanics/CLI/spells/detect-magic.md)

**1/day each**: [arcane eye](2-Mechanics/CLI/spells/arcane-eye.md), [hypnotic pattern](2-Mechanics/CLI/spells/hypnotic-pattern.md)

**3/day each**: [confusion](2-Mechanics/CLI/spells/confusion.md), [silence](2-Mechanics/CLI/spells/silence.md)

## Actions

***Multiattack.*** The spider of Leng makes two Claw attacks and one Staff of Leng attack, or it makes three Spit Venom attacks.

***Claw.*** *Melee Weapon Attack:* `dice:1d20+6|noform|text(+6)` to hit, reach 5 ft., one target. *Hit:* `dice:2d8+3|noform|avg|text(12)` (`2d8 + 3`) slashing damage plus `dice:1d8|noform|avg|text(4)` (`1d8`) poison damage.

***Staff of Leng.*** *Melee Weapon Attack:* `dice:1d20+6|noform|text(+6)` to hit, reach 5 ft., one target. *Hit:* `dice:1d6+3|noform|avg|text(7)` (`1d6 + 3`) bludgeoning damage plus `dice:2d6|noform|avg|text(7)` (`2d6`) psychic damage, and the target must succeed on a DC 15 Wisdom saving throw or be [stunned](2-Mechanics/CLI/rules/conditions.md#Stunned) until the end of is next turn.

***Spit Venom.*** *Ranged Weapon Attack:* `dice:1d20+6|noform|text(+6)` to hit, range 20/60 ft., one target. *Hit:* `dice:3d8+3|noform|avg|text(16)` (`3d8 + 3`) poison damage, and the target must succeed on a DC 15 Constitution saving throw or be [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned) and [blinded](2-Mechanics/CLI/rules/conditions.md#Blinded) until the end of its next turn.

## Reactions

***Poisonous Riposte.*** The spider of Leng adds 3 to its AC against one melee attack that would hit it. To do so, the spider must see the attacker. If this effect causes the attack to miss, the attacker takes `dice:1d8|noform|avg|text(4)` (`1d8`) poison damage.
```
^statblock

## Environment

planar