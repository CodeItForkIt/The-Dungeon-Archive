---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/ghloe
- monster/cr/3
- monster/size/large
- monster/type/aberration
aliases: ["Skinweaver"]
---
# Skinweaver
*Source: Grim Hollow: Lairs of Etharis p. 30*  

> [!quote]  
> 
> I don't brook with tanners no longer. If ya' know what's good for you, ya' won't ask me why.

## Salvage

Skinweavers collect valuable artwork and other items that display their erudition and refinement. They're never without their custom-made suits of bespoke leather armor. This leather is so finely crafted that a suit of armor stitched from a skinweaver's own suit is better than almost any other tanner's creations.

If a proficient armorer or leather worker uses a skinweaver's suit to create a humanoid suit of light armor and succeeds on a successful DC 15 Dexterity ([Nature](2-Mechanics/CLI/rules/skills.md#Nature)) check, the armor acts as [+1 leather armor](2-Mechanics/CLI/items/1-armor.md) and can be donned or doffed as a standard action. This process takes 24 hours and requires 250 gp of other components.

## Lore

- **DC 10 Intelligence ([Arcana](2-Mechanics/CLI/rules/skills.md#Arcana)).** A skinweaver is resistant to fire damage because of its leathery skin and armor.  
- **DC 15 Intelligence ([History](2-Mechanics/CLI/rules/skills.md#History)).** A skinweaver's terrifying appearance can scare an opponent multiple times in the same fight.  

## Statblock

```ad-statblock
title: Skinweaver
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/GHLoE/Skinweaver.webp#token)
*Large aberration, Chaotic Evil*

- **Armor Class** 17 (natural & tailored leather)
- **Hit Points** 68 (`8d10 + 24`)
- **Speed** 30 ft., climb 15 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|12 (+1)|14 (+2)|16 (+3)|14 (+2)|13 (+1)|18 (+4)|

- **Proficiency Bonus** +2
- **Saving Throws** ⏤
- **Skills** Stealth +4
- **Senses** darkvision 60 ft., passive Perception 11
- **Damage Resistances** fire
- **Languages** any three languages
- **Challenge** 3

## Traits

***Supernaturally Sharp.*** Skinweaver's tanning knives overcome slashing damage resistance (though not immunity).

***Shocking Visage.*** Any humanoid that starts its turn within 30 feet of the skinweaver and can see it must make a DC 11 Wisdom saving throw. On a failed save, the creature is [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened) until the end of the creature's next turn). Whether a creature succeeds or fails, it cannot be affected by this ability again until it loses sight of the skinweaver (as when the skinweaver moves behind total cover or successfully hides).

## Actions

***Multiattack.*** The skinweaver makes two tanning knife attacks or one tanning knife and one web whip attack.

***Tanning Knife.*** *Melee Weapon Attack:* `dice:1d20+4|noform|text(+4)` to hit, reach 5 ft., one target. *Hit:* `dice:2d8+2|noform|avg|text(11)` (`2d8 + 2`) slashing damage.

***Web Whip.*** *Ranged Weapon Attack:* Attack: `dice:1d20+4|noform|text(+4)` to hit, reach 25 ft., one target. *Hit:* `dice:2d4+2|noform|avg|text(7)` (`2d4 + 2`) piercing damage, and the target is pulled up to 20 feet toward the skinweaver.

***Web Net (Recharge 5-6).*** *Ranged Weapon Attack:* `dice:1d20+4|noform|text(+4)` to hit, range 30/60 ft., one creature. *Hit:* The target is [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained) by leathery webbing. As an action, the [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained) target can attempt a DC 13 Strength check, bursting the webbing on a success. The webbing can also be attacked and destroyed (AC 10; hp 10; vulnerability to slashing damage; immunity to bludgeoning, poison, and psychic damage).
```
^statblock