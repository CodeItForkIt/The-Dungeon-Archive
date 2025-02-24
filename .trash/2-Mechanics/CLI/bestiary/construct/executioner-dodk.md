---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/dodk
- monster/cr/20
- monster/size/huge
- monster/type/construct
aliases: ["Executioner"]
---
# Executioner
*Source: Dungeons of Drakkenheim p. 209*  

> [!quote] A quote from Lieutenant Petra Lang  
> 
> ...and that's why we don't go to Slaughterstone Square.


```ad-statblock
title: Executioner
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/DoDk/Executioner.webp#token)
*Huge construct, Lawful Evil*

- **Armor Class** 20 (natural armor)
- **Hit Points** 405 (`30d12 + 210`)
- **Speed** 40 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|29 (+9)|11 (+0)|25 (+7)|10 (+0)|11 (+0)|10 (+0)|

- **Proficiency Bonus** +6
- **Saving Throws** Strength +15, Constitution +13, Wisdom +6
- **Skills** ⏤
- **Senses** darkvision 120 ft., passive Perception 10
- **Damage Immunities** poison; psychic; bludgeoning, piercing, slashing from nonmagical attacks that aren't adamantine
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened), [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed), [petrified](2-Mechanics/CLI/rules/conditions.md#Petrified), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** understands common but does not speak
- **Challenge** 20

## Traits

***Legendary Resistance (3/Day).*** If the Executioner fails a saving throw, it can choose to succeed instead.

***Immutable Form.*** The Executioner is immune to any spell or effect that would alter its form.

***Magic Resistance.*** The Executioner has advantage on saving throws against spells and other magical effects.

***Magic Weapons.*** The Executioner's weapon attacks are magical.

***Rejuvenation.*** If the Executioner is destroyed, it returns with all its hit points in 24 hours unless a [disintegrate](2-Mechanics/CLI/spells/disintegrate.md) spell is cast on its remains.

## Actions

***Guillotine Blade.*** *Melee or Ranged Weapon Attack:* `dice:1d20+15|noform|text(+15)` to hit, reach 10 ft., or range 30/120 ft., one target. *Hit:* `dice:6d6+9|noform|avg|text(30)` (`6d6 + 9`) slashing damage plus `dice:4d6|noform|avg|text(14)` (`4d6`) necrotic damage. The target must succeed on a DC 21 Constitution saving throw or its hit point maximum is reduced by an amount equal to the necrotic damage taken. This reduction lasts until the creature finishes a long rest. The target dies if this effect reduces its hit point maximum to 0. Immediately after making a ranged attack, this weapon flies back to the Executioner's hands.

***Necrotic Vents (Recharge 5-6).*** The Executioner vents necrotic gas in a 30-foot radius. Each creature in that area must succeed on a DC 21 Constitution saving throw, taking `dice:10d8|noform|avg|text(45)` (`10d8`) necrotic damage on a failed save, or half as much damage on a successful one. A creature who fails this saving throw by 5 or more gains one level of contamination.

## Legendary Actions

***Lumber Forward.*** The Executioner moves half its speed.

***Attack (Costs 2 actions).*** The Executioner makes a melee or ranged attack with its Guillotine Blade.

***Summon Shadows. (Costs 3 actions).*** The Executioner targets up to six humanoid corpses it can see within 60 feet of it that have died violently. Each target's spirit rises as a shadow in the space of its corpse or in the nearest unoccupied space. The shadows act after the Executioner on the same initiative count, are under its control, and remain for 1 minute or until they're destroyed. They disappear if the Executioner is destroyed.
```
^statblock