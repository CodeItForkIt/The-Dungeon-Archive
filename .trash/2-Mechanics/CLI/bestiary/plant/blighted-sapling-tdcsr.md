---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/tdcsr
- monster/cr/
- monster/size/medium
- monster/type/plant
aliases: ["Blighted Sapling"]
---
# Blighted Sapling
*Source: Tal'Dorei Campaign Setting Reborn p. 172*  

```ad-statblock
title: Blighted Sapling
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/TDCSR/Blighted%20Sapling.webp#token)
*Medium plant, Unaligned*


- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
| 8 (-1)|13 (+1)|12 (+1)| 4 (-3)| 8 (-1)| 3 (-4)|

- **Proficiency Bonus** +2
- **Saving Throws** ⏤
- **Skills** ⏤
- **Senses** blindsight 60 ft. (blind beyond this radius), passive Perception 9
- **Damage Vulnerabilities** fire
- **Damage Resistances** necrotic, poison
- **Condition Immunities** [blinded](2-Mechanics/CLI/rules/conditions.md#Blinded), [deafened](2-Mechanics/CLI/rules/conditions.md#Deafened), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** understands the languages you speak
- **Challenge** 

## Traits

***Blighted Resilience (10th level or higher).*** The creature has immunity to necrotic and poison damage and to the [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned) condition.

***Toxic Demise (10th level or higher).*** When the creature is reduced to 0 hit points, it explodes in a burst of toxic mulch or fetid viscera. Each creature within 5 feet of the exploding creature must succeed on a Constitution saving throw against your spell save DC or take necrotic damage based on the creature's challenge rating (see the table below). As an action, you can also cause a summoned creature to explode, immediately killing it.

**Toxic Demise Damage**

| Creature CR | Damage |
|-------------|--------|
| 1/4 or lower | `dice:1d4\\|noform\\|avg` (`1d4`) necrotic damage |
| 1/2 | `dice:1d6\\|noform\\|avg` (`1d6`) necrotic damage |
| 1 or higher | A number of  d8s of necrotic damage equal to the creature's challenge rating |
| No challenge rating | A number of d6s of necrotic damage equal to your proficiency bonus |
^toxic-demise-damage

## Actions

***Multiattack.*** When you reach 14th level in this class, the blighted sapling makes two claw attacks.

***Claws.*** *Melee Weapon Attack:* `YourSpellAttack` to hit, reach 5 ft., one target. *Hit:*  `2d4 + PB` piercing damage.
```
^statblock