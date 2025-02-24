---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/coa
- monster/cr/21
- monster/size/large
- monster/type/fiend/devil
aliases: ["Brother Morax"]
---
# Brother Morax
*Source: Chains of Asmodeus p. 186*  

```ad-statblock
title: Brother Morax
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/CoA/Brother%20Morax.webp#token)
*Large fiend (devil), Lawful Evil*

- **Armor Class** 21 (natural armor)
- **Hit Points** 337 (`25d10 + 200`)
- **Speed** 40 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|24 (+7)|22 (+6)|27 (+8)|14 (+2)|16 (+3)|18 (+4)|

- **Proficiency Bonus** +7
- **Saving Throws** Strength +14, Dexterity +13, Constitution +15
- **Skills** Acrobatics +20, Athletics +21, Intimidation +11, Medicine +10, Stealth +13, Survival +10
- **Senses** darkvision 120 ft., passive Perception 13
- **Damage Resistances** cold; bludgeoning, piercing, slashing from nonmagical attacks that aren't silvered
- **Damage Immunities** fire, poison
- **Condition Immunities** [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** Celestial, Common, Draconic, Infernal, telepathy 120 ft.
- **Challenge** 21

## Traits

***Brittle Spine.*** For each Brittle Spine a creature has, the creature takes `dice:1d6|noform|avg|text(3)` (`1d6`) poison damage at the start of each of their turns, and when Morax activates Burrow or Deep Burrow. Spines can only be removed by a Regeneration spell or similar, or by killing Morax.

***Devil's Sight.*** Magical darkness doesn't impede Morax's darkvision.

***Magic Resistance.*** Morax has advantage on saving throws against spells and other magical effects.

***Spined Hide.*** Whenever Morax is hit with a melee attack, the attacker takes `dice:2d6|noform|avg|text(7)` (`2d6`) piercing damage and gains 1 Brittle Spine.

***Unbreakable Bond.*** If Morax is reduced to 0 hit points while Brother Adramalech still lives, Morax regenerates 50 hit points at the start of his next turn. This regeneration is interrupted if Brother Adramalech is reduced to 0 hit points before the start of Morax's turn.

## Actions

***Multiattack.*** Morax makes four attacks using his Claw, Spine Fling, or a combination of the two.

***Claw.*** *Melee Weapon Attack:* `dice:1d20+14|noform|text(+14)` to hit, reach 10 ft., one target. *Hit:* `dice:3d6+7|noform|avg|text(17)` (`3d6 + 7`) slashing damage, and the target gains 1 Brittle Spine.

***Spine Fling.*** *Ranged Weapon Attack:* `dice:1d20+13|noform|text(+13)` to hit, range 30/60 ft., one target. *Hit:* `dice:1d12+6|noform|avg|text(12)` (`1d12 + 6`) piercing damage, and the target gains 1 Brittle Spine.

***Deep Burrow.*** Morax immediately deals Brittle Spine ongoing damage to all creatures that have at least one Brittle Spine that he can see.

***Bone Spikes (Recharge 6).*** Morax shoves an arm into the ground, rapidly growing bones that erupt at a point he can see within 100 feet of him. Each creature in a 60-foot-radius sphere centered on that point must make a DC 21 Dexterity saving throw, taking `dice:8d6|noform|avg|text(28)` (`8d6`) piercing damage on a failed save, or half as much damage on a successful one. Creatures that fail the save gain 2 Brittle Spines, while creatures that succeed only gain 1 Brittle Spine.

## Legendary Actions

***Claw.*** Morax makes a Claw attack.

***Bone Splinters (Costs 2 Actions).*** Morax gestures at a creature he can see that has at least 1 Brittle Spine. That creature must succeed on a DC 21 Constitution saving throw or the number of Brittle Spines it has doubles.

***Burrow (Costs 2 Actions).*** Morax bristles the spines within a creature that he can see. The target immediately takes Brittle Spine ongoing damage.
```
^statblock