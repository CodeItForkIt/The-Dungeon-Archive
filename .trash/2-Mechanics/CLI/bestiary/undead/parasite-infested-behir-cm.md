---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/cm
- monster/cr/11
- monster/size/huge
- monster/type/undead
aliases: ["Parasite-infested Behir"]
---
# Parasite-infested Behir
*Source: Candlekeep Mysteries p. 220*  

When a parasite-infested behir roars or discharges their lightning breath, thousands of gray, parasitic blood worms can be seen writhing inside their mouths. Targeting the behir with magic that removes a disease kills off its blood parasites.

```ad-statblock
title: Parasite-infested Behir
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/CM/Parasite-infested%20Behir.webp#token)
*Huge undead, Neutral Evil*

- **Armor Class** 17 (natural armor)
- **Hit Points** 168 (`16d12 + 64`)
- **Speed** 50 ft., climb 40 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|23 (+6)|16 (+3)|18 (+4)| 7 (-2)|14 (+2)|12 (+1)|

- **Proficiency Bonus** +4
- **Saving Throws** ⏤
- **Skills** Perception +6, Stealth +7
- **Senses** darkvision 90 ft., passive Perception 16
- **Damage Immunities** lightning
- **Languages** Draconic
- **Challenge** 11

## Actions

***Multiattack.*** The behir makes two attacks: one with its bite and one to constrict.

***Bite.*** *Melee Weapon Attack:* `dice:1d20+10|noform|text(+10)` to hit, reach 10 ft., one target. *Hit:* `dice:3d10+6|noform|avg|text(22)` (`3d10 + 6`) piercing damage.

***Constrict.*** *Melee Weapon Attack:* `dice:1d20+10|noform|text(+10)` to hit, reach 5 ft., one Large or smaller creature. *Hit:* `dice:2d10+6|noform|avg|text(17)` (`2d10 + 6`) bludgeoning damage plus `dice:2d10+6|noform|avg|text(17)` (`2d10 + 6`) slashing damage. The target is [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) (escape DC 16) if the behir isn't already constricting a creature, and the target is [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained) until this grapple ends.

***Lightning Breath (Recharge 5-6).*** The behir exhales a line of lightning that is 20 feet long and 5 feet wide. Each creature in that line must make a DC 16 Dexterity saving throw, taking `dice:12d10|noform|avg|text(66)` (`12d10`) lightning damage on a failed save, or half as much damage on a successful one.

***Swallow.*** The behir makes one bite attack against a Medium or smaller target it is grappling. If the attack hits, the target is also swallowed, and the grapple ends. While swallowed, the target is [blinded](2-Mechanics/CLI/rules/conditions.md#Blinded) and [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained), it has total cover against attacks and other effects outside the behir, and it takes `dice:6d6|noform|avg|text(21)` (`6d6`) acid damage at the start of each of the behir's turns. A behir can have only one creature swallowed at a time.

Any creature swallowed by a parasite-infested behir must succeed on a DC 19 Constitution saving throw at the start of each of the behir's turns or be feasted upon by blood parasites, taking `dice:8d8|noform|avg|text(36)` (`8d8`) necrotic damage on a failed save, or half as much damage on a successful save. This damage is in addition to the damage caused by the behir's digestive acids.

If the behir takes 30 damage or more on a single turn from the swallowed creature, the behir must succeed on a DC 14 Constitution saving throw at the end of that turn or regurgitate the creature, which falls [prone](2-Mechanics/CLI/rules/conditions.md#Prone) in a space within 10 feet of the behir. If the behir dies, a swallowed creature is no longer [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained) by it and can escape from the corpse by using 15 feet of movement, exiting [prone](2-Mechanics/CLI/rules/conditions.md#Prone).
```
^statblock