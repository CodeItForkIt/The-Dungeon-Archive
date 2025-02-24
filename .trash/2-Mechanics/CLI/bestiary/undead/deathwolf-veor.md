---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/veor
- monster/cr/15
- monster/size/medium
- monster/type/undead
aliases: ["Deathwolf"]
---
# Deathwolf
*Source: Vecna: Eve of Ruin p. 217*  

A deathwolf combines the might of a werewolf, the unholy powers of undeath, and the magic of the full moon. Deathwolves are most common on Krynn but occasionally are found in other locations where lycanthropy and necromancy are prevalent.

To create a deathwolf, a necromancer reanimates the body of a powerful werewolf by conducting a profane ritual fueled by lunar magic. The result is an Undead abomination that resembles a skeletal, shadowy werewolf in hybrid form. Deathwolves can't shapeshift, but they can create dangerous illusions. A deathwolf's bite makes its victims more susceptible to the mind-bending phantoms the deathwolf can conjure.

> [!note] Deathwolves in Dragonlance
> 
> On the world of Krynn, deathwolves are associated with Lunitari, Krynn's red moon and the god of neutral magic. The god Lunitari is a trickster and master of illusions; necromancers perform the ritual to create a deathwolf under the light of her moon to instill the deathwolf with powers of illusion and trickery.
^deathwolves-in-dragonlance

```ad-statblock
title: Deathwolf
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/VEoR/Deathwolf.webp#token)
*Medium undead, typically  Chaotic Evil*

- **Armor Class** 15 (natural armor)
- **Hit Points** 153 (`18d8 + 72`)
- **Speed** 40 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|20 (+5)|16 (+3)|18 (+4)|10 (+0)|17 (+3)|19 (+4)|

- **Proficiency Bonus** +5
- **Saving Throws** Strength +10, Dexterity +8, Charisma +9
- **Skills** Perception +13, Stealth +8
- **Senses** darkvision 60 ft., passive Perception 23
- **Damage Immunities** poison; bludgeoning, piercing, slashing from nonmagical attacks that aren't silvered
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** Common
- **Challenge** 15

## Traits

***Legendary Resistance (2/Day).*** If the deathwolf fails a saving throw, it can choose to succeed instead.

***Moon's Grace.*** When the deathwolf falls, it descends at a rate of 60 feet per round and takes no falling damage.

## Actions

***Multiattack.*** The deathwolf makes one Bite attack and two Claw attacks. It can replace one of these attacks with Phantom Deathwolf if available.

***Bite.*** *Melee Weapon Attack:* `dice:1d20+10|noform|text(+10)` to hit, reach 5 ft., one target. *Hit:* `dice:2d8+5|noform|avg|text(14)` (`2d8 + 5`) piercing damage plus `dice:2d8|noform|avg|text(9)` (`2d8`) necrotic damage. The target must succeed on a DC 16 Wisdom saving throw or have disadvantage on saving throws against the [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened) condition. This curse lasts until removed by the [Remove Curse](2-Mechanics/CLI/spells/remove-curse.md) spell or other magic.

***Claw.*** *Melee Weapon Attack:* `dice:1d20+10|noform|text(+10)` to hit, reach 5 ft., one target. *Hit:* `dice:2d6+5|noform|avg|text(12)` (`2d6 + 5`) slashing damage plus `dice:1d8|noform|avg|text(4)` (`1d8`) necrotic damage.

***Phantom Deathwolf (Recharge 5-6).*** The deathwolf creates a terrifying phantom of itself in the mind of a creature the deathwolf can see within 60 feet of itself. The target must succeed on a DC 17 Intelligence saving throw or have the [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened) condition for 1 minute.

While the target is [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened), the phantom deals `dice:6d6|noform|avg|text(21)` (`6d6`) psychic damage to the target at the start of each of the target's turns. A [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened) target can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.

## Reactions

The deathwolf can take up to two reactions per round but only one per turn.

***Imposing Slash.*** When a creature within 5 feet of the deathwolf makes an attack roll against it, the deathwolf forces the creature to succeed on a DC 17 Wisdom saving throw or have disadvantage on that roll. After the attack hits or misses, the deathwolf makes one Claw attack against the creature.

***Phase Step.*** Immediately after taking damage, the deathwolf teleports up to 30 feet to an unoccupied space it can see that is in dim light or darkness.
```
^statblock