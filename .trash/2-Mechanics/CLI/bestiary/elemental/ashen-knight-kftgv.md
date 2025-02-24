---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/kftgv
- monster/cr/3
- monster/size/medium
- monster/type/elemental/any-race
aliases: ["Ashen Knight"]
---
# Ashen Knight
*Source: Keys from the Golden Vault p. 158*  

Knights are warriors who pledge service to rulers, religious orders, and noble causes. A knight's alignment determines the extent to which a pledge is honored. Whether undertaking a quest or patrolling a realm, a knight often travels with an entourage that includes squires and hirelings who are commoners.

```ad-statblock
title: Ashen Knight
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/KftGV/Ashen%20Knight.webp#token)
*Medium elemental (any race), Lawful Evil*

- **Armor Class** 18 ([plate armor](2-Mechanics/CLI/items/plate-armor.md))
- **Hit Points** 52 (`8d8 + 16`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|16 (+3)|11 (+0)|14 (+2)|11 (+0)|11 (+0)|15 (+2)|

- **Proficiency Bonus** +2
- **Saving Throws** Constitution +4, Wisdom +2
- **Skills** ⏤
- **Senses** passive Perception 10
- **Damage Immunities** fire
- **Languages** any one language (usually Common)
- **Challenge** 3

## Traits

***Brave.*** The ashen knight has advantage on saving throws against being [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened).

***Ashen Creature.*** When the knight drops to 0 hit points, it is reduced to a pile of ash, and any equipment it was wearing or carrying falls to the ground.

## Actions

***Multiattack.*** The ashen knight makes two melee attacks.

***Greatsword.*** *Melee Weapon Attack:* `dice:1d20+5|noform|text(+5)` to hit, reach 5 ft., one target. *Hit:* `dice:2d6+3|noform|avg|text(10)` (`2d6 + 3`) slashing damage.

***Heavy Crossbow.*** *Ranged Weapon Attack:* `dice:1d20+2|noform|text(+2)` to hit, range 100/400 ft., one target. *Hit:* `dice:1d10|noform|avg|text(5)` (`1d10`) piercing damage.

***Leadership (Recharges after a Short or Long Rest).*** For 1 minute, the ashen knight can utter a special command or warning whenever a nonhostile creature that it can see within 30 feet of it makes an attack roll or a saving throw. The creature can add a `dice:d4|noform|avg` (`d4`) to its roll provided it can hear and understand the ashen knight. A creature can benefit from only one Leadership die at a time. This effect ends if the ashen knight is [incapacitated](2-Mechanics/CLI/rules/conditions.md#Incapacitated).

## Reactions

***Parry.*** The ashen knight adds 2 to its AC against one melee attack that would hit it. To do so, the ashen knight must see the attacker and be wielding a melee weapon.
```
^statblock