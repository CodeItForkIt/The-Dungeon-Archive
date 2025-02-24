---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/hwcs
- monster/cr/6
- monster/size/huge
- monster/type/beast
aliases: ["Wakewyrm"]
---
# Wakewyrm
*Source: Humblewood Campaign Setting p. 187*  

Wakewyrms are massive reptiles that have aspects of both snakes and eels. On rare occasions they've been spotted close to the shores of the Talongrip Coast, though many are quick to dismiss these accounts. Their name originates from the powerful tidal waves their bodies cause, which pose a considerable threat to nearby vessels.

## Ocean Tales

Despite their size, wakewyrms are elusive, able to hide within the vast expanse of the ocean. The rarity of this creature has bred many rumors about the exact nature of wakewyrms. All sailors know at least a few stories about bizarre creatures of the sea, including fantastical accounts of wakewyrms that lurk in the ocean's gloomy depths, able to sink an entire fleet of ships. Such tales are more often fabrications than not, as few have actually encountered these creatures.

## Devourer from the Deeps

Wakewyrms are more than a 100 feet long and weigh over 1000 tons. Their lashing tails, snapping jaws, and huge bodies can deal significant damage to a ship's hull, though they prefer to swallow sailors whole, swiftly pulling them into the fathoms below with hardly more than a splash. Filling their gullet with as many creatures as possible, wakewyrms let their strong stomachs take care of their meals. While a fine tactic for devouring fish or other large marine creatures, wakewyrms that swallow adventurers whole sometimes find the snack too much to handle.

Though wakewyrms rarely encounter sailing vessels as they cross the ocean looking for food, the results are often violent. Afterwards, all that remains is nothing but a derelict phantom ship, found wrecked against the rocks of distant shores.

## Statblock

```ad-statblock
title: Wakewyrm
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/HWCS/Wakewyrm.webp#token)
*Huge beast, Unaligned*

- **Armor Class** 16 (natural armor)
- **Hit Points** 136 (`13d12 + 52`)
- **Speed** 20 ft., swim 50 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|20 (+5)|14 (+2)|18 (+4)| 3 (-4)|12 (+1)| 3 (-4)|

- **Proficiency Bonus** +3
- **Saving Throws** ⏤
- **Skills** ⏤
- **Senses** passive Perception 11
- **Languages** —
- **Challenge** 6

## Traits

***Hold Breath.*** The Wakewyrm can hold its breath for 1 hour.

## Actions

***Multiattack.*** The wakewyrm makes two attacks, one with its bite and one with its tail, or two bite attacks.

***Bite.*** *Melee Weapon Attack:* `dice:1d20+8|noform|text(+8)` to hit, reach 20 ft., one target. *Hit:* `dice:3d6+5|noform|avg|text(15)` (`3d6 + 5`) piercing damage. The target must succeed on a DC 16 Strength saving throw or be [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) (escape DC 16). The wakewyrm can only grapple one creature at a time, and cannot make bite attacks against other creatures while it has a creature [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled).

***Tail.*** *Melee Weapon Attack:* `dice:1d20+8|noform|text(+8)` to hit, reach 25 ft., one target. *Hit:* `dice:3d8+5|noform|avg|text(18)` (`3d8 + 5`) bludgeoning damage.

***Swallow.*** The wakewyrm makes a bite attack against a Large or smaller creature it is grappling, and if the attack hits the target is swallowed, and the grapple ends. The swallowed target is [blinded](2-Mechanics/CLI/rules/conditions.md#Blinded) and [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained), it has total cover against attacks and other effects outside the wakewyrm, and it takes `dice:3d6|noform|avg|text(11)` (`3d6`) acid damage at the start of each of the wakewyrm's turns. If the wakewyrm takes 18 or more points of damage from a creature inside of it, the wakewyrm must succeed on a DC 15 Constitution saving throw at the end of that turn or regurgitate all swallowed creatures, which fall [prone](2-Mechanics/CLI/rules/conditions.md#Prone) in a space within 10 feet of the wakewyrm. If the wakewyrm dies, a swallowed creature is no longer [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained) by it, and it can escape from the corpse using 20 feet of movement. After death, internal gasses keep the wakewyrm's body afloat for several hours, before it begins to sink gradually to a watery grave.
```
^statblock