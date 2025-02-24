---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/tdcsr
- monster/cr/8
- monster/environment/forest
- monster/environment/underdark
- monster/size/large
- monster/type/fiend
aliases: ["Demonfeed Spider"]
---
# Demonfeed Spider
*Source: Tal'Dorei Campaign Setting Reborn p. 237*  

> [!quote] A quote from Orac Wioda  
> 
> It was poor guidance that left us wandering through that sulfurous nest of web and ash, but it was cruel fate that woke the matron beast and her brood of burning blood. The only reason I stand before you today is because I had the wisdom to run.

These monstrous spiders, the spawn of the divine Spider Queen, lurk in the darkest recesses of the world. They have gorged themselves on the ichor of demons since the earliest days of the "Calamity", when demons were slain in such quantity that the subterranean depths were awash with their foul blood.

## Monstrosities Transformed

Demonfeed spiders are terrible fiends as a result of having supped upon the remains of demons, but all are descended from the overlarge spiders that haunt caverns and forests across Tal'Dorei. As such, most are native to the Material Plane, so that once killed, they are slain forever—unlike fiends that are simply banished to their home plane.

## Endless Hunger

No sustenance is more delectable to a demonfeed spider than the ichor remaining behind after a demon has been slain on the Material Plane. However, in the absence of such remains, they will sate themselves on the fluids of any living creature.

## Toxic Blood

The terrible poison of spiders, when mixed with the vile ichor of demons, becomes the demonfeed spider's most potent weapon. When its chitinous hide is pierced and its blood begins to flow, the spider can expel arcing sprays of caustic blood that seep into the exposed flesh of its attackers.

## Alignment

Chaotic evil.

## Statblock

```ad-statblock
title: Demonfeed Spider
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/TDCSR/Demonfeed%20Spider.webp#token)
*Large fiend, Chaotic Evil*

- **Armor Class** 16 (natural armor)
- **Hit Points** 75 (`10d10 + 20`)
- **Speed** 40 ft., climb 40 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|16 (+3)|18 (+4)|15 (+2)| 6 (-2)|10 (+0)| 6 (-2)|

- **Proficiency Bonus** +3
- **Saving Throws** Dexterity +7
- **Skills** Perception +3, Stealth +7
- **Senses** darkvision 120 ft., passive Perception 13
- **Damage Resistances** cold, fire, lightning
- **Damage Immunities** poison
- **Condition Immunities** [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** —
- **Challenge** 8

## Traits

***Spider Climb.*** The spider can climb difficult surfaces, including upside down on ceilings, without needing to make an ability check.

***Web Walker.*** The spider ignores movement restrictions caused by webbing.

## Actions

***Multiattack.*** The spider makes two melee attacks: one with its bite and one with its stinger; or the spider can make one attack with its web spinner followed by a melee attack.

***Bite.*** *Melee Weapon Attack:* `dice:1d20+7|noform|text(+7)` to hit, reach 5 ft., one target. *Hit:* `dice:1d10+3|noform|avg|text(8)` (`1d10 + 3`) piercing damage, and the target must make a DC 14 Constitution saving throw. On a failed save, the target takes `dice:6d8|noform|avg|text(27)` (`6d8`) poison damage and is [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned) for 1 minute. On a successful save, the target takes half as much damage and isn't [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned). If this poison damage reduces the target to 0 hit points, the target is stable but [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned) for 1 hour, even after regaining hit points, and is [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed) while [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned) in this way.

***Stinger.*** *Melee Weapon Attack:* `dice:1d20+7|noform|text(+7)` to hit, reach 5 ft., one target. *Hit:* `dice:1d12+3|noform|avg|text(9)` (`1d12 + 3`) piercing damage, and the target must succeed on a DC 14 Constitution saving throw or be [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed) for 1 minute. The target can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.

***Web Spinner.*** *Ranged Weapon Attack:* `dice:1d20+7|noform|text(+7)` to hit, reach 40 ft., one target. *Hit:*  The target is pulled 40 feet toward the spider and is [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) (escape DC 14). The spider can [grapple](2-Mechanics/CLI/rules/actions.md#Grapple) only one creature at a time in this way. As an action, the spider can cocoon a creature it has [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) in webbing, causing it to be [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained) and ending the [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) condition.

## Reactions

***Arterial Spray.*** When the spider takes damage while below half its hit point maximum, it can spray poisonous blood in a 15-foot cone. Each creature in the area must make a DC 14 Constitution saving throw. On a failed save, a creature takes `dice:3d8|noform|avg|text(13)` (`3d8`) poison damage and is [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned) for 1 minute. On a successful save, the creature takes half as much damage and isn't [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned). If this poison damage reduces a creature to 0 hit points, the creature is stable but [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned) for 1 hour, even after regaining hit points, and is [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed) while [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned) in this way.
```
^statblock

## Environment

forest, underdark