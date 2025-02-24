---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/scc
- monster/cr/22
- monster/size/gargantuan
- monster/type/dragon/bard
aliases: ["Shadrix Silverquill"]
---
# Shadrix Silverquill
*Source: Strixhaven: A Curriculum of Chaos p. 212*  

Centuries ago, the dragon Shadrix Silverquill mastered the magic of light and shadow, and he focused that magic through communication. Shadrix's words thrummed with power, inspiring his allies and demoralizing his enemies.

He established Silverquill College on the principles of eloquence and leadership, seeking to produce leaders who would go forth to guide others.

```ad-statblock
title: Shadrix Silverquill
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/SCC/Shadrix%20Silverquill.webp#token)
*Gargantuan dragon (bard), Neutral*

- **Armor Class** 21 (natural armor)
- **Hit Points** 363 (`22d20 + 132`)
- **Speed** 40 ft., fly 80 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|25 (+7)|14 (+2)|23 (+6)|18 (+4)|18 (+4)|26 (+8)|

- **Proficiency Bonus** +7
- **Saving Throws** Dexterity +9, Constitution +13, Wisdom +11, Charisma +15
- **Skills** Arcana +18, Deception +15, Perception +11, Persuasion +15
- **Senses** blindsight 120 ft., passive Perception 21
- **Damage Immunities** psychic, radiant
- **Languages** all
- **Challenge** 22

## Traits

***Legendary Resistance (3/Day).*** If Shadrix fails a saving throw, he can choose to succeed instead.

***Spellcasting.*** Shadrix casts one of the following spells, requiring no material components and using Charisma as the spellcasting ability (spell save DC 23):

**1/day each**: [darkness](2-Mechanics/CLI/spells/darkness.md), [daylight](2-Mechanics/CLI/spells/daylight.md), [hypnotic pattern](2-Mechanics/CLI/spells/hypnotic-pattern.md), [sending](2-Mechanics/CLI/spells/sending.md), [suggestion](2-Mechanics/CLI/spells/suggestion.md)

## Actions

***Multiattack.*** Shadrix makes one Bite attack and two Claw attacks.

***Bite.*** *Melee Weapon Attack:* `dice:1d20+14|noform|text(+14)` to hit, reach 15 ft., one target. *Hit:* `dice:1d10+7|noform|avg|text(12)` (`1d10 + 7`) piercing damage plus `dice:1d8|noform|avg|text(4)` (`1d8`) radiant damage.

***Claw.*** *Melee Weapon Attack:* `dice:1d20+14|noform|text(+14)` to hit, reach 10 ft., one target. *Hit:* `dice:1d6+7|noform|avg|text(10)` (`1d6 + 7`) slashing damage. If the target is a creature, it is wracked with despair and has disadvantage on attack rolls until the end of its next turn.

***Illuminating Shadow Breath (Recharge 5-6).*** Shadrix exhales an entwined burst of blinding radiance and unnerving shadow in a 90-foot cone. Each creature in that area must make a DC 21 Constitution saving throw. On a failed save, a creature takes `dice:7d8|noform|avg|text(31)` (`7d8`) radiant damage and `dice:7d8|noform|avg|text(31)` (`7d8`) psychic damage and is [blinded](2-Mechanics/CLI/rules/conditions.md#Blinded) until the start of Shadrix's next turn. On a successful save, a creature takes half as much damage and isn't [blinded](2-Mechanics/CLI/rules/conditions.md#Blinded).

## Legendary Actions

***Claw.*** Shadrix makes one Claw attack.

***Shadow Slip (Costs 2 Actions).*** Shadrix becomes an inky cloud of shadow and can move up to half his flying speed without provoking opportunity attacks, then resumes his true form. During this movement, he can move through creatures and objects as if they were difficult terrain. If he moves through a creature, it must succeed on a DC 21 Constitution saving throw or become [blinded](2-Mechanics/CLI/rules/conditions.md#Blinded) until the end of its next turn. If Shadrix ends this move inside an object, he takes `dice:1d10|noform|avg|text(5)` (`1d10`) force damage and is shunted to the nearest unoccupied space.

***Flash of Inspiration (Costs 3 Actions).*** Shadrix magically summons `dice:1d4|noform|avg` (`1d4`) [inkling mascots](2-Mechanics/CLI/bestiary/ooze/inkling-mascot-scc.md) in unoccupied spaces he can see within 60 feet of himself. The inklings obey his commands and take their turns immediately after his. While any of these inklings live, Shadrix has advantage on attack rolls and saving throws. These inklings disappear after 10 minutes, when Shadrix dies, or when he uses this action again.
```
^statblock