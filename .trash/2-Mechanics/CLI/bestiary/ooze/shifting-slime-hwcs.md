---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/hwcs
- monster/cr/1-2
- monster/size/large
- monster/type/ooze
aliases: ["Shifting Slime"]
---
# Shifting Slime
*Source: Humblewood Campaign Setting p. 187*  

Deep in the murky marshes of the Mokk Fields, where water lays stagnant and the stench of decay permeates all, the worlds of life and death intertwine. Within this ominous mire lurk some of the most unusual natural predators in Humblewood. Collectively known as "slimes", these oozes move slowly through the muck, well-camouflaged by the dark and pungent waters, waiting to devour any hapless being that wanders within reach.

Slimes are easily provoked, and while it isn't difficult to outrun one, some who have strayed into a slime's territory only find out too late that they have been detected. Fortunately for many swampland travelers, slimes have a slow metabolism, and can go without feeding for long periods.

In addition to being an important part of the ecosystem, many slimes are either naturally magical, or yield organic materials which are in high demand among mages, scholars, and researchers. While slime hunting is a dangerous undertaking, the perch of Winnowing Reach was built on the labor of so-called "slime-wranglers", whose skill collecting valuable residue from live slimes is directly responsible for transforming the once minor outpost into a thriving site for scholarly innovation.

Three main types of slimes have been classified, but as magical creatures with strange properties, it's speculated that more elusive slime species might exist somewhere in the remote swamps. The three documented types are: [caustic slimes](2-Mechanics/CLI/bestiary/ooze/caustic-slime-hwcs.md), [shifting slimes](2-Mechanics/CLI/bestiary/ooze/shifting-slime-hwcs.md), and [sticky slimes](2-Mechanics/CLI/bestiary/ooze/sticky-slime-hwcs.md).

## Shifting Slime

A type of large and fluid ooze, shifting slimes have an iridescent hue to them which seems to shift as they move. According to slime-wranglers, they can use magical energy to create an eerie bioluminescence. Shifting slime residue is a highly sought after potent reagent, but it is hard to come by. Despite their size, these slimes are elusive and generally spend their time below ground where visibility is low. They can be quite difficult to locate when they conceal themselves in the subterranean darkness, though these strange creatures are known to leave trails of bioluminescent residue to lure in prey.

### Adaptive Defenses

This type of slime can harness magical energy within its form. Shifting slimes absorb and store magic passively over time, but are also capable of absorbing magical jolts from spells. It is unclear exactly how much energy they can store, or for how long.

Shifting slimes can develop a temporary immunity to various types of magic after exposure. This immunity in turn makes it exceptionally difficult to destroy the slimes with a single type of magical energy. Luckily for slime-wranglers, shifting slimes are only capable of containing one energy type at a time.

### Manifestation of Stored Power

After absorbing magical energy, these slimes will change color based on the type of power absorbed. Because of the rarity of shifting slimes, only a handful of people have witnessed these changes. But, over generations, skilled slime-wranglers have managed to record which color a shifting slime will turn in response to different types of magic.

## Statblock

```ad-statblock
title: Shifting Slime
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/HWCS/Shifting%20Slime.webp#token)
*Large ooze, Unaligned*

- **Armor Class** 9
- **Hit Points** 31 (`3d10 + 15`)
- **Speed** 20 ft., climb 20 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|14 (+2)| 8 (-1)|20 (+5)| 1 (-5)| 6 (-2)| 1 (-5)|

- **Proficiency Bonus** +2
- **Saving Throws** ⏤
- **Skills** ⏤
- **Senses** blindsight 60 ft. (blind beyond this radius), passive Perception 8
- **Damage Immunities** Special; see Adaptive ability
- **Condition Immunities** [blinded](2-Mechanics/CLI/rules/conditions.md#Blinded), [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [deafened](2-Mechanics/CLI/rules/conditions.md#Deafened), [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened), [prone](2-Mechanics/CLI/rules/conditions.md#Prone)
- **Languages** —
- **Challenge** 1/2

## Traits

***Amorphous.*** The Caustic Slime can move through a space as narrow as 1 inch wide without squeezing.

***Spider Climb.*** The Caustic Slime can climb difficult surfaces, including upside down on ceilings, without needing to make an ability check.

## Actions

***Psuedopod.*** *Melee Weapon Attack:* `dice:1d20+4|noform|text(+4)` to hit, reach 5 ft., one target. *Hit:* `dice:1d6+2|noform|avg|text(5)` (`1d6 + 2`) acid damage. The target is [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) (escape DC 13). Until this grapple ends, the target is [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained) and the shifting slime can't make a pseudopod attack against another target.

***Swallow.*** The shifting slime makes one pseudopod attack against a target it is grappling that is at least one size smaller than itself. If the attack hits, the target is swallowed, and the grapple ends. The swallowed target is [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained), it has total cover against attacks and other effects outside the shifting slime, and it must make a DC 13 Constitution saving throw at the start of each of its turns taking `dice:1d6|noform|avg|text(3)` (`1d6`) acid damage on a failure. If the shifting slime used its adaptive ability to become immune to a damage type, the damage dealt to the target on a failed save becomes that type instead. The shifting slime can have only one target swallowed at a time.

If the shifting slime dies, a swallowed creature is no longer [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained) by it, and may move freely as the body of the slime quivers and neutralizes into an inert puddle of goo.

## Reactions

***Split.*** When a slime that is Medium or larger and has 10 or more hit points is hit with slashing damage, it splits into two new slimes. Each new slime has hit points equal to half the original slime's, rounded down. New slimes are one size smaller than the previous size. New shifting slimes each have the same damage type immunity as their parent slime and retain the Adaptive ability.

***Adaptive.*** Each time the slime is hit by a spell that deals damage, it can become immune to that damage type for 1 hour. When the slime changes the damage type it's immune to, its color changes based on the table on the below. The slime can only be immune to one damage type at a time. Normally, shifting slimes are iridescent, shimmering with all the colors of the rainbow.

| Damage Type | Slime Color |
|-------------|-------------|
| Acid | Lime Green |
| Cold | Ice Blue |
| Fire | Bright Crimson |
| Force | Clear |
| Lightning | Vibrant Yellow |
| Necrotic | Dark Black |
| Poison | Dark Green |
| Psychic | Bright Violet |
| Radiant | Warm Orange |
| Thunder | Bright White |
^damage-type-slime-color
```
^statblock