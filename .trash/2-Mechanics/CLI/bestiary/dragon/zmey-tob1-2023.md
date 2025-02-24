---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/tob1-2023
- monster/cr/15
- monster/environment/forest
- monster/environment/swamp
- monster/size/huge
- monster/type/dragon
aliases: ["Zmey"]
---
# Zmey
*Source: Tome of Beasts 1 (2023 Edition) p. 403*  

*Crashing through the forest, this three-headed dragon stands upright, its long tail thrashing from side to side as it walks.*

Hunting beneath the canopy of the forest, lurking below the surfaces of lakes, and guarding caves concealing great treasure and mystery, the zmey has two roles—vicious terror and nature's protector.

## Claws of the Forest

Single-mindedly destructive, the zmey keeps the heart of the forest free from interlopers. Rumors suggest the heart of an ancient forest itself can control the actions of these lesser dragons, while others believe zmeys have pacts with certain druid circles.

## Voracious Headlings

A zmey's head doesn't die when severed from its body. Within days, it becomes a miniature zmey, developing into a full-grown zmey after two months. Voracious appetite fuels this growth. Coating the head or headling in the first month of life prevents this growth.

## A Zmey's Lair

Zmeys make their lairs in the deepest parts of the forest. They plant and grow trees into "caves" with satellite "rooms" within their lair.

## Statblock

```ad-statblock
title: Zmey
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ToB1-2023/Zmey.webp#token)
*Huge dragon, Chaotic Evil*

- **Armor Class** 18 (natural armor)
- **Hit Points** 189 (`18d12 + 72`)
- **Speed** 30 ft., fly 50 ft., swim 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|22 (+6)|13 (+1)|19 (+4)|16 (+3)|16 (+3)|12 (+1)|

- **Proficiency Bonus** +5
- **Saving Throws** Constitution +9, Wisdom +8, Charisma +6
- **Skills** Perception +8
- **Senses** blindsight 60 ft., darkvision 90 ft., passive Perception 18
- **Damage Resistances** cold, fire
- **Condition Immunities** [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed), [unconscious](2-Mechanics/CLI/rules/conditions.md#Unconscious)
- **Languages** Common, Draconic, Elvish, Sylvan
- **Challenge** 15

## Traits

***Amphibious.*** The zmey can breathe air and water.

***Legendary Resistance (3/Day).*** If the zmey fails a saving throw, it can choose to succeed instead.

***Regeneration.*** The zmey regains 15 hp at the start of its turn. If the zmey takes acid or fire damage, this trait doesn't function at the start of the zmey's next turn. The zmey dies if it starts its turn with 0 hp and doesn't regenerate.

***Three Heads.*** The zmey has three heads. While it has more than one head, the zmey has advantage on saving throws against being [blinded](2-Mechanics/CLI/rules/conditions.md#Blinded), [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [deafened](2-Mechanics/CLI/rules/conditions.md#Deafened), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened), [stunned](2-Mechanics/CLI/rules/conditions.md#Stunned), and knocked [unconscious](2-Mechanics/CLI/rules/conditions.md#Unconscious). Whenever the zmey takes 40 damage or more in a single turn, one of its heads is severed. If it has only one head remaining, dealing 40 damage or more to it doesn't sever the final head. It regrows any severed heads when it finishes a long rest.

The zmey's severed head grows into a zmey headling in `dice:1d4|noform|avg` (`1d4`) rounds. The headling isn't under the zmey's control, but it takes the zmey's requests or actions in the most favorable way it can.

## Actions

***Multiattack.*** The zmey makes two Claw attacks and as many Bite attacks as it has heads.

***Bite.*** *Melee Weapon Attack:* `dice:1d20+11|noform|text(+11)` to hit, reach 10 ft., one target. *Hit:* `dice:2d12+6|noform|avg|text(19)` (`2d12 + 6`) piercing damage.

***Claw.*** *Melee Weapon Attack:* `dice:1d20+11|noform|text(+11)` to hit, reach 5 ft., one target. *Hit:* `dice:4d6+6|noform|avg|text(20)` (`4d6 + 6`) slashing damage.

***Fire Breath (Recharge 5-6).*** The zmey exhales fire in a 30-foot cone out of each of its heads. Each creature in a cone must make a DC 17 Dexterity saving throw, taking `dice:14d6|noform|avg|text(49)` (`14d6`) fire damage on a failed save, or half as much damage on a successful one. If the cones overlap, each creature in the overlapping cones must make one saving throw with disadvantage against only one of the cones rather than one saving throw for each cone. The zmey can choose for this breath to not harm plants or Plant creatures.

## Legendary Actions

***Move.*** The zmey moves up to its speed, or flies up to half its flying speed, without provoking opportunity attacks.

***Tail Whip.*** The zmey whips its tail around it. Each creature within 15 feet of the zmey must succeed on a DC 17 Dexterity saving throw or be knocked [prone](2-Mechanics/CLI/rules/conditions.md#Prone).

***Tripartite Roar (Costs 2 Actions).*** The zmey's heads exhale a three‑part roar, one a deafening shriek, one a frightful screech, and one a stunning bellow, in a 30-foot cone. Each creature in that area must succeed on a DC 17 Wisdom saving throw or suffer the effects of the roars until the end of its next turn. The effects depend upon the number of heads the zmey has remaining: [deafened](2-Mechanics/CLI/rules/conditions.md#Deafened) for only one head, [deafened](2-Mechanics/CLI/rules/conditions.md#Deafened) and [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened) for two heads, or [stunned](2-Mechanics/CLI/rules/conditions.md#Stunned) for three heads.

![Zmey](2-Mechanics/CLI/bestiary/legendary-group/zmey-tob1-2023.md)
```
^statblock

## Environment

forest, swamp