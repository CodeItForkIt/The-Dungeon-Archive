---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/psa
- monster/cr/15
- monster/size/medium
- monster/type/undead
aliases: ["Amonkhet Mummy Lord"]
---
# Amonkhet Mummy Lord
*Source: Plane Shift: Amonkhet p. 34*  

Not every citizen of Naktamun proves to be worthy of the afterlife. Acolytes sometimes die before the Ceremony of Measurement, perhaps in training accidents. Many [initiates](2-Mechanics/CLI/backgrounds/initiate-psa.md) perish in one of the first four trials, before earning their five cartouches. [Viziers](2-Mechanics/CLI/backgrounds/vizier-psa.md) sometimes die before they have truly earned a place in the afterlife serving their gods. Without having proven themselves worthy, these poor souls have no place as Eternals in the afterlife—but neither have they committed a grievous sin that would warrant abandoning them to the Curse of Wandering as marauding [mummies](2-Mechanics/CLI/bestiary/undead/amonkhet-mummy-psa.md).

Fortunately, the beneficence of the God-Pharaoh is great enough to provide a role for these people. Called the anointed, they are carefully embalmed, protected from the Curse of Wandering, and allowed to spend another lifetime in service to the worthy. The God-Pharaoh promises that those who faithfully serve as the anointed will earn a place as attendants in the afterlife as well, and even an eternity of service in the afterlife is prefera-ble to an eternity subjected to the Curse of Wandering.

The bodies of the anointed are carefully wrapped in cloth and adorned with cartouches. In contrast to the cartouches of [initiates](2-Mechanics/CLI/backgrounds/initiate-psa.md) and [viziers](2-Mechanics/CLI/backgrounds/vizier-psa.md), these do not harbor the life essence of the deceased at their best. Instead, they coach the anointed for a particular form of service. With their cartouches in place, the anointed rise and join the ranks of serving [mummies](2-Mechanics/CLI/bestiary/undead/amonkhet-mummy-psa.md) who attend to the needs of daily life in Amonkhet.

## The Curse of Wandering

The Curse of Wandering is the greatest danger of the desert lands. A creature killed in the desert rises again as a [zombie](2-Mechanics/CLI/bestiary/undead/zombie.md) as soon as the moisture has dried from its flesh. As a result, the corpses of every kind of desert creature shamble across the dunes alongside the humanoid [zombies](2-Mechanics/CLI/bestiary/undead/zombie.md) of dissenters and would-be explorers. Most of these former humanoids are mindless marauders, though some tales speak of [mummies](2-Mechanics/CLI/bestiary/undead/amonkhet-mummy-psa.md) that have retained a sinister intelligence and even magical ability, becoming [mummy lords](2-Mechanics/CLI/bestiary/undead/amonkhet-mummy-lord-psa.md).

## Statblock

```ad-statblock
title: Amonkhet Mummy Lord
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/PSA/Amonkhet%20Mummy%20Lord.webp#token)
*Medium undead, Lawful Evil*

- **Armor Class** 17 (natural armor)
- **Hit Points** 97 (`13d8 + 39`)
- **Speed** 20 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|18 (+4)|10 (+0)|17 (+3)|11 (+0)|18 (+4)|16 (+3)|

- **Proficiency Bonus** +5
- **Saving Throws** Constitution +8, Intelligence +5, Wisdom +9, Charisma +8
- **Skills** History +5, Religion +5
- **Senses** darkvision 60 ft., passive Perception 14
- **Damage Vulnerabilities** fire
- **Damage Immunities** necrotic; poison; bludgeoning, piercing, slashing from nonmagical attacks
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened), [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** the languages it knew in life
- **Challenge** 15

## Traits

***Magic Resistance.*** The mummy lord has advantage on saving throws against spells and other magical effects.

***Rejuvenation.*** A destroyed mummy lord gains a new body in 24 hours if its heart is intact, regaining all its hit points and becoming active again. The new body appears within 5 feet of the mummy lord's heart.

***Spellcasting.*** The mummy lord is a 10th-level spellcaster. Its spellcasting ability is Wisdom (spell save DC 17, `dice:1d20+9|noform|text(+9)` to hit with spell attacks). The mummy lord has the following cleric spells prepared:

**Cantrips (at will)**: [sacred flame](2-Mechanics/CLI/spells/sacred-flame.md), [thaumaturgy](2-Mechanics/CLI/spells/thaumaturgy.md)

**1st level (4 slots)**: [command](2-Mechanics/CLI/spells/command.md), [guiding bolt](2-Mechanics/CLI/spells/guiding-bolt.md), [shield of faith](2-Mechanics/CLI/spells/shield-of-faith.md)

**2nd level (3 slots)**: [hold person](2-Mechanics/CLI/spells/hold-person.md), [silence](2-Mechanics/CLI/spells/silence.md), [spiritual weapon](2-Mechanics/CLI/spells/spiritual-weapon.md)

**3rd level (3 slots)**: [animate dead](2-Mechanics/CLI/spells/animate-dead.md), [dispel magic](2-Mechanics/CLI/spells/dispel-magic.md)

**4th level (3 slots)**: [divination](2-Mechanics/CLI/spells/divination.md), [guardian of faith](2-Mechanics/CLI/spells/guardian-of-faith.md)

**5th level (2 slots)**: [contagion](2-Mechanics/CLI/spells/contagion.md), [insect plague](2-Mechanics/CLI/spells/insect-plague.md)

**6th level (1 slots)**: [harm](2-Mechanics/CLI/spells/harm.md)

## Actions

***Multiattack.*** The mummy can use its Dreadful Glare and makes one attack with its rotting fist.

***Rotting Fist.*** *Melee Weapon Attack:* `dice:1d20+9|noform|text(+9)` to hit, reach 5 ft., one target. *Hit:* `dice:3d6+4|noform|avg|text(14)` (`3d6 + 4`) bludgeoning damage plus `dice:6d6|noform|avg|text(21)` (`6d6`) necrotic damage. If the target is a creature, it must succeed on a DC 16 Constitution saving throw or be cursed with mummy rot. The cursed target can't regain hit points, and its hit point maximum decreases by `dice:3d6|noform|avg|text(10)` (`3d6`) for every 24 hours that elapse. If the curse reduces the target's hit point maximum to 0, the target dies, and its body turns to dust. The curse lasts until removed by the [remove curse](2-Mechanics/CLI/spells/remove-curse.md) spell or other magic.

***Dreadful Glare.*** The mummy lord targets one creature it can see within 60 feet of it. If the target can see the mummy lord, it must succeed on a DC 16 Wisdom saving throw against this magic or become [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened) until the end of the mummy's next turn. If the target fails the saving throw by 5 or more, it is also [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed) for the same duration. A target that succeeds on the saving throw is immune to the Dreadful Glare of all mummies and mummy lords for the next 24 hours.

## Legendary Actions

***Attack.*** The mummy lord makes one attack with its rotting fist or uses its Dreadful Glare.

***Blinding Dust.*** Blinding dust and sand swirls magically around the mummy lord. Each creature within 5 feet of the mummy lord must succeed on a DC 16 Constitution saving throw or be [blinded](2-Mechanics/CLI/rules/conditions.md#Blinded) until the end of the creature's next turn.

***Blasphemous Word (Costs 2 Actions).*** The mummy lord utters a blasphemous word. Each non-undead creature within 10 feet of the mummy lord that can hear the magical utterance must succeed on a DC 16 Constitution saving throw or be [stunned](2-Mechanics/CLI/rules/conditions.md#Stunned) until the end of the mummy lord's next turn.

***Channel Negative Energy (Costs 2 Actions).*** The mummy lord magically unleashes negative energy. Creatures within 60 feet of the mummy lord, including ones behind barriers and around corners, can't regain hit points until the end of the mummy lord's next turn.

***Whirlwind of Sand (Costs 2 Actions).*** The mummy lord magically transforms into a whirlwind of sand, moves up to 60 feet, and reverts to its normal form. While in whirlwind form, the mummy lord is immune to all damage, and it can't be [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled), [petrified](2-Mechanics/CLI/rules/conditions.md#Petrified), knocked [prone](2-Mechanics/CLI/rules/conditions.md#Prone), [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained), or [stunned](2-Mechanics/CLI/rules/conditions.md#Stunned). Equipment worn or carried by the mummy lord remain in its possession.
```
^statblock