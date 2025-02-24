---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/hwcs
- monster/cr/1
- monster/size/large
- monster/type/beast
aliases: ["Mountain Lion"]
---
# Mountain Lion
*Source: Humblewood Campaign Setting p. 184*  

> [!quote]  
> 
> "The results of their roar can have quite an impact on adventurers."

The mountain lions of Humblewood's Crest Mountains are more than the mere beasts travelers may mistake them for. Covered in rocky protrusions that serve to protect as well as camouflage them, mountain lions possess special powers as a result of their ties to the elemental earth of their territory.

## Mountain Stalker

Mountain lions live and hunt in their craggy mountain homes. They are natural climbers and prefer to ambush unsuspecting prey rather than engage in prolonged chases across the treacherous cliffs. A pride of mountain lions is led and protected by a large female. Males compete for the right to mate, and work together as a hunting party. While not as adept at pack hunting as wolves, a few mountain lions working in tandem can take down dangerous creatures of unusual size, including basilisks and griffons.

## Roar of the Earth

Owing to the magic of the elemental earth, mountain lions can gain limited control over nearby rocks with their roar. Using this ability, they can cause rockslides to hinder their prey's escape or inflict critical damage. The ability takes a great deal of energy, so many mountain lions use it sparingly, knowing it will be some time before they can call upon it again. 

## Statblock

```ad-statblock
title: Mountain Lion
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/HWCS/Mountain%20Lion.webp#token)
*Large beast, Unaligned*

- **Armor Class** 15 (natural armor)
- **Hit Points** 37 (`5d10 + 10`)
- **Speed** 40 ft., climb 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|17 (+3)|15 (+2)|14 (+2)| 3 (-4)|14 (+2)| 6 (-2)|

- **Proficiency Bonus** +2
- **Saving Throws** ⏤
- **Skills** Perception +4, Stealth +4
- **Senses** passive Perception 14
- **Languages** —
- **Challenge** 1

## Traits

***Keen Smell.*** The Mountain Lion has advantage on Wisdom ([Perception](2-Mechanics/CLI/rules/skills.md#Perception)) checks that rely on smell.

***Pounce (Lion).*** If the Mountain Lion moves at least 20 feet toward a creature and then hits it with a claw attack on the same turn, that target must succeed on a DC 13 Strength saving throw or be knocked [prone](2-Mechanics/CLI/rules/conditions.md#Prone). The mountain lion can make a bite attack against a [prone](2-Mechanics/CLI/rules/conditions.md#Prone) target as a bonus action.

## Actions

***Bite.*** *Melee Weapon Attack:* `dice:1d20+5|noform|text(+5)` to hit, reach 5 ft., one target. *Hit:* `dice:1d10+3|noform|avg|text(8)` (`1d10 + 3`) piercing damage.

***Claw.*** *Melee Weapon Attack:* `dice:1d20+5|noform|text(+5)` to hit, reach 5 ft., one target. *Hit:* `dice:1d8+3|noform|avg|text(7)` (`1d8 + 3`) slashing damage.

***Call Avalanche (Recharges after a Short or Long Rest).*** With a mystic roar, the mountain lion can call down the very rocks. So long as it is in mountainous terrain, it can use its action to cause a rockslide to fall within a 15-foot-radius of a space it can see within 60 feet. Creatures in this area must make a DC 12 Dexterity saving throw, taking `dice:3d8|noform|avg|text(13)` (`3d8`) bludgeoning damage on a failure and half as much on a success.
```
^statblock