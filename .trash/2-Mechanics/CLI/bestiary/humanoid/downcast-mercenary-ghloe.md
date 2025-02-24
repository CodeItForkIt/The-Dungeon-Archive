---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/ghloe
- monster/cr/5
- monster/size/medium
- monster/type/humanoid
aliases: ["Downcast Mercenary"]
---
# Downcast Mercenary
*Source: Grim Hollow: Lairs of Etharis p. 49*  

> [!quote]  
> 
> To assume the downcast are good at heart is foolish. Many still cling to delusions of grandeur and do anything to maintain them.

## Salvage

The recently deceased body of a downcast can be used in a ritual to unlock magical power. This ritual takes 16 hours to complete and requires candles, chalk, incense, silver, and other reagents worth 2,000 gp. Upon completion of this ritual, the downcast's body disintegrates, and the ritualist can choose one benefit.

- **Life Force.** The ritualist's maximum hit points increase by 2 per level (or Hit Die) the ritualist has. Each time the ritualist gains a level (or Hit Die), the ritualist's hit point maximum increases by 2. Also, the ritualist's natural lifespan increases by 250 years.  
- **Magic Power.** The ritualist learns the thaumaturgy cantrip and gains additional benefits based on the type of downcast sacrificed, as follows.  

    *Aurelian*: The ritualist's Charisma score increases by 1, to a maximum of 20. Once per day, the ritualist can cast cure wounds as a 1st level spell.  

    *Galiant*: The ritualist's Constitution score increases by 1, to a maximum of 20. Once per day, the ritualist can cast shield of faith as a 1st level spell.  

    *Maliganti*: The ritualist's Strength score increases by 1, to a maximum of 20. Once per day, the ritualist can cast branding smite as a 1st level spell.  

    *Ulmyrite*: The ritualist's Intelligence score increases by 1, to a maximum of 20. Once per day, the ritualist can cast detect magic.  
- **Resurrection.** Upon finishing the ritual, the ritualist can cast resurrection without expending a spell slot or providing any other components.  

## Lore

- **DC 10 Intelligence ([History](2-Mechanics/CLI/rules/skills.md#History)).** The downcast were once immortal celestial servants to the gods. Each has inclinations and aptitudes based on the god they once served.  
- **DC 13 Intelligence ([Religion](2-Mechanics/CLI/rules/skills.md#Religion)).** As a result of their divine nature, fallen though it might be, downcast have resistance to necrotic damage and limited access to innate magic.  
- **DC 15 Intelligence ([Arcana](2-Mechanics/CLI/rules/skills.md#Arcana)).** The physical form of a downcast contains significant power from before their fallen state. A ritual requiring the sacrifice or corpse of a downcast can draw out this power.  

## Statblock

```ad-statblock
title: Downcast Mercenary
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/GHLoE/Downcast%20Mercenary.webp#token)
*Medium humanoid, Any alignment*

- **Armor Class** 17 ([half plate](2-Mechanics/CLI/items/half-plate-armor.md))
- **Hit Points** 82 (`11d8 + 33`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|17 (+3)|15 (+2)|16 (+3)|12 (+1)|13 (+1)|14 (+2)|

- **Proficiency Bonus** +3
- **Saving Throws** Wisdom +4
- **Skills** Athletics +6, Perception +4, Religion +4
- **Senses** passive Perception 14
- **Damage Resistances** necrotic
- **Languages** Celestial and two other languages
- **Challenge** 5

## Traits

***Action Surge (Recharges after a Short or Long Rest).*** The downcast mercenary takes one extra action.

***Indomitable (2/Day).*** If the downcast mercenary fails a saving throw, it can reroll the saving throw and use the new roll.

***Thaumaturge.*** The downcast mercenary can cast [thaumaturgy](2-Mechanics/CLI/spells/thaumaturgy.md) at will.

## Actions

***Multiattack.*** The downcast mercenary makes three attacks.

***Greatsword.*** *Melee Weapon Attack:* `dice:1d20+6|noform|text(+6)` to hit, reach 5 ft., one target. *Hit:* `dice:2d6+3|noform|avg|text(10)` (`2d6 + 3`) slashing damage.
```
^statblock