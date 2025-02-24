---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/psi
- monster/cr/5
- monster/size/medium
- monster/type/undead/shapechanger
aliases: ["Elder Vampire: All Abilities"]
---
# Elder Vampire: All Abilities
*Source: Plane Shift: Innistrad p. 17*  

```ad-statblock
title: Elder Vampire: All Abilities
*Medium undead (shapechanger), Neutral Evil*

- **Armor Class** 15 (natural armor)
- **Hit Points** 82 (`11d8 + 33`)
- **Speed** 30 ft., fly 30 ft.

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

***Shapechanger.*** If the vampire isn't in sunlight or running water, it can use its action to polymorph into a Tiny bat or a Medium cloud of mist, or back into its true form.

While in bat form, the vampire can't speak, its walking speed is 5 feet, and it has a flying speed of 30 feet. Its statistics, other than its size and speed, are unchanged. Anything it is wearing transforms with it, but nothing it is carrying does. It reverts to its true form if it dies.

While in mist form, the vampire can't take any actions, speak, or manipulate objects. It is weightless, has a flying speed of 20 feet, can hover, and can enter a hostile creature's space and stop there. In addition, if air can pass through a space, the mist can do so without squeezing, and it can't pass through water. It has advantage on Strength, Dexterity, and Constitution saving throws, and it is immune to all nonmagical damage, except the damage it takes from sunlight.

***Gorger.*** The vampire has advantage on melee attack rolls, but attack rolls against it have advantage.

***Cleric Spellcasting.*** > [!note]
> The [Priest](2-Mechanics/CLI/bestiary/humanoid/priest.md) has been used as an example Cleric.

The vampire is a 5th-level spellcaster. Its spellcasting ability is Wisdom (spell save DC 13, `dice:1d20+5|noform|text(+5)` to hit with spell attacks). The vampire has the following cleric spells prepared:

**Cantrips (at will)**: [light](2-Mechanics/CLI/spells/light.md), [sacred flame](2-Mechanics/CLI/spells/sacred-flame.md), [thaumaturgy](2-Mechanics/CLI/spells/thaumaturgy.md)

**1st level (4 slots)**: [cure wounds](2-Mechanics/CLI/spells/cure-wounds.md), [guiding bolt](2-Mechanics/CLI/spells/guiding-bolt.md), [sanctuary](2-Mechanics/CLI/spells/sanctuary.md)

**2nd level (3 slots)**: [lesser restoration](2-Mechanics/CLI/spells/lesser-restoration.md), [spiritual weapon](2-Mechanics/CLI/spells/spiritual-weapon.md)

**3rd level (2 slots)**: [dispel magic](2-Mechanics/CLI/spells/dispel-magic.md), [spirit guardians](2-Mechanics/CLI/spells/spirit-guardians.md)

***Wizard Spellcasting.*** > [!note]
> The [Mage](2-Mechanics/CLI/bestiary/humanoid/mage.md) has been used as an example Wizard.

The vampire is a 9th-level spellcaster. Its spellcasting ability is Intelligence (spell save DC 14, `dice:1d20+6|noform|text(+6)` to hit with spell attacks). The vampire has the following wizard spells prepared:

**Cantrips (at will)**: [fire bolt](2-Mechanics/CLI/spells/fire-bolt.md), [light](2-Mechanics/CLI/spells/light.md), [mage hand](2-Mechanics/CLI/spells/mage-hand.md), [prestidigitation](2-Mechanics/CLI/spells/prestidigitation.md)

**1st level (4 slots)**: [detect magic](2-Mechanics/CLI/spells/detect-magic.md), [mage armor](2-Mechanics/CLI/spells/mage-armor.md), [magic missile](2-Mechanics/CLI/spells/magic-missile.md), [shield](2-Mechanics/CLI/spells/shield.md)

**2nd level (3 slots)**: [misty step](2-Mechanics/CLI/spells/misty-step.md), [suggestion](2-Mechanics/CLI/spells/suggestion.md)

**3rd level (3 slots)**: [counterspell](2-Mechanics/CLI/spells/counterspell.md), [fireball](2-Mechanics/CLI/spells/fireball.md), [fly](2-Mechanics/CLI/spells/fly.md)

**4th level (3 slots)**: [greater invisibility](2-Mechanics/CLI/spells/greater-invisibility.md), [ice storm](2-Mechanics/CLI/spells/ice-storm.md)

**5th level (1 slots)**: [cone of cold](2-Mechanics/CLI/spells/cone-of-cold.md)

## Actions

***Multiattack.*** The vampire makes two attacks, only one of which can be a bite attack.

***Claws.*** *Melee Weapon Attack:* `dice:1d20+6|noform|text(+6)` to hit, reach 5 ft., one creature. *Hit:* `dice:2d4+3|noform|avg|text(8)` (`2d4 + 3`) slashing damage. Instead of dealing damage, the vampire can grapple the target (escape DC 13).

***Bite.*** *Melee Weapon Attack:* `dice:1d20+6|noform|text(+6)` to hit, reach 5 ft., one willing creature, or a creature that is [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) by the vampire, [incapacitated](2-Mechanics/CLI/rules/conditions.md#Incapacitated), or [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained). *Hit:* `dice:1d6+3|noform|avg|text(6)` (`1d6 + 3`) piercing damage plus `dice:2d6|noform|avg|text(7)` (`2d6`) necrotic damage. The target's hit point maximum is reduced by an amount equal to the necrotic damage taken, and the vampire regains hit points equal to that amount. The reduction lasts until the target finishes a long rest. The target dies if this effect reduces its hit point maximum to 0.

***Vampiric Glamer.*** The vampire obscures its form with mind-affecting magic that makes others perceive it as a beautiful human of the same size and shape. The illusion ends if the vampire takes a bonus action to end it or if the vampire dies. A creature that can see the vampire can take an action to visually inspect it, ending the mental effect on itself and seeing the vampire's true form with a successful DC 20 Wisdom ([Perception](2-Mechanics/CLI/rules/skills.md#Perception)) check.

***Aura of Silence.*** The vampire shrouds itself in a cloak of silence to a radius of 2 feet. Within that radius, the effect is the same as the [silence](2-Mechanics/CLI/spells/silence.md) spell.

***Charm.*** The vampire targets one humanoid it can see within 30 feet of it. If the target can see the vampire, the target must succeed on a DC 17 Wisdom saving throw against this magic or be [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed) by the vampire. The [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed) target regards the vampire as a trusted friend to be heeded and protected. Although the target isn't under the vampire's control, it takes the vampire's requests or actions in the most favorable way it can, and it is a willing target for the vampire's bite attack.

Each time the vampire or the vampire's companions do anything harmful to the target, it can repeat the saving throw, ending the effect on itself on a success. Otherwise, the effect lasts 24 hours or until the vampire is destroyed, is on a different plane of existence than the target, or takes a bonus action to end the effect.
```
^statblock