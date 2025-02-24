---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/qftis
- monster/cr/3
- monster/size/medium
- monster/type/construct
aliases: ["Worker Robot"]
---
# Worker Robot
*Source: Quests from the Infinite Staircase p. 215*  

Worker robots are built for physical labor such as hauling cargo, construction, and maintenance, though some worker robots fill public-facing service roles. Antigravity technology and built-in tractor beams allow worker robots to effortlessly lift cargo and other heavy objects with their mechanical tentacles, which double as weapons if the robots are threatened or drafted for security purposes. A worker robot's voice is often utilitarian, programmed to use simple phrases without embellishment. Worker robots designed to be in public view—such as units that carry out deliveries, repairs, or transportation—have voices that more closely mimic those of their creators. These robots employ mollifying phrases or make shallow but pleasant small talk.

## Robots

Robots are Constructs created for heavy labor, menial tasks, or routine security. Despite robots' hardy construction, their circuitry is prone to overload if exposed to strong electrical currents. A robot has a pair of small appendages for fine motor control and object manipulation, as well as two larger appendages specialized for its role. Robots are programmed with intelligence, understanding, and usually loyalty to their creators. Despite that, long-operating robots sometimes develop their own personalities and ideas. Robots that endure long stretches of isolation, mistreatment, or neglect are prone to malfunctions. Some robots become despondent or cruel, while others obsessively repeat their last directive or adopt new, peculiar purposes of their own.

## Statblock

```ad-statblock
title: Worker Robot
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/QftIS/Worker%20Robot.webp#token)
*Medium construct, typically  Neutral*

- **Armor Class** 13 (natural armor)
- **Hit Points** 75 (`10d8 + 30`)
- **Speed** 30 ft., climb 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|20 (+5)| 9 (-1)|16 (+3)|10 (+0)|12 (+1)|10 (+0)|

- **Proficiency Bonus** +2
- **Saving Throws** ⏤
- **Skills** Athletics +9
- **Senses** darkvision 60 ft., passive Perception 11
- **Damage Resistances** acid, fire
- **Damage Immunities** cold, poison
- **Condition Immunities** [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** Common plus the languages spoken by its creator
- **Challenge** 3

## Traits

***Lightning Overload.*** When the robot takes lightning damage, it must succeed on a DC 10 Constitution saving throw or have the [stunned](2-Mechanics/CLI/rules/conditions.md#Stunned) condition until the start of its next turn.

## Actions

***Multiattack.*** The robot makes two Cargo Tentacle attacks.

***Cargo Tentacle.*** *Melee Weapon Attack:* `dice:1d20+7|noform|text(+7)` to hit, reach 10 ft., one target. *Hit:* `dice:1d8+5|noform|avg|text(9)` (`1d8 + 5`) bludgeoning damage. If the target is a Medium or smaller creature, it has the [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) condition (escape DC 15). The robot has two cargo tentacles, each of which can grapple one target.

***Tractor Beam.*** The robot casts [Telekinesis](2-Mechanics/CLI/spells/telekinesis.md), targeting only creatures with the [incapacitated](2-Mechanics/CLI/rules/conditions.md#Incapacitated) condition or objects. It requires no spell components and uses Wisdom as the spellcasting ability.
```
^statblock