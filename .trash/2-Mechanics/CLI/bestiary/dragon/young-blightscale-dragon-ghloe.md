---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/ghloe
- monster/cr/8
- monster/size/large
- monster/type/dragon/cursed
aliases: ["Young Blightscale Dragon"]
---
# Young Blightscale Dragon
*Source: Grim Hollow: Lairs of Etharis p. 82*  

> [!quote]  
> 
> Dragons are rare, so seeing one is terrifying. Seeing one rotting before your eyes as it approaches? Mind-shattering!

## Salvage

A claw from a young or older blightscale dragon can be fashioned into a dagger of venom. Doing so requires proficiency with smith's tools or woodcarver's tools, 5 days of work, and other materials worth 1,000 gp.

Blood and other fluids of a blightscale dragon can be harvested and used to offset the shadowsteel component when bestowing a curse of foul blight. A wyrmling is worth 250 gp, a young dragon 750 gp, an adult 1,500 gp, and an ancient dragon 3,000 gp.

## Lore

- **DC 15 Wisdom ([History](2-Mechanics/CLI/rules/skills.md#History)).** A blightscale dragon is a dragon that has been subjected to a powerful curse.  
- **DC 15 Wisdom ([Medicine](2-Mechanics/CLI/rules/skills.md#Medicine)).** A blightscale dragon is immune to necrotic damage and poison. Its breath weapon is a swarm of poisonous insects and gas.  
- **DC 20 Intelligence ([Arcana](2-Mechanics/CLI/rules/skills.md#Arcana)).** The curse on the blightscale dragon makes it exude a toxic, cursed gas when it dies, possibly passing on a portion of the curse.  

## A Blightscale Dragon's Lair

Blightscale dragons create temporary lairs in which they suffer the curse in rage and despair. Whether a cave or a building, the dragon pulls easy entrances down so that none can view it in its agonized state. The air inside is rank, and those who draw a full breath become nauseated. The curse attracts insects that construct colonies resembling yellow, congealed lumps.

## Statblock

```ad-statblock
title: Young Blightscale Dragon
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/GHLoE/Young%20Blightscale%20Dragon.webp#token)
*Large dragon (cursed), Neutral Evil*

- **Armor Class** 18 (natural armor)
- **Hit Points** 152 (`16d10 + 64`)
- **Speed** 40 ft., fly 80 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|19 (+4)|12 (+1)|19 (+4)|12 (+1)|11 (+0)| 8 (-1)|

- **Proficiency Bonus** +3
- **Saving Throws** Dexterity +4, Wisdom +3, Charisma +2
- **Skills** Insight +3, Perception +6, Stealth +4
- **Senses** blindsight 30 ft., darkvision 120 ft., passive Perception 16
- **Damage Immunities** necrotic, poison
- **Condition Immunities** [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** Draconic and one national language
- **Challenge** 8

## Traits

***Accursed Death.*** When the dragon dies, it exudes a cloud of sickening, accursed gas. Each creature within 20 ft. of the dragon must succeed on a DC 15 Constitution saving throw or become [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned) for 1 minute. A creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success. However, a creature that fails two of these saving throws becomes cursed. A creature cursed in this way takes `dice:3d6|noform|avg|text(10)` (`3d6`) necrotic damage and can't regain hit points, and the creature's hit point maximum is reduced by an amount equal to the necrotic damage taken. Every 24 hours, the cursed creature takes `dice:3d6|noform|avg|text(10)` (`3d6`) necrotic damage with similar reduction to the creature's hit point maximum. If the curse reduces the target's hit point maximum to 0, the target dies.

## Actions

***Multiattack.*** The dragon makes three attacks: one with its bite and two with its claws.

***Bite.*** *Melee Weapon Attack:* `dice:1d20+7|noform|text(+7)` to hit, reach 10 ft., one target. *Hit:* `dice:2d8+4|noform|avg|text(13)` (`2d8 + 4`) piercing damage and `dice:2d4|noform|avg|text(5)` (`2d4`) necrotic damage.

***Claw.*** *Melee Weapon Attack:* `dice:1d20+7|noform|text(+7)` to hit, reach 5 ft., one target. *Hit:* `dice:2d4+4|noform|avg|text(9)` (`2d4 + 4`) slashing damage and `dice:1d4|noform|avg|text(2)` (`1d4`) poison damage.

***Swarm Breath (Recharge 5-6).*** The dragon exhales a 30-foot cone of poisonous insects and vile gas. Each creature in that area must make a DC 15 Constitution saving throw, taking `dice:4d6|noform|avg|text(14)` (`4d6`) piercing damage and `dice:8d6|noform|avg|text(28)` (`8d6`) poison damage on a failed save, or half as much damage on a successful one.
```
^statblock