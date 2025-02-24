---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/mpmm
- monster/cr/4
- monster/environment/arctic
- monster/environment/forest
- monster/environment/mountain
- monster/environment/swamp
- monster/environment/urban
- monster/size/medium
- monster/type/humanoid
aliases: ["Warlock of the Archfey"]
---
# Warlock of the Archfey
*Source: Mordenkainen Presents: Monsters of the Multiverse p. 255*  

Warlocks of the Archfey gain their powers through magical pacts forged with lords of the Feywild. These warlocks commonly associate with lesser Fey creatures such as [boggles](2-Mechanics/CLI/bestiary/fey/boggle-mpmm.md), [quicklings](2-Mechanics/CLI/bestiary/fey/quickling-mpmm.md), and [redcaps](2-Mechanics/CLI/bestiary/fey/redcap-mpmm.md) (all appear in "this book") or even [satyrs](2-Mechanics/CLI/bestiary/fey/satyr.md) and [sprites](2-Mechanics/CLI/bestiary/fey/sprite.md).

## Warlocks

Warlocks gain arcane might through magical pacts with mysterious entities. While some use their abilities to serve the sources of their power, others use them to undermine or even destroy these entities.

## Statblock

```ad-statblock
title: Warlock of the Archfey
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/MPMM/Warlock%20of%20the%20Archfey.webp#token)
*Medium humanoid, Any alignment*

- **Armor Class** 13 (16 with [mage armor](2-Mechanics/CLI/spells/mage-armor.md))
- **Hit Points** 67 (`15d8`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
| 9 (-1)|16 (+3)|11 (+0)|11 (+0)|12 (+1)|18 (+4)|

- **Proficiency Bonus** +2
- **Saving Throws** Wisdom +3, Charisma +6
- **Skills** Arcana +2, Deception +6, Nature +2, Persuasion +6
- **Senses** passive Perception 11
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed)
- **Languages** any two languages (usually Sylvan)
- **Challenge** 4

***Spellcasting.*** The warlock casts one of the following spells, using Charisma as the spellcasting ability (spell save DC 14): 

**At will**: [dancing lights](2-Mechanics/CLI/spells/dancing-lights.md), [disguise self](2-Mechanics/CLI/spells/disguise-self.md), [mage armor](2-Mechanics/CLI/spells/mage-armor.md) (self only), [mage hand](2-Mechanics/CLI/spells/mage-hand.md), [minor illusion](2-Mechanics/CLI/spells/minor-illusion.md), [prestidigitation](2-Mechanics/CLI/spells/prestidigitation.md), [speak with animals](2-Mechanics/CLI/spells/speak-with-animals.md)

**1/day each**: [charm person](2-Mechanics/CLI/spells/charm-person.md), [dimension door](2-Mechanics/CLI/spells/dimension-door.md), [hold monster](2-Mechanics/CLI/spells/hold-monster.md)

## Actions

***Multiattack.*** The warlock makes two Rapier attacks, or it uses Bewildering Word twice.

***Rapier.*** *Melee Weapon Attack:* `dice:1d20+5|noform|text(+5)` to hit, reach 5 ft., one target. *Hit:* `dice:1d8+3|noform|avg|text(7)` (`1d8 + 3`) piercing damage plus `dice:2d6|noform|avg|text(7)` (`2d6`) force damage.

***Bewildering Word.*** The warlock utters a magical bewilderment, targeting one creature it can see within 60 feet of it. The target must succeed on a DC 14 Wisdom saving throw or take `dice:2d8|noform|avg|text(9)` (`2d8`) psychic damage and have disadvantage on attack rolls until the end of the warlock's next turn.

## Reactions

***Misty Escape (Recharges after a Short or Long Rest).*** In response to taking damage, the warlock turns [invisible](2-Mechanics/CLI/rules/conditions.md#Invisible) and teleports, along with any equipment it is wearing or carrying, up to 60 feet to an unoccupied space it can see. It remains [invisible](2-Mechanics/CLI/rules/conditions.md#Invisible) until the start of its next turn or until it attacks, makes a damage roll, or casts a spell.
```
^statblock

## Environment

arctic, forest, mountain, swamp, urban