---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/mpp
- monster/cr/12
- monster/size/small-or-medium
- monster/type/humanoid
aliases: ["Doomguard Doom Lord"]
---
# Doomguard Doom Lord
*Source: Morte's Planar Parade p. 54, Sigil and the Outlands*  

Doom lords are the highest-ranking members of the Doomguard, embodying the multiverse's inevitable collapse into dust. Doom lords' mere presence snuffs the life from weaker foes, and the stoutest walls crumble before them.

```ad-statblock
title: Doomguard Doom Lord
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/MPP/Doomguard%20Doom%20Lord.webp#token)
*Small or Medium humanoid, Any alignment*

- **Armor Class** 18 ([plate armor](2-Mechanics/CLI/items/plate-armor.md))
- **Hit Points** 202 (`27d8 + 81`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|20 (+5)|12 (+1)|16 (+3)|15 (+2)|14 (+2)|18 (+4)|

- **Proficiency Bonus** +4
- **Saving Throws** Strength +9, Constitution +7
- **Skills** Perception +6
- **Senses** passive Perception 16
- **Damage Immunities** necrotic
- **Languages** Common plus three more languages
- **Challenge** 12

## Traits

***Aura of Doom.*** Any creature that starts its turn within 10 feet of the doom lord must make a DC 16 Constitution saving throw, taking `dice:4d8|noform|avg|text(18)` (`4d8`) necrotic damage on a failed save, or half as much damage on a successful one. If the doom lord doesn't have the [incapacitated](2-Mechanics/CLI/rules/conditions.md#Incapacitated) condition, it can suppress or resume this aura at the start of its turn (no action required).

***Siege Monster.*** The doom lord deals double damage to objects and structures.

## Actions

***Multiattack.*** The doom lord makes two Entropic Greatsword or Entropic Javelin attacks.

***Entropic Greatsword.*** *Melee Weapon Attack:* `dice:1d20+9|noform|text(+9)` to hit, reach 5 ft., one target. *Hit:* `dice:2d6+5|noform|avg|text(12)` (`2d6 + 5`) slashing damage plus `dice:3d6|noform|avg|text(10)` (`3d6`) necrotic damage. A creature killed by this attack has its body and everything it is wearing or carrying, except for magic items, reduced to ash.

***Entropic Javelin.*** *Melee or Ranged Weapon Attack:* `dice:1d20+9|noform|text(+9)` to hit, reach 5 ft. or range 30/120 ft., one target. *Hit:* `dice:1d6+5|noform|avg|text(8)` (`1d6 + 5`) piercing damage plus `dice:4d6|noform|avg|text(14)` (`4d6`) necrotic damage. A creature killed by this attack has its body and everything it is wearing or carrying, except for magic items, reduced to ash.
```
^statblock