---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/ggr
- monster/cr/5
- monster/size/medium
- monster/type/humanoid/elf
aliases: ["Golgari Shaman"]
---
# Golgari Shaman
*Source: Guildmasters' Guide to Ravnica p. 236*  

Golgari shamans are the spiritual leaders of the Golgari Swarm. They teach the guild's beliefs about the cycles of nature, using their necromantic magic to show how life sprouts from death.

Golgari shamans paint their faces so they appear to have extra eyes on their cheeks and chins. They sometimes use magical moodmark paint (described in chapter 5) to allow them to communicate by means of these marks. They wear clothing adorned with beetle carapaces, spiderwebs, or shelf fungus.

## Golgari Lairs

Members of the Golgari Swarm have an intimate connection to their territory. When at least six Golgari defend their territory together, they can call on the environment to aid them. The group must include Jarad Vod Savo or at least one Golgari shaman, kraul death priest, undercity medusa, or Devkarin lich. When determining the difficulty of such an encounter, consider the lair to be one additional creature of challenge rating 1.

## Statblock

```ad-statblock
title: Golgari Shaman
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/GGR/Golgari%20Shaman.webp#token)
*Medium humanoid (elf), Neutral Evil*

- **Armor Class** 14 ([hide armor](2-Mechanics/CLI/items/hide-armor.md))
- **Hit Points** 88 (`16d8 + 16`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|11 (+0)|15 (+2)|12 (+1)|12 (+1)|17 (+3)|16 (+3)|

- **Proficiency Bonus** +3
- **Saving Throws** Constitution +4, Wisdom +6
- **Skills** Arcana +4, Insight +6, Nature +4, Religion +4
- **Senses** darkvision 60 ft., passive Perception 13
- **Languages** Common, Elvish
- **Challenge** 5

## Traits

***Fey Ancestry.*** The shaman has advantage on saving throws against being [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), and magic can't put it to sleep.

***Spellcasting.*** The shaman is an 8th-level Golgari spellcaster. Its spellcasting ability is Wisdom (spell save DC 14, `dice:1d20+6|noform|text(+6)` to hit with spell attacks). The shaman has the following druid spells prepared:

**Cantrips (at will)**: [poison spray](2-Mechanics/CLI/spells/poison-spray.md), [shillelagh](2-Mechanics/CLI/spells/shillelagh.md), [thorn whip](2-Mechanics/CLI/spells/thorn-whip.md)

**1st level (4 slots)**: [cure wounds](2-Mechanics/CLI/spells/cure-wounds.md), [entangle](2-Mechanics/CLI/spells/entangle.md), [ray of sickness](2-Mechanics/CLI/spells/ray-of-sickness.md)

**2nd level (3 slots)**: [pass without trace](2-Mechanics/CLI/spells/pass-without-trace.md), [ray of enfeeblement](2-Mechanics/CLI/spells/ray-of-enfeeblement.md), [spike growth](2-Mechanics/CLI/spells/spike-growth.md)

**3rd level (3 slots)**: [animate dead](2-Mechanics/CLI/spells/animate-dead.md), [dispel magic](2-Mechanics/CLI/spells/dispel-magic.md), [plant growth](2-Mechanics/CLI/spells/plant-growth.md)

**4th level (2 slots)**: [blight](2-Mechanics/CLI/spells/blight.md), [giant insect](2-Mechanics/CLI/spells/giant-insect.md)

## Actions

***Quarterstaff.*** *Melee Weapon Attack:* `dice:1d20+4|noform|text(+4)` to hit, reach 5 ft., one target. *Hit:* `dice:1d6+2|noform|avg|text(5)` (`1d6 + 2`) bludgeoning damage, or `dice:1d8+2|noform|avg|text(6)` (`1d8 + 2`) bludgeoning damage if used with two hands.

***Fungal Rot.*** *Melee Spell Attack:* `dice:1d20+6|noform|text(+6)` to hit, reach 5 ft., one target. *Hit:* `dice:2d8|noform|avg|text(9)` (`2d8`) necrotic damage, and the target must make a DC 14 Constitution saving throw, taking `dice:4d8|noform|avg|text(18)` (`4d8`) poison damage on a failed save, or half as much damage on a successful one.

## Reactions

***Feed on Death.*** When a creature within 30 feet of the shaman drops to 0 hit points, the shaman gains `dice:1d10|noform|avg|text(5)` (`1d10`) temporary hit points.
```
^statblock