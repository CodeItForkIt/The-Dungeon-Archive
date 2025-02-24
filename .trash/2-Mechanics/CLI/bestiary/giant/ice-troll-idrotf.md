---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/idrotf
- monster/cr/8
- monster/size/large
- monster/type/giant
aliases: ["Ice Troll"]
---
# Ice Troll
*Source: Icewind Dale: Rime of the Frostmaiden p. 295*  

Ice trolls have all the meanness and hunger of common trolls. Their hearts radiate extreme cold, to the detriment of other nearby creatures.

## Ice Troll Hearts

An ice troll's heart remains cold even after the troll's destruction. As long as the troll can't regenerate, its heart can be safely removed from its remains, handled, and kept. An ice troll's heart, once removed, becomes a harmless Tiny object with AC 13, 4 hit points, and immunity to all damage except fire damage. For the next 24 hours, the heart has the following magical properties:

- A creature that eats the heart gains the ability to regenerate for the next 24 hours, regaining 5 hit points at the start of each of its turns. If the creature takes acid or fire damage, this trait doesn't function at the start of its next turn. The creature dies only if it starts its turn with 0 hit points and doesn't regenerate.  
- If buried in the ground under a foot or more of earth, the heart melts away and summons a blizzard like that created by the [control weather](2-Mechanics/CLI/spells/control-weather.md) spell. It takes 10 minutes for the heart to melt and the blizzard to form. The blizzard lasts for 8 hours.  
- A hag or similar creature can perform a ritual that turns the heart into a magical talisman that acts like a patch of brown mold (see "[Brown Mold](2-Mechanics/CLI/traps-hazards/brown-mold.md)" in the "Dungeon Master's Guide"). This effect lasts until the heart is destroyed.  
- A creature proficient with alchemist's supplies can squeeze enough residual fluid out of the heart to mix with other alchemical ingredients, creating one [potion of resistance (cold)](2-Mechanics/CLI/items/potion-of-cold-resistance.md). It takes 1 hour to create this potion.   

## Statblock

```ad-statblock
title: Ice Troll
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/IDRotF/Ice%20Troll.webp#token)
*Large giant, Chaotic Evil*

- **Armor Class** 16 (natural armor)
- **Hit Points** 115 (`10d10 + 60`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|18 (+4)| 8 (-1)|22 (+6)| 7 (-2)| 9 (-1)| 7 (-2)|

- **Proficiency Bonus** +3
- **Saving Throws** ⏤
- **Skills** Perception +2
- **Senses** darkvision 60 ft., passive Perception 12
- **Damage Immunities** cold
- **Languages** Giant
- **Challenge** 8

## Traits

***Cold Aura.*** While it's alive, the troll generates an aura of bitter cold that fills the area within 10 feet of it. At the start of the troll's turn, all nonmagical flames in the aura are extinguished. Any creature that starts its turn within 10 feet of the troll takes `dice:3d6|noform|avg|text(10)` (`3d6`) cold damage.

***Keen Smell.*** The ice troll has advantage on Wisdom ([Perception](2-Mechanics/CLI/rules/skills.md#Perception)) checks that rely on smell.

***Regeneration.*** The ice troll regains 10 hit points at the start of its turn. If the troll takes acid or fire damage, this trait doesn't function at the start of the troll's next turn. The ice troll dies only if it starts its turn with 0 hit points and doesn't regenerate.

## Actions

***Multiattack.*** The troll makes three attacks: one with its bite and two with its claws.

***Bite.*** *Melee Weapon Attack:* `dice:1d20+7|noform|text(+7)` to hit, reach 5 ft., one target. *Hit:* `dice:1d6+4|noform|avg|text(7)` (`1d6 + 4`) piercing damage plus `dice:2d8|noform|avg|text(9)` (`2d8`) cold damage.

***Claw.*** *Melee Weapon Attack:* `dice:1d20+7|noform|text(+7)` to hit, reach 5 ft., one target. *Hit:* `dice:2d6+4|noform|avg|text(11)` (`2d6 + 4`) slashing damage plus `dice:2d8|noform|avg|text(9)` (`2d8`) cold damage. If the target takes any of the cold damage, the target must succeed on a DC 15 Constitution saving throw or have disadvantage on its attack rolls until the end of its next turn.
```
^statblock