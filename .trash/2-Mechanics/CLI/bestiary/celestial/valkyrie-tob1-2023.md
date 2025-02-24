---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/tob1-2023
- monster/cr/11
- monster/environment/any
- monster/environment/planar
- monster/size/medium
- monster/type/celestial
aliases: ["Valkyrie"]
---
# Valkyrie
*Source: Tome of Beasts 1 (2023 Edition) p. 379*  

*These warrior women, armed with cruel-looking swords, sit astride massive winged wolves. Each of them is as beautiful, graceful, and fierce as a well-honed war axe.*

## Choosers of the Slain

Valkyries are sent by Odin to decide the course of battles and harvest the souls of brave fallen warriors. Riding winged wolves (use the statistics of a winter wolf with a flying speed of 80 feet and a neutral alignment), they visit battlefields to do their master's will, surrounded by crows and ravens. Valkyries remain hidden among the ravens during these missions, acting only when fate decrees.

## Love Battle

Valkyries love battle and bloodshed, and their presence on the battlefield inspires warriors to great acts of valor and heroism.

## Neutral Parties

Valkyries seldom interfere in mortal affairs, save to ensure the proper course of battles. When duty demands, as a punishment, or when they fall in love, a valkyrie may wander the mortal world.

## Statblock

```ad-statblock
title: Valkyrie
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ToB1-2023/Valkyrie.webp#token)
*Medium celestial, Neutral*

- **Armor Class** 18 ([chain mail](2-Mechanics/CLI/items/chain-mail.md), [shield](2-Mechanics/CLI/items/shield.md))
- **Hit Points** 150 (`20d8 + 60`)
- **Speed** 30 ft., fly 60 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|18 (+4)|18 (+4)|16 (+3)|12 (+1)|19 (+4)|18 (+4)|

- **Proficiency Bonus** +4
- **Saving Throws** Constitution +7, Intelligence +5, Wisdom +8, Charisma +8
- **Skills** Perception +8
- **Senses** truesight 60 ft., passive Perception 18
- **Damage Resistances** acid, cold, fire, lightning, thunder
- **Damage Immunities** poison; bludgeoning, piercing, slashing from nonmagical attacks
- **Condition Immunities** [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** all, telepathy 60 ft.
- **Challenge** 11

## Traits

***Aura of Valor.*** Friendly creatures wielding weapons within 30 feet of the valkyrie have advantage on weapon attack rolls and ability checks. At the start of each of its turns, the valkyrie can choose to exclude any number of friendly creatures from this aura (no action required).

***Immortal Nature.*** The valkyrie doesn't require food, drink, or sleep.

***Magic Resistance.*** The valkyrie has advantage on saving throws against spells and other magical effects.

***Radiant Weapons.*** The valkyrie's weapon attacks are magical. When it hits with any weapon, the weapon deals an extra `dice:3d10|noform|avg|text(16)` (`3d10`) radiant damage (included in the attack).

## Actions

***Multiattack.*** The valkyrie can use its Gaze of Doom. It then makes two Longsword attacks and one Spear attack, or it makes three Radiant Bolt attacks.

***Longsword.*** *Melee Weapon Attack:* `dice:1d20+8|noform|text(+8)` to hit, reach 5 ft., one target. *Hit:* `dice:1d8+4|noform|avg|text(8)` (`1d8 + 4`) slashing damage, or `dice:1d10+4|noform|avg|text(9)` (`1d10 + 4`) slashing damage if used with two hands, plus `dice:3d10|noform|avg|text(16)` (`3d10`) radiant damage.

***Spear.*** *Melee or Ranged Weapon Attack:* `dice:1d20+8|noform|text(+8)` to hit, reach 5 ft. or range 20/60 ft., one target. *Hit:* `dice:1d6+4|noform|avg|text(7)` (`1d6 + 4`) piercing damage, or `dice:1d8+4|noform|avg|text(8)` (`1d8 + 4`) piercing damage if used with two hands to make a melee attack, plus `dice:3d10|noform|avg|text(16)` (`3d10`) radiant damage.

***Radiant Bolt.*** *Ranged Spell Attack:* `dice:1d20+8|noform|text(+8)` to hit, range 120 ft., one target. *Hit:* `dice:4d10+4|noform|avg|text(26)` (`4d10 + 4`) radiant damage.

***Gaze of Doom.*** The valkyrie's gaze foretells a doomed fate for one creature the valkyrie can see within 60 feet of it. The target must succeed on a DC 16 Wisdom saving throw or be [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened) for 1 minute. The target can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.

***Healing Touch (4/Day).*** The valkyrie touches another creature. The target magically regains 21 `dice:6d6|noform|avg` (`6d6`) hp and is freed from any curse, disease, poison, blindness, or deafness.

## Reactions

***Ascension.*** When a friendly creature the valkyrie can see and within its Aura of Valor is reduced to 0 hp while engaged in melee combat, the valkyrie can reincarnate the creature as a gladiator. If the gladiator reduces at least three creatures to 0 hp within 1 minute of its reincarnation, it transforms into an einherjar. The valkyrie can provide ascension to up to two creatures each hour with this reaction.
```
^statblock

## Environment

any, planar