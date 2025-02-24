---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/skt
- monster/cr/3
- monster/size/medium
- monster/type/humanoid/any-race
aliases: ["Knight of the Mithral Shield"]
---
# Knight of the Mithral Shield
*Source: Storm King's Thunder p. 79*  

```ad-statblock
title: Knight of the Mithral Shield
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/SKT/Knight%20of%20the%20Mithral%20Shield.webp#token)
*Medium humanoid (any race), Lawful Good*

- **Armor Class** 20 ([plate armor](2-Mechanics/CLI/items/plate-armor.md), [shield](2-Mechanics/CLI/items/shield.md))
- **Hit Points** 52 (`8d8 + 16`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|16 (+3)|11 (+0)|14 (+2)|11 (+0)|11 (+0)|15 (+2)|

- **Proficiency Bonus** +2
- **Saving Throws** Constitution +4, Wisdom +2
- **Skills** ⏤
- **Senses** passive Perception 10
- **Languages** any one language (usually Common)
- **Challenge** 3

## Traits

***Possessed.*** While the knight is possessed by yakfolk, its alignment is lawful evil and it can speak Yikaria (the yakfolk tongue).

***Brave.*** The knight has advantage on saving throws against being [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened).

## Actions

***Multiattack.*** The knight makes two melee attacks.

***Warhammer.*** *Melee Weapon Attack:* `dice:1d20+5|noform|text(+5)` to hit, reach 5 ft., one target. *Hit:* `dice:1d8+3|noform|avg|text(7)` (`1d8 + 3`) bludgeoning damage, or `dice:1d10+3|noform|avg|text(8)` (`1d10 + 3`) bludgeoning damage if used with two hands.

***Heavy Crossbow.*** *Ranged Weapon Attack:* `dice:1d20+2|noform|text(+2)` to hit, range 100/400 ft., one target. *Hit:* `dice:1d10|noform|avg|text(5)` (`1d10`) piercing damage.

***Leadership (Recharges after a Short or Long Rest).*** For 1 minute, the knight can utter a special command or warning whenever a nonhostile creature that it can see within 30 feet of it makes an attack roll or a saving throw. The creature can add a `dice:d4|noform|avg` (`d4`) to its roll provided it can hear and understand the knight. A creature can benefit from only one Leadership die at a time. This effect ends if the knight is [incapacitated](2-Mechanics/CLI/rules/conditions.md#Incapacitated).

## Reactions

***Parry.*** The knight adds 2 to its AC against one melee attack that would hit it. To do so, the knight must see the attacker and be wielding a melee weapon.
```
^statblock