---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/tob1-2023
- monster/cr/13
- monster/environment/urban
- monster/size/large
- monster/type/construct
aliases: ["Steam Golem"]
---
# Steam Golem
*Source: Tome of Beasts 1 (2023 Edition) p. 220*  

*With wicked axe blades fastened along its arms and bronze runes inlaid on its armored torso, this golem is a smooth-running machine of death.*

## Boilers and Hydraulics

A steam golem is built around a central boiler with clockwork gears and hydraulic cylinders powering its legs and arms. Most steam golems have axe blades welded onto each of their arms, and many have one arm extended in a single, long-hafted axe. They tower 10 feet tall, and their legs are often built with reversed knee joints for greater leverage when they move. The eyes of a steam golem glow orange or red from its internal fires.

## Steam Whistle

A steam golem has four to six vents for releasing steam. These whistles are mounted over the shoulders and can be heard at distances up to a mile in open terrain.

## Fuel Required

A steam golem's machinery consumes 30 pounds of coal and 100 gallons of water per day if it engages in more than brief combat. When resting or standing guard, a steam golem needs only one third of those amounts.

## Statblock

```ad-statblock
title: Steam Golem
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ToB1-2023/Steam%20Golem.webp#token)
*Large construct, Unaligned*

- **Armor Class** 18 (natural armor)
- **Hit Points** 171 (`18d10 + 72`)
- **Speed** 40 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|26 (+8)|12 (+1)|18 (+4)| 3 (-4)|10 (+0)| 1 (-5)|

- **Proficiency Bonus** +5
- **Saving Throws** ⏤
- **Skills** ⏤
- **Senses** darkvision 120 ft., passive Perception 10
- **Damage Immunities** fire; poison; psychic; bludgeoning, piercing, slashing from nonmagical attacks that aren't adamantine
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened), [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed), [petrified](2-Mechanics/CLI/rules/conditions.md#Petrified), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** understands the languages of its creator but can't speak
- **Challenge** 13

## Traits

***Boiler Weakness.*** If the steam golem starts its turn immersed in water, or if it was soaked with at least 20 gallons of water on its previous turn, it risks losing steam pressure in its boiler. The steam golem must succeed on a DC 20 Constitution saving throw or its internal fire is extinguished. Until its internal fire is relit, the golem's speed is halved, its AC is reduced by 2, and it must repeat the saving throw at the start of each of its turns. On a failure, it stops repeating this saving throw and becomes dormant, effectively dead until the fire is relit. A Medium or smaller creature within 5 feet of the golem can take an action to relight the golem's internal fire, making it active again.

***Construct Nature.*** The golem doesn't require air, food, drink, or sleep.

***Heated Weapons.*** The steam golem's weapon attacks are magical. When the golem hits with any weapon, the weapon deals an extra `dice:4d8|noform|avg` (`4d8`) fire damage (included in the attack).

***Immutable Form.*** The golem is immune to any spell or effect that would alter its form.

***Magic Resistance.*** The golem has advantage on saving throws against spells and other magical effects.

## Actions

***Multiattack.*** The steam golem makes one Axe Arm attack and one Long Axe attack.

***Axe Arm.*** *Melee Weapon Attack:* `dice:1d20+13|noform|text(+13)` to hit, reach 5 ft., one target. *Hit:* `dice:4d6+8|noform|avg|text(22)` (`4d6 + 8`) slashing damage plus `dice:4d8|noform|avg|text(18)` (`4d8`) fire damage.

***Long Axe.*** *Melee Weapon Attack:* `dice:1d20+13|noform|text(+13)` to hit, reach 10 ft., one target. *Hit:* `dice:4d8+8|noform|avg|text(26)` (`4d8 + 8`) slashing damage plus `dice:4d8|noform|avg|text(18)` (`4d8`) fire damage.

***Steam Blast (Recharge 5-6).*** The steam golem releases a blast of steam in a 30-foot cone or in a 10-foot-radius cloud that extends from it, spreading around corners. Each creature in the area must make a DC 17 Dexterity saving throw, taking `dice:12d8|noform|avg|text(54)` (`12d8`) fire damage on a failed save, or half as much damage on a successful one.

## Reactions

***Whistle (Recharge 4-6).*** When a creature the steam golem can see within 30 feet of it casts a spell, the steam golem emits a shriek from its twin steam whistles. The spellcaster must succeed on a DC 17 Constitution saving throw or the spell fails and has no effect.
```
^statblock

## Environment

urban