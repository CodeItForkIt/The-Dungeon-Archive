---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/ghloe
- monster/cr/12
- monster/size/medium
- monster/type/humanoid/any
- monster/type/humanoid/shapechanger
aliases: ["Werebear Ascetic"]
---
# Werebear Ascetic
*Source: Grim Hollow: Lairs of Etharis p. 37*  

> [!quote]  
> 
> During full moons, inhabitants of Etharis stay inside with the doors barred and windows tightly shut. Even then, they look at those indoors with them with a suspicious eye. One never knows.

## Salvage

Lycanthropes exist in a state of perpetual mental turmoil, and over time their memories fragment. As a result, many carry keepsakes of their past lives to strengthen the memories they do not want to lose. The pelt of a lycanthrope is prized by certain mages for the crafting of magical cloaks, particularly cloaks that allow a person to change their form such as the cloak of the bat or the cloak of the manta ray.

Weapons made from the fangs or claws of deceased lycanthropes have special properties and are known as [lycan weapons](2-Mechanics/CLI/items/lycan-weapon-ghloe.md) (see Appendix A of Lairs of Etharis). These weapons require a successful DC 15 Intelligence ([Arcana](2-Mechanics/CLI/rules/skills.md#Arcana)) check by a proficient weaponsmith, consuming 500 gp worth of components, and requiring 10 days of work.

## Lore

- **DC 10 Intelligence ([Nature](2-Mechanics/CLI/rules/skills.md#Nature)).** Lycanthropy is a common affliction in Etharis. The source is a curse that twists mind and body into that of a savage beast. Though they can change at will, the light of the full moon triggers the transformation no matter what.  
- **DC 15 Intelligence ([Nature](2-Mechanics/CLI/rules/skills.md#Nature)).** In addition to the normal transmission of the curse through the bite of a lycanthrope, certain druidic sects also perform rituals to create new lycanthropes. This ritual is known as the Lunar Sacrament, used as a tool to protect druid groves from invasion.  
- **DC 20 Intelligence ([Nature](2-Mechanics/CLI/rules/skills.md#Nature)).** While the nature of the transformation tends to override the senses with bestial fury, some can control themselves. By finding a balance between man and beast, they gain greater control over the curse, gaining the ability to turn into a full animal and retain their mental faculties.  

## Statblock

```ad-statblock
title: Werebear Ascetic
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/GHLoE/Werebear%20Ascetic.webp#token)
*Medium humanoid (any, shapechanger), Any alignment*

- **Armor Class** 12 (15 from natural armor in hybrid form)
- **Hit Points** 150 (`20d8 + 60`)
- **Speed** 30 ft. (50 ft. and 30 ft. climb in hybrid and kindred form)

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|16 (+3)|14 (+2)|17 (+3)|10 (+0)|16 (+3)|11 (+0)|

- **Proficiency Bonus** +4
- **Saving Throws** Wisdom +7
- **Skills** Animal Handling +7, Nature +4, Perception +7
- **Senses** darkvision 60 ft., passive Perception 17
- **Languages** any three languages
- **Challenge** 12

## Traits

***Shapechanger.*** The werebear ascetic can use its action to polymorph into a bear-humanoid hybrid or into its kindred bear form, or back into its true form, which is humanoid. Its statistics, unless noted, are the same in each form. Any armor it is wearing merges into its alternate forms. It reverts to its true form if it dies.

***Kindred Form.*** The werebear's kindred form takes the shape of a Large bear. While in this form, it can speak to and understand bears, cannot take any actions requiring hands, adds its Constitution modifier to the result of any saving throw, and gains 25 temporary hit points the first time it takes this form each day.

***Spellcasting.*** The werebear is a 13th-level spellcaster. Its spellcasting ability is Wisdom (spell save DC 15, `dice:1d20+6|noform|text(+6)` to hit with spell attacks). It can cast spells in any form, regardless of verbal, somatic, or material components provided they have no gold cost. It has the following druid spells prepared:

**Cantrips (at will)**: [druidcraft](2-Mechanics/CLI/spells/druidcraft.md), [guidance](2-Mechanics/CLI/spells/guidance.md), [mending](2-Mechanics/CLI/spells/mending.md), [resistance](2-Mechanics/CLI/spells/resistance.md)

**1st level (4 slots)**: [animal friendship](2-Mechanics/CLI/spells/animal-friendship.md), [faerie fire](2-Mechanics/CLI/spells/faerie-fire.md), [healing word](2-Mechanics/CLI/spells/healing-word.md)

**2nd level (3 slots)**: [hold person](2-Mechanics/CLI/spells/hold-person.md), [lesser restoration](2-Mechanics/CLI/spells/lesser-restoration.md)

**3rd level (3 slots)**: [conjure animals](2-Mechanics/CLI/spells/conjure-animals.md), [dispel magic](2-Mechanics/CLI/spells/dispel-magic.md), [plant growth](2-Mechanics/CLI/spells/plant-growth.md)

**4th level (3 slots)**: [freedom of movement](2-Mechanics/CLI/spells/freedom-of-movement.md), [ice storm](2-Mechanics/CLI/spells/ice-storm.md)

**5th level (2 slots)**: [commune with nature](2-Mechanics/CLI/spells/commune-with-nature.md), [tree stride](2-Mechanics/CLI/spells/tree-stride.md)

**6th level (1 slots)**: [wall of thorns](2-Mechanics/CLI/spells/wall-of-thorns.md)

**7th level (1 slots)**: [arboreal curse](2-Mechanics/CLI/spells/arboreal-curse-ghloe.md)

## Actions

***Multiattack.*** The werebear makes three melee attacks, only one of which can be a bite.

***Bite (Hybrid or Kindred Form Only).*** *Melee Weapon Attack:* `dice:1d20+7|noform|text(+7)` to hit, reach 5 ft., one creature. *Hit:* `dice:3d8+3|noform|avg|text(16)` (`3d8 + 3`) piercing damage. If the target is a humanoid, it must succeed on a DC 15 Constitution saving throw or be cursed with werebear lycanthropy.

***Claw (Hybrid or Kindred Form Only).*** *Melee Weapon Attack:* `dice:1d20+7|noform|text(+7)` to hit, reach 5 ft., one creature. *Hit:* `dice:2d6+3|noform|avg|text(10)` (`2d6 + 3`) slashing damage.
```
^statblock