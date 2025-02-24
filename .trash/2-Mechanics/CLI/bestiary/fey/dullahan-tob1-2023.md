---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/tob1-2023
- monster/cr/11
- monster/environment/any
- monster/environment/forest
- monster/size/large
- monster/type/fey
aliases: ["Dullahan"]
---
# Dullahan
*Source: Tome of Beasts 1 (2023 Edition) p. 151*  

*The black horse strides out of the shadows with its nostrils huffing steam. Its rider, swathed in black leather, raises its arm to reveal not a lantern but its own severed, grinning head.*

Though it appears to be a headless rider astride a black horse, the dullahan is a single creature. The fey spirit takes the shape of a horse rider holding its own head aloft like a lantern, or (more rarely) the form of an ogre cradling its head in one arm.

## Harbingers of Death

Hailing from the darkest of fey courts, the dullahan are macabre creatures that walk hand in hand with death. They sometimes serve powerful fey lords and ladies, riding far and wide in the capacity of a herald, bard, or ambassador. More often than not they carry doom to a wretch who roused their lord's ire.

## Statblock

```ad-statblock
title: Dullahan
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ToB1-2023/Dullahan.webp#token)
*Large fey, Lawful Evil*

- **Armor Class** 17 (natural armor)
- **Hit Points** 178 (`17d10 + 85`)
- **Speed** 60 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|19 (+4)|18 (+4)|20 (+5)|13 (+1)|15 (+2)|17 (+3)|

- **Proficiency Bonus** +4
- **Saving Throws** ⏤
- **Skills** Intimidation +7, Perception +6, Persuasion +7, Survival +6
- **Senses** truesight 60 ft., passive Perception 16
- **Damage Resistances** bludgeoning, piercing, slashing from nonmagical attacks
- **Damage Immunities** necrotic
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened)
- **Languages** Common, Elvish, Sylvan
- **Challenge** 11

## Traits

***Baleful Glare.*** When a creature that can see the eyes of the dullahan's severed head starts its turn within 30 feet of the dullahan, the dullahan can force it to make a DC 17 Wisdom saving throw if the dullahan isn't [incapacitated](2-Mechanics/CLI/rules/conditions.md#Incapacitated) and can see the creature. On a failed save, the creature is [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened) until the start of its next turn. While [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened) in this way, the creature must take the Dash action and move away from the dullahan by the safest available route. A doomed creature that fails this saving throw is [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained) while [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened) instead.

Unless surprised, a creature can avert its eyes to avoid the saving throw at the start of its turn. If the creature does so, it can't see the dullahan until the start of its next turn, when it can avert its eyes again. If the creature looks at the dullahan in the meantime, it must immediately make the save.

***Relentless Advance.*** Moving through difficult terrain doesn't cost the dullahan extra movement, and the dullahan can move across the surface of water as if it were harmless, solid ground.

***Relentless Nature.*** The dullahan doesn't require food, drink, or sleep.

## Actions

***Multiattack.*** The dullahan makes three Spine Whip or Necrotic Bolt attacks. It can replace one attack with a use of Seal the Doom.

***Spine Whip.*** *Melee Weapon Attack:* `dice:1d20+8|noform|text(+8)` to hit, reach 10 ft., one target. *Hit:* `dice:2d6+4|noform|avg|text(11)` (`2d6 + 4`) slashing damage plus `dice:3d6|noform|avg|text(10)` (`3d6`) necrotic damage. If the target is a creature, it must succeed on a DC 17 Constitution saving throw or fall [prone](2-Mechanics/CLI/rules/conditions.md#Prone) as it is wracked with pain.

***Necrotic Bolt.*** *Ranged Spell Attack:* `dice:1d20+7|noform|text(+7)` to hit, range 120 ft., one target. *Hit:* `dice:4d8+3|noform|avg|text(21)` (`4d8 + 3`) necrotic damage.

***Seal the Doom.*** The dullahan points at a creature doomed by Deathly Doom within 40 feet of it that it can see. The creature must make a DC 17 Constitution saving throw. On a failure, the target immediately drops to 0 hp if it is below half its hp maximum. On a success, the target is immune to the dullahan's Seal the Doom for the next 24 hours.

## Bonus Actions

***Deathly Doom.*** The dullahan magically dooms a creature for 1 hour. It can have only one creature doomed at a time. If it dooms another, the effect on the previous target ends. The dullahan knows the direction to the doomed creature as long as both are on the same plane of existence.
```
^statblock

## Environment

any, forest