---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/tob1-2023
- monster/cr/8
- monster/environment/forest
- monster/size/large
- monster/type/beast
aliases: ["Savager"]
---
# Savager
*Source: Tome of Beasts 1 (2023 Edition) p. 318*  

*A porcupine-quilled creature built like a grizzly bear with claws and fangs like scimitars rises on its hind legs. Its forelegs are mangled and scabbed, and its eyes shine with hatred and anticipation.*

## Driven by Dark Spirits

While many druids claim these bear-like animals are not cursed or enchanted, the savager's habit of killing any living creature on sight is not natural behavior. Hunger doesn't explain their attacks, since savagers eat only part of their kills before abandoning the meal and looking for other animals to attack. Some dark forest spirit drives them.

## Gnaws Itself

When there are no other creatures nearby to attack, a savager gnaws on its own forelimbs, resulting in scabs, scars, and calluses so thick and numb that they protect the savager from even the sharpest of swords.

## Rare Meetings

The only creature a savager won't attack on sight is another savager, giving each other a wide berth or meeting briefly to produce young. A savager litter contains anywhere from ten to twenty-five cubs, all of them born able to walk and fend for themselves.

## Statblock

```ad-statblock
title: Savager
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ToB1-2023/Savager.webp#token)
*Large beast, Neutral Evil*

- **Armor Class** 17 (natural armor)
- **Hit Points** 105 (`10d10 + 50`)
- **Speed** 40 ft., climb 20 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|22 (+6)|14 (+2)|21 (+5)| 2 (-4)|10 (+0)|13 (+1)|

- **Proficiency Bonus** +3
- **Saving Throws** Dexterity +5, Constitution +8
- **Skills** Perception +3
- **Senses** darkvision 60 ft., passive Perception 13
- **Damage Resistances** bludgeoning, piercing, slashing from nonmagical attacks
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened)
- **Languages** —
- **Challenge** 8

## Traits

***Mighty Swing.*** If the savager doesn't move during its turn, it has advantage on the next Claw attack it makes before the start of its next turn.

***Spines.*** A creature that touches the savager or hits it with a melee attack while within 5 feet of it takes `dice:2d4|noform|avg|text(5)` (`2d4`) piercing damage. In addition, a creature [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) by or grappling the savager takes `dice:2d4|noform|avg|text(5)` (`2d4`) piercing damage at the start of the savager's turn.

## Actions

***Multiattack.*** The savager makes one Bite attack and two Claw attacks. If both Claw attacks hit one creature, the target must succeed on a DC 15 Strength saving throw or take `dice:2d8|noform|avg|text(9)` (`2d8`) slashing damage as the savager rips into the target.

***Bite.*** *Melee Weapon Attack:* `dice:1d20+9|noform|text(+9)` to hit, reach 5 ft., one target. *Hit:* `dice:2d12+6|noform|avg|text(19)` (`2d12 + 6`) piercing damage.

***Claw.*** *Melee Weapon Attack:* `dice:1d20+9|noform|text(+9)` to hit, reach 5 ft., one target. *Hit:* `dice:2d8+6|noform|avg|text(15)` (`2d8 + 6`) slashing damage.
```
^statblock

## Environment

forest