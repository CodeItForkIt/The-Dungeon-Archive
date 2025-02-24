---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/psi
- monster/cr/5
- monster/size/medium
- monster/type/undead
aliases: ["Elder Vampire: Spellcasting—Cleric"]
---
# Elder Vampire: Spellcasting—Cleric
*Source: Plane Shift: Innistrad p. 17*  

```ad-statblock
title: Elder Vampire: Spellcasting—Cleric
*Medium undead, Neutral Evil*

- **Armor Class** 15 (natural armor)
- **Hit Points** 82 (`11d8 + 33`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|16 (+3)|16 (+3)|16 (+3)|11 (+0)|10 (+0)|12 (+1)|

- **Proficiency Bonus** +3
- **Saving Throws** Dexterity +6, Wisdom +3
- **Skills** Perception +3, Stealth +6
- **Senses** darkvision 60 ft., passive Perception 13
- **Damage Resistances** necrotic; bludgeoning, piercing, slashing from nonmagical attacks not made with living wood weapons
- **Languages** Common
- **Challenge** 5

## Traits

***Regeneration.*** The vampire regains 10 hit points at the start of its turn if it has at least 1 hit point. If the vampire takes radiant damage or damage from holy water, this trait doesn't function at the start of the vampire's next turn.

***Spellcasting.*** > [!note]
> The [Priest](2-Mechanics/CLI/bestiary/humanoid/priest.md) has been used as an example Cleric.

The vampire is a 5th-level spellcaster. Its spellcasting ability is Wisdom (spell save DC 13, `dice:1d20+5|noform|text(+5)` to hit with spell attacks). The vampire has the following cleric spells prepared:

**Cantrips (at will)**: [light](2-Mechanics/CLI/spells/light.md), [sacred flame](2-Mechanics/CLI/spells/sacred-flame.md), [thaumaturgy](2-Mechanics/CLI/spells/thaumaturgy.md)

**1st level (4 slots)**: [cure wounds](2-Mechanics/CLI/spells/cure-wounds.md), [guiding bolt](2-Mechanics/CLI/spells/guiding-bolt.md), [sanctuary](2-Mechanics/CLI/spells/sanctuary.md)

**2nd level (3 slots)**: [lesser restoration](2-Mechanics/CLI/spells/lesser-restoration.md), [spiritual weapon](2-Mechanics/CLI/spells/spiritual-weapon.md)

**3rd level (2 slots)**: [dispel magic](2-Mechanics/CLI/spells/dispel-magic.md), [spirit guardians](2-Mechanics/CLI/spells/spirit-guardians.md)

## Actions

***Multiattack.*** The vampire makes two attacks, only one of which can be a bite attack.

***Claws.*** *Melee Weapon Attack:* `dice:1d20+6|noform|text(+6)` to hit, reach 5 ft., one creature. *Hit:* `dice:2d4+3|noform|avg|text(8)` (`2d4 + 3`) slashing damage. Instead of dealing damage, the vampire can grapple the target (escape DC 13).

***Bite.*** *Melee Weapon Attack:* `dice:1d20+6|noform|text(+6)` to hit, reach 5 ft., one willing creature, or a creature that is [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) by the vampire, [incapacitated](2-Mechanics/CLI/rules/conditions.md#Incapacitated), or [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained). *Hit:* `dice:1d6+3|noform|avg|text(6)` (`1d6 + 3`) piercing damage plus `dice:2d6|noform|avg|text(7)` (`2d6`) necrotic damage. The target's hit point maximum is reduced by an amount equal to the necrotic damage taken, and the vampire regains hit points equal to that amount. The reduction lasts until the target finishes a long rest. The target dies if this effect reduces its hit point maximum to 0.

***Vampiric Glamer.*** The vampire obscures its form with mind-affecting magic that makes others perceive it as a beautiful human of the same size and shape. The illusion ends if the vampire takes a bonus action to end it or if the vampire dies. A creature that can see the vampire can take an action to visually inspect it, ending the mental effect on itself and seeing the vampire's true form with a successful DC 20 Wisdom ([Perception](2-Mechanics/CLI/rules/skills.md#Perception)) check.

***Aura of Silence.*** The vampire shrouds itself in a cloak of silence to a radius of 2 feet. Within that radius, the effect is the same as the [silence](2-Mechanics/CLI/spells/silence.md) spell.
```
^statblock