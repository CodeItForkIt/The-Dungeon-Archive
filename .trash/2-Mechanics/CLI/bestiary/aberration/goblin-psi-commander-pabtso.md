---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/pabtso
- monster/cr/4
- monster/size/small
- monster/type/aberration/goblinoid
aliases: ["Goblin Psi Commander"]
---
# Goblin Psi Commander
*Source: Phandelver and Below: The Shattered Obelisk p. 216*  

Goblin psi commanders are among the few psionic goblins who manage to fully control the power within themselves. Awakened to the total breadth of their psionic abilities, goblin psi commanders wield blades of pure psychic energy. They can throw barriers of mental force while toppling foes with a single, mind-splitting burst.

## Psionic Goblins

The specifics of how a psionic goblin comes to exist vary. Some are born, changed by energy leaking from the Far Realm. Others transform themselves with their psionic power or enter into agreements with other Aberrations, which help them transform in return for their service as shock troops. Regardless, the result is the same: a goblin with unnatural and barely contained psychic power.

Psionic goblins often struggle to handle the turbulent psychic energy within their minds and bodies. Those psionic goblins who learn how to safely tap into this psychic power are formidable forces in combat. Psionic goblins often augment their martial skills with telekinesis, and stealthy squads of psionic goblin warriors can communicate via telepathy, making them excellent infiltrators and ambushers.

## Statblock

```ad-statblock
title: Goblin Psi Commander
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/PaBTSO/Goblin%20Psi%20Commander.webp#token)
*Small aberration (goblinoid), Any alignment*

- **Armor Class** 16 ([studded leather armor](2-Mechanics/CLI/items/studded-leather-armor.md))
- **Hit Points** 58 (`13d6 + 13`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|12 (+1)|19 (+4)|13 (+1)|17 (+3)|15 (+2)|10 (+0)|

- **Proficiency Bonus** +2
- **Saving Throws** Intelligence +5, Wisdom +4
- **Skills** Stealth +8
- **Senses** darkvision 60 ft., passive Perception 12
- **Damage Resistances** psychic
- **Languages** Common, Goblin, telepathy 60 ft.
- **Challenge** 4

## Traits

***Mental Burst.*** When the goblin dies, its pent-up mental energy explodes in a psychic blast. Each creature within 5 feet of it must succeed on a DC 13 Intelligence saving throw or take `dice:4d4|noform|avg|text(10)` (`4d4`) psychic damage.

***Mental Fortitude.*** The goblin has advantage on saving throws against effects that would make it have the [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed) or [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened) conditions.

***Spellcasting (Psionics).*** The goblin casts one of the following spells, requiring no spell components and using Intelligence as the spellcasting ability (spell save DC 13):

**At will**: [mage hand](2-Mechanics/CLI/spells/mage-hand.md) (the hand is invisible), [minor illusion](2-Mechanics/CLI/spells/minor-illusion.md)

**1/day each**: [charm person](2-Mechanics/CLI/spells/charm-person.md), [dissonant whispers](2-Mechanics/CLI/spells/dissonant-whispers.md), [telekinesis](2-Mechanics/CLI/spells/telekinesis.md)

## Actions

***Multiattack.*** The goblin makes three Psychic Blade attacks.

***Psychic Blade.*** *Melee or Ranged Weapon Attack:* `dice:1d20+6|noform|text(+6)` to hit, reach 5 ft. or range 60 ft., one creature. *Hit:* `dice:2d6+4|noform|avg|text(11)` (`2d6 + 4`) psychic damage, and the target must subtract `dice:1d4|noform|avg` (`1d4`) from the next attack roll or saving throw it makes before the end of the goblin's next turn.

***Synaptic Rend (Recharge 5-6).*** The goblin unleashes a 30-foot-radius sphere of psychic energy, centered on a point the goblin can see within 60 feet of itself. Each creature in that area must make a DC 13 Intelligence saving throw. On a failed save, a creature takes `dice:4d6|noform|avg|text(14)` (`4d6`) psychic damage and has the [incapacitated](2-Mechanics/CLI/rules/conditions.md#Incapacitated) condition until the end of the goblin's next turn. On a successful save, a creature takes half as much damage only.

## Bonus Actions

***Nimble Escape.*** The goblin takes the Disengage or Hide action.

## Reactions

***Psionic Shield.*** When the goblin or one of its allies within 15 feet of it is hit by an attack roll, the goblin conjures a shield of force. The target of the attack gains a +3 bonus to its AC against the triggering attack roll, potentially causing it to miss.
```
^statblock