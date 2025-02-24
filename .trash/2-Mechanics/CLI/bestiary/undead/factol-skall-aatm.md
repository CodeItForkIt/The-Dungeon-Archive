---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/aatm
- monster/cr/17
- monster/size/medium
- monster/type/undead/wizard
aliases: ["Factol Skall"]
---
# Factol Skall
*Source: Adventure Atlas: The Mortuary*  

Skall is the current factol of the Heralds of Dust and the only leader the faction has ever had. A popular Duster legend holds that other than the Lady of Pain herself, Skall is Sigil's oldest resident, the first creature to live and die in the City of Doors. The Heralds of Dust idolize their ageless factol, whose stoic visage has become the faction's emblem. Skall can usually be found examining his orrery of souls (detailed in *Adventure Atlas: The Mortuary*).

After eons of existence, Skall is in an advanced state of deterioration. Once a spry lich with a wrinkled frame, he now drifts listlessly through the Mortuary's forlorn halls, rasping to himself. Skall appears as little more than a floating, disembodied head and two hands, his tattered cloak fluttering behind them. Notorious among the factols of Sigil but rarely seen in the flesh, Skall often delegates his bureaucratic responsibilities to Undead proxies or—on rare occasions—appears as an illusory duplicate. Subtle social cues are lost on the factol, whose eternal nature has eroded any memory of mortal life.

As a result of his decay, Skall's power has waned considerably, but challenging him in combat is as much a death sentence as ever. Factol Skall imparts a lasting oblivion to his enemies. Caretaker, custodian, and grave keeper, the factol ushers allies and foes alike from this false existence toward the path to True Death.

```ad-statblock
title: Factol Skall
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/AATM/Factol%20Skall.webp#token)
*Medium undead (wizard), Neutral Evil*

- **Armor Class** 17 (natural armor)
- **Hit Points** 210 (`28d8 + 84`)
- **Speed** 30 ft., fly 30 ft. (hover)

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|11 (+0)|16 (+3)|16 (+3)|20 (+5)|14 (+2)|16 (+3)|

- **Proficiency Bonus** +6
- **Saving Throws** Constitution +9, Intelligence +11, Wisdom +8
- **Skills** Arcana +17, History +11, Medicine +8, Perception +8
- **Senses** truesight 120 ft., passive Perception 18
- **Damage Resistances** cold; bludgeoning, piercing, slashing from nonmagical attacks
- **Damage Immunities** necrotic, poison
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened), [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned), [stunned](2-Mechanics/CLI/rules/conditions.md#Stunned)
- **Languages** all
- **Challenge** 17

## Traits

***Aura of Death.*** Creatures within 30 feet of Skall have disadvantage on death saving throws.

***Cosmic Annihilation.*** A creature killed by Skall can be restored to life only by means of a true resurrection or [wish](2-Mechanics/CLI/spells/wish.md) spell.

***Legendary Resistance (4/Day).*** If Skall fails a saving throw, he can choose to succeed instead.

***Rejuvenation.*** If Skall dies, he turns to dust. If his orrery of souls hasn't been destroyed, Skall re-forms within the Mortuary in `dice:1d10|noform|avg` (`1d10`) days. He appears within 5 feet of the orrery.

***Turn Resistance.*** Skall has advantage on saving throws against any effect that turns Undead.

***Spellcasting.*** Skall casts one of the following spells, requiring no material components and using Intelligence as the spellcasting ability (spell save DC 19):

**At will**: [detect magic](2-Mechanics/CLI/spells/detect-magic.md), [mage hand](2-Mechanics/CLI/spells/mage-hand.md), [prestidigitation](2-Mechanics/CLI/spells/prestidigitation.md)

**1/day each**: [finger of death](2-Mechanics/CLI/spells/finger-of-death.md), [plane shift](2-Mechanics/CLI/spells/plane-shift.md) (self only), [project image](2-Mechanics/CLI/spells/project-image.md)

**2/day each**: [animate dead](2-Mechanics/CLI/spells/animate-dead.md) (as an action), [dispel magic](2-Mechanics/CLI/spells/dispel-magic.md), [speak with dead](2-Mechanics/CLI/spells/speak-with-dead.md)

## Actions

***Multiattack.*** Skall makes one Withering Touch attack or uses Spellcasting. He also uses Death Knell twice.

***Withering Touch.*** *Melee Spell Attack:* `dice:1d20+11|noform|text(+11)` to hit, reach 5 ft., one target. *Hit:* `dice:6d8+5|noform|avg|text(32)` (`6d8 + 5`) cold damage plus `dice:7d8|noform|avg|text(31)` (`7d8`) necrotic damage, and if the target is a creature, it can't regain hit points until the start of Skall's next turn.

***Death Knell.*** Skall points his finger at a creature he can see within 120 feet of himself, filling the target's mind with visions of death and the plangent toll of an iron bell. The target must succeed on a DC 19 Wisdom saving throw or take `dice:4d6|noform|avg|text(14)` (`4d6`) psychic damage and have the [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened) condition until the start of Skall's next turn.

***Fog of Death (1/Day).*** Skall exudes a killing fog in a 30-foot-radius sphere centered on himself. The sphere spreads around corners, and its area is heavily obscured. The fog lasts until the start of Skall's next turn, and it can't be dispersed by wind. It does not move with him.

Each creature that enters the fog for the first time on a turn or starts its turn there must make a DC 19 Constitution saving throw, taking `dice:8d6|noform|avg|text(28)` (`8d6`) necrotic damage and `dice:8d6|noform|avg|text(28)` (`8d6`) poison damage on a failed save, or half as much damage on a successful one. A Medium or smaller Humanoid killed by this damage becomes a zombie under Skall's control. The zombie acts on Skall's initiative but immediately after his turn. Absent any other command, the zombie tries to kill any non-Undead creature it encounters.

## Reactions

Skall can take up to three reactions per round but only one per turn.

***Baleful Counterspell.*** Skall chatters his teeth to interrupt a creature he can see within 60 feet of himself that is casting a spell. If the spell is 4th level or lower, it fails and has no effect. If the spell is 5th level or higher, Skall makes an Intelligence check (DC 10 + the spell's level). On a successful check, the spell fails and has no effect. Whatever the spell's level, the caster takes `dice:3d6|noform|avg|text(10)` (`3d6`) necrotic damage if the spell fails.

***Near-Death Experience.*** In response to being hit by an attack, Skall teleports, along with any equipment he is wearing or carrying, up to 30 feet to an unoccupied space he can see.
```
^statblock