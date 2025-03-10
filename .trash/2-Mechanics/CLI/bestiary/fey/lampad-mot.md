---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/mot
- monster/cr/3
- monster/size/medium
- monster/type/fey
aliases: ["Lampad"]
---
# Lampad
*Source: Mythic Odysseys of Theros p. 235*  

Lampads guard the shadowed paths of the world, depths typically trod by souls destined for the Underworld. These rarely seen nymphs assist Athreos in guiding the dead, moving among the spirits that collect along the Tartyx River and reclaiming wayward souls that try to slip back to the mortal world. This means lampads are most often spotted in graveyards, crumbling crypts, and tunnels that bore deep into the earth, and near portals to the Underworld.

## Nymphs

Divine servants that inhabit unspoiled corners of the world, nymphs protect places of natural power and infuse their surroundings with the magic of Nyx. Some are benevolent and aid those who live off the land, while others embody violent aspects of nature. In either case, nymphs generally avoid other sapient creatures, preferring to mind the cycles of nature, the daily interplay of wild animals, or other cosmic forces. Occasionally, though, groups of the same kind of nymphs congregate in a place of natural power or beauty. In times of special need, deities tied to facets of nature might employ nymphs as messengers, guardians, or scouts.

### Immortal Nature

A nymph doesn't require food, drink, or sleep.

## Statblock

```ad-statblock
title: Lampad
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/MOT/Lampad.webp#token)
*Medium fey, Neutral Evil*

- **Armor Class** 15 (natural armor)
- **Hit Points** 52 (`8d8 + 16`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|12 (+1)|13 (+1)|14 (+2)|11 (+0)|12 (+1)|18 (+4)|

- **Proficiency Bonus** +2
- **Saving Throws** ⏤
- **Skills** Deception +6, Intimidation +6
- **Senses** passive Perception 11
- **Damage Resistances** necrotic
- **Damage Immunities** poison
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** Common, Sylvan
- **Challenge** 3

## Traits

***Corpse Stride.*** Once on its turn, the lampad can use 10 feet of its movement to step magically into one creature's corpse within its reach and emerge from a second creature's corpse within 60 feet of the first corpse, appearing in an unoccupied space within 5 feet of the second corpse. Both corpses must be Medium or bigger.

***Magic Resistance.*** The lampad has advantage on saving throws against spells and other magical effects.

***Innate Spellcasting.*** The lampad's spellcasting ability is Charisma (`dice:1d20+6|noform|text(+6)` to hit with spell attacks). It can innately cast the following spells, requiring no material components:

**At will**: [chill touch](2-Mechanics/CLI/spells/chill-touch.md) (see "Actions" below), [gentle repose](2-Mechanics/CLI/spells/gentle-repose.md)

## Actions

***Multiattack.*** The lampad attacks twice with its necrotic touch or chill touch.

***Necrotic Touch.*** *Melee Spell Attack:* `dice:1d20+6|noform|text(+6)` to hit, reach 5 ft., one target. *Hit:* `dice:1d10+4|noform|avg|text(9)` (`1d10 + 4`) necrotic damage.

***Chill Touch (Cantrip).*** *Ranged Spell Attack:* `dice:1d20+6|noform|text(+6)` to hit, range 120 ft., one creature. *Hit:* `dice:2d8|noform|avg|text(9)` (`2d8`) necrotic damage, and the target can't regain hit points until the start of the lampad's next turn. If the target is undead, it has disadvantage on attack rolls against the lampad until the end of the lampad's next turn.
```
^statblock