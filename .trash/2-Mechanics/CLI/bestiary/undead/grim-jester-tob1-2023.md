---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/tob1-2023
- monster/cr/11
- monster/environment/any
- monster/size/medium
- monster/type/undead
aliases: ["Grim Jester"]
---
# Grim Jester
*Source: Tome of Beasts 1 (2023 Edition) p. 224*  

*A skeletal cadaver bedecked in the motley attire of a fool capers about while making jokes that mock mortality.*

## Amusing Death

When a jester on its deathbed moves an evil death god to laughter, the fool sometimes gains a reprieve as a grim jester. Their purpose is to bring an end to mortal lives in a gruesome, comic, and absurd manner. As long as such jesters keep the death god amused, their continued unlife is assured.

## Grisly Humor

A grim jester's jokes are not funny to their victims, but they offer a grim finality in combat. A killing joke might be absurd or sheer braggadocio, while others might be high-flown. Grim jesters are famous for grim, bitter mockery, but such humor rarely entertains mortals.

## Randomness

Grim jesters enjoy randomness and often get their hands on wands of wonder and scrolls of chaos magic. Beware the grim jester with a deck of many things—they are quite talented in pulling cards whose magic then applies to foes and spectators.

## Statblock

```ad-statblock
title: Grim Jester
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ToB1-2023/Grim%20Jester.webp#token)
*Medium undead, Chaotic Evil*

- **Armor Class** 18 (natural armor)
- **Hit Points** 136 (`16d8 + 64`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|14 (+2)|22 (+6)|18 (+4)|16 (+3)|16 (+3)|20 (+5)|

- **Proficiency Bonus** +4
- **Saving Throws** Dexterity +10, Constitution +8, Charisma +9
- **Skills** Acrobatics +10, Deception +9, Perception +7, Performance +9, Sleight of Hand +10, Stealth +10
- **Senses** darkvision 120 ft., passive Perception 17
- **Damage Resistances** cold
- **Damage Immunities** necrotic; poison; bludgeoning, piercing, slashing from nonmagical attacks
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened), [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** Abyssal, Celestial, Common, Gnomish, telepathy 120 ft.
- **Challenge** 11

## Traits

***Last Laugh.*** Unless it is destroyed in a manner amusing to the god of death that created it, the grim jester gains a new body in `dice:1d20|noform|avg` (``) days, regaining all its hp and becoming active again. The new body appears in a place of the god's choosing.

***Mock the Dying.*** Death saving throws made within 60 feet of the grim jester have disadvantage.

***Turn Resistance.*** The grim jester has advantage on saving throws against any effect that turns undead.

***Undead Nature.*** The grim jester doesn't require air, food, drink, or sleep.

***Spellcasting.*** The grim jester casts one of the following spells, requiring no components and using Charisma as the spellcasting ability (spell save DC 17):

**At will**: [disguise self](2-Mechanics/CLI/spells/disguise-self.md), [grease](2-Mechanics/CLI/spells/grease.md)

**1/day each**: [mislead](2-Mechanics/CLI/spells/mislead.md), [seeming](2-Mechanics/CLI/spells/seeming.md)

**3/day each**: [magic mouth](2-Mechanics/CLI/spells/magic-mouth.md) (as an action), [mirror image](2-Mechanics/CLI/spells/mirror-image.md)

## Actions

***Multiattack.*** The grim jester can use its Killing Joke. It then makes two Necrotic Claw attacks. It can replace one attack with a use of Spellcasting.

***Necrotic Claw.*** *Melee Spell Attack:* `dice:1d20+9|noform|text(+9)` to hit, range 5 ft., one target. *Hit:* `dice:2d8+5|noform|avg|text(14)` (`2d8 + 5`) slashing damage plus `dice:4d6|noform|avg|text(14)` (`4d6`) necrotic damage.

***Killing Joke.*** The grim jester tells an ancient, nihilistic joke to one creature it can see within 60 feet of it. The target must succeed on a DC 17 Wisdom saving throw or fall [prone](2-Mechanics/CLI/rules/conditions.md#Prone) in a fit of laughter, becoming [incapacitated](2-Mechanics/CLI/rules/conditions.md#Incapacitated) and unable to stand up for 1 minute. A creature that fails this saving throw by 5 or more is reduced to 0 hp instead. The [incapacitated](2-Mechanics/CLI/rules/conditions.md#Incapacitated) target can repeat the saving throw at the end of each of its turns, taking `dice:4d6|noform|avg|text(14)` (`4d6`) necrotic damage on a failed save or ending the effect on itself on a success.

## Bonus Actions

***Joker's Shuffle (Recharge 6).*** The grim jester exchanges locations with a Medium or smaller creature it can see within 60 feet of it. The jester and target each teleport to the other's space, and each becomes covered in a magical illusion to look and sound like the other. A creature must take an action to visually inspect an illusion and succeed on a DC 19 Intelligence ([Investigation](2-Mechanics/CLI/rules/skills.md#Investigation)) check to discern that the jester and target are disguised. The illusions last for 1 minute, until the jester dies, or until the jester dismisses them as a bonus action.
```
^statblock

## Environment

any