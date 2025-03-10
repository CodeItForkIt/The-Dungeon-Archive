---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/mpmm
- monster/cr/20
- monster/environment/underdark
- monster/size/medium
- monster/type/humanoid/cleric
- monster/type/humanoid/elf
aliases: ["Drow Matron Mother"]
---
# Drow Matron Mother
*Source: Mordenkainen Presents: Monsters of the Multiverse p. 104, Mordenkainen's Tome of Foes p. 186*  

Among drow followers of Lolth, each noble house is led by a matron mother, an influential priestess of Lolth charged with carrying out the god's will while also advancing the interests of the family. Matron mothers embody the scheming and treachery associated with the Queen of Spiders. Each stands at the center of a vast conspiratorial web, with demons, spiders, and conscripted soldiers positioned between them and their enemies. Although matron mothers command great power, that power depends on maintaining the Spider Queen's favor, and the goddess sometimes capriciously takes back what she has given. The stat block here represents a matron mother at the height of her power.

A matron mother is almost never encountered alone. She is typically accompanied by a [drow favored consort](2-Mechanics/CLI/bestiary/humanoid/drow-favored-consort-mpmm.md) and a [drow house captain](2-Mechanics/CLI/bestiary/humanoid/drow-house-captain-mpmm.md), each of whom appears in this book. Other Underdark creatures might also be in the priestess's presence, providing protection or advice.

## Mothers of Rebellion

Some matron mothers renounce Lolth and join the war against their former goddess. Such drow could be of any alignment, and they lose the following abilities in the stat block: Lolth's Fickle Favor, Summon Servant, and Compel Demon. Even without these abilities, drow matron mothers are formidable opponents, and several of them hold positions of great influence in the Underdark armies arrayed against the followers of Lolth.

## A Matron Mother's Lair

The palace of a drow matron mother is her home and fortress. Sigils throughout the building allow the matron mother to use the following lair actions while within it.

Any temple of Lolth also functions as a matron mother's lair while she is inside it, unless she has renounced Lolth or another matron mother is present. When two or more matron mothers gather within a temple of their goddess, none of them can use it as their lair.

## Statblock

