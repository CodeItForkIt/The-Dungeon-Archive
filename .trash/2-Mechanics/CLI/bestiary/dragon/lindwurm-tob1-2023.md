---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/tob1-2023
- monster/cr/6
- monster/environment/arctic
- monster/environment/underwater
- monster/size/large
- monster/type/dragon
aliases: ["Lindwurm"]
---
# Lindwurm
*Source: Tome of Beasts 1 (2023 Edition) p. 255*  

*Coiling like a living corkscrew and moving with a scraping hiss, this serpentine creature skates nimbly across ice on long curving claws, maw agape and stinking of a hundred graves.*

## Swift and Smooth as Ice

Lindwurms have long bodies and crocodilian jaws, but they skitter overland on spindly limbs. Their talons are long and curved, acting as skates or short skis when moving over ice. Few things are swifter on the ice.

## Sea Hunters

In the wild, lindwurms hunt in groups, looking for breaching whales, seals, or incautious fishermen. They enjoy surrounding and surprising foes. With their considerable cunning, they may skate by their prey at speed, snapping a bite as they pass or snatching up prey with their constricting tails.

## Statblock

```ad-statblock
title: Lindwurm
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ToB1-2023/Lindwurm.webp#token)
*Large dragon, Neutral Evil*

- **Armor Class** 15
- **Hit Points** 136 (`16d10 + 48`)
- **Speed** 40 ft., swim 20 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|18 (+4)|20 (+5)|16 (+3)| 6 (-2)|12 (+1)| 8 (-1)|

- **Proficiency Bonus** +3
- **Saving Throws** Strength +7, Dexterity +8, Constitution +6
- **Skills** Acrobatics +8, Athletics +7, Perception +4, Stealth +8
- **Senses** darkvision 60 ft., tremorsense 120 ft., passive Perception 14
- **Damage Vulnerabilities** fire
- **Damage Immunities** cold
- **Condition Immunities** [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed), [unconscious](2-Mechanics/CLI/rules/conditions.md#Unconscious)
- **Languages** Draconic
- **Challenge** 6

## Traits

***Ice Walk.*** The lindwurm can move across icy surfaces without needing to make an ability check. Additionally, difficult terrain composed of ice or snow doesn't cost it extra movement.

***Sure-Footed Skater.*** While the lindwurm is on snow or ice, it has advantage on Strength and Dexterity saving throws made against effects that would knock it [prone](2-Mechanics/CLI/rules/conditions.md#Prone).

## Actions

***Multiattack.*** The lindwurm makes one Bite attack and two Claw attacks. It can replace its Bite attack with one Constrict attack.

***Bite.*** *Melee Weapon Attack:* `dice:1d20+8|noform|text(+8)` to hit, reach 10 ft., one target. *Hit:* `dice:2d10+5|noform|avg|text(16)` (`2d10 + 5`) piercing damage. If the target is a creature, it must succeed on a DC 15 Constitution saving throw or contract a disease and be [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned) until the disease is cured. At the end of each long rest, the diseased creature must repeat the saving throw. On a failure, the creature suffers one level of [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion) and doesn't regain expended Hit Dice from the rest. On a success, the creature's [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion) level decreases by one, and it regains expended Hit Dice as normal from the rest. If a successful saving throw reduces the diseased creature's level of [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion) below 1, the creature recovers from the disease, ending it.

***Claw.*** *Melee Weapon Attack:* `dice:1d20+8|noform|text(+8)` to hit, reach 5 ft., one target. *Hit:* `dice:2d6+5|noform|avg|text(12)` (`2d6 + 5`) slashing damage.

***Constrict.*** *Melee Weapon Attack:* `dice:1d20+8|noform|text(+8)` to hit, reach 10 ft., one target. *Hit:* `dice:2d8+5|noform|avg|text(14)` (`2d8 + 5`) bludgeoning damage, and the target is [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) (escape DC 15). Until this grapple ends, the target is [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained), and the lindwurm can't Constrict another target.
```
^statblock

## Environment

arctic, underwater