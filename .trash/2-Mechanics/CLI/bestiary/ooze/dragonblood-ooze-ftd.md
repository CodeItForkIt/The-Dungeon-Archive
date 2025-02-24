---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/ftd
- monster/cr/5
- monster/size/large
- monster/type/ooze
aliases: ["Dragonblood Ooze"]
---
# Dragonblood Ooze
*Source: Fizban's Treasury of Dragons p. 182*  

Magic-minded artisans have long incorporated parts of dragons' bodies into magic items, crafting dragon hide into armor and forging weapons from claws and teeth. Alchemists have found beneficial uses for dragon blood, but ill-advised experiments have also given rise to dragonblood oozes.

The congealed blood of a dragon given mobility and hunger, the ooze tries to shape itself into a draconic form. It cannot hold a coherent shape for long and soon collapses into an amorphous heap. Similarly, it tries to manifest a breath weapon but manages only to spew forth part of its own body that it then reels back in.

```ad-statblock
title: Dragonblood Ooze
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/FTD/Dragonblood%20Ooze.webp#token)
*Large ooze, Unaligned*

- **Armor Class** 14 (natural armor)
- **Hit Points** 68 (`8d10 + 24`)
- **Speed** 20 ft., climb 20 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|18 (+4)| 6 (-2)|17 (+3)| 2 (-4)|12 (+1)|10 (+0)|

- **Proficiency Bonus** +3
- **Saving Throws** ⏤
- **Skills** Perception +4, Stealth +4
- **Senses** blindsight 120 ft. (blind beyond this radius), passive Perception 14
- **Damage Resistances** acid, cold, fire, lightning, poison
- **Condition Immunities** [blinded](2-Mechanics/CLI/rules/conditions.md#Blinded), [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [deafened](2-Mechanics/CLI/rules/conditions.md#Deafened), [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened), [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled), [prone](2-Mechanics/CLI/rules/conditions.md#Prone), [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained)
- **Languages** understands Draconic and the languages of its creator but can't speak
- **Challenge** 5

## Traits

***Amorphous.*** The ooze can move through a space as narrow as 1 inch wide without squeezing.

***Spider Climb.*** The ooze can climb difficult surfaces, including upside down on ceilings, without needing to make an ability check.

## Actions

***Multiattack.*** The ooze makes two Pseudopod attacks. The ooze can replace one Pseudopod attack with its Slime Breath, if available.

***Pseudopod.*** *Melee Weapon Attack:* `dice:1d20+7|noform|text(+7)` to hit, reach 10 ft., one target. *Hit:* `dice:1d10+4|noform|avg|text(9)` (`1d10 + 4`) bludgeoning damage plus `dice:4d6|noform|avg|text(14)` (`4d6`) acid damage. If the target is a Large or smaller creature, it is [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) (escape DC 15). Until this grapple ends, the target takes `dice:2d6|noform|avg|text(7)` (`2d6`) acid damage at the start of each of its turns.

***Slime Breath (Recharge 6).*** The ooze expels a spray of its gelatinous mass in a 30-foot cone. Each creature in that area must make a DC 14 Dexterity saving throw. On a failed save, the creature takes `dice:4d10|noform|avg|text(22)` (`4d10`) acid damage and is pulled up to 30 feet straight toward the ooze. On a successful save, the creature takes half as much damage and isn't pulled.
```
^statblock