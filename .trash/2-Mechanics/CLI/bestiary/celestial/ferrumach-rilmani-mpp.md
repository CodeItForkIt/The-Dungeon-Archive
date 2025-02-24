---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/mpp
- monster/cr/9
- monster/size/medium
- monster/type/celestial
aliases: ["Ferrumach Rilmani"]
---
# Ferrumach Rilmani
*Source: Morte's Planar Parade p. 44, Turn of Fortune's Wheel*  

Ferrumachs are the foot soldiers of the rilmani, preserving the balance between the planes through martial force. They vigilantly defend the Spire and fight at the command of aurumachs to protect the neutrality of the multiverse. Ferrumachs gleam with the sheen of bare iron. Their bodies are honed to razor edges, and from it they can fling bolts of sharpened metal.

## Rilmani

Rilmani protect the balance between the forces and philosophies of the multiverse. They seek to maintain planar equilibrium, assuring that good, evil, law, or chaos never grow too powerful or too weak. To the rilmani, each of these forces is fundamental to the multiverse's existence. Whenever one threatens to tip the balance in its favor or a plane is on the verge of collapse, the rilmani act to even the odds.

While the rilmani might be found anywhere, they're most frequently encountered on their home plane, the Outlands, where they work to ensure that no force overexerts itself on the Concordant Opposition.

Rilmani are bipedal, with bodies of living metal that ranges in appearance from cold iron to brilliant gold. Most have smooth faces with few features, and their extraordinary anatomies often act in defiance of natural forces.

## Statblock

```ad-statblock
title: Ferrumach Rilmani
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/MPP/Ferrumach%20Rilmani.webp#token)
*Medium celestial, typically  Neutral*

- **Armor Class** 18 (natural armor)
- **Hit Points** 136 (`16d8 + 64`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|19 (+4)|14 (+2)|18 (+4)|15 (+2)|14 (+2)|10 (+0)|

- **Proficiency Bonus** +4
- **Saving Throws** Strength +8, Constitution +8
- **Skills** Athletics +8, Perception +6
- **Senses** truesight 120 ft., passive Perception 16
- **Damage Resistances** psychic
- **Languages** telepathy 120 ft., any two languages
- **Challenge** 9

## Traits

***Bladed Edges.*** A creature takes `dice:3d6|noform|avg|text(10)` (`3d6`) slashing damage if it starts its turn grappling or being [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) by the ferrumach.

***Skewering Charge.*** If the ferrumach moves at least 20 feet in a straight line toward a Large or smaller creature and ends within 5 feet of it, that creature must succeed on a DC 16 Strength saving throw or have the [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) condition (escape DC 18) and take `dice:3d6|noform|avg|text(10)` (`3d6`) piercing damage.

***Spellcasting.*** The ferrumach casts one of the following spells, requiring no material components and using Intelligence as the spellcasting ability (spell save DC 14):

**At will**: [detect magic](2-Mechanics/CLI/spells/detect-magic.md)

**1/day each**: [dispel magic](2-Mechanics/CLI/spells/dispel-magic.md), [ice storm](2-Mechanics/CLI/spells/ice-storm.md)

## Actions

***Multiattack.*** The ferrumach makes three Sharpened Limb or Bolt attacks.

***Sharpened Limb.*** *Melee Weapon Attack:* `dice:1d20+8|noform|text(+8)` to hit, reach 10 ft., one target. *Hit:* `dice:1d10+4|noform|avg|text(9)` (`1d10 + 4`) slashing damage plus `dice:2d10|noform|avg|text(11)` (`2d10`) psychic damage.

***Bolt.*** *Ranged Weapon Attack:* `dice:1d20+8|noform|text(+8)` to hit, range 20/60 ft., one target. *Hit:* `dice:1d6+4|noform|avg|text(7)` (`1d6 + 4`) piercing damage plus `dice:2d10|noform|avg|text(11)` (`2d10`) psychic damage.
```
^statblock