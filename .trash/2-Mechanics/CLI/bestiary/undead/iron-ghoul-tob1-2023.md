---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/tob1-2023
- monster/cr/5
- monster/environment/underdark
- monster/size/medium
- monster/type/undead
aliases: ["Iron Ghoul"]
---
# Iron Ghoul
*Source: Tome of Beasts 1 (2023 Edition) p. 204*  

*A vicious-looking ghoul carries a cruel glaive, its forearms stained with dried blood. Its glowing, rust-colored eyes penetrate with a calculating stare of restrained hunger.*

## Backbone of the Legions

Iron ghouls and ghasts are the elite members of the imperial legions, acting as officers, non-commissioned officers, and standard-bearers. They feed from the slave pits and march on the orders of the darakhul nobility.

## Fond of Uniforms

Iron ghouls are proud of their status and uniforms. Their standard breastplates and open-faced helms are black iron with brass trim, and the helm's crest is often a ruby-dyed fan of bat wings or carrion beetle bristles to indicate their authority.

## Tooth and Bone Weaponry

Many items of an iron ghoul's gear are decorated with inlaid bone or set with teeth, much as pearls might be used for weapons crafted elsewhere.

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
title: Iron Ghoul
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ToB1-2023/Iron%20Ghoul.webp#token)
*Medium undead, Lawful Evil*

- **Armor Class** 16 ([breastplate](2-Mechanics/CLI/items/breastplate.md))
- **Hit Points** 143 (`22d8 + 44`)
- **Speed** 30 ft., burrow 20 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|18 (+4)|16 (+3)|14 (+2)|14 (+2)|14 (+2)|14 (+2)|

- **Proficiency Bonus** +3
- **Saving Throws** ⏤
- **Skills** ⏤
- **Senses** darkvision 60 ft., passive Perception 12
- **Damage Immunities** poison
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** Common, Darakhul, Undercommon
- **Challenge** 5

## Traits

***Hungry Dead Nature.*** The ghoul requires no air or sleep.

***Turning Defiance.*** The iron ghoul and any ghouls within 30 feet of it have advantage on saving throws against effects that turn Undead.

## Actions

***Multiattack.*** The iron ghoul makes one Bite attack and one Claw attack, or it makes three Glaive attacks.

***Bite.*** *Melee Weapon Attack:* `dice:1d20+7|noform|text(+7)` to hit, reach 5 ft., one target. *Hit:* `dice:3d8+4|noform|avg|text(17)` (`3d8 + 4`) piercing damage. If the target is a Humanoid, it must succeed on a DC 13 Constitution saving throw or contract the darakhul fever disease.

***Claw.*** *Melee Weapon Attack:* `dice:1d20+7|noform|text(+7)` to hit, reach 5 ft., one target. *Hit:* `dice:4d6+4|noform|avg|text(18)` (`4d6 + 4`) slashing damage. If the target is a creature other than an elf or Undead, it must succeed on a DC 13 Constitution saving throw or be [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed) for 1 minute. The target can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.

***Glaive.*** *Melee Weapon Attack:* `dice:1d20+7|noform|text(+7)` to hit, reach 10 ft., one target. *Hit:* `dice:1d10+4|noform|avg|text(9)` (`1d10 + 4`) slashing damage.

***Heavy Crossbow.*** *Ranged Weapon Attack:* `dice:1d20+6|noform|text(+6)` to hit, range 100/400, one target. *Hit:* `dice:1d10+3|noform|avg|text(8)` (`1d10 + 3`) piercing damage.
```
^statblock

## Environment

underdark