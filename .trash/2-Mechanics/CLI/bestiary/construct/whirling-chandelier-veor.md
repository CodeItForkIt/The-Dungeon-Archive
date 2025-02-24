---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/veor
- monster/cr/7
- monster/size/large
- monster/type/construct
aliases: ["Whirling Chandelier"]
---
# Whirling Chandelier
*Source: Vecna: Eve of Ruin p. 239*  

Compared to other animated objects, whirling chandeliers seem to have capricious personalities. Victims typically perceive a whirling chandelier's Blazing Vortex as mischievousness or outright malevolence, though the chandelier lacks any understanding of such concepts. A whirling chandelier makes tactical decisions only as a means to perform its master's orders to the best of its ability.

```ad-statblock
title: Whirling Chandelier
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/VEoR/Whirling%20Chandelier.webp#token)
*Large construct, Unaligned*

- **Armor Class** 13 (natural armor)
- **Hit Points** 105 (`14d10 + 28`)
- **Speed** 30 ft., fly 30 ft. (hover)

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|18 (+4)|15 (+2)|15 (+2)| 3 (-4)| 5 (-3)| 1 (-5)|

- **Proficiency Bonus** +3
- **Saving Throws** ⏤
- **Skills** ⏤
- **Senses** blindsight 60 ft. (blind beyond this radius), passive Perception 7
- **Damage Resistances** fire
- **Damage Immunities** poison, psychic
- **Condition Immunities** [blinded](2-Mechanics/CLI/rules/conditions.md#Blinded), [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [deafened](2-Mechanics/CLI/rules/conditions.md#Deafened), [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened), [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed), [petrified](2-Mechanics/CLI/rules/conditions.md#Petrified), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** understands Common but can't speak
- **Challenge** 7

## Traits

***False Appearance.*** If the chandelier is motionless at the start of combat, it has advantage on its initiative roll. Moreover, if a creature hasn't observed the chandelier move or act, that creature must succeed on a DC 18 Intelligence ([Investigation](2-Mechanics/CLI/rules/skills.md#Investigation)) check to discern that the chandelier is animate.

***Fiery Aura.*** Any creature that starts its turn within 5 feet of the chandelier takes `dice:2d6|noform|avg|text(7)` (`2d6`) fire damage.

## Actions

***Multiattack.*** The chandelier makes three Chain attacks, three Lamp attacks, or a combination thereof.

***Chain.*** *Melee Weapon Attack:* `dice:1d20+7|noform|text(+7)` to hit, reach 15 ft., one target. *Hit:* `dice:2d8+4|noform|avg|text(13)` (`2d8 + 4`) bludgeoning damage, and the target must succeed on a DC 15 Strength saving throw or be pulled into an unoccupied space within 5 feet of the chandelier.

***Lamp.*** *Melee Weapon Attack:* `dice:1d20+7|noform|text(+7)` to hit, reach 5 ft., one target. *Hit:* `dice:2d4+4|noform|avg|text(9)` (`2d4 + 4`) bludgeoning damage plus `dice:3d8|noform|avg|text(13)` (`3d8`) fire damage.

***Blazing Vortex (Recharge 5-6).*** Each creature within 20 feet of the chandelier and not behind total cover must succeed on a DC 14 Constitution saving throw or take `dice:8d8|noform|avg|text(36)` (`8d8`) fire damage and have the [blinded](2-Mechanics/CLI/rules/conditions.md#Blinded) condition until the start of the chandelier's next turn.
```
^statblock