---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/mpmm
- monster/cr/9
- monster/environment/desert
- monster/environment/urban
- monster/size/medium
- monster/type/humanoid
aliases: ["Necromancer Wizard"]
---
# Necromancer Wizard
*Source: Mordenkainen Presents: Monsters of the Multiverse p. 264, Vecna: Eve of Ruin*  

Necromancers study the interaction of life, death, and undeath. Some necromancers dig up or purchase corpses to create Undead servitors. A few instead use their powers for good, hunting Undead.

## Wizards

Wizards pursue magical power through the study of arcane texts. Some travel the world searching for esoteric tomes while others train lesser wizards or collaborate with colleagues to create new spells.

## Statblock

```ad-statblock
title: Necromancer Wizard
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/MPMM/Necromancer%20Wizard.webp#token)
*Medium humanoid, Any alignment*

- **Armor Class** 12 (15 with [mage armor](2-Mechanics/CLI/spells/mage-armor.md))
- **Hit Points** 110 (`20d8 + 20`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
| 9 (-1)|14 (+2)|12 (+1)|17 (+3)|12 (+1)|11 (+0)|

- **Proficiency Bonus** +4
- **Saving Throws** Intelligence +7, Wisdom +5
- **Skills** Arcana +7, History +7
- **Senses** passive Perception 11
- **Damage Resistances** necrotic
- **Languages** any four languages
- **Challenge** 9

***Spellcasting.*** The necromancer casts one of the following spells, using Intelligence as the spellcasting ability (spell save DC 15):

**At will**: [dancing lights](2-Mechanics/CLI/spells/dancing-lights.md), [mage hand](2-Mechanics/CLI/spells/mage-hand.md), [prestidigitation](2-Mechanics/CLI/spells/prestidigitation.md)

**1/day each**: [circle of death](2-Mechanics/CLI/spells/circle-of-death.md)

**2/day each**: [bestow curse](2-Mechanics/CLI/spells/bestow-curse.md), [dimension door](2-Mechanics/CLI/spells/dimension-door.md), [mage armor](2-Mechanics/CLI/spells/mage-armor.md), [web](2-Mechanics/CLI/spells/web.md)

## Actions

***Multiattack.*** The necromancer makes three Arcane Burst attacks.

***Arcane Burst.*** *Melee or Ranged Spell Attack:* `dice:1d20+7|noform|text(+7)` to hit, reach 5 ft. or range 120 ft., one target. *Hit:* `dice:4d10+3|noform|avg|text(25)` (`4d10 + 3`) necrotic damage.

## Bonus Actions

***Summon Undead (1/Day).*** The necromancer magically summons five [skeletons](2-Mechanics/CLI/bestiary/undead/skeleton.md) or [zombies](2-Mechanics/CLI/bestiary/undead/zombie.md). The summoned creatures appear in unoccupied spaces within 60 feet of the necromancer, whom they obey. They take their turns immediately after the necromancer. Each lasts for 1 hour, until it or the necromancer dies, or until the necromancer dismisses it as a bonus action.

## Reactions

***Grim Harvest (1/Turn).*** When the necromancer kills a creature with necrotic damage, the necromancer regains `dice:2d8|noform|avg|text(9)` (`2d8`) hit points. 
```
^statblock

## Environment

desert, urban