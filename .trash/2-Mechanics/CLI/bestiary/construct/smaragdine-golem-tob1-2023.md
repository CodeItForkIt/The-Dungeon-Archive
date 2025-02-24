---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/tob1-2023
- monster/cr/14
- monster/environment/urban
- monster/size/large
- monster/type/construct
aliases: ["Smaragdine Golem"]
---
# Smaragdine Golem
*Source: Tome of Beasts 1 (2023 Edition) p. 219*  

*This large statue of emerald-green crystal has a humanoid body with the head of an ibis. Tiny symbols and runes are etched into it, and portions of it are inlaid with bits of gold.*

## Occult Initiates

Smaragdine golems are crafted by disciples of occult esoterica to guard their secret meeting halls, sacred texts, and the arcane books of power.

## Emerald Body

Though they seem to be made entirely of emeralds (and some are used in their construction), a smaragdine golem's body is closer to enchanted glass than to gemstones, a sad truth that has disappointed many plunderers.

## A Maker's Privilege

Though smaragdine golems are sometimes given to powerful mages, scholars, theurgists, and hierophants as a token of esteem, they are always subject first to the magic and orders of their creators.

## Statblock

```ad-statblock
title: Smaragdine Golem
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ToB1-2023/Smaragdine%20Golem.webp#token)
*Large construct, Unaligned*

- **Armor Class** 17 (natural armor)
- **Hit Points** 231 (`22d10 + 110`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|24 (+7)|11 (+0)|21 (+5)| 3 (-4)|11 (+0)| 1 (-5)|

- **Proficiency Bonus** +5
- **Saving Throws** ⏤
- **Skills** ⏤
- **Senses** darkvision 120 ft., passive Perception 10
- **Damage Immunities** poison; psychic; bludgeoning, piercing, slashing from nonmagical attacks that aren't adamantine
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened), [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed), [petrified](2-Mechanics/CLI/rules/conditions.md#Petrified), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** understands the languages of its creator but can't speak
- **Challenge** 14

## Traits

***Construct Nature.*** The golem doesn't require air, food, drink, or sleep.

***Enchanted Weapons.*** The golem's weapon attacks are magical. When the golem hits with any weapon, the weapon deals an extra `dice:5d8|noform|avg` (`5d8`) force damage (included in the attack).

***Immutable Form.*** The golem is immune to any spell or effect that would alter its form.

***Magic Resistance.*** The golem has advantage on saving throws against spells and other magical effects.

***Magic Vessel.*** When the smaragdine golem counters or ends a spell with Absorb Spell, it holds the spell's magical energy within its body and becomes Charged for 1 minute. While Charged, the golem sheds dim light in a 10-foot radius.

## Actions

***Multiattack.*** The smaragdine golem makes two Slam attacks. It can replace one attack with a use of Release Spell.

***Slam.*** *Melee Weapon Attack:* `dice:1d20+12|noform|text(+12)` to hit, reach 5 ft., one target. *Hit:* `dice:3d8+7|noform|avg|text(20)` (`3d8 + 7`) bludgeoning damage plus `dice:5d8|noform|avg|text(22)` (`5d8`) force damage.

***Release Spell (Recharge Special).*** The smaragdine golem releases an absorbed spell's energy in a green burst centered on a point the golem can see within 60 feet of it. Each creature, other than the smaragdine golem, within 5 feet of that point per level of the absorbed spell must make a DC 18 Dexterity saving throw. On a failure, a creature takes `dice:3d6|noform|avg|text(10)` (`3d6`) force damage per level of the absorbed spell and is [incapacitated](2-Mechanics/CLI/rules/conditions.md#Incapacitated) until the end of its next turn. On a success, a creature takes half the damage and isn't [incapacitated](2-Mechanics/CLI/rules/conditions.md#Incapacitated). The golem can use this action only if it is Charged (see the Magic Vessel trait).

## Reactions

***Absorb Spell.*** When a creature the smaragdine golem can see within 30 feet of it casts a spell, the golem can absorb the spell's energy, countering it. This works like the [counterspell](2-Mechanics/CLI/spells/counterspell.md) spell, except the golem must always make a spellcasting ability check, no matter the spell's level. Alternatively, when a creature the golem can see within 30 feet of the golem starts its turn while under the effects of a spell, such as bless or heroes' feast, the golem can absorb the spell's magic, ending the effect. In either case, the golem's ability check for this is +10. If it successfully counters or ends the spell, it becomes Charged (see the Magic Vessel trait). The golem can't use Absorb Spell while it is Charged.
```
^statblock

## Environment

urban