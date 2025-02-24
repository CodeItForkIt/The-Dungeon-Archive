---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/veor
- monster/cr/6
- monster/size/medium
- monster/type/construct
aliases: ["Moonlight Guardian"]
---
# Moonlight Guardian
*Source: Vecna: Eve of Ruin p. 227*  

> [!quote] A quote from Werthil,Kender Adventurer  
> 
> Thought it was a person at first, but then I saw its head. Next, its arm. I knew I had to run.

Moonlight guardians are gleaming bipedal statues made of silver and mithral. They were originally created by a desperate mage on Krynn who drew the Moon card from a Deck of Many Things. The mage wished for a retinue of bodyguards ideally suited to fighting lycanthropes and other shapeshifting creatures. In response, the Moon card spawned the first moonlight guardian.

A moonlight guardian's body is infused with magical moonlight that the creature can channel into its blows. It can also unleash searing blasts of lunar energy that can expose shapeshifters by forcing them into their true forms.

```ad-statblock
title: Moonlight Guardian
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/VEoR/Moonlight%20Guardian.webp#token)
*Medium construct, Unaligned*

- **Armor Class** 16 (natural armor)
- **Hit Points** 105 (`14d8 + 42`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|19 (+4)| 9 (-1)|16 (+3)| 6 (-2)|12 (+1)| 6 (-2)|

- **Proficiency Bonus** +3
- **Saving Throws** ⏤
- **Skills** ⏤
- **Senses** truesight 120 ft., passive Perception 11
- **Damage Resistances** bludgeoning, piercing, slashing from nonmagical attacks
- **Damage Immunities** poison, radiant
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened), [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed), [petrified](2-Mechanics/CLI/rules/conditions.md#Petrified), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** understands the languages of its creator but can't speak
- **Challenge** 6

## Traits

***Immutable Form.*** The guardian is immune to any spell or other effect that would alter its form.

***Magic Resistance.*** The guardian has advantage on saving throws against spells and other magical effects.

***Radiant Absorption.*** Whenever the guardian is subjected to radiant damage, it takes no damage and instead regains a number of hit points equal to the radiant damage.

## Actions

***Multiattack.*** The guardian makes two Moonlight Slam attacks.

***Moonlight Slam.*** *Melee Weapon Attack:* `dice:1d20+7|noform|text(+7)` to hit, reach 5 ft., one target. *Hit:* `dice:1d8+4|noform|avg|text(8)` (`1d8 + 4`) bludgeoning damage plus `dice:1d8|noform|avg|text(4)` (`1d8`) radiant damage.

***Moonlight Blast (Recharge 5-6).*** The guardian unleashes a magical blast of moonlight in a line 60 feet long and 5 feet wide. Each creature in that area must make a DC 14 Dexterity saving throw. Creatures that aren't in their true form have disadvantage on the save. On a failed save, a creature takes `dice:5d8|noform|avg|text(22)` (`5d8`) radiant damage, and if it isn't in its true form, it is forced into its true form and can't change forms until the end of the guardian's next turn. On a successful save, a creature takes half as much damage only.
```
^statblock