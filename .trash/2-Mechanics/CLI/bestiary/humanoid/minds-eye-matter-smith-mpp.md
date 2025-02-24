---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/mpp
- monster/cr/4
- monster/size/small-or-medium
- monster/type/humanoid
aliases: ["Mind's Eye Matter Smith"]
---
# Mind's Eye Matter Smith
*Source: Morte's Planar Parade p. 60, Sigil and the Outlands, Turn of Fortune's Wheel*  

Members of the Mind's Eye believe the power to transcend the multiverse lies in every individual. Matter smiths harness this innate power to reshape reality in Sigil's Great Foundry, manifesting useful tools from nothing.

```ad-statblock
title: Mind's Eye Matter Smith
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/MPP/Mind%27s%20Eye%20Matter%20Smith.webp#token)
*Small or Medium humanoid, Any alignment*

- **Armor Class** 12 (15 with [mage armor](2-Mechanics/CLI/spells/mage-armor.md))
- **Hit Points** 78 (`12d8 + 24`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|10 (+0)|14 (+2)|14 (+2)|14 (+2)|14 (+2)|16 (+3)|

- **Proficiency Bonus** +2
- **Saving Throws** Intelligence +4, Charisma +5
- **Skills** Investigation +4, Perception +6
- **Senses** passive Perception 16
- **Languages** Common plus two more languages
- **Challenge** 4

***Spellcasting.*** The matter smith casts one of the following spells, using Charisma as the spellcasting ability:

**At will**: [mage armor](2-Mechanics/CLI/spells/mage-armor.md), [mage hand](2-Mechanics/CLI/spells/mage-hand.md), [prestidigitation](2-Mechanics/CLI/spells/prestidigitation.md)

**1/day each**: [create food and water](2-Mechanics/CLI/spells/create-food-and-water.md), [fabricate](2-Mechanics/CLI/spells/fabricate.md) (as an action)

## Actions

***Multiattack.*** The matter smith makes two Manifested Force attacks.

***Manifested Force.*** *Melee or Ranged Spell Attack:* `dice:1d20+5|noform|text(+5)` to hit, reach 5 ft. or range 120 ft., one target. *Hit:* `dice:2d6+3|noform|avg|text(10)` (`2d6 + 3`) force damage.

## Bonus Actions

***Planar Smithing.*** The matter smith magically manipulates the energy of the plane of existence it's on to produce one of the following effects (choose one or roll a `dice:d4|noform|avg` (`d4`)):

- **1-2 Chains.** The matter smith creates spectral bindings around a creature it can see within 30 feet of itself. The target must succeed on a DC 13 Dexterity saving throw or have the [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained) condition until the end of its next turn.  
- **3-4 Magic Shield.** The matter smith conjures a floating, spectral shield that grants the matter smith a +5 bonus to its AC until the shield disappears at the start of the matter smith's next turn. The first time a creature misses a melee attack roll against the matter smith while the shield is conjured, that creature takes `dice:2d6|noform|avg|text(7)` (`2d6`) force damage.  
```
^statblock