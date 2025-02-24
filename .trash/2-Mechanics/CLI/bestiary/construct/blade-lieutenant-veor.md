---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/veor
- monster/cr/9
- monster/size/medium
- monster/type/construct/warforged
aliases: ["Blade Lieutenant"]
---
# Blade Lieutenant
*Source: Vecna: Eve of Ruin p. 209*  

Blade lieutenants lead subordinates on raids on behalf of the Lord of Blades. Soldiers who fail to meet a lieutenant's demands are harshly disciplined.

## Blades of Eberron

In the aftermath of Eberron's Last War, a warforged called the Lord of Blades rose to fill the power vacuum left in the devastated Mournland. The Lord of Blades' followers, known as blades, formed a cult of personality that deifies the Lord of Blades and preaches a bloody, jingoistic doctrine of warforged superiority. The primary tenet of the blades is that non-warforged on the continent of Khorvaire must be slaughtered.

## Statblock

```ad-statblock
title: Blade Lieutenant
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/VEoR/Blade%20Lieutenant.webp#token)
*Medium construct (warforged), typically  Lawful Evil*

- **Armor Class** 16 (natural armor)
- **Hit Points** 153 (`18d8 + 72`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|18 (+4)|13 (+1)|19 (+4)|14 (+2)|14 (+2)|17 (+3)|

- **Proficiency Bonus** +4
- **Saving Throws** Intelligence +6, Charisma +7
- **Skills** Insight +6, Intimidation +7, Perception +6
- **Senses** passive Perception 16
- **Damage Resistances** poison
- **Condition Immunities** [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** Common
- **Challenge** 9

## Traits

***Pack Tactics.*** The lieutenant has advantage on an attack roll against a creature if at least one of the lieutenant's allies is within 5 feet of the creature and the ally doesn't have the [incapacitated](2-Mechanics/CLI/rules/conditions.md#Incapacitated) condition.

## Actions

***Multiattack.*** The lieutenant makes three Longsword or Javelin Launcher attacks.

***Longsword.*** *Melee Weapon Attack:* `dice:1d20+8|noform|text(+8)` to hit, reach 5 ft., one target. *Hit:* `dice:3d8+4|noform|avg|text(17)` (`3d8 + 4`) slashing damage, or `dice:3d10+4|noform|avg|text(20)` (`3d10 + 4`) slashing damage if used with two hands.

***Javelin Launcher.*** *Ranged Weapon Attack:* `dice:1d20+8|noform|text(+8)` to hit, range 30/120 ft., one target. *Hit:* `dice:3d6+4|noform|avg|text(14)` (`3d6 + 4`) piercing damage, and the target has the [prone](2-Mechanics/CLI/rules/conditions.md#Prone) condition.

## Bonus Actions

***Command Ally.*** The lieutenant targets one ally it can see within 30 feet of itself. If the target can see or hear the lieutenant, the target can make one melee attack using its reaction, if available, and has advantage on the attack roll.

***Rally the Troops (1/Day).*** The lieutenant ends the [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed) and [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened) conditions on itself and each creature of its choice that it can see within 30 feet of itself.

## Reactions

***Parry.*** The lieutenant adds 3 to its AC against one melee attack that would hit it. To do so, the lieutenant must see the attacker and be wielding a melee weapon.
```
^statblock