---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/dsotdq
- monster/cr/10
- monster/size/large
- monster/type/undead
aliases: ["Lesser Death Dragon"]
---
# Lesser Death Dragon
*Source: Dragonlance: Shadow of the Dragon Queen p. 195*  

Most death dragons are pale imitations of their former selves. They remember flashes and echoes, and sometimes things or creatures they encounter painfully remind them of what they once had. These fleeting moments of lucidity quickly burn away in rage and anguish, driving the dragons to destroy the would-be memento.

## Death Dragons

Death dragons are the Undead skeletal remains of metallic or chromatic dragons, infused with the lingering fires of the Cataclysm by foul magic. Rarely, death dragons arise when a dragon meets its end in a way that torments its soul and consumes it with a need for vengeance. Regardless of how it arose, a death dragon retains a shadow of its former personality. The stronger the death dragon, the more it fights the hate consuming it, holding on to some vestige of its memories.

A death dragon's bones burn with violet Cataclysmic fire, which it can unleash in a horrific mockery of the breath weapon it possessed in life. The breath snuffs out life force and infuses undeath into corpses it touches. These zombies burn with Cataclysmic fire and serve the death dragon's will, typically going on rampages to destroy all living creatures in sight.

## Statblock

```ad-statblock
title: Lesser Death Dragon
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/DSotDQ/Lesser%20Death%20Dragon.webp#token)
*Large undead, typically  Chaotic Evil*

- **Armor Class** 15 (natural armor)
- **Hit Points** 199 (`21d10 + 84`)
- **Speed** 40 ft., fly 80 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|20 (+5)|10 (+0)|18 (+4)| 5 (-3)|10 (+0)| 5 (-3)|

- **Proficiency Bonus** +4
- **Saving Throws** Dexterity +4, Wisdom +4
- **Skills** Perception +4, Stealth +4
- **Senses** blindsight 30 ft., darkvision 60 ft., passive Perception 14
- **Damage Resistances** piercing
- **Damage Immunities** necrotic, poison
- **Condition Immunities** [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** understands Common and Draconic but can't speak
- **Challenge** 10

## Traits

***Unusual Nature.*** The dragon doesn't require air, food, drink, or sleep.

## Actions

***Multiattack.*** The dragon makes one Bite attack and two Claw attacks.

***Bite.*** *Melee Weapon Attack:* `dice:1d20+9|noform|text(+9)` to hit, reach 10 ft., one target. *Hit:* `dice:2d8+5|noform|avg|text(14)` (`2d8 + 5`) piercing damage plus `dice:1d8|noform|avg|text(4)` (`1d8`) necrotic damage.

***Claw.*** *Melee Weapon Attack:* `dice:1d20+9|noform|text(+9)` to hit, reach 5 ft. one target. *Hit:* `dice:1d6+5|noform|avg|text(8)` (`1d6 + 5`) slashing damage. If the target is a Medium or smaller creature, it is [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) (escape DC 15). Until this grapple ends, the target is [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained). The dragon has two claws, each of which can grapple one target.

***Cataclysmic Breath (Recharge 5-6).*** The dragon exhales a wave of ghostly purple flames in a 30-foot cone. Each creature in that area must make a DC 16 Dexterity saving throw, taking `dice:8d8|noform|avg|text(36)` (`8d8`) necrotic damage on a failed save, or half as much damage on a successful one. A creature dies if the breath reduces it to 0 hit points. Additionally, any Medium or smaller Humanoid killed by the breath's damage, as well as every corpse of such a creatures within the cone, becomes a zombie (see the Monster Manual) under the dragon's control. The zombie acts on the dragon's initiative but immediately after the dragon's turn. Absent any other command, the zombie tries to kill any non-Undead creature it encounters.
```
^statblock