---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/mcv4ec
- monster/cr/2
- monster/size/medium
- monster/type/fey
aliases: ["Faerie Pathlighter"]
---
# Faerie Pathlighter
*Source: Monstrous Compendium Volume 3: 4: Eldraine Creatures*  

Faerie pathlighters pry into human lives, sometimes to help (like a classic fairy godparent) and sometimes to harm. In the wilds of Eldraine, faerie pathlighters often serve as protectors for the lost, the glow of their guiding lanterns leading weary travelers to respite.

A faerie pathlighter has an almost angelic appearance. Their large, white wings become more translucent toward the edges. Motes of magical light drift around their heads, and a faint white aura surrounds their bodies.

> [!quote]  
> 
> For good or ill, most fae can't resist meddling in the adventures of any knight they meet.

## Faeries

The faeries of Eldraine are winged, elfin creatures similar to sprites or pixies. Unpredictable, unreliable, and amoral, they lurk in the wilds and harass travelers they perceive as intruders.

> [!note] Ouphes
> 
> Ouphes are curious creatures found throughout the wilds of Eldraine. While often seen as foolish, ouphes are magically connected to the natural world and know more about the secret lives of trees, mushrooms, and moss than most mortals. While ouphes are related to Eldraine's faeries, the faeries treat them like distant (and somewhat embarrassing) cousins. Ouphes can be represented with the stat blocks for pixies or sprites.
^ouphes

## Statblock

```ad-statblock
title: Faerie Pathlighter
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/MCV4EC/Faerie%20Pathlighter.webp#token)
*Medium fey, typically  Chaotic Good*

- **Armor Class** 12
- **Hit Points** 38 (`7d8 + 7`)
- **Speed** 30 ft., fly 30 ft. (hover)

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|10 (+0)|14 (+2)|12 (+1)|13 (+1)|17 (+3)|18 (+4)|

- **Proficiency Bonus** +2
- **Saving Throws** ⏤
- **Skills** Insight +5, Perception +5, Survival +5
- **Senses** passive Perception 15
- **Languages** Common, Sylvan
- **Challenge** 2

## Traits

***Faerie Illumination.*** The faerie sheds dim light in a 15-foot radius.

***Spellcasting.*** The faerie casts one of the following spells, requiring no material components and using Charisma as the spellcasting ability:

**At will**: [dancing lights](2-Mechanics/CLI/spells/dancing-lights.md), [detect magic](2-Mechanics/CLI/spells/detect-magic.md), [prestidigitation](2-Mechanics/CLI/spells/prestidigitation.md)

**1/day**: [locate creature](2-Mechanics/CLI/spells/locate-creature.md)

## Actions

***Multiattack.*** The faerie makes two Shining Strike attacks.

***Shining Strike.*** *Melee or Ranged Spell Attack:* `dice:1d20+6|noform|text(+6)` to hit, reach 5 ft. or range 30 ft., one target. *Hit:* `dice:2d6|noform|avg|text(7)` (`2d6`) radiant damage, and if the target is a creature, it must succeed on a DC 14 Dexterity saving throw or be wreathed in light until the end of the faerie's next turn. While a creature is wreathed in light, attack rolls against the creature have advantage, and the creature can't benefit from the [invisible](2-Mechanics/CLI/rules/conditions.md#Invisible) condition.

## Bonus Actions

***Guiding Light (2/Day).*** The faerie summons a 30-foot-radius sphere of magical light centered on itself, which lasts for 1 minute or until the faerie has the [incapacitated](2-Mechanics/CLI/rules/conditions.md#Incapacitated) condition. Each creature of the faerie's choice (other than the faerie) that starts its turn in that area gains 5 temporary hit points and has advantage on Wisdom saving throws and Wisdom checks until the start of its next turn.

The sphere is bright light, sheds dim light for an additional 30 feet, and moves with the faerie. If any of the sphere's area overlaps with an area of darkness created by a spell of 3rd level or lower, the spell that created the darkness is dispelled.
```
^statblock