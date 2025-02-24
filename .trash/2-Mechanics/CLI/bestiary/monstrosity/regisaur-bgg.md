---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/bgg
- monster/cr/14
- monster/size/gargantuan
- monster/type/monstrosity/dinosaur
aliases: ["Regisaur"]
---
# Regisaur
*Source: Bigby Presents: Glory of the Giants p. 130*  

Aptly called "the ruler of dinosaurs," a regisaur is an enormous predator large enough to swallow a giant whole. Fiery veins of elemental energy course through its skin and glow in its eyes and nostrils.

## Dinosaurs

When Annam's children first began to populate the worlds of the Material Plane, the All-Father created behemoth dinosaurs to live alongside them as companions. The primeval magic used to create the dinosaurs still thrums through their being and manifests in colorful, scar-like lines on their towering bodies. Some of these ancient dinosaurs persist in timeless jungles, hidden enclaves, and other lands untouched by the rest of the world.

## Statblock

```ad-statblock
title: Regisaur
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/BGG/Regisaur.webp#token)
*Gargantuan monstrosity (dinosaur), Unaligned*

- **Armor Class** 17 (natural armor)
- **Hit Points** 181 (`11d20 + 66`)
- **Speed** 40 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|27 (+8)| 8 (-1)|23 (+6)| 4 (-3)|12 (+1)| 6 (-2)|

- **Proficiency Bonus** +5
- **Saving Throws** ⏤
- **Skills** ⏤
- **Senses** passive Perception 11
- **Languages** —
- **Challenge** 14

## Traits

***Magic Resistance.*** The regisaur has advantage on saving throws against spells and other magical effects.

## Actions

***Multiattack.*** The regisaur makes one Bite attack and one Tail attack. The regisaur can't target the same creature with both attacks.

***Bite.*** *Melee Weapon Attack:* `dice:1d20+13|noform|text(+13)` to hit, reach 10 ft., one target. *Hit:* `dice:6d12+8|noform|avg|text(47)` (`6d12 + 8`) piercing damage, and the target has the [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) condition (escape DC 18). Until this grapple ends, the target has the [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained) condition, and the regisaur can't Bite another target.

***Tail.*** *Melee Weapon Attack:* `dice:1d20+13|noform|text(+13)` to hit, reach 20 ft., one target. *Hit:* `dice:4d8+8|noform|avg|text(26)` (`4d8 + 8`) bludgeoning damage.

## Bonus Actions

***Swallow.*** *Melee Weapon Attack:* `dice:1d20+13|noform|text(+13)` to hit, reach 5 ft., one Huge or smaller creature [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) by the regisaur. *Hit:* The regisaur swallows the target, and the grapple ends. A swallowed creature has the [blinded](2-Mechanics/CLI/rules/conditions.md#Blinded) and [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained) conditions, it has total cover against attacks and other effects outside the regisaur, and it takes `dice:2d6|noform|avg|text(7)` (`2d6`) acid damage at the start of each of its turns. The regisaur can have up to two creatures swallowed at a time.

If the regisaur takes 25 damage or more on a single turn from a swallowed creature, the regisaur must succeed on a DC 16 Constitution saving throw at the end of that turn or regurgitate the creature, which falls in a space within 5 feet of the regisaur and has the [prone](2-Mechanics/CLI/rules/conditions.md#Prone) condition; the creature no longer has the [blinded](2-Mechanics/CLI/rules/conditions.md#Blinded) and [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained) conditions.
```
^statblock