---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/veor
- monster/cr/17
- monster/size/huge
- monster/type/monstrosity
aliases: ["Hertilod"]
---
# Hertilod
*Source: Vecna: Eve of Ruin p. 223*  

> [!quote] A quote from Melthena Vellaine, Wizard and Spelljammer  
> 
> They ain't dragons. They ain't lizards. Oh no, they're much worse."

When a dead god is left adrift in the Astral Sea, its corpse sometimes spawns a parasitic monster known as a hertilod. Voracious and terrifying, a hertilod resembles a skinless, serpentine lizard, with sharp claws and a gaping maw that drips venom. A hertilod's gruesomely exposed muscle renders it susceptible to lightning.

```ad-statblock
title: Hertilod
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/VEoR/Hertilod.webp#token)
*Huge monstrosity, Unaligned*

- **Armor Class** 14
- **Hit Points** 241 (`21d12 + 105`)
- **Speed** 50 ft., climb 50 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|23 (+6)|18 (+4)|20 (+5)| 3 (-4)|15 (+2)|10 (+0)|

- **Proficiency Bonus** +6
- **Saving Throws** Strength +12, Dexterity +10
- **Skills** Perception +8
- **Senses** blindsight 30 ft., tremorsense 60 ft., passive Perception 18
- **Damage Resistances** necrotic; bludgeoning, piercing, slashing from nonmagical attacks
- **Damage Immunities** poison
- **Condition Immunities** [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** —
- **Challenge** 17

## Traits

***Legendary Resistances (3/Day).*** If the hertilod fails a saving throw, it can choose to succeed instead.

***Magic Resistance.*** The hertilod has advantage on saving throws against spells and other magical effects.

***Shock Susceptibility.*** If the hertilod takes lightning damage, its speed is halved until the end of its next turn, and it must succeed on a DC 15 Constitution saving throw or immediately regurgitate all swallowed creatures, each of which lands in a space within 10 feet of the hertilod and has the [prone](2-Mechanics/CLI/rules/conditions.md#Prone) condition.

***Spider Climb.*** The hertilod can climb difficult surfaces, including upside down on ceilings, without needing to make an ability check.

## Actions

***Multiattack.*** The hertilod makes one Bite attack and two Claw attacks.

***Bite.*** *Melee Weapon Attack:* `dice:1d20+12|noform|text(+12)` to hit, reach 10 ft., one target. *Hit:* `dice:2d8+6|noform|avg|text(15)` (`2d8 + 6`) piercing damage plus `dice:2d12|noform|avg|text(13)` (`2d12`) poison damage. If the target is a Large or smaller creature, it must succeed on a DC 20 Strength saving throw or be swallowed by the hertilod. A swallowed creature has the [blinded](2-Mechanics/CLI/rules/conditions.md#Blinded) and [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained) conditions, and it has total cover against attacks and other effects outside the hertilod. At the start of each of the hertilod's turns, each swallowed creature takes `dice:2d12|noform|avg|text(13)` (`2d12`) poison damage from the poisonous secretion in the hertilod's gullet.

The hertilod's gullet can hold up to two creatures at a time. If the hertilod takes 40 damage or more on a single turn from a swallowed creature, the hertilod must succeed on a DC 15 Constitution saving throw at the end of that turn or regurgitate all swallowed creatures, each of which lands in a space within 10 feet of the hertilod and has the [prone](2-Mechanics/CLI/rules/conditions.md#Prone) condition. If the hertilod dies, a swallowed creature is no longer [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained) and can escape from the corpse by using 10 feet of movement, exiting with the [prone](2-Mechanics/CLI/rules/conditions.md#Prone) condition.

***Claw.*** *Melee Weapon Attack:* `dice:1d20+12|noform|text(+12)` to hit, reach 5 ft., one target. *Hit:* `dice:2d10+6|noform|avg|text(17)` (`2d10 + 6`) slashing damage.

## Legendary Actions

***Sprint.*** The hertilod moves up to its speed. This movement doesn't provoke opportunity attacks.

***Feed (Costs 2 Actions).*** The hertilod drains life from the creatures in its gullet to bolster itself. Each creature in the hertilod's gullet takes `dice:3d6|noform|avg|text(10)` (`3d6`) necrotic damage, and the hertilod regains a number of hit points equal to the damage.
```
^statblock