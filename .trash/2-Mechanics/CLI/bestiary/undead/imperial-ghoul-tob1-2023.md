---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/tob1-2023
- monster/cr/4
- monster/environment/underdark
- monster/size/medium
- monster/type/undead
aliases: ["Imperial Ghoul"]
---
# Imperial Ghoul
*Source: Tome of Beasts 1 (2023 Edition) p. 203*  

*An imperial ghoul stands tall and proud, its gray flesh robust and muscled, and its clothing strangely well kept. Its flickering red eyes have an intelligent, malicious gleam.*

## Shock Troops

Imperial ghouls are the shock troops of the ghoul empire, eager to expand its power and influence. Treated like auxiliaries, they get the most difficult tasks: to engage and hold foes while the darakhul, iron legionnaires, and others outflank them.

## Ambitious Strivers

Many believe that the hunger cults or the necrophagi know some secret of transforming imperial ghouls into iron ghouls. This rumor gives them hope of advancement. Their power over the lesser ghouls and slaves gives them a taste of tyranny. Because they are ambitious and always hungry for power, imperial ghouls are eager to prove themselves as hunters, as warriors, and as spies.

## Immune to Sun

Unlike a standard darakhul, an imperial ghoul does not suffer from sunlight and feels little need to disguise its true appearance.

> [!note] Darakhul Fever
> 
> Spread mainly through bite wounds, this disease makes itself known within 24 hours by swiftly debilitating the infected. An infected creature must make a DC 17 Constitution saving throw after every long rest. On a failed save, the victim takes `dice:4d6|noform|avg|text(14)` (`4d6`) necrotic damage, and its hp maximum is reduced by an amount equal to the damage taken. This reduction lasts until the victim finishes a long rest after the disease is cured. The victim recovers from the disease by making two consecutive successful saving throws. Greater restoration cures the disease, while lesser restoration gives the victim advantage on the next saving throw. Primarily spread among Humanoids, the disease can affect ogres, and therefore other Giants may be susceptible. If a creature dies while infected with darakhul fever, roll a `dice:d20|noform|avg` (`d20`), add the character's Constitution modifier, and find the result on the Adjustment Table below to determine what Undead form the victim's body rises in.
> 
> | Roll | Result |
> |------|--------|
> | 1-9 | None; victim is simply dead |
> | 10-16 | Ghoul |
> | 17-20 | Ghast |
> | 21+ | Darakhul |
> ^roll-result
^darakhul-fever

## Statblock

```ad-statblock
title: Imperial Ghoul
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ToB1-2023/Imperial%20Ghoul.webp#token)
*Medium undead, Lawful Evil*

- **Armor Class** 16 ([breastplate](2-Mechanics/CLI/items/breastplate.md))
- **Hit Points** 93 (`17d8 + 17`)
- **Speed** 30 ft., burrow 15 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|16 (+3)|14 (+2)|12 (+1)|13 (+1)|14 (+2)|14 (+2)|

- **Proficiency Bonus** +2
- **Saving Throws** ⏤
- **Skills** ⏤
- **Senses** darkvision 60 ft., passive Perception 12
- **Damage Immunities** poison
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** Common, Darakhul, Undercommon
- **Challenge** 4

## Traits

***Hungry Dead Nature.*** The ghoul requires no air or sleep.

***Turning Defiance.*** The ghoul and any ghouls within 30 feet of it have advantage on saving throws against effects that turn Undead.

## Actions

***Multiattack.*** The imperial ghoul makes one Bite attack and one Claw attack.

***Bite.*** *Melee Weapon Attack:* `dice:1d20+5|noform|text(+5)` to hit, reach 5 ft., one target. *Hit:* `dice:2d8+3|noform|avg|text(12)` (`2d8 + 3`) piercing damage, and, if the target is a Humanoid, it must succeed on a DC 11 Constitution saving throw or contract the darakhul fever disease.

***Claw.*** *Melee Weapon Attack:* `dice:1d20+5|noform|text(+5)` to hit, reach, one target. *Hit:* `dice:4d6+3|noform|avg|text(17)` (`4d6 + 3`) slashing damage. If the target is a creature other than an elf or Undead, it must succeed on a DC 11 Constitution saving throw or be [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed) for 1 minute. The target can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.

***Light Crossbow.*** *Ranged Weapon Attack:* `dice:1d20+4|noform|text(+4)` to hit, range 80/320 ft., one target. *Hit:* `dice:1d8+2|noform|avg|text(6)` (`1d8 + 2`) piercing damage.
```
^statblock

## Environment

underdark