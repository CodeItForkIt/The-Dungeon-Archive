---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/ggr
- monster/cr/4
- monster/size/medium
- monster/type/humanoid/kraul
aliases: ["Kraul Death Priest"]
---
# Kraul Death Priest
*Source: Guildmasters' Guide to Ravnica p. 214*  

The death priests occupy the highest roles in kraul society. They lead the buzzing chants of the kraul rites. Their inscrutable clicks and buzzing can summon crippling necromantic magic, and the presence of death seems to fortify them. They draw power from the defeat of their enemies and channel it to their followers, ensuring the continuation of the cycle.

The current leader of the kraul is a death priest named Mazirek.

## Kraul

The kraul are an ascendant power group within the Golgari Swarm, long content to linger at the margins of the undercity but now increasingly making their buzzing voices heard in the subterranean Golgari guildhall. These six-legged, insectile beings are hard-headed and literal-minded, with little grasp of metaphor or nuance.

## Statblock

```ad-statblock
title: Kraul Death Priest
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/GGR/Kraul%20Death%20Priest.webp#token)
*Medium humanoid (kraul), Neutral Evil*

- **Armor Class** 18 (natural armor)
- **Hit Points** 65 (`10d8 + 20`)
- **Speed** 30 ft., climb 30 ft., fly 40 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|16 (+3)|12 (+1)|14 (+2)|12 (+1)|15 (+2)|10 (+0)|

- **Proficiency Bonus** +2
- **Saving Throws** Constitution +4, Wisdom +4
- **Skills** Insight +4, Nature +3, Religion +3
- **Senses** darkvision 60 ft., passive Perception 12
- **Languages** Common, Kraul
- **Challenge** 4

## Traits

***Feed on Death.*** When a creature within 30 feet of the kraul drops to 0 hit points, the kraul or another creature of its choice within 30 feet of it gains `dice:1d10|noform|avg|text(5)` (`1d10`) temporary hit points, provided the kraul isn't [incapacitated](2-Mechanics/CLI/rules/conditions.md#Incapacitated).

***Hive Mind.*** The kraul is immune to the [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed) and [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened) conditions while within 30 feet of at least one other kraul.

***Pack Tactics.*** The kraul has advantage on an attack roll against a creature if at least one of the kraul's allies is within 5 feet of the creature and the ally isn't [incapacitated](2-Mechanics/CLI/rules/conditions.md#Incapacitated).

***Spider Climb.*** The kraul can climb difficult surfaces, including upside down on ceilings, without needing to make an ability check.

***Innate Spellcasting.*** The kraul's innate spellcasting ability is Wisdom (spell save DC 12, `dice:1d20+4|noform|text(+4)` to hit with spell attacks). The kraul can innately cast the following spells, requiring no material components:

**At will**: [chill touch](2-Mechanics/CLI/spells/chill-touch.md), [poison spray](2-Mechanics/CLI/spells/poison-spray.md)

**1/day each**: [animate dead](2-Mechanics/CLI/spells/animate-dead.md), [blight](2-Mechanics/CLI/spells/blight.md), [vampiric touch](2-Mechanics/CLI/spells/vampiric-touch.md)

**3/day each**: [ray of enfeeblement](2-Mechanics/CLI/spells/ray-of-enfeeblement.md), [ray of sickness](2-Mechanics/CLI/spells/ray-of-sickness.md)

## Actions

***Multiattack.*** The kraul makes one attack with its quarterstaff and casts one of its spells with a casting time of 1 action.

***Quarterstaff.*** *Melee Weapon Attack:* `dice:1d20+5|noform|text(+5)` to hit, reach 5 ft., one target. *Hit:* `dice:1d6+3|noform|avg|text(6)` (`1d6 + 3`) bludgeoning damage, or `dice:1d8+3|noform|avg|text(7)` (`1d8 + 3`) bludgeoning damage if used with two hands.
```
^statblock