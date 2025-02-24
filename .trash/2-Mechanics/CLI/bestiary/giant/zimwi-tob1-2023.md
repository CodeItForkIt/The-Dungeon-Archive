---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/tob1-2023
- monster/cr/5
- monster/environment/grassland
- monster/size/medium
- monster/type/giant
aliases: ["Zimwi"]
---
# Zimwi
*Source: Tome of Beasts 1 (2023 Edition) p. 402*  

*This swift-moving, lanky humanoid has long arms ending in wicked claws and jaws that open impossibly wide.*

## Swift as Horses

Distantly related to trolls, the swift and nimble zimwi are a plague upon grasslands. They are constantly hungry, ill-tempered and capable of running down horses, leading many zimwi to attack large caravans for food.

## Always Starving

Most zimwi attacks are driven by hunger. The stomach of a zimwi is larger than its body, extending extra-dimensionally and driving the zimwi nearly insane with constant hunger, leaving the zimwi always feeling as if it is starving to death. Because of their endless hunger and low intelligence, zimwi have little awareness of the course of a battle. Losing means only that they have not eaten. As long as they continue to feast, they fight on, feeling victorious until death comes to them or all of their prey.

## Stomachs of Holding

The extradimensional pouch within a zimwi's stomach makes the stomach serviceable as a bag of holding if treated and enchanted properly. The harder part is relieving the zimwi of its prize.

## Statblock

```ad-statblock
title: Zimwi
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ToB1-2023/Zimwi.webp#token)
*Medium giant, Chaotic Evil*

- **Armor Class** 16 (natural armor)
- **Hit Points** 119 (`13d8 + 52`)
- **Speed** 60 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|13 (+1)|18 (+4)|19 (+4)| 6 (-2)| 9 (-1)| 7 (-2)|

- **Proficiency Bonus** +3
- **Saving Throws** ⏤
- **Skills** Perception +2
- **Senses** darkvision 60 ft., passive Perception 12
- **Languages** Giant
- **Challenge** 5

## Traits

***Desperate Hunger.*** When the zimwi is below half its hp maximum, it has advantage on melee attack rolls against creatures that aren't Constructs.

## Actions

***Multiattack.*** The zimwi makes one Bite attack and one Claw attack. It can replace its Bite attack with a use of Swallow.

***Bite.*** *Melee Weapon Attack:* `dice:1d20+7|noform|text(+7)` to hit, reach 5 ft., one target. *Hit:* `dice:2d8+4|noform|avg|text(13)` (`2d8 + 4`) piercing damage.

***Claws.*** *Melee Weapon Attack:* `dice:1d20+7|noform|text(+7)` to hit, reach 5 ft., one target. *Hit:* `dice:2d6+4|noform|avg|text(11)` (`2d6 + 4`) slashing damage, and the target is [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) (escape DC 12) if it is a Medium or smaller creature. The zimwi has two claws, each of which can grapple only one target.

***Swallow.*** The zimwi makes one Bite attack against a Medium or smaller creature it is grappling. If the attack hits, the target is also swallowed, and the grapple ends. While swallowed, the target is [blinded](2-Mechanics/CLI/rules/conditions.md#Blinded) and [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained), it has total cover against attacks and other effects outside the zimwi, and it takes `dice:3d6|noform|avg|text(10)` (`3d6`) acid damage at the start of each of the zimwi's turns. A zimwi can have up to two creatures swallowed at a time.

If the zimwi takes 20 damage or more on a single turn from a swallowed creature, the zimwi must succeed on a DC 14 Constitution saving throw at the end of that turn or regurgitate all swallowed creatures, which fall [prone](2-Mechanics/CLI/rules/conditions.md#Prone) in a space within 5 feet of the zimwi. If the zimwi dies, a swallowed creature is no longer [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained) by it and can escape from the corpse by using 5 feet of movement, exiting [prone](2-Mechanics/CLI/rules/conditions.md#Prone).
```
^statblock

## Environment

grassland