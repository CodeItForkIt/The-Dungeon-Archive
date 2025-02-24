---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/toa
- monster/cr/4
- monster/size/medium
- monster/type/undead
aliases: ["Withers"]
---
# Withers
*Source: Tomb of Annihilation p. 145*  

Before he was turned into an undead creature, Withers was an Omuan engineer named Gorra. Like all of Omu's citizens, Gorra was enslaved and put to work constructing the tomb. When Acererak sacrificed his workers to their own dungeon, Gorra's traps performed the best.

```ad-statblock
title: Withers
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ToA/Withers.webp#token)
*Medium undead, Neutral Evil*

- **Armor Class** 14 ([studded leather](2-Mechanics/CLI/items/studded-leather-armor.md))
- **Hit Points** 45 (`6d8 + 18`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|15 (+2)|14 (+2)|16 (+3)|16 (+3)|13 (+1)|15 (+2)|

- **Proficiency Bonus** +2
- **Saving Throws** ⏤
- **Skills** Perception +3, Stealth +4
- **Senses** darkvision 60 ft., passive Perception 13
- **Damage Resistances** necrotic; bludgeoning, piercing, slashing from nonmagical attacks that aren't silvered
- **Damage Immunities** poison
- **Condition Immunities** [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** the languages he knew in life
- **Challenge** 4

## Traits

***Special Equipment.*** Withers carries the [amulet of the black skull](2-Mechanics/CLI/items/amulet-of-the-black-skull-toa.md).

***Sunlight Sensitivity.*** While in sunlight, Withers has disadvantage on attack rolls, as well as on Wisdom ([Perception](2-Mechanics/CLI/rules/skills.md#Perception)) checks that rely on sight.

***Spellcasting.*** Withers is a 9th-level spellcaster. His spellcasting ability is Intelligence (spell save DC 13, `dice:1d20+5|noform|text(+5)` to hit with spell attacks). Withers has the following wizard spells prepared:

**Cantrips (at will)**: [acid splash](2-Mechanics/CLI/spells/acid-splash.md), [mage hand](2-Mechanics/CLI/spells/mage-hand.md), [minor illusion](2-Mechanics/CLI/spells/minor-illusion.md), [prestidigitation](2-Mechanics/CLI/spells/prestidigitation.md)

**1st level (4 slots)**: [detect magic](2-Mechanics/CLI/spells/detect-magic.md), [expeditious retreat](2-Mechanics/CLI/spells/expeditious-retreat.md), [feather fall](2-Mechanics/CLI/spells/feather-fall.md), [thunderwave](2-Mechanics/CLI/spells/thunderwave.md)

**2nd level (4 slots)**: [darkness](2-Mechanics/CLI/spells/darkness.md), [hold person](2-Mechanics/CLI/spells/hold-person.md), [rope trick](2-Mechanics/CLI/spells/rope-trick.md)

**3rd level (3 slots)**: [dispel magic](2-Mechanics/CLI/spells/dispel-magic.md), [lightning bolt](2-Mechanics/CLI/spells/lightning-bolt.md)

**4th level (3 slots)**: [blight](2-Mechanics/CLI/spells/blight.md), [wall of fire](2-Mechanics/CLI/spells/wall-of-fire.md)

**5th level (1 slots)**: [telekinesis](2-Mechanics/CLI/spells/telekinesis.md)

## Actions

***Multiattack.*** Withers makes two longsword attacks. He can use his Life Drain in place of one longsword attack.

***Life Drain.*** *Melee Weapon Attack:* `dice:1d20+4|noform|text(+4)` to hit, reach 5 ft., one creature. *Hit:* `dice:1d6+2|noform|avg|text(5)` (`1d6 + 2`) necrotic damage. The target must succeed on a DC 13 Constitution saving throw or its hit point maximum is reduced by an amount equal to the damage taken. This reduction lasts until the target finishes a long rest. The target dies if this effect reduces its hit point maximum to 0.

A humanoid slain by this attack rises 24 hours later as a zombie under the Withers's control, unless the humanoid is restored to life or its body is destroyed. Withers can have no more than twelve zombies under its control at one time.

***Longsword.*** *Melee Weapon Attack:* `dice:1d20+4|noform|text(+4)` to hit, reach 5 ft., one target. *Hit:* `dice:1d8+2|noform|avg|text(6)` (`1d8 + 2`) slashing damage, or `dice:1d10+2|noform|avg|text(7)` (`1d10 + 2`) slashing damage if used with two hands.
```
^statblock