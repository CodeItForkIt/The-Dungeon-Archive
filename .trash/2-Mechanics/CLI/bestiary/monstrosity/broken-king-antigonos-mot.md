---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/mot
- monster/cr/3
- monster/size/large
- monster/type/monstrosity
aliases: ["Broken King Antigonos"]
---
# Broken King Antigonos
*Source: Mythic Odysseys of Theros p. 189*  

He is old and decrepit, garbed in ancient finery worn to tatters. A dented crown rests on his brow, and one of his horns ends in a jagged stump. He drags a rusty greataxe in the dirt, and tied to his back is a 30-pound, clay amphora painted with images of warring hoplites—all of whom have had horns crudely painted on them to make them look like minotaurs. The broad-mouthed amphora is large enough to hold roughly 55 gallons of wine.

He claims that he was a great king who was cursed by Mogis after he defied his war advisors by making his sickly but beloved child his heir. He was cast out and has since become tragically obsessed with finding a worthy heir.

```ad-statblock
title: Broken King Antigonos
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/MOT/Broken%20King%20Antigonos.webp#token)
*Large monstrosity, Chaotic Evil*

- **Armor Class** 14 (natural armor)
- **Hit Points** 38 (`9d10 + 27`)
- **Speed** 40 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|18 (+4)|11 (+0)|16 (+3)| 6 (-2)|16 (+3)| 9 (-1)|

- **Proficiency Bonus** +2
- **Saving Throws** ⏤
- **Skills** Perception +7
- **Senses** darkvision 60 ft., passive Perception 17
- **Languages** Abyssal
- **Challenge** 3

## Traits

***Charge.*** If Antigonos moves at least 10 feet straight toward a target and then hits it with a gore attack on the same turn, the target takes an extra `dice:2d8|noform|avg|text(9)` (`2d8`) piercing damage. If the target is a creature, it must succeed on a DC 14 Strength saving throw or be pushed up to 10 feet away and knocked [prone](2-Mechanics/CLI/rules/conditions.md#Prone).

***Labyrinthine Recall.*** Antigonos can perfectly recall any path he has traveled.

***Reckless.*** At the start of his turn, Antigonos can gain advantage on all melee weapon attack rolls he makes during that turn, but attack rolls against him have advantage until the start of his next turn.

***Decrepit State.*** Antigonos has disadvantage on his attack rolls.

## Actions

***Greataxe.*** *Melee Weapon Attack:* `dice:1d20+6|noform|text(+6)` to hit, reach 5 ft., one target. *Hit:* `dice:2d12+4|noform|avg|text(17)` (`2d12 + 4`) slashing damage.

***Gore.*** *Melee Weapon Attack:* `dice:1d20+6|noform|text(+6)` to hit, reach 5 ft., one target. *Hit:* `dice:2d8+4|noform|avg|text(13)` (`2d8 + 4`) piercing damage.

***Amphora.*** *Melee Weapon Attack:* `dice:1d20+6|noform|text(+6)` to hit, reach 5 ft., one Medium or smaller creature. *Hit:* `dice:1d8+4|noform|avg|text(8)` (`1d8 + 4`) bludgeoning damage. If there is not already a creature inside the amphora, the target is [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained) inside. As an action, the [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained) creature can make a DC 14 Dexterity ([Acrobatics](2-Mechanics/CLI/rules/skills.md#Acrobatics)) check, escaping from the amphora on a success. The effect also ends if the amphora is destroyed. The amphora has AC 8, 20 hit points, and immunity to poison and psychic damage.
```
^statblock