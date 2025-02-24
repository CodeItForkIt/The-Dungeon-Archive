---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/coa
- monster/cr/20
- monster/size/gargantuan
- monster/type/dragon
aliases: ["Styx Dragon"]
---
# Styx Dragon
*Source: Chains of Asmodeus p. 252*  

One of the only draconic beings that makes its home in the Nine Hells, the Styx dragon is an aquatic creature that lives within the River Styx. The waters of the Styx have no effect on its mental faculties or memories, and their breath weapon replicates the effects of the Styx. Their diet consists mostly of devils foolish enough to wander close to the banks of the Styx, though they prefer mortals and corpses over Fiends. Occasional Styx dragons have been spotted in non-infernal planes, possibly by traveling the Styx to their destination.

## Unusual Dragons

Unlike other Dragons, the scales of the Styx dragon have no effect on their capabilities, and range from darker hues all the way up to chromatic scales, though they always appear muddied. They have no wings and very small limbs, relying primarily on their tails for mobility and combat. Their serpentine body lends itself to muddy nests along the banks of the Styx and quick underwater travel. Good captains know where Styx dragon clutches are along the river, and steer their boats specifically to avoid the creatures.

## Statblock

```ad-statblock
title: Styx Dragon
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/CoA/Styx%20Dragon.webp#token)
*Gargantuan dragon, Chaotic Evil*

- **Armor Class** 17 (natural armor)
- **Hit Points** 296 (`16d20 + 128`)
- **Speed** 30 ft., burrow 20 ft., swim 60 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|27 (+8)|14 (+2)|26 (+8)|19 (+4)|20 (+5)|19 (+4)|

- **Proficiency Bonus** +6
- **Saving Throws** Dexterity +8, Constitution +14, Wisdom +11, Charisma +10
- **Skills** Athletics +21, Insight +11, Perception +11, Survival +17
- **Senses** blindsight 120 ft., passive Perception 21
- **Damage Resistances** damage from spells
- **Damage Immunities** cold, poison
- **Condition Immunities** [blinded](2-Mechanics/CLI/rules/conditions.md#Blinded), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** Draconic, Infernal
- **Challenge** 20

## Traits

***Amphibious.*** The dragon can breathe air and water.

***Stygian Wasting.*** Creatures afflicted with this disease are incapable of regaining hit points in any way until the disease is cured. Additionally, as their flesh starts to rot, a creature with this disease takes `dice:8d8|noform|avg|text(36)` (`8d8`) necrotic damage after each long rest they finish.

***Styx Dweller.*** The dragon is immune to all negative effects from the River Styx.

## Actions

***Multiattack.*** The dragon can use its Frightful Presence. It then makes three attacks using its Bite, Tail, or a combination of the two. It can replace one of the attacks with Constrict.

***Bite.*** *Melee Weapon Attack:* `dice:1d20+14|noform|text(+14)` to hit, reach 5 ft., one target. *Hit:* `dice:2d10+8|noform|avg|text(19)` (`2d10 + 8`) piercing damage plus `dice:2d6|noform|avg|text(7)` (`2d6`) poison damage, and the target must make a DC 19 Constitution saving throw. On a failed save, the target contracts Stygian Wasting.

***Tail.*** *Melee Weapon Attack:* `dice:1d20+14|noform|text(+14)` to hit, reach 10 ft., one target. *Hit:* `dice:2d6+8|noform|avg|text(15)` (`2d6 + 8`) bludgeoning damage. If the target is a Large or smaller creature, it has the [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) condition (escape DC 22). The dragon can't make a Tail attack while a creature is [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) in this way.

***Constrict.*** The dragon tightens its grip on a creature [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) by its tail. The creature takes `dice:3d12+8|noform|avg|text(27)` (`3d12 + 8`) bludgeoning damage, has the [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained) condition until the start of the dragon's next turn, and must make a DC 19 Constitution saving throw. On a failed save, the target contracts Stygian Wasting.

***Frightful Presence.*** Each creature of the dragon's choice that is within 120 feet of the dragon must succeed on a DC 18 Wisdom saving throw or have the [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened) condition for 1 minute. A creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success. If a creature's saving throw is successful or the effect ends for it, the creature is immune to the dragon's Frightful Presence for the next 24 hours.

***Stygian Breath (Recharge 5-6).*** The dragon exhales poisonous Styx water in a 60-foot-long, 10-foot-wide line. Each creature in that line must make a DC 19 Dexterity saving throw, taking `dice:12d8|noform|avg|text(54)` (`12d8`) poison damage on a failed save, or half as much on a successful one. Creatures that fail the save contract Stygian Wasting.

## Legendary Actions

***Detect.*** The dragon makes a Wisdom ([Perception](2-Mechanics/CLI/rules/skills.md#Perception)) check.

***Tail Attack.*** The dragon makes a Tail attack. If a creature is already [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled), the dragon may use Constrict instead.

***Death Throw (Costs 3 Actions).*** If the dragon has successfully [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained) a creature with the Constrict ability, it may throw them up to 100 feet away. When it lands, the creature takes `dice:6d6|noform|avg|text(21)` (`6d6`) bludgeoning damage and must make a DC 18 Constitution saving throw. On a failed save, the creature has the [unconscious](2-Mechanics/CLI/rules/conditions.md#Unconscious) condition for 10 minutes.
```
^statblock