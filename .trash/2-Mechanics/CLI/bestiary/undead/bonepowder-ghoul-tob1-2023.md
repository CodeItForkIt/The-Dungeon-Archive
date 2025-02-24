---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/tob1-2023
- monster/cr/12
- monster/environment/underdark
- monster/size/small
- monster/type/undead
aliases: ["Bonepowder Ghoul"]
---
# Bonepowder Ghoul
*Source: Tome of Beasts 1 (2023 Edition) p. 201*  

*Distilled to nothing but dry, whispering sand and a full set of teeth, this ghoulish creature still hungers for flesh and blood.*

## Starved Into Dust

The bonepowder ghoul is a small and unassuming pile of dust and bone fragments. Ghouls can achieve this powdery form through long starvation, a process that invariably takes decades. Rarely purposefully created, a bonepowder ghoul typically rises from the remnants of a ghoul trapped away from food, becoming animate hunger and hatred.

## Whispering Voices

Though bonepowder ghouls speak, their voices are faint. When they drain life force from living creatures, their dusty forms gain some substance, strengthening their voices enough to cast spells and command allies.

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
title: Bonepowder Ghoul
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ToB1-2023/Bonepowder%20Ghoul.webp#token)
*Small undead, Neutral Evil*

- **Armor Class** 18 (natural armor)
- **Hit Points** 180 (`24d6 + 96`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|10 (+0)|20 (+5)|18 (+4)|19 (+4)|15 (+2)|18 (+4)|

- **Proficiency Bonus** +4
- **Saving Throws** Dexterity +9, Constitution +8, Wisdom +6, Charisma +8
- **Skills** Perception +6, Stealth +9
- **Senses** darkvision 60 ft., passive Perception 16
- **Damage Resistances** cold; lightning; bludgeoning, piercing, slashing from nonmagical attacks
- **Damage Immunities** necrotic, poison
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened), [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** Common, Darakhul, Draconic, Dwarvish
- **Challenge** 12

## Traits

***Amorphous (Dust Form Only).*** The bonepowder ghoul can move through a space as narrow as 1 inch wide without squeezing.

***Hungry Dead Nature.*** The ghoul requires no air or sleep.

***Turning Defiance.*** The bonepowder ghoul and any ghouls within 30 feet of it have advantage on saving throws against effects that turn Undead.

***Spellcasting (Coalesced Form Only).*** The bonepowder ghoul casts one of the following spells, requiring no material components and using Charisma as the spellcasting ability (spell save DC 16):

**At will**: [dispel magic](2-Mechanics/CLI/spells/dispel-magic.md), [mage hand](2-Mechanics/CLI/spells/mage-hand.md), [ray of enfeeblement](2-Mechanics/CLI/spells/ray-of-enfeeblement.md)

**1/day**: [phantasmal killer](2-Mechanics/CLI/spells/phantasmal-killer.md)

**3/day each**: [blindness/deafness](2-Mechanics/CLI/spells/blindness-deafness.md), [fear](2-Mechanics/CLI/spells/fear.md)

## Actions

***Multiattack.*** The bonepowder ghoul makes two Bite attacks. It can replace one Bite attack with a use of Gravedust or Spellcasting. If both Bite attacks hit the same creature, the target must succeed on a DC 17 Constitution saving throw or be [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed) for 1 minute. The target can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.

***Bite.*** *Melee Weapon Attack:* `dice:1d20+9|noform|text(+9)` to hit, reach 5 ft., one target. *Hit:* `dice:3d8+5|noform|avg|text(18)` (`3d8 + 5`) piercing damage plus `dice:2d8|noform|avg|text(9)` (`2d8`) necrotic damage, and the target's Strength score is reduced by `dice:1d4|noform|avg` (`1d4`). The target dies if this reduces its Strength to 0. Otherwise, the reduction lasts until the target finishes a short or long rest. If the target is a Humanoid, it must succeed on a DC 17 Constitution saving throw or contract the darakhul fever disease.

***Gravedust.*** The ghoul projects a 30-foot cone of grave dust. Each creature in the area must succeed on a DC 17 Dexterity saving throw or take `dice:3d8|noform|avg|text(13)` (`3d8`) necrotic damage. If a creature is a Humanoid, it must also succeed on a DC 17 Constitution saving throw or contract the darakhul fever disease.

***Whirlwind (Dust Form Only; Recharge 5-6).*** The ghoul creates a whirlwind of bones and teeth in a 20-foot cube originating from it. Each creature in that area must make a DC 17 Dexterity saving throw. On a failure, a creature takes `dice:10d10|noform|avg|text(55)` (`10d10`) slashing damage, and its Strength score is reduced by `dice:1d6|noform|avg` (`1d6`). The creature dies if this reduces its Strength to 0. Otherwise, the reduction lasts until the target finishes a short or long rest. On a success, a creature takes half the damage and its Strength score isn't reduced.

## Reactions

***Coalesce.*** When a bonepowder ghoul deals necrotic damage with Gravedust to at least one creature that isn't a Construct or Undead, it can magically transform from its dusty form into a coalesced form. Its statistics are the same in each form, except it can speak audibly only in its coalesced form. The coalesced form lasts for a number of minutes equal to the total necrotic damage it dealt with Gravedust to creatures that aren't Constructs or Undead or until the ghoul ends it as a bonus action.
```
^statblock

## Environment

underdark