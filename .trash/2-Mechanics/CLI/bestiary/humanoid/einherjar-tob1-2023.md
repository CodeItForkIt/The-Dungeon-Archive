---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/tob1-2023
- monster/cr/7
- monster/environment/planar
- monster/size/medium
- monster/type/humanoid
aliases: ["Einherjar"]
---
# Einherjar
*Source: Tome of Beasts 1 (2023 Edition) p. 156*  

*A line of stout, bearded warriors with golden auras stand ready, adorned in chain mail and carrying battle axes and oaken shields. Their badges and symbols are all different, and no two have the same braided pattern in their beards.*

The einherjar are great warriors chosen by the valkyries. They eat and drink their fill of boar and mead each night, then spend their days preparing for Ragnarok. Some of this is combat training, and other portions are raids against the giants fighting the gods. Regardless of how often they are slain, the einherjar reappear each morning in Odin's hall, leaving them without fear of death.

## Defenders of the Mortal World

Occasionally, ravenfolk guide a troop of einherjar against some of Loki's minions on the Material Plane. These raids are often small battles that further delay the inevitable rise of the world serpent and its many evil spawn. They fight against giants, demons, [Tooltip Not Found], and other evil creatures, but the einherjar themselves are not exactly saintly. They can drink and carouse with the loudest and most boastful of humanoids. Though otherworldly and servants of Odin, einherjar are very humanlike, if somewhat larger than life.

## Fear Dragons

The einherjar are superstitiously fearful of dragons and dragonkin, the distant progeny of the world serpent.

## Never Speak to the Living

In theory, the einherjar are forbidden from speaking with the living: they must pass their words through a valkyrie, ratatosk, ravenfolk, or one of the other races allied with Odin. In practice, this rule is often flouted, though if Loki's servants notice it, they can dismiss any einherjar back to Valhalla for a day.

## Statblock

```ad-statblock
title: Einherjar
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ToB1-2023/Einherjar.webp#token)
*Medium humanoid, Chaotic Neutral*

- **Armor Class** 18 ([chain mail](2-Mechanics/CLI/items/chain-mail.md), [shield](2-Mechanics/CLI/items/shield.md))
- **Hit Points** 119 (`14d8 + 56`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|19 (+4)|16 (+3)|19 (+4)|10 (+0)|14 (+2)|11 (+0)|

- **Proficiency Bonus** +3
- **Saving Throws** ⏤
- **Skills** Animal Handling +5, Intimidation +6, Perception +5
- **Senses** truesight 60 ft., passive Perception 15
- **Damage Resistances** piercing from nonmagical attacks
- **Languages** Celestial, Common
- **Challenge** 7

## Traits

***Battle Frenzy.*** The einherjar has advantage on all attack rolls it makes while it is below 30 hp.

***Fearsome Gaze.*** The stare of an einherjar is especially piercing to Humanoids. It has advantage on any Charisma ([Intimidation](2-Mechanics/CLI/rules/skills.md#Intimidation)) check it makes against a Humanoid.

***Runic Weapons.*** The einherjar's weapon attacks are magical. When the einherjar hits with any weapon, the weapon deals an extra `dice:3d8|noform|avg` (`3d8`) radiant damage (included in the attack).

## Actions

***Multiattack.*** The einherjar makes two Battleaxe attacks, or it makes three Celestial Bolt attacks. It can replace one attack with Celestial Blessing, if available.

***Battleaxe.*** *Melee Weapon Attack:* `dice:1d20+7|noform|text(+7)` to hit, reach 5 ft., one target. *Hit:* `dice:1d8+4|noform|avg|text(8)` (`1d8 + 4`) slashing damage, or `dice:1d10+4|noform|avg|text(9)` (`1d10 + 4`) slashing damage if used with two hands, plus `dice:3d8|noform|avg|text(13)` (`3d8`) radiant damage.

***Celestial Bolt.*** *Ranged Spell Attack:* `dice:1d20+5|noform|text(+5)` to hit, range 60 ft., one target. *Hit:* `dice:3d8+2|noform|avg|text(15)` (`3d8 + 2`) radiant damage.

***Celestial Blessing (Recharge 5-6).*** The einherjar calls on its celestial patrons for one of the following blessings:

- **Odin's Strength.** The einherjar roars a battle prayer to Odin. Each friendly creature within 60 feet of the einherjar and that can hear the prayer deals an extra `dice:1d8|noform|avg|text(4)` (`1d8`) radiant damage when it hits with any weapon. In addition, when an affected creature makes an attack roll, the creature can roll a `dice:d6|noform|avg` (`d6`) and add the number rolled to the attack roll.  
- **Valkyries' Mercy.** The einherjar pleads for the assistance of the valkyries to save one friendly creature it can see within 60 feet of it that has been reduced to 0 hp. The creature regains 13 `dice:3d8|noform|avg` (`3d8`) hp. Once the einherjar has aided a creature with Valkyries' Mercy, it can't target that creature with Valkyries' Mercy again until the creature finishes a long rest.  
```
^statblock

## Environment

planar