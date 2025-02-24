---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/idrotf
- monster/cr/5
- monster/size/medium
- monster/type/humanoid/human
aliases: ["Frost Druid"]
---
# Frost Druid
*Source: Icewind Dale: Rime of the Frostmaiden p. 288*  

Frost druids are solitary defenders of nature and the natural enemies of civilization in the North. They seek to preserve the arctic wilderness by destroying outsiders who cross their path. Each patrols its territory in the guise of an arctic fox, a mountain goat, a snowy owl, or a wolf, reverting to human form only when it attacks. Clever ambushers, they use [hallucinatory terrain](2-Mechanics/CLI/spells/hallucinatory-terrain.md) spells to create illusory snowdrifts under which they can hide, or to obscure pools covered by thin ice through which others might fall.

## Awakened Companions

A frost druid is often accompanied by one or more beasts, shrubs, or evergreen trees that it has made sentient using the [awaken](2-Mechanics/CLI/spells/awaken.md) spell. These druids favor polar bears and reindeer (use the [elk](2-Mechanics/CLI/bestiary/beast/elk.md) stat block in the "Monster Manual") as companions, and such creatures typically share the druid's disposition.

## Ice Sickle

A frost druid can carve a sickle out of ice, requiring a total of 24 hours for the work. Bitter cold courses through this weapon while it's in the druid's hands. If the druid dies, the ice sickle melts away. The weapon is otherwise identical to a normal sickle.

## Statblock

```ad-statblock
title: Frost Druid
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/IDRotF/Frost%20Druid.webp#token)
*Medium humanoid (human), Any alignment*

- **Armor Class** 13 ([hide armor](2-Mechanics/CLI/items/hide-armor.md))
- **Hit Points** 67 (`9d8 + 27`)
- **Speed** 40 ft. (wolf form only), burrow 5 ft. (fox form only), climb 30 ft. (goat form only), fly 60 ft. (owl form only)

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|12 (+1)|13 (+1)|16 (+3)|10 (+0)|16 (+3)| 9 (-1)|

- **Proficiency Bonus** +3
- **Saving Throws** Intelligence +3, Wisdom +6
- **Skills** Nature +3, Perception +6, Survival +6
- **Senses** darkvision 60 ft. (beast form only), passive Perception 16
- **Damage Resistances** cold
- **Languages** Common, Druidic
- **Challenge** 5

***Spellcasting (Humanoid Form Only).*** The druid is a 9th-level spellcaster. Its spellcasting ability is Wisdom (spell save DC 14; `dice:1d20+6|noform|text(+6)` to hit with spell attacks). It has the following druid spells prepared:

**Cantrips (at will)**: [druidcraft](2-Mechanics/CLI/spells/druidcraft.md), [guidance](2-Mechanics/CLI/spells/guidance.md), [resistance](2-Mechanics/CLI/spells/resistance.md)

**1st level (4 slots)**: [animal friendship](2-Mechanics/CLI/spells/animal-friendship.md), [fog cloud](2-Mechanics/CLI/spells/fog-cloud.md), [speak with animals](2-Mechanics/CLI/spells/speak-with-animals.md)

**2nd level (3 slots)**: [animal messenger](2-Mechanics/CLI/spells/animal-messenger.md), [moonbeam](2-Mechanics/CLI/spells/moonbeam.md), [pass without trace](2-Mechanics/CLI/spells/pass-without-trace.md)

**3rd level (3 slots)**: [conjure animals](2-Mechanics/CLI/spells/conjure-animals.md), [sleet storm](2-Mechanics/CLI/spells/sleet-storm.md), [wind wall](2-Mechanics/CLI/spells/wind-wall.md)

**4th level (3 slots)**: [hallucinatory terrain](2-Mechanics/CLI/spells/hallucinatory-terrain.md), [ice storm](2-Mechanics/CLI/spells/ice-storm.md)

**5th level (1 slots)**: [awaken](2-Mechanics/CLI/spells/awaken.md)

## Actions

***Multiattack.*** The druid makes two melee attacks.

***Ice Sickle (Humanoid Form Only).*** *Melee Weapon Attack:* `dice:1d20+4|noform|text(+4)` to hit, reach 5 ft., one target. *Hit:* `dice:1d4+1|noform|avg|text(3)` (`1d4 + 1`) slashing damage plus `dice:2d4|noform|avg|text(5)` (`2d4`) cold damage.

***Maul (Beast Form Only).*** *Melee Weapon Attack:* `dice:1d20+4|noform|text(+4)` to hit, reach 5 ft., one target. *Hit:* `dice:1d4+1|noform|avg|text(3)` (`1d4 + 1`) piercing damage.

***Change Shape.*** The druid magically polymorphs into a beast form—fox, mountain goat, owl, or wolf—or back into its humanoid form. Any equipment it is wearing or carrying is absorbed or borne by the beast form (the druid's choice). It reverts to its humanoid form when it dies. The druid's statistics are the same in each form, except where noted in this stat block.
```
^statblock