```ad-statblock
title: Drow Matron Mother
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/MPMM/Drow%20Matron%20Mother.webp#token)
*Medium humanoid (cleric, elf), Typically  Neutral Evil*

- **Armor Class** 17 ([half plate](2-Mechanics/CLI/items/half-plate-armor.md))
- **Hit Points** 247 (`33d8 + 99`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|12 (+1)|18 (+4)|16 (+3)|17 (+3)|21 (+5)|22 (+6)|

- **Proficiency Bonus** +6
- **Saving Throws** Constitution +9, Wisdom +11, Charisma +12
- **Skills** Insight +11, Perception +11, Religion +9, Stealth +10
- **Senses** darkvision 120 ft., passive Perception 21
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** Elvish, Undercommon
- **Challenge** 20

## Traits

***Fey Ancestry.*** The drow has advantage on saving throws against being [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), and magic can't put the drow to sleep.

***Special Equipment.*** The drow wields a [tentacle rod](2-Mechanics/CLI/items/tentacle-rod.md).

***Sunlight Sensitivity.*** While in sunlight, the drow has disadvantage on attack rolls, as well as on Wisdom ([Perception](2-Mechanics/CLI/rules/skills.md#Perception)) checks that rely on sight.

***Spellcasting.*** The drow casts one of the following spells, requiring no material components and using Charisma as the spellcasting ability (spell save DC 20):

**At will**: [command](2-Mechanics/CLI/spells/command.md), [dancing lights](2-Mechanics/CLI/spells/dancing-lights.md), [detect magic](2-Mechanics/CLI/spells/detect-magic.md), [thaumaturgy](2-Mechanics/CLI/spells/thaumaturgy.md)

**1/day each**: [clairvoyance](2-Mechanics/CLI/spells/clairvoyance.md), [darkness](2-Mechanics/CLI/spells/darkness.md), [detect thoughts](2-Mechanics/CLI/spells/detect-thoughts.md), [dispel magic](2-Mechanics/CLI/spells/dispel-magic.md), [faerie fire](2-Mechanics/CLI/spells/faerie-fire.md), [gate](2-Mechanics/CLI/spells/gate.md), [levitate](2-Mechanics/CLI/spells/levitate.md) (self only), [suggestion](2-Mechanics/CLI/spells/suggestion.md)

**2/day each**: [banishment](2-Mechanics/CLI/spells/banishment.md), [blade barrier](2-Mechanics/CLI/spells/blade-barrier.md), [cure wounds](2-Mechanics/CLI/spells/cure-wounds.md), [hold person](2-Mechanics/CLI/spells/hold-person.md), [plane shift](2-Mechanics/CLI/spells/plane-shift.md), [silence](2-Mechanics/CLI/spells/silence.md)

## Actions

***Multiattack.*** The drow makes two Demon Staff attacks or one Demon Staff attack and three Tentacle Rod attacks.

***Demon Staff.*** *Melee Weapon Attack:* `dice:1d20+10|noform|text(+10)` to hit, reach 5 ft., one target. *Hit:* `dice:1d6+4|noform|avg|text(7)` (`1d6 + 4`) bludgeoning damage, or `dice:1d8+4|noform|avg|text(8)` (`1d8 + 4`) bludgeoning damage if used with two hands, plus `dice:4d6|noform|avg|text(14)` (`4d6`) psychic damage. The target must succeed on a DC 19 Wisdom saving throw or become [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened) of the drow for 1 minute. The [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened) target can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.

***Tentacle Rod.*** *Melee Weapon Attack:* `dice:1d20+9|noform|text(+9)` to hit, reach 15 ft., one creature. *Hit:* `dice:1d6|noform|avg|text(3)` (`1d6`) bludgeoning damage. If the target is hit three times by the [rod](2-Mechanics/CLI/items/tentacle-rod.md) on one turn, the target must succeed on a DC 15 Constitution saving throw or suffer the following effects for 1 minute: the target's speed is halved, it has disadvantage on Dexterity saving throws, and it can't use reactions. Moreover, on each of its turns, it can take either an action or a bonus action, but not both. At the end of each of its turns, it can repeat the saving throw, ending the effect on itself on a success.

***Divine Flame (2/Day).*** A 10-foot-radius, 40-foot-high column of divine fire sprouts in an area up to 120 feet away from the drow. Each creature in the column must make a DC 20 Dexterity saving throw, taking `dice:4d6|noform|avg|text(14)` (`4d6`) fire damage and `dice:4d6|noform|avg|text(14)` (`4d6`) radiant damage on a failed save, or half as much damage on a successful one.

## Bonus Actions

***Lolth's Fickle Favor.*** The drow bestows the Spider Queen's blessing on one ally she can see within 30 feet of her. The ally takes `dice:2d6|noform|avg|text(7)` (`2d6`) psychic damage but has advantage on the next attack roll it makes before the end of its next turn.

***Summon Servant (1/Day).*** The drow magically summons a [glabrezu](2-Mechanics/CLI/bestiary/fiend/glabrezu.md) or a [yochlol](2-Mechanics/CLI/bestiary/fiend/yochlol.md). The summoned creature appears in an unoccupied space within 60 feet of its summoner, acts as an ally of its summoner, and can't summon other demons. It remains for 10 minutes, until it or its summoner dies, or until its summoner dismisses it as an action.

## Legendary Actions

***Compel Demon.*** An allied demon within 30 feet of the drow uses its reaction to make one attack against a target of the drow's choice that she can see.

***Demon Staff.*** The drow makes one Demon Staff attack.

***Cast a Spell (Costs 2 Actions).*** The drow uses Spellcasting.

![Drow Matron Mother](2-Mechanics/CLI/bestiary/legendary-group/drow-matron-mother-mpmm.md)
```
^statblock

## Environment

underdark