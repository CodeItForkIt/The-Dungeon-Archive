---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/tob1-2023
- monster/cr/4
- monster/environment/forest
- monster/environment/underdark
- monster/size/small
- monster/type/celestial
aliases: ["Firebird"]
---
# Firebird
*Source: Tome of Beasts 1 (2023 Edition) p. 187*  

*This proud bird struts like a peacock, made all the more majestic by its flaming fan of feathers, which shift through the color spectrum.*

## Guides and Helpers

Firebirds are welcome sights to those in need of warmth and safety. They primarily work at night or in underground areas, where their talents are most needed. Friendly to all creatures, they become aggressive only upon witnessing obviously evil acts. Firebirds enjoy working with good adventuring parties, providing light and healing, though their wanderlust prevents them from staying for long.

## Redeemers

Firebirds enjoy acting as reformers. They search for creatures they perceive as potential "light bringers," and they grant boons to such creatures, magically coaxing the creatures into performing good deeds in the hope such acts redeem the creatures.

## Magical Feathers

Firebird feathers are prized throughout the mortal world, and occasionally, the creatures bestow feathers upon those they favor. Firebirds also seed hidden locations with specialized feathers, which burst into full-grown firebirds after a year. Firebirds live over 100 years.

## Statblock

```ad-statblock
title: Firebird
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ToB1-2023/Firebird.webp#token)
*Small celestial, Neutral Good*

- **Armor Class** 16 (natural armor)
- **Hit Points** 88 (`16d6 + 32`)
- **Speed** 20 ft., fly 60 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|12 (+1)|19 (+4)|14 (+2)|16 (+3)|15 (+2)|21 (+5)|

- **Proficiency Bonus** +2
- **Saving Throws** Wisdom +4, Charisma +7
- **Skills** Insight +4, Medicine +4, Perception +6
- **Senses** truesight 60 ft., passive Perception 16
- **Damage Resistances** bludgeoning, piercing, slashing from nonmagical attacks
- **Damage Immunities** fire, poison
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** Celestial, Common, Primordial, telepathy 60 ft.
- **Challenge** 4

## Traits

***Enforce Good Deeds.*** A creature that has received assistance, such as healing or a glowing feather, from the firebird must succeed on a DC 15 Wisdom saving throw or be affected by the [geas](2-Mechanics/CLI/spells/geas.md) spell for 30 days. While under the geas, the affected creature must assist nonhostile creatures suffering from starvation or thirst by alleviating the starvation or thirst.

***Fiery Weapons.*** The firebird's weapon attacks are magical. When the firebird hits with any weapon, the weapon deals an extra `dice:2d6|noform|avg` (`2d6`) fire damage (included in the attack).

***Glowing Feathers.*** The firebird sheds bright light in a 5- to 20-foot radius and dim light for an additional number of feet equal to the chosen radius. The firebird can alter the radius as a bonus action. If the firebird willingly gifts a feather to a creature, the feather sheds bright light in a 10-foot radius and dim light for an additional 10 feet indefinitely.

***Magic Resistance.*** The firebird has advantage on saving throws against spells and other magical effects.

***Warming Presence.*** The firebird and each creature within 5 feet of it are immune to the effects of cold environments, provided the cold is caused by naturally occurring weather and climate. When the firebird is inside a structure, it can choose for this trait to affect all creatures within the structure (no action required), regardless of how close they are to it.

## Actions

***Multiattack.*** The firebird makes one Beak attack and one Talon attack.

***Beak.*** *Melee Weapon Attack:* `dice:1d20+6|noform|text(+6)` to hit, reach 5 ft., one target. *Hit:* `dice:1d6+4|noform|avg|text(7)` (`1d6 + 4`) piercing damage plus `dice:2d6|noform|avg|text(7)` (`2d6`) fire damage.

***Talon.*** *Melee Weapon Attack:* `dice:1d20+6|noform|text(+6)` to hit, reach 5 ft., one target. *Hit:* `dice:2d4+4|noform|avg|text(9)` (`2d4 + 4`) slashing damage plus `dice:2d6|noform|avg|text(7)` (`2d6`) fire damage.

***Blinding Ray (Recharge 5-6).*** The firebird fires a burning ray of light from its tail feathers in a 30-foot line that is 5 feet wide. Each creature in that line must make a DC 15 Dexterity saving throw. On a failure, a creature takes `dice:5d6|noform|avg|text(17)` (`5d6`) fire damage and is [blinded](2-Mechanics/CLI/rules/conditions.md#Blinded) until the end of its next turn. On a success, a creature takes half the damage and isn't [blinded](2-Mechanics/CLI/rules/conditions.md#Blinded).

***Healing Feathers (3/Day).*** The firebird touches another creature, brushing its wings against the creature. The target magically regains 10 `dice:3d6|noform|avg` (`3d6`) hp and is freed from any disease, poison, blindness, or deafness.
```
^statblock

## Environment

forest, underdark