---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/tob1-2023
- monster/cr/2
- monster/environment/hill
- monster/environment/mountain
- monster/environment/planar
- monster/size/medium
- monster/type/humanoid
aliases: ["Folk of Leng"]
---
# Folk of Leng
*Source: Tome of Beasts 1 (2023 Edition) p. 190*  

*This person has goatlike legs, small horns partially hidden beneath a hood, and a mouth full of rows of serrated teeth. Its clothes are a mixture of heavy leathers and bright silks.*

## Dimensional Merchants

The folk of Leng are interplanar merchants and avid slavers, trading silks, rubies, and the magicinfused stones of Leng for humanoid slaves. They sail between worlds in peculiar ships with split, lateen-rigged masts and rigging that howls like the damned in high winds. They are said to befriend Void dragons, heralds of darkness, and other servants of the Void.

## A High Plateau

Leng is a forbidding plateau surrounded by hills and peaks. Its cities are places which some claim have fallen into ruin, and which others claim to have visited in living memory.

## Love of Nets

When in combat, the folk of Leng use nets woven from silk taken from their enemies, the spiders of Leng.

## Statblock

```ad-statblock
title: Folk of Leng
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ToB1-2023/Folk%20of%20Leng.webp#token)
*Medium humanoid, Neutral Evil*

- **Armor Class** 14 ([studded leather](2-Mechanics/CLI/items/studded-leather-armor.md))
- **Hit Points** 68 (`8d8 + 32`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|12 (+1)|15 (+2)|18 (+4)|14 (+2)|16 (+3)|19 (+4)|

- **Proficiency Bonus** +2
- **Saving Throws** Dexterity +4, Wisdom +5
- **Skills** Arcana +4, Deception +8, Perception +5
- **Senses** passive Perception 15
- **Damage Resistances** cold
- **Damage Immunities** necrotic
- **Condition Immunities** [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened)
- **Languages** all
- **Challenge** 2

## Traits

***Ethereal Sight.*** The folk of Leng can see 60 feet into the Ethereal Plane when it is on the Material Plane, and vice versa.

***Leng Rejuvenation.*** If the folk of Leng dies on the Material Plane, it gains a new body in `dice:1d10|noform|avg` (`1d10`) days, regaining all its hp and becoming active again, unless it is killed with radiant damage wielded by a good-aligned creature or its remains are sprinkled with holy water within 24 hours of its death. The folk's new body appears in its family's crypt in Leng.

***Mortal Void Traveler.*** The folk of Leng doesn't require air or ambient pressure.

***Phrenic Weapons.*** The folk of Leng's weapon attacks are magical. When the folk hits with any weapon, the weapon deals an extra `dice:3d6|noform|avg` (`3d6`) psychic damage (included in the attack).

***Regeneration.*** The folk of Leng regains 2 hp at the start of its turn. If the folk of Leng takes fire or radiant damage, this trait doesn't function at the start of the folk's next turn. The folk of Leng dies only if it starts its turn with 0 hp and doesn't regenerate.

***Spellcasting.*** The folk of Leng casts one of the following spells, requiring no material components and using Charisma as the spellcasting ability (spell save DC 14):

**At will**: [message](2-Mechanics/CLI/spells/message.md), [minor illusion](2-Mechanics/CLI/spells/minor-illusion.md)

**3/day each**: [disguise self](2-Mechanics/CLI/spells/disguise-self.md), [suggestion](2-Mechanics/CLI/spells/suggestion.md)

## Actions

***Scimitar.*** *Melee Weapon Attack:* `dice:1d20+4|noform|text(+4)` to hit, reach 5 ft., one target. *Hit:* `dice:1d6+2|noform|avg|text(5)` (`1d6 + 2`) slashing damage plus `dice:3d6|noform|avg|text(10)` (`3d6`) psychic damage.

***Psychic Bolt.*** *Ranged Spell Attack:* `dice:1d20+6|noform|text(+6)` to hit, range 120 ft., one creature. *Hit:* `dice:3d6+4|noform|avg|text(14)` (`3d6 + 4`) psychic damage.

***Hooked Spider Net.*** *Ranged Weapon Attack:* `dice:1d20+4|noform|text(+4)` to hit, range 10/30 ft., one target. *Hit:* `dice:1d4+2|noform|avg|text(4)` (`1d4 + 2`) piercing damage plus `dice:3d6|noform|avg|text(10)` (`3d6`) psychic damage, and the target is [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained). While [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained), the target takes `dice:1d10|noform|avg|text(5)` (`1d10`) poison damage at the start of each of its turns. Any creature, including the [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained) target, can take an action to remove the net by succeeding on a DC 14 Strength check. If the check succeeds by 5 or more, the creature breaks the net instead, and the folk of Leng can't use the broken net again until it finishes a long rest.

## Bonus Actions

***Etherealness.*** The folk of Leng enters the Ethereal Plane from the Material Plane, or vice versa. It is visible on the Material Plane while it is in the Border Ethereal, and vice versa, yet it can't affect or be affected by anything on the other plane.
```
^statblock

## Environment

hill, mountain, planar