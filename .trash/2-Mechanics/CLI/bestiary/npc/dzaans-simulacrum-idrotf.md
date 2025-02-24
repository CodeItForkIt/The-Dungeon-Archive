---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/idrotf
- monster/cr/1
- monster/size/medium
- monster/type/construct
aliases: ["Dzaan's Simulacrum"]
---
# Dzaan's Simulacrum
*Source: Icewind Dale: Rime of the Frostmaiden p. 270*  

Unbeknownst to his executioners, Dzaan had used a spell scroll of simulacrum to create a copy of himself. This simulacrum dwells in the sunken Netherese spire, waiting for its creator to return.

The simulacrum, which looks and acts like Dzaan, has half of Dzaan's hit points and can't regain expended spell slots. It has wasted its 3rd-level spell slots trying to reach Dzaan with [sending](2-Mechanics/CLI/spells/sending.md) spells, to no avail, and has expended other spell slots to help it survive the perils of the spire. It uses its remaining spell slots sparingly.

The sunken Netherese tower contains a special room that can transform the simulacrum into a real person—or any magical illusion into the real thing, for that matter. If this change occurs, the simulacrum effectively becomes a clone of Dzaan, authentic in every way.

```ad-statblock
title: Dzaan's Simulacrum
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/IDRotF/Dzaan%27s%20Simulacrum.webp#token)
*Medium construct, Lawful Evil*

- **Armor Class** 10
- **Hit Points** 24 (`9d8 + 9`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|10 (+0)|11 (+0)|12 (+1)|16 (+3)|13 (+1)|15 (+2)|

- **Proficiency Bonus** +2
- **Saving Throws** Intelligence +5, Wisdom +3
- **Skills** Arcana +5, Deception +4, History +5
- **Senses** passive Perception 11
- **Languages** Abyssal, Common, Giant, Infernal
- **Challenge** 1

***Spellcasting.*** The simulacrum is a 9th-level spellcaster. Its spellcasting ability is Intelligence (spell save DC 13, `dice:1d20+5|noform|text(+5)` to hit with spell attacks). It has the following wizard spells prepared:

**Cantrips (at will)**: [acid splash](2-Mechanics/CLI/spells/acid-splash.md)*, [light](2-Mechanics/CLI/spells/light.md), [minor illusion](2-Mechanics/CLI/spells/minor-illusion.md), [shocking grasp](2-Mechanics/CLI/spells/shocking-grasp.md)*

**1st level (2 slots)**: [detect magic](2-Mechanics/CLI/spells/detect-magic.md), [disguise self](2-Mechanics/CLI/spells/disguise-self.md), [magic missile](2-Mechanics/CLI/spells/magic-missile.md)*

**2nd level (2 slots)**: [invisibility](2-Mechanics/CLI/spells/invisibility.md), [levitate](2-Mechanics/CLI/spells/levitate.md), [phantasmal force](2-Mechanics/CLI/spells/phantasmal-force.md)

*See "Actions" below.

## Actions

***Shocking Grasp (Cantrip).*** *Melee Spell Attack:* `dice:1d20+5|noform|text(+5)` to hit, reach 5 ft., one creature (the attack roll has advantage if the target is wearing armor made of metal). *Hit:* `dice:2d8|noform|avg|text(9)` (`2d8`) lightning damage, and the target can't take reactions until the start of its next turn.

***Acid Splash (Cantrip).*** The simulacrum hurls a bubble of acid at one creature it can see within 60 feet of it, or at two such creatures that are within 5 feet of each other. A target must succeed on a DC 13 Dexterity saving throw or take `dice:2d6|noform|avg|text(7)` (`2d6`) acid damage.

***Magic Missile (1st-Level Spell; Requires a Spell Slot).*** The simulacrum creates three darts of magical force. Each dart unerringly strikes one creature the simulacrum can see within 120 feet of it, dealing `dice:1d4+1|noform|avg|text(3)` (`1d4 + 1`) force damage. If the simulacrum casts this spell using a 2nd-level spell slot, it creates one more dart.
```
^statblock