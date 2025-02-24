---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/ghloe
- monster/cr/1-8
- monster/size/medium
- monster/type/humanoid/gnoll
aliases: ["Beast Gnoll"]
---
# Beast Gnoll
*Source: Grim Hollow: Lairs of Etharis p. 60*  

> [!quote]  
> 
> I never believed the rumors about the Beast and how it could change people. Then I saw how everyone at the logging camp had been transformed. It had to be a power even greater than a god's.

## Salvage

The spine spikes of a venomous gnoll can be fashioned into four arrows, bolts, or darts. Someone who has proficiency with smith's tools or tinker's tools can make these projectiles in 4 hours. Each time one of these projectiles hits a target, the target takes an extra (`dice:1d4|noform|avg` (`1d4`)) poison damage, but if the `dice:d20|noform|avg` (`d20`) on the attack roll is a 1 or an even number other than 20, the projectile ceases to be poisonous.

Someone who has proficiency with alchemist's supplies can use the saliva glands from two gnoll brutes or one rampage gnoll to create a potion of growth. The glands must be harvested by someone who has proficiency in the Medicine skill, and doing so requires a successful DC 13 Wisdom ([Medicine](2-Mechanics/CLI/rules/skills.md#Medicine)) check. These glands must be used within 3 days or they go bad, although a gentle repose spell cast on the glands makes them last for that spell's duration. Making the potion requires 1 day of work and reagents worth 25 gp.

The wings of a rampage gnoll can be used to fashion bat wings of flying. Someone who has proficiency in leatherworker's tools can make this cloak in 5 days, using reagents worth 500 gp. Somebody must cast fly on the cloak on three out of the five days of its making. These wings give you a fly speed of only 40 feet, but they can be used once every `dice:1d8|noform|avg` (`1d8`) hours.

## Lore

- **DC 10 Intelligence ([Arcana](2-Mechanics/CLI/rules/skills.md#Arcana)).** Gnolls were once normal humanoids, but they have been mutated by the power of the Beast.  
- **DC 10 Intelligence ([Nature](2-Mechanics/CLI/rules/skills.md#Nature)).** Some gnolls use spikes that grow from their bones, usually the spine, as projectiles. Different gnolls have different mutations, though, and some of these spikes are poisonous. The strongest mutants develop wings and infect the minds of those nearby with bloodthirsty fury.  
- **DC 15 Intelligence ([History](2-Mechanics/CLI/rules/skills.md#History)).** Gnolls form bands along with other mutated creatures to rampage across their region. The gnolls eat the flesh and drink the blood of any living things they kill. They speak to each other in their own language of howls, snarls, and grunts.  

## Statblock

```ad-statblock
title: Beast Gnoll
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/GHLoE/Beast%20Gnoll.webp#token)
*Medium humanoid (gnoll), Chaotic Evil*

- **Armor Class** 11
- **Hit Points** 9 (`2d8`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|13 (+1)|12 (+1)|11 (+0)| 6 (-2)|10 (+0)| 7 (-2)|

- **Proficiency Bonus** +2
- **Saving Throws** ⏤
- **Skills** ⏤
- **Senses** darkvision 60 ft., passive Perception 10
- **Languages** Gnoll
- **Challenge** 1/8

## Traits

***Rampage.*** When the beast gnoll reduces a creature to 0 hit points with a melee attack on its turn, the gnoll can take a bonus action to move up to half its speed and make a bite attack.

## Actions

***Bite.*** *Melee Weapon Attack:* `dice:1d20+3|noform|text(+3)` to hit, reach 5 ft., one target. *Hit:* `dice:1d4+1|noform|avg|text(3)` (`1d4 + 1`) piercing damage.

***Claws.*** *Melee Weapon Attack:* `dice:1d20+3|noform|text(+3)` to hit, reach 5 ft., one target. *Hit:* `dice:1d6+1|noform|avg|text(4)` (`1d6 + 1`) slashing damage.

***Spine Spike.*** *Ranged Weapon Attack:* `dice:1d20+3|noform|text(+3)` to hit, range 20/60 ft., one target. *Hit:* `dice:1d4+1|noform|avg|text(3)` (`1d4 + 1`) piercing damage.
```
^statblock