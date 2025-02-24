---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/ghloe
- monster/cr/2
- monster/size/medium
- monster/type/undead
aliases: ["Oblivion Whistler"]
---
# Oblivion Whistler
*Source: Grim Hollow: Lairs of Etharis p. 27*  

> [!quote]  
> 
> If you hear the strange, low whistling in the darkness, run! They whistle before they strike, striding out of the darkness, hungry for the souls of the living.

## Salvage

There is a 25% chance that an oblivion stalker leaves behind a gemstone when it is defeated. These stones are worth between 10 and 500 gp, depending on the size of the creature. There is a 10% chance that one of these stones acts as a magnet to additional oblivion stalkers, which appear and attack the holder of the gem at midnight during a new moon. A remove curse makes the gemstone safe.

## Lore

- **DC 10 Intelligence ([History](2-Mechanics/CLI/rules/skills.md#History)).** An oblivion stalker is at disadvantage in daylight.  
- **DC 15 Intelligence ([Arcana](2-Mechanics/CLI/rules/skills.md#Arcana)).** An oblivion stalker is vulnerable to radiant damage and resistant to nonmagical weapons.  
- **DC 20 Intelligence ([Religion](2-Mechanics/CLI/rules/skills.md#Religion)).** If an oblivion stalker kills a mortal, it's believed that mortal joins their shadowy ranks.  

> [!note] Customizing Oblivion Stalkers
> 
> Since oblivion stalkers can drain almost any living creature's energy, they can take just about any form. Some oblivion stalkers retain the natural abilities of their original form. For instance, an oblivion stalker that was once a wolf might retain the Pack Tactics trait. Similarly, a boar could possess a version of Charge, draining its prey while adding slashing damage and the possibility of knocking their victim prone.
> 
> Keep one special ability that makes sense for a creature of the stalker's former form without affecting the Challenge of the stalker. Avoid bestowing an oblivion stalker any ability that is magical, grants the stalker a ranged attack, or expands its resistances or immunities.
^customizing-oblivion-stalkers

## Statblock

```ad-statblock
title: Oblivion Whistler
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/GHLoE/Oblivion%20Whistler.webp#token)
*Medium undead, Neutral Evil*

- **Armor Class** 13
- **Hit Points** 33 (`6d8 + 6`)
- **Speed** 40 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|12 (+1)|16 (+3)|13 (+1)|10 (+0)|10 (+0)| 8 (-1)|

- **Proficiency Bonus** +2
- **Saving Throws** ⏤
- **Skills** Stealth +5
- **Senses** darkvision 60 ft., passive Perception 10
- **Damage Vulnerabilities** radiant
- **Damage Resistances** cold; bludgeoning, piercing, slashing from nonmagical attacks
- **Damage Immunities** necrotic, poison
- **Condition Immunities** [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened), [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled), [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed), [petrified](2-Mechanics/CLI/rules/conditions.md#Petrified), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned), [prone](2-Mechanics/CLI/rules/conditions.md#Prone), [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained)
- **Languages** —
- **Challenge** 2

## Traits

***Shadow Stealth.*** While in dim light or darkness, the oblivion whistler can take the Hide action as a bonus action.

***Sunlight Weakness.*** While in sunlight, the oblivion whistler has disadvantage on attack rolls, ability checks, and saving throws.

***Unbearable Whistling.*** Creatures of the oblivion whistler's choice that aren't [deafened](2-Mechanics/CLI/rules/conditions.md#Deafened) and start their turn within 30 feet of the oblivion whistler must make a DC 11 Wisdom saving throw. A target that fails is [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened) until the start of its next turn and unable to hide the distress of hearing the whistling, which is the source of the fear and considered to be within line of sight while the target can hear and is within 30 feet of it. On a successful saving throw, the creature is immune to any oblivion whistler's Unbearable Whistling for 1 hour.

## Actions

***Soul Drain.*** *Melee Weapon Attack:* `dice:1d20+5|noform|text(+5)` to hit, reach 5 ft., one creature. *Hit:* `dice:2d6+3|noform|avg|text(10)` (`2d6 + 3`) necrotic damage, and the target must make a DC 11 Constitution saving throw. On a failure, the target's available Hit Dice are reduced by 1. If this effect reduces the target's Hit Dice to 0, the target falls [unconscious](2-Mechanics/CLI/rules/conditions.md#Unconscious). The target can repeat the saving throw at the end of each of its turns, regaining consciousness on a success. Hit Dice lost this way return at the end of a short rest, in time to spend them to regain hit points.

If an oblivion whistler kills a living creature with this attack when the creature is at 0 Hit Dice, the target's soul is lost to the realm of shadow. This lost soul can be raised from the dead only with mighty magic, such as wish or divine intervention.
```
^statblock