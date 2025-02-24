---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/tob1-2023
- monster/cr/4
- monster/environment/desert
- monster/environment/grassland
- monster/size/medium
- monster/type/undead
aliases: ["Edimmu"]
---
# Edimmu
*Source: Tome of Beasts 1 (2023 Edition) p. 154*  

*An evil wind swirls out of the desert, parching those it touches and whispering evil plans.*

## Bitter Exiles

Desert and plains tribes often exile their criminals to wander as outcasts. A banished criminal who dies of thirst sometimes rises as an edimmu, a hateful undead that blames all sentient living beings for its fate.

## Rise Again

Unless its body is found and given a proper burial, an edimmu is nearly impossible to destroy. Edimmus rarely venture more than a mile from their remains, but they sometimes follow prey they have cursed to seal the creature's fate. Once that creature is slain, they return to the site of their demise.

## Statblock

```ad-statblock
title: Edimmu
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ToB1-2023/Edimmu.webp#token)
*Medium undead, Chaotic Evil*

- **Armor Class** 15 (natural armor)
- **Hit Points** 75 (`10d8 + 30`)
- **Speed** 0 ft., fly 60 ft. (hover)

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
| 1 (-5)|19 (+4)|16 (+3)|12 (+1)|18 (+4)|13 (+1)|

- **Proficiency Bonus** +2
- **Saving Throws** ⏤
- **Skills** ⏤
- **Senses** blindsight 60 ft. (blind beyond this radius), passive Perception 14
- **Damage Resistances** acid; cold; fire; lightning; thunder; bludgeoning, piercing, slashing from nonmagical attacks
- **Damage Immunities** necrotic, poison
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened), [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled), [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed), [petrified](2-Mechanics/CLI/rules/conditions.md#Petrified), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned), [prone](2-Mechanics/CLI/rules/conditions.md#Prone), [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained), [unconscious](2-Mechanics/CLI/rules/conditions.md#Unconscious)
- **Languages** understands Common but can't speak
- **Challenge** 4

## Traits

***Incorporeal Movement.*** The edimmu can move through other creatures and objects as if they were difficult terrain. It takes `dice:1d10|noform|avg|text(5)` (`1d10`) force damage if it ends its turn inside an object.

***Rejuvenation.*** If destroyed, an edimmu rises again in `dice:2d4|noform|avg` (`2d4`) days, regaining all its hp and becoming active again. When the edimmu rises, it appears within 5 feet of its remains. Only burying its mortal remains in consecrated or hallowed ground prevents this trait from functioning.

***Undead Nature.*** The edimmu doesn't require air, food, drink, or sleep.

***Water Siphon.*** The edimmu has advantage on attack rolls against creatures made of or gaining power from magical water, such as water elementals, water jinnborn, water genies, and sorcerers with water-based origins. In addition, such creatures have disadvantage on the saving throw against the edimmu's Draining Touch and Multiattack.

## Actions

***Multiattack.*** The edimmu makes two Draining Touch attacks. If both attacks hit one creature that isn't a Construct or Undead, the target must succeed on a DC 14 Constitution saving throw or suffer one level of [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion). A creature that fails this saving throw by 5 or more is also [stunned](2-Mechanics/CLI/rules/conditions.md#Stunned) until the end of its next turn.

***Draining Touch.*** *Melee Spell Attack:* `dice:1d20+6|noform|text(+6)` to hit, reach 5 ft., one creature. *Hit:* `dice:2d8+4|noform|avg|text(13)` (`2d8 + 4`) necrotic damage, and the target must succeed on a DC 14 Constitution saving throw or its hp maximum is reduced by an amount equal to the damage taken. This reduction lasts until the creature finishes a long rest after drinking 1 pint of water. The target dies if this effect reduces its hp maximum to 0.
```
^statblock

## Environment

desert, grassland