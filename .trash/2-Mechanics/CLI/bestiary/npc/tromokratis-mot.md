---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/mot
- monster/cr/26
- monster/size/gargantuan
- monster/type/monstrosity/titan
aliases: ["Tromokratis"]
---
# Tromokratis
*Source: Mythic Odysseys of Theros p. 254*  

Most krakens roam the seas, shattering hulls and scattering fleets, but the kraken Tromokratis notoriously vents its wrath on coastal settlements. Whether it acts at the command of the god Thassa or to sate its own hunger, Tromokratis numbers among the most feared threats in the sea, having no fixed lair and wandering where it will. In recent memory, the massive menace rose from the waves to topple the Pyrgnos, Meletis's great repository of scholarly knowledge. Since that day, the polis keeps a watch specifically for Tromokratis.

```ad-statblock
title: Tromokratis
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/MOT/Tromokratis.webp#token)
*Gargantuan monstrosity (titan), Any alignment*

- **Armor Class** 22 (natural armor)
- **Hit Points** 409 (`21d20 + 189`)
- **Speed** 30 ft., swim 80 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|30 (+10)|11 (+0)|29 (+9)|22 (+6)|11 (+0)|10 (+0)|

- **Proficiency Bonus** +8
- **Saving Throws** Intelligence +14, Wisdom +8
- **Skills** ⏤
- **Senses** blindsight 120 ft., passive Perception 10
- **Damage Resistances** cold, lightning, thunder
- **Damage Immunities** fire; bludgeoning, piercing, slashing from nonmagical attacks
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened), [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed), [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained)
- **Languages** —
- **Challenge** 26

## Traits

***Amphibious.*** Tromokratis can breathe air and water.

***Hearts of the Kraken (Mythic Trait; Recharges after a Short or Long Rest).*** When Tromokratis is reduced to 0 hit points, it doesn't die or fall [unconscious](2-Mechanics/CLI/rules/conditions.md#Unconscious). Instead, the damage creates cracks in its carapace, revealing its hearts. Tromokratis has four hearts: two on its chest, one on its back, and one at the base of its tail. A heart has an AC of 22 and 100 hit points. It is immune to bludgeoning, piercing, and slashing damage from nonmagical attacks, and it is immune to all conditions. If it is forced to make a saving throw, treat its ability scores as 10 (+0). If it finishes a short or long rest, the carapace heals, any destroyed hearts regenerate, and the hearts are covered again. Tromokratis dies when all the hearts are destroyed.

***Legendary Resistance (3/Day).*** If Tromokratis fails a saving throw, it can choose to succeed instead.

***Magic Weapons.*** Tromokratis's weapon attacks are magical.

***Siege Monster.*** Tromokratis deals double damage to objects and structures.

***Spell-Resistant Carapace.*** Tromokratis has advantage on saving throws against spells, and any creature that makes a spell attack against Tromokratis has disadvantage on the attack roll.

## Actions

***Multiattack.*** Tromokratis makes three attacks: one with its pincer, one with its tail, and one with its tentacle grasp.

***Pincer.*** *Melee Weapon Attack:* `dice:1d20+18|noform|text(+18)` to hit, reach 20 ft., one target. *Hit:* `dice:3d6+10|noform|avg|text(20)` (`3d6 + 10`) bludgeoning damage, and if the target is a creature, it is [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) (escape DC 26). Until the grapple ends, the target is [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained), and Tromokratis can't use this attack on anyone else.

***Tail.*** *Melee Weapon Attack:* `dice:1d20+18|noform|text(+18)` to hit, reach 20 ft., one target. *Hit:* `dice:3d8+10|noform|avg|text(23)` (`3d8 + 10`) bludgeoning damage, and if the target is a creature, it is knocked [prone](2-Mechanics/CLI/rules/conditions.md#Prone).

***Tentacle Grasp.*** *Melee Weapon Attack:* `dice:1d20+18|noform|text(+18)` to hit, reach 20 ft., one creature. *Hit:* `dice:3d6+10|noform|avg|text(20)` (`3d6 + 10`) bludgeoning damage, and the target is [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) (escape DC 26). If the target doesn't escape by the end of its next turn, Tromokratis throws the target up to 60 feet in a straight line. The target lands [prone](2-Mechanics/CLI/rules/conditions.md#Prone) and takes `dice:6d6|noform|avg|text(21)` (`6d6`) bludgeoning damage.

***Bite.*** *Melee Weapon Attack:* `dice:1d20+18|noform|text(+18)` to hit, reach 5 ft., one target. *Hit:* `dice:3d12+10|noform|avg|text(29)` (`3d12 + 10`) piercing damage. If the target is a Large or smaller creature [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) by Tromokratis, that creature is swallowed, and the grapple ends. While swallowed, the creature is [blinded](2-Mechanics/CLI/rules/conditions.md#Blinded) and [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained), it has total cover against attacks and other effects outside Tromokratis, and it takes `dice:12d6|noform|avg|text(42)` (`12d6`) acid damage at the start of each of Tromokratis's turns. If Tromokratis takes 50 damage or more on a single turn from a creature inside it, Tromokratis must succeed on a DC 20 Constitution saving throw at the end of that turn or regurgitate all swallowed creatures, which fall [prone](2-Mechanics/CLI/rules/conditions.md#Prone) in a space within 10 feet of Tromokratis. If Tromokratis dies, a swallowed creature is no longer [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained) by it and can escape from the corpse by using 15 feet of movement, exiting [prone](2-Mechanics/CLI/rules/conditions.md#Prone).

## Legendary Actions

***Move.*** Tromokratis moves up to half its speed.

***Tail.*** Tromokratis makes one tail attack.

***Bite (Costs 3 Actions).*** Tromokratis makes one bite attack.

![Tromokratis](2-Mechanics/CLI/bestiary/legendary-group/tromokratis-mot.md)
```
^statblock