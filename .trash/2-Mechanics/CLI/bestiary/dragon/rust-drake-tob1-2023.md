---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/tob1-2023
- monster/cr/8
- monster/environment/urban
- monster/size/medium
- monster/type/dragon
aliases: ["Rust Drake"]
---
# Rust Drake
*Source: Tome of Beasts 1 (2023 Edition) p. 145*  

*This rust-covered dragon could easily be mistaken for a pile of scrap metal.*

## Shedding Rust

Aside from fangs and claws like iron spikes, this dragon-like creature seems to be nothing more than a collection of rust. Each beating of its wings brings a shower of flakes.

## Warped Metallics

Many sages claim that rust dragons are a perversion of nature's order obtained either by the corruption of a metallic dragon's egg or the transformation of such a dragon by way of a ritual. Others disagree and propose another theory about a malady that affects the skin of young metallic dragons and ferrous drakes alike. So far, no one has discovered the truth about their origins.

## Filthy Scrap Metal Eaters

These foul creatures feed on rust and are known as disease carriers.

## Statblock

```ad-statblock
title: Rust Drake
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ToB1-2023/Rust%20Drake.webp#token)
*Medium dragon, Chaotic Evil*

- **Armor Class** 17 (natural armor)
- **Hit Points** 161 (`19d8 + 76`)
- **Speed** 30 ft., fly 80 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|20 (+5)|15 (+2)|19 (+4)|12 (+1)| 8 (-1)| 8 (-1)|

- **Proficiency Bonus** +3
- **Saving Throws** ⏤
- **Skills** Perception +5, Stealth +5
- **Senses** darkvision 60 ft., passive Perception 15
- **Damage Vulnerabilities** acid
- **Damage Immunities** poison
- **Condition Immunities** [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** Common, Draconic
- **Challenge** 8

## Traits

***Rust Drake Lockjaw.*** A creature infected with this disease manifests symptoms `dice:1d4|noform|avg` (`1d4`) days after infection, which include painful muscle spasms, particularly in the jaw. At the end of each long rest, the infected creature must succeed on a DC 15 Constitution saving throw or be [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed) for 1 hour and have its Dexterity score reduced by `dice:1d4|noform|avg` (`1d4`). This reduction lasts until the disease is cured. If the disease reduces the creature's Dexterity to 0, the creature dies. A creature that succeeds on two saving throws recovers from the disease.

## Actions

***Multiattack.*** The drake makes one Bite attack and two Tail Swipe attacks.

***Bite.*** *Melee Weapon Attack:* `dice:1d20+8|noform|text(+8)` to hit, reach 5 ft., one target. *Hit:* `dice:3d8+5|noform|avg|text(18)` (`3d8 + 5`) piercing damage, and the target must succeed on a DC 15 Constitution save or contract the rust drake lockjaw disease (see the Rust Drake Lockjaw trait).

***Tail Swipe.*** *Melee Weapon Attack:* `dice:1d20+8|noform|text(+8)` to hit, reach 5 ft., one target. *Hit:* `dice:2d8+5|noform|avg|text(14)` (`2d8 + 5`) bludgeoning damage.

***Vomit Scrap (Recharge 5-6).*** The rust drake vomits forth a 15-foot cone of rusted metal. Each creature in the area must make a DC 15 Dexterity saving throw, taking `dice:5d8|noform|avg|text(22)` (`5d8`) slashing damage and `dice:5d8|noform|avg|text(22)` (`5d8`) poison damage on a failed save, or half as much damage on a successful one. In addition, each creature that failed the saving throw must succeed on a DC 15 Constitution saving throw or contract the rust drake lockjaw disease (see the Rust Drake Lockjaw trait).
```
^statblock

## Environment

urban