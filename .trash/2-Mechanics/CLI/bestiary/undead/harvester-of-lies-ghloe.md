---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/ghloe
- monster/cr/9
- monster/size/medium
- monster/type/undead
aliases: ["Harvester of Lies"]
---
# Harvester of Lies
*Source: Grim Hollow: Lairs of Etharis p. 13*  

> [!quote]  
> 
> Don't lie to me, or the harvester will steal your tongue!

## Salvage

If defeated, the harvester's [coat of lies](2-Mechanics/CLI/items/coat-of-lies-ghloe.md) (see Appendix A of Lairs of Etharis) can be claimed.

## Lore

- **DC 10 Intelligence ([History](2-Mechanics/CLI/rules/skills.md#History)).** Harvesters of lies can detect when a lie is uttered from 1 mile away. They are attracted to lies, the more frequent the lies and the more outlandish, the greater the attraction.  
- **DC 15 Intelligence ([Arcana](2-Mechanics/CLI/rules/skills.md#Arcana)).** Harvesters are resistant to nonmagical weapons and necrotic damage, and immune to poison.  
- **DC 20 Intelligence ([Arcana](2-Mechanics/CLI/rules/skills.md#Arcana)).** The harvester wears a coat made of the severed tongues of its victims that allow it to cast several spells.  

## Statblock

```ad-statblock
title: Harvester of Lies
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/GHLoE/Harvester%20of%20Lies.webp#token)
*Medium undead, Neutral Evil*

- **Armor Class** 17 (coat of lies)
- **Hit Points** 91 (`14d8 + 28`)
- **Speed** 40 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|13 (+1)|20 (+5)|14 (+2)|11 (+0)|16 (+3)|15 (+2)|

- **Proficiency Bonus** +4
- **Saving Throws** Dexterity +9, Wisdom +7, Charisma +6
- **Skills** Acrobatics +9, Insight +7, Perception +7, Stealth +13
- **Senses** darkvision 120 ft., passive Perception 17
- **Damage Resistances** necrotic; bludgeoning, piercing, slashing from nonmagical attacks
- **Damage Immunities** poison
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** the languages it knew in life
- **Challenge** 9

## Traits

***Coat of Lies.*** While wearing their specially prepared coat, the harvester's AC is increase by 2 and it can use its innate spellcasting.

***Hear Lies.*** The harvester hears all lies uttered within 1 mile of it and knows the liar's distance and direction while the harvester choses to concentrate.

***Spider Climb.*** The harvester can climb difficult surfaces, including upside down on ceilings, without needing to make an ability check.

***Trackless.*** The harvester leaves no tracks to indicate where it has been or where it's headed.

***Innate Spellcasting.*** The harvester's spellcasting ability is Charisma (spell save DC 14). It can innately cast the following spells, requiring only that the harvester be wearing its coat of lies:

**At will**: [detect thoughts](2-Mechanics/CLI/spells/detect-thoughts.md), [zone of truth](2-Mechanics/CLI/spells/zone-of-truth.md)

**1/day each**: [levitate](2-Mechanics/CLI/spells/levitate.md), [tongues](2-Mechanics/CLI/spells/tongues.md)

**3/day each**: [hold person](2-Mechanics/CLI/spells/hold-person.md), [invisibility](2-Mechanics/CLI/spells/invisibility.md), [misty step](2-Mechanics/CLI/spells/misty-step.md), [silence](2-Mechanics/CLI/spells/silence.md)

## Actions

***Multiattack.*** The harvester makes three attacks, only one of which can be sever tongue.

***Claw.*** *Melee Weapon Attack:* `dice:1d20+9|noform|text(+9)` to hit, reach 5 ft., one target. *Hit:* `dice:2d6+5|noform|avg|text(12)` (`2d6 + 5`) slashing damage. If the target is Medium or smaller, it is [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) (escape DC 17).

***Sever Tongue.*** *Melee Weapon Attack:* `dice:1d20+9|noform|text(+9)` to hit, reach 5 ft., one humanoid [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) by the harvester of lies. *Hit:* `dice:8d6+5|noform|avg|text(33)` (`8d6 + 5`) slashing damage and the target must succeed on a DC 17 Constitution saving throw or have their tongue ripped out. A creature without a tongue cannot speak or cast spells with verbal components. A creature is immune to this effect if it is immune to slashing damage, doesn't have or need a tongue, or has legendary actions.

A tongue can be reattached within 1 hour of being severed with a successful DC 10 Wisdom ([Medicine](2-Mechanics/CLI/rules/skills.md#Medicine)) check, or at can be regrown using magic that replaces lost limbs.
```
^statblock