---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/egw
- monster/cr/10
- monster/size/large
- monster/type/construct
aliases: ["Gearkeeper Construct"]
---
# Gearkeeper Construct
*Source: Explorer's Guide to Wildemount p. 290*  

Rolling, deadly whirlwinds of metal plates and curving blades, these clockwork automatons were initially designed by tinkerers and mage engineers to be sentries and guardians in the deepest of vaults during the Age of Arcanum. While most of these majestic and deadly curiosities have fallen to rust and ruin, forgotten along with their long-destroyed and buried societies, some continue to patrol the tunnels and pathways of forgotten tombs and dungeons, following their original operations and directives to protect the contents of their domain.

Resembling a rolling ball of shield-like plates, a gearkeeper construct can rapidly travel through corridors to seek intruders. Upon discovering an unrecognized creature, the shields expand to reveal gaps where numerous metallic legs emerge for precision movement. Bladed appendages whir around the construct, threatening any unlucky delvers who wander too close, while heavy spears of steel can be fired from within the construct's core, impaling unwanted guests. If overwhelmed, the construct can discharge a spray of heated, jagged metal fragments to subdue groups of intruders.

Reverse engineering from the recovered shells and scraps of excavated gearkeeper constructs, a number of modern tinkerers have developed updated variations of these sentinels. Such designs are only recently seeing use in select prisons, or by wealthy collectors seeking to keep their collections safe.

```ad-statblock
title: Gearkeeper Construct
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/EGW/Gearkeeper%20Construct.webp#token)
*Large construct, Unaligned*

- **Armor Class** 18 (natural armor)
- **Hit Points** 161 (`17d10 + 68`)
- **Speed** 60 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|20 (+5)|16 (+3)|18 (+4)| 3 (-4)|11 (+0)| 1 (-5)|

- **Proficiency Bonus** +4
- **Saving Throws** ⏤
- **Skills** ⏤
- **Senses** blindsight 120 ft., passive Perception 10
- **Damage Resistances** bludgeoning, piercing, slashing from nonmagical attacks
- **Damage Immunities** fire, poison, psychic
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened), [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed), [petrified](2-Mechanics/CLI/rules/conditions.md#Petrified), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** understands the languages of its creator but can't speak
- **Challenge** 10

## Traits

***Immutable Form.*** The gearkeeper is immune to any spell or effect that would alter its form.

***Rapid Shifting.*** Opportunity attacks made against the gearkeeper have disadvantage.

***Whirling Blades.*** Any creature that starts its turn within 5 feet of the gearkeeper takes `dice:1d8|noform|avg|text(4)` (`1d8`) slashing damage.

## Actions

***Multiattack.*** The gearkeeper makes two Arm Blade attacks, or one Arm Blade attack and one Spear Launcher attack.

***Arm Blade.*** *Melee Weapon Attack:* `dice:1d20+9|noform|text(+9)` to hit, reach 5 ft., one target. *Hit:* `dice:3d8+5|noform|avg|text(18)` (`3d8 + 5`) slashing damage.

***Spear Launcher.*** *Ranged Weapon Attack:* `dice:1d20+9|noform|text(+9)` to hit, range 90 ft., one target. *Hit:* `dice:2d6+5|noform|avg|text(12)` (`2d6 + 5`) piercing damage, and the target is knocked [prone](2-Mechanics/CLI/rules/conditions.md#Prone).

***Shrapnel Blast (Recharge 6).*** The gearkeeper jettisons a spray of jagged metal in a 30-foot cone. Each creature in the area must make a DC 15 Dexterity saving throw, taking `dice:6d6|noform|avg|text(21)` (`6d6`) piercing damage on a failed save, or half as much damage on a successful one.
```
^statblock