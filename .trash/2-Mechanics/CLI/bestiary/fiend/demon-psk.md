---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/psk
- monster/cr/12
- monster/size/medium
- monster/type/fiend/devil
aliases: ["Demon"]
---
# Demon
*Source: Plane Shift: Kaladesh p. 27*  

Demons are artificial creatures, carefully constructed and imbued with aether according to a pattern called the Dark Schematic. Unknown artificers of the ancient past devised this blueprint—perhaps in an attempt to imitate the angels, or possibly to replicate native demons that have since been hunted to extinction. Just as angels embody white mana and the construction phase of the Aether Cycle, demons are ravenous incarnations of black mana that feast on aether. They raid night markets, pillage airships, and break into refinement plants seeking aether to slake their thirst, causing as much destruction as possible in the process. They can thus be imagined as an embodiment of the reclamation stage of the Aether Cycle.

Artificers execute the Dark Schematic only in great desperation, often in the course of seeking power for themselves or revenge against their enemies. The destructive might of demons is hard to control, though, and these creatures have no particular regard for or gratitude toward their creators. As often as not, even an inventor who performs the steps necessary to create a demon with the utmost care suffers the same dismal fate as all its other victims.

Demons resemble angels on a superficial level, wearing ornate masks and headdresses, and often armored. The aether a demon consumes marks its skin with whorls of fiery red, deep purple, or searing yellow.

The statistics of an [erinyes](2-Mechanics/CLI/bestiary/fiend/erinyes.md) work well for demons on Kaladesh, but their weapons deal extra necrotic damage rather than extra poison damage.

```ad-statblock
title: Demon
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/PSK/Demon.webp#token)
*Medium fiend (devil), Lawful Evil*

- **Armor Class** 18 ([plate armor](2-Mechanics/CLI/items/plate-armor.md))
- **Hit Points** 153 (`18d8 + 72`)
- **Speed** 30 ft., fly 60 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|18 (+4)|16 (+3)|18 (+4)|14 (+2)|14 (+2)|18 (+4)|

- **Proficiency Bonus** +4
- **Saving Throws** Dexterity +7, Constitution +8, Wisdom +6, Charisma +8
- **Skills** ⏤
- **Senses** truesight 120 ft., passive Perception 12
- **Damage Resistances** cold; bludgeoning, piercing, slashing from nonmagical attacks that aren't silvered
- **Damage Immunities** fire, poison
- **Condition Immunities** [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** Infernal, telepathy 120 ft.
- **Challenge** 12

## Traits

***Hellish Weapons.*** The demon's weapon attacks are magical and deal an extra `dice:3d8|noform|avg|text(13)` (`3d8`) necrotic damage on a hit (included in the attacks).

***Magic Resistance.*** The demon has advantage on saving throws against spells and other magical effects.

## Actions

***Multiattack.*** The demon makes three attacks.

***Longsword.*** *Melee Weapon Attack:* `dice:1d20+8|noform|text(+8)` to hit, reach 5 ft., one target. *Hit:* `dice:1d8+4|noform|avg|text(8)` (`1d8 + 4`) slashing damage, or `dice:1d10+4|noform|avg|text(9)` (`1d10 + 4`) slashing damage if used with two hands, plus `dice:3d8|noform|avg|text(13)` (`3d8`) necrotic damage.

***Longbow.*** *Ranged Weapon Attack:* `dice:1d20+7|noform|text(+7)` to hit, range 150/600 ft., one target. *Hit:* `dice:1d8+3|noform|avg|text(7)` (`1d8 + 3`) piercing damage plus `dice:3d8|noform|avg|text(13)` (`3d8`) necrotic damage.

## Reactions

***Parry.*** The demon adds 4 to its AC against one melee attack that would hit it. To do so, the demon must see the attacker and be wielding a melee weapon.
```
^statblock