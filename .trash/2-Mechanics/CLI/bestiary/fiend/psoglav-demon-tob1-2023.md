---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/tob1-2023
- monster/cr/7
- monster/environment/planar
- monster/size/large
- monster/type/fiend/demon
aliases: ["Psoglav Demon"]
---
# Psoglav Demon
*Source: Tome of Beasts 1 (2023 Edition) p. 86*  

*An immense creature sniffs at the air, its singular eye glowing with malice.*

## Paid in Souls and Memories

These demonic creations are bred for protection, which they provide for a select few. The price for their guardianship is always high and never in coin. They demand everything from memories to souls in exchange for their services.

## Fond of Trophies

Psoglav demons carry recent kills along with them as grisly toys, and they often wear strings of scalps or ears as trophies. They do not mind the stench, and enjoy gnawing bones as a pastime, the larger and more durable the better.

## Shadow Stealers

The psoglav has a single, menacing eye that is capable of commanding a creature's shadow to separate from its owner and follow the psoglav. The psoglav's command of the shadow is tenuous, however, and the shadow returns to its owner within a few days. Psoglav demons sometimes use this to sow further fear, allowing the shadow to return and letting the victim believe the psoglav has moved on, only for the psoglav to show up days later to finish the kill.

## Statblock

```ad-statblock
title: Psoglav Demon
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ToB1-2023/Psoglav%20Demon.webp#token)
*Large fiend (demon), Chaotic Evil*

- **Armor Class** 17 (natural armor)
- **Hit Points** 115 (`11d10 + 55`)
- **Speed** 40 ft., fly 60 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|21 (+5)|23 (+6)|20 (+5)|16 (+3)|19 (+4)|18 (+4)|

- **Proficiency Bonus** +3
- **Saving Throws** Dexterity +9, Constitution +8, Wisdom +7, Charisma +7
- **Skills** Acrobatics +9, Intimidation +7, Perception +7, Stealth +9
- **Senses** blindsight 30 ft., darkvision 60 ft., passive Perception 17
- **Damage Resistances** cold, fire, lightning
- **Damage Immunities** poison
- **Condition Immunities** [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** Abyssal, Common, telepathy 60 ft.
- **Challenge** 7

## Traits

***Magic Resistance.*** The psoglav has advantage on saving throws against spells and other magical effects.

***Magic Weapons.*** The psoglav's weapon attacks are magical.

## Actions

***Multiattack.*** The psoglav makes three Bite attacks.

***Bite.*** *Melee Weapon Attack:* `dice:1d20+8|noform|text(+8)` to hit, reach 5 ft., one target. *Hit:* `dice:2d12+5|noform|avg|text(18)` (`2d12 + 5`) piercing damage.

***Invisibility.*** The psoglav magically turns [invisible](2-Mechanics/CLI/rules/conditions.md#Invisible) until it attacks or uses Shadow-Stealing Ray, or until its [concentration](2-Mechanics/CLI/rules/conditions.md#Concentration) ends (as if concentrating on a spell). Any equipment the psoglav wears or carries is [invisible](2-Mechanics/CLI/rules/conditions.md#Invisible) with it.

***Shadow-Stealing Ray (Recharge 5-6).*** The psoglav emits a beam from its single eye at one creature it can see within 60 feet of it. The target must make a DC 15 Constitution saving throw. On a failure, the target is pushed up to 20 feet away from the psoglav, and its shadow becomes a creature under the psoglav's control for 24 hours or until the shadow is reduced to 0 hp. On a success, the target is pushed up to 10 feet away from the psoglav and its shadow isn't stolen. Each controlled shadow uses the statistics of a shadow, except it can't create shadows from killing Humanoids. The psoglav can have no more than five shadows under its control at a time. The shadow becomes permanently under the psoglav's control if the shadow's original owner dies.

If a shadow's original owner died within the past minute, the psoglav can command (no action required) the shadow to inhabit and control the body, using the owner's statistics, proficiencies, and class features. A shadow inhabiting a body in this way can't cast spells or activate magic items the owner possessed, and it loses its Amorphous, Shadow [Stealth](2-Mechanics/CLI/rules/skills.md#Stealth), and Sunlight Weakness traits while inhabiting the body. The shadow can inhabit or exit the body as a bonus action. The shadow can inhabit the body for up to 24 hours after the creature died, after which time it is ejected and can't inhabit the body again.

If a creature's saving throw is successful or its shadow is returned to it, the creature is immune to the Shadow-Stealing Ray of all psoglav demons for the next 24 hours.

## Bonus Actions

***Shadow Jump (3/Day).*** While in shadows, dim light, or darkness, the psoglav disappears into the darkness and reappears in an unoccupied space it can see within 60 feet.
```
^statblock

## Environment

planar