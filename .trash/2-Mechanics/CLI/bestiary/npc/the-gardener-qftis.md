---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/qftis
- monster/cr/12
- monster/size/medium
- monster/type/fey/archfey
- monster/type/fey/druid
aliases: ["The Gardener"]
---
# The Gardener
*Source: Quests from the Infinite Staircase p. 200*  

The Gardener is an archfey who adores the splendor of nature, the joy of song, and the glow of shared merriment. This ancient being once wandered the Feywild and worlds of the Material Plane until two dear friends created a wondrous garden and asked the Gardener to tend to it. The Gardener agreed to the request, then pulled the garden from the Material Plane and transformed it into a Domain of Delight—a region of the Feywild that bows to an archfey's will. This place became known as the Eternal Garden.

The Gardener abhors bloodshed and avoids killing even those who threaten the garden, preferring to entangle them in vines and pacify them with tranquilizing breaths of flowery mist.

## The Gardener's Lair

The Gardener's lair is the entirety of the Eternal Garden.

## Statblock

```ad-statblock
title: The Gardener
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/QftIS/The%20Gardener.webp#token)
*Medium fey (archfey, druid), Neutral Good*

- **Armor Class** 17 (natural armor)
- **Hit Points** 209 (`22d8 + 110`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|21 (+5)|16 (+3)|20 (+5)|17 (+3)|20 (+5)|18 (+4)|

- **Proficiency Bonus** +4
- **Saving Throws** Dexterity +7, Constitution +9, Wisdom +9, Charisma +8
- **Skills** Insight +9, Nature +11, Perception +9, Survival +13
- **Senses** truesight 120 ft., passive Perception 19
- **Damage Resistances** cold, fire
- **Damage Immunities** poison
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** Common, Druidic, Elvish, Sylvan
- **Challenge** 12

## Traits

***Fey Rebirth.*** If the Gardener dies in the Eternal Garden, they revive with all their hit points `dice:1d4|noform|avg` (`1d4`) days later in a safe location within the garden.

***Legendary Resistance (3/Day).*** If the Gardener fails a saving throw, they can choose to succeed instead.

***Unfettered Steps.*** The Gardener is unaffected by difficult terrain.

***Spellcasting.*** The Gardener casts one of the following spells, requiring no material components and using Wisdom as the spellcasting ability (spell save DC 17):

**At will**: [Druidcraft](2-Mechanics/CLI/spells/druidcraft.md), [Speak with Animals](2-Mechanics/CLI/spells/speak-with-animals.md), [Speak with Plants](2-Mechanics/CLI/spells/speak-with-plants.md)

**1/day each**: [Heroes' Feast](2-Mechanics/CLI/spells/heroes-feast.md) (as an action), [Teleport](2-Mechanics/CLI/spells/teleport.md)

**2/day each**: [Awaken](2-Mechanics/CLI/spells/awaken.md) (as an action), [Goodberry](2-Mechanics/CLI/spells/goodberry.md), [Plant Growth](2-Mechanics/CLI/spells/plant-growth.md) (as an action only)

## Actions

***Multiattack.*** The Gardener makes two Vine attacks and can use Breath of Tranquility if available.

***Vine.*** *Melee Weapon Attack:* `dice:1d20+9|noform|text(+9)` to hit, reach 10 ft., one target. *Hit:* `dice:1d12+5|noform|avg|text(11)` (`1d12 + 5`) bludgeoning damage plus `dice:2d8|noform|avg|text(9)` (`2d8`) psychic damage, and if the target is a Large or smaller creature, the vine wraps around the target, and the target has the [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) condition (escape DC 17). The vine vanishes when the target is no longer [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled), or when the Gardener wills it to (no action required). A creature reduced to 0 hit points by the vine has the [unconscious](2-Mechanics/CLI/rules/conditions.md#Unconscious) condition but is stable instead of dying.

***Breath of Tranquility (Recharge 5-6).*** The Gardener exhales soporific vapor in a 30-foot cone. Each creature in that area must succeed on a DC 17 Constitution saving throw or have the [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned) condition. A [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned) creature must repeat the saving throw at the end of its next turn. On a failed save, it has the [unconscious](2-Mechanics/CLI/rules/conditions.md#Unconscious) condition, and on a successful save, the effect ends on it. An [unconscious](2-Mechanics/CLI/rules/conditions.md#Unconscious) creature is no longer [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned) and remains [unconscious](2-Mechanics/CLI/rules/conditions.md#Unconscious) for 1 hour, until it takes damage, or until a creature uses an action to shake it awake.

## Reactions

The Gardener can take up to three reactions per round but only one per turn.

***Pacification.*** When a creature within 120 feet of the Gardener damages the Gardener, that creature takes `dice:3d6|noform|avg|text(10)` (`3d6`) psychic damage, and the Gardener teleports, along with anything they are wearing or carrying, to an unoccupied space they can see within 15 feet. A creature reduced to 0 hit points by the psychic damage has the [unconscious](2-Mechanics/CLI/rules/conditions.md#Unconscious) condition and is stable instead of dying.

***Spell Refuge.*** When the Gardener or a creature within 30 feet of the Gardener takes damage from a spell, the Gardener chooses up to 5 creatures within 30 feet of themself. The Gardener and the chosen creatures have resistance to all damage from the triggering spell.

![The Gardener](2-Mechanics/CLI/bestiary/legendary-group/the-gardener-qftis.md)
```
^statblock