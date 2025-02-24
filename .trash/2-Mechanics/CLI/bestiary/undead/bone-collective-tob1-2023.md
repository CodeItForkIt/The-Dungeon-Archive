---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/tob1-2023
- monster/cr/8
- monster/environment/urban
- monster/size/small
- monster/type/undead
aliases: ["Bone Collective"]
---
# Bone Collective
*Source: Tome of Beasts 1 (2023 Edition) p. 39*  

*Thousands of tiny bones coalesce into a humanoid form, then disperse in a clattering swarm the next moment. The bones rustle as the creature moves, a sound like sand sliding down a dune.*

## Spies and Sneaks

Bone collectives are not primarily fighters, preferring to spy and skulk. However, when cornered, they fight fearlessly, seeking to strip the flesh from their foes. They wear robes or cloaks to pass as humanoid, as they know that most creatures find them disturbing.

## Commanders and Servants of Undeath

Bone collectives' long finger bones and hooked claws help them ascend and control zombie mounts, and their magic allows them to control small groups of undead. This undead affinity occasionally leads them to serve as spies or spymasters for necromancers, darakhul, vampires, or liches.

## Feed on Society

Bone collectives join societies around them, whether human, goblin, or ghoul. They prey on the living and the dead, to replenish lost bones. They produce a reddish venom that drains the luster of life from victims. Those who survive can describe the horrifying red smile of the collective's venom‑coated fangs.

## Statblock

```ad-statblock
title: Bone Collective
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ToB1-2023/Bone%20Collective.webp#token)
*Small undead, Chaotic Evil*

- **Armor Class** 17 (natural armor)
- **Hit Points** 120 (`16d6 + 64`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|10 (+0)|20 (+5)|18 (+4)|14 (+2)|10 (+0)|16 (+3)|

- **Proficiency Bonus** +3
- **Saving Throws** Dexterity +8
- **Skills** Arcana +5, Deception +6, Perception +3, Stealth +11
- **Senses** darkvision 120 ft., passive Perception 13
- **Damage Resistances** bludgeoning, piercing, slashing
- **Damage Immunities** necrotic, poison
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened), [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed), [petrified](2-Mechanics/CLI/rules/conditions.md#Petrified), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned), [prone](2-Mechanics/CLI/rules/conditions.md#Prone), [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained), [stunned](2-Mechanics/CLI/rules/conditions.md#Stunned)
- **Languages** Common, Darakhul (can't speak in shapeless form)
- **Challenge** 8

## Traits

***Collective Mind.*** The collective's individual bones are connected via a hive mind. It can telepathically communicate with any of its individual bones within 50 miles of it, and it can't be surprised. If the collective is reduced to half its hp or fewer, its Intelligence score is reduced to 1, it can't cast spells, it immediately changes to its shapeless form, and it can't take on a Humanoid form.

***Grasping Limbs (Humanoid Form Only).*** The bone collective can wield weapons and hold, grasp, push, pull, or interact with objects that might otherwise require a Humanoid form to accomplish.

***Swarm (Shapeless Form Only).*** The bone collective can occupy another creature's space and vice versa, and the swarm can move through any opening large enough for a Tiny bone.

***Undead Nature.*** The bone collective doesn't require air, food, drink, or sleep.

***Wyrmblood Venom.*** When the bone collective hits a [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned) creature with a Bite or Piercing Bones attack, the target's Charisma score is reduced by `dice:1d4|noform|avg` (`1d4`). The target is [incapacitated](2-Mechanics/CLI/rules/conditions.md#Incapacitated) if this reduces its Charisma to 0. The reduction lasts until the target finishes a long rest.

***Spellcasting (3/Day; Humanoid Form Only).*** The bone collective casts the [animate dead](2-Mechanics/CLI/spells/animate-dead.md) spell as an action, requiring no material components and using Charisma as the spellcasting ability (spell save DC 14).

**3/day each**: [animate dead](2-Mechanics/CLI/spells/animate-dead.md)

## Actions

***Multiattack.*** The bone collective makes two Claw attacks, or one Claw attack and one Bite attack.

***Bite (Humanoid Form Only).*** *Melee Weapon Attack:* `dice:1d20+8|noform|text(+8)` to hit, reach 5 ft., one target. *Hit:* `dice:4d12+5|noform|avg|text(31)` (`4d12 + 5`) piercing damage, and the target must succeed on a DC 16 Constitution saving throw or become [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned) for 1 minute. The target can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.

***Claw (Humanoid Form Only).*** *Melee Weapon Attack:* `dice:1d20+8|noform|text(+8)` to hit, reach 5 ft., one target. *Hit:* `dice:3d12+5|noform|avg|text(25)` (`3d12 + 5`) slashing damage.

***Piercing Bones (Shapeless Form Only).*** *Melee Weapon Attack:* `dice:1d20+8|noform|text(+8)` to hit, reach 0 ft., one creature in the collective's space. *Hit:* `dice:8d12|noform|avg|text(52)` (`8d12`) piercing damage, or `dice:4d12|noform|avg|text(26)` (`4d12`) piercing damage if the collective has half its hp or fewer.

## Bonus Actions

***Shape Swarm.*** The bone collective can shape itself into a Small Humanoid or back into a shapeless form of Tiny bones. Its statistics are the same in each form, and it can't regain hp or gain temporary hp. It can't take on a Humanoid form if it is occupying the space of another creature.
```
^statblock

## Environment

urban