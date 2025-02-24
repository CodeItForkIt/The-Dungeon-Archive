---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/hat-tg
- monster/cr/15
- monster/size/medium
- monster/type/humanoid/wizard
aliases: ["Sofina"]
---
# Sofina
*Source: Honor Among Thieves: Thieves' Gallery*  

Sofina is a Red Wizard of Thay, an elite practitioner of magic with ties to Thay's tyrannical magocracy. Sofina specializes in necromancy. Death magic and fear are both tools in her arsenal.

As Red Wizards are shunned outside Thay, Sofina conceals her affiliations and coldly rebuffs any who seek her friendship. A canny operator, she has patiently moved her pieces into place, and her grand designs now begin to take shape.

```ad-statblock
title: Sofina
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/HAT-TG/Sofina.webp#token)
*Medium humanoid (wizard), Neutral Evil*

- **Armor Class** 14
- **Hit Points** 161 (`19d8 + 76`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|12 (+1)|14 (+2)|18 (+4)|20 (+5)|14 (+2)| 8 (-1)|

- **Proficiency Bonus** +5
- **Saving Throws** Intelligence +10, Wisdom +7
- **Skills** Arcana +10, History +10, Insight +7
- **Senses** passive Perception 12
- **Damage Resistances** necrotic
- **Languages** Abyssal, Common, Draconic, Infernal, Thayan
- **Challenge** 15

## Traits

***Special Equipment.*** Sofina wears a magic robe that grants her a +2 bonus to AC and a +1 bonus to saving throws (included above).

***Spellcasting.*** Sofina casts one of the following spells, using Intelligence as the spellcasting ability (spell save DC 18):

**At will**: [mage hand](2-Mechanics/CLI/spells/mage-hand.md), [message](2-Mechanics/CLI/spells/message.md), [prestidigitation](2-Mechanics/CLI/spells/prestidigitation.md)

**1/day each**: [Evard's black tentacles](2-Mechanics/CLI/spells/evards-black-tentacles.md), [finger of death](2-Mechanics/CLI/spells/finger-of-death.md), [time stop](2-Mechanics/CLI/spells/time-stop.md)

**2/day each**: [bestow curse](2-Mechanics/CLI/spells/bestow-curse.md), [Bigby's hand](2-Mechanics/CLI/spells/bigbys-hand.md), [dimension door](2-Mechanics/CLI/spells/dimension-door.md), [mage armor](2-Mechanics/CLI/spells/mage-armor.md), [Otiluke's resilient sphere](2-Mechanics/CLI/spells/otilukes-resilient-sphere.md), [thunderwave](2-Mechanics/CLI/spells/thunderwave.md)

## Actions

***Multiattack.*** Sofina makes three Necrotic Strike attacks.

***Necrotic Strike.*** *Melee or Ranged Spell Attack:* `dice:1d20+10|noform|text(+10)` to hit, reach 5 ft. or range 120 ft., one target. *Hit:* `dice:5d10+5|noform|avg|text(32)` (`5d10 + 5`) necrotic damage.

***Swarm of Meteors (1/Day).*** Sofina magically calls down a meteor swarm that detonates in four 40-foot-radius spheres, each one centered on a point she can see within 1 mile of herself. These spheres can overlap. Each creature in one or more of these spheres must make a DC 18 Dexterity saving throw, taking `dice:10d6|noform|avg|text(35)` (`10d6`) fire damage and `dice:10d6|noform|avg|text(35)` (`10d6`) bludgeoning damage on a failed saving throw, or half as much damage on a successful one. A creature in multiple spheres takes this damage only once.

## Bonus Actions

***Summon Wraith (1/Day).*** Sofina magically summons the spirit of a Thayan assassin, which appears as a wraith (see the Monster Manual). The summoned wraith appears in an unoccupied space within 60 feet of Sofina, whom it obeys. The summoned wraith takes its turn immediately after Sofina. It lasts for 1 hour, until it or Sofina dies, or until Sofina dismisses it as a bonus action.
```
^statblock