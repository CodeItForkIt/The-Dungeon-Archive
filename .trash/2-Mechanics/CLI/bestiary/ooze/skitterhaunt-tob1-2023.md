---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/tob1-2023
- monster/cr/4
- monster/environment/forest
- monster/environment/underdark
- monster/size/large
- monster/type/ooze
aliases: ["Skitterhaunt"]
---
# Skitterhaunt
*Source: Tome of Beasts 1 (2023 Edition) p. 332*  

*This large beetle moves erratically, leaking noxious fluid from its cracked exoskeleton.*

## Ooze Vermin

This parasitic ooze lives in the shells of monstrous vermin, such as beetles, scorpions, and spiders, which it has infested and killed. A skitterhaunt creature might be mistaken for its original, living version at a glance, but the sluggish, erratic movements and oozing carapace of skitterhaunts quickly reveal their true nature.

## Wide Range of Prey

A skitterhaunt infection can decimate whole nests of vermin. When those are in short supply, these oozes move on to prey on other species, such as ants, crabs, and other creatures with exoskeletons or similar hard outer shells.

## Hosts Required

Skitterhaunts can't survive long outside their host creatures; they quickly liquefy and lose their cohesion. A body abandoned by a skitterhaunt is an eerie, hollowed-out husk with a strong, acidic odor.

## Statblock

```ad-statblock
title: Skitterhaunt
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ToB1-2023/Skitterhaunt.webp#token)
*Large ooze, Unaligned*

- **Armor Class** 14 (natural armor)
- **Hit Points** 95 (`10d10 + 40`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|15 (+2)|11 (+0)|19 (+4)| 3 (-4)| 7 (-2)| 1 (-5)|

- **Proficiency Bonus** +2
- **Saving Throws** ⏤
- **Skills** ⏤
- **Senses** blindsight 60 ft. (blind beyond this radius), passive Perception 8
- **Damage Immunities** acid
- **Condition Immunities** [blinded](2-Mechanics/CLI/rules/conditions.md#Blinded), [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [deafened](2-Mechanics/CLI/rules/conditions.md#Deafened), [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened), [prone](2-Mechanics/CLI/rules/conditions.md#Prone)
- **Languages** —
- **Challenge** 4

## Traits

***Broken Shell.*** A creature that hits the skitterhaunt with a melee attack while within 5 feet of it takes `dice:1d8|noform|avg|text(4)` (`1d8`) acid damage.

***Ooze Nature.*** The skitterhaunt doesn't require sleep.

***Vermin Encasement.*** The creature within the vermin's shell is a shapeless ooze protected by the vermin's exoskeleton. When the skitterhaunt is reduced to 0 hp, the exoskeleton breaks, and the skitterhaunt ooze exits it. Once out of its exoskeleton, the ooze is Small, has an AC of 10, 10 hp, and a speed of 15 feet, and it can move through a space as narrow as 1 inch wide without squeezing. In addition, its only attack is a Slam that uses the same statistics as its Sting, except it deals bludgeoning damage instead of piercing damage. The skitterhaunt dies if it remains outside of a host for more than 24 hours. It can exit or enter a dead host's exoskeleton as a bonus action.

## Actions

***Multiattack.*** The skitterhaunt makes one Mandibles attack and one Sting attack, or it makes two Sting attacks.

***Mandibles.*** *Melee Weapon Attack:* `dice:1d20+4|noform|text(+4)` to hit, reach 5 ft., one target. *Hit:* `dice:1d4+2|noform|avg|text(5)` (`1d4 + 2`) slashing damage plus `dice:2d8|noform|avg|text(9)` (`2d8`) acid damage, and the target is [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) (escape DC 12) if it is a Medium or smaller creature. Until this grapple ends, the creature is [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained), and the skitterhaunt can't use its Mandibles on another target.

***Sting.*** *Melee Weapon Attack:* `dice:1d20+4|noform|text(+4)` to hit, reach 5 ft., one creature. *Hit:* `dice:1d8+2|noform|avg|text(6)` (`1d8 + 2`) piercing damage plus `dice:2d8|noform|avg|text(9)` (`2d8`) acid damage.

***Infest Vermin.*** The skitterhaunt infests a Large or smaller Beast with an exoskeleton within 5 feet of it. The target must succeed on a DC 14 Constitution saving throw or become [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned) until the skitterhaunt no longer infests it. Every 24 hours that elapse, the target must repeat the saving throw or take `dice:2d6|noform|avg|text(7)` (`2d6`) acid damage, and its hp maximum is reduced by that amount. This reduction lasts until the target finishes a long rest after the skitterhaunt no longer infests it. The target dies if this reduces its hp maximum to 0. The skitterhaunt then takes control of the body, dissolving the flesh and hiding within the exoskeleton. A target that succeeds on two consecutive saving throws forces the skitterhaunt out of its body and is immune to the skitterhaunt's Infest Vermin for the next 24 hours.

***Acid Spray (Recharge 6).*** The skitterhaunt spits acid in a 30-foot line that is 5 feet wide. Each creature in that line must make a DC 14 Dexterity saving throw, taking `dice:4d8|noform|avg|text(18)` (`4d8`) acid damage on a failed save, or half as much damage on a successful one.
```
^statblock

## Environment

forest, underdark