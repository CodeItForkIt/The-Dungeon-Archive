---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/mcv2dc
- monster/cr/4
- monster/size/medium
- monster/type/giant/sorcerer
aliases: ["Irda Veil Keeper"]
---
# Irda Veil Keeper
*Source: Monstrous Compendium Volume 2: Dragonlance Creatures p. 9*  

Masters of their innate illusory powers, irda veil keepers protect their companions by weaving magical mirages that disorient foes. Rumors say that the most skilled irda veil keepers can keep entire enclaves hidden, guarding a community's inhabitants from the outside world for centuries.

## Irda

The Dragon Queen created the irda long ago. While most irda embraced their wicked creator's teachings, some of them adopted the philosophies of other deities. Those irda who don't serve the Dragon Queen live in hidden communities across Krynn, avoiding the eyes of their creator and her minions.

Distantly related to oni, ogres, and other giant folk, irda have shimmering skin that ranges through shades of indigo and sea green. Their innate magic provides them with limited shape-shifting abilities and the power to create illusions.

## Statblock

```ad-statblock
title: Irda Veil Keeper
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/MCV2DC/Irda%20Veil%20Keeper.webp#token)
*Medium giant (sorcerer), Any alignment*

- **Armor Class** 13
- **Hit Points** 49 (`9d8 + 9`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
| 9 (-1)|16 (+3)|13 (+1)|14 (+2)|17 (+3)|19 (+4)|

- **Proficiency Bonus** +2
- **Saving Throws** Intelligence +4, Wisdom +5, Charisma +6
- **Skills** Arcana +4, Insight +7, Perception +7
- **Senses** darkvision 60 ft., truesight 5 ft., passive Perception 17
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened)
- **Languages** Common, Giant, Sylvan
- **Challenge** 4

***Spellcasting.*** The veil keeper casts one of the following spells, requiring no material components and using Charisma as the spellcasting ability (spell save DC 14):

**At will**: [dancing lights](2-Mechanics/CLI/spells/dancing-lights.md), [minor illusion](2-Mechanics/CLI/spells/minor-illusion.md)

**1/day**: [hallucinatory terrain](2-Mechanics/CLI/spells/hallucinatory-terrain.md) (as an action)

**2/day each**: [invisibility](2-Mechanics/CLI/spells/invisibility.md), [major image](2-Mechanics/CLI/spells/major-image.md), [phantasmal force](2-Mechanics/CLI/spells/phantasmal-force.md)

## Actions

***Multiattack.*** The veil keeper uses Augment Physicality, if available, and makes two Mirage Flare attacks.

***Mirage Flare.*** *Melee or Ranged Spell Attack:* `dice:1d20+6|noform|text(+6)` to hit, reach 5 ft. or range 60 ft., one target. *Hit:* `dice:2d6+4|noform|avg|text(11)` (`2d6 + 4`) radiant damage, and the target must succeed on a DC 14 Wisdom saving throw or be [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed) by the veil keeper until the start of the veil keeper's next turn. While [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed) in this way, a creature is [incapacitated](2-Mechanics/CLI/rules/conditions.md#Incapacitated) as it is beset by hypnotic, illusory visions.

***Augment Physicality (1/Day).*** For 1 minute, the veil keeper magically obscures it location, heightens its physical ability, and increases in size, along with anything it is wearing or carrying. While the veil keeper is augmented, attack rolls against it have disadvantage, it is Large, and it makes Strength and Dexterity saving throws with advantage. If the veil keeper lacks the room to become Large, it attains the maximum size possible in the space available. These augmentations end if the veil keeper is [incapacitated](2-Mechanics/CLI/rules/conditions.md#Incapacitated).

***Change Shape (3/Day).*** The veil keeper magically transforms to look and feel like a Medium Humanoid it has seen. Any equipment the veil keeper is wearing or carrying isn't transformed, and the veil keeper's statistics don't change. The veil keeper reverts to its true form if the veil keeper is reduced to 0 hit points or if the veil keeper uses an action to end the transformation.

## Reactions

***Obscuring Mist.*** If a creature that the veil keeper can see within 30 feet of itself is targeted by an attack, the veil keeper surrounds the creature with illusory mist, granting the creature half cover until the start of the veil keeper's next turn.
```
^statblock