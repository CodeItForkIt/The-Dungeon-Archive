---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/tob1-2023
- monster/cr/5
- monster/environment/desert
- monster/environment/underdark
- monster/environment/urban
- monster/size/medium
- monster/type/undead
aliases: ["Corrupted Ushabti"]
---
# Corrupted Ushabti
*Source: Tome of Beasts 1 (2023 Edition) p. 375*  

*The eye sockets of the funerary figure's ornate death mask suddenly ignite with a golden radiance. With the creak of long-unused limbs, this towering figure in ancient armor raises its weapons once more.*Ushabtis are placed in tombs as servants in the afterlife for those buried there—as both a laborer in the kingdom of the dead and a guardian in the kingdom of the living. These sentinels tend to the physical work and maintenance required after death that is beyond the abilities of those of flesh and blood. Dressed in ceremonial regalia, they are sometimes mistaken for living beings by those who would intrude upon their domain, but careful examination reveals faintly glowing hieroglyphs graven into their garments and bodies.

## Tomb Guardians

Ushabtis are most commonly encountered as guardians—a function they fulfill effectively, fiercely attacking anything that threatens their sworn charge. An ushabti is sometimes obvious from the blood of its victims staining its form. Some ceaselessly babble ancient scriptures or invocations to the gods of death. Tombs are often littered with bones of tomb robbers an ushabti has dispatched.

## Serene Repose

Most ushabtis have human faces and proportions, with features resembling a death mask. When at rest, they stand or lie with arms folded across their chests, clutching their ceremonial weapons. Many variations have been found, however, including some that are animal-headed, completely monstrous, or have abstract or fanciful designs, such as a sun-sphere head or a body made of papyrus scrolls.

## Sacrificial Corruptions

Some dark practitioners use sacrifices—willing or not—as undying servants of their godkings and god-queens. Generals, trusted advisors, and close allies have willingly accompanied their dying lords into the afterlife through this horrifying transformation. The sacrifices are tightly bound in linens and sealed within a sarcophagus among a swarm of flesh-eating scarabs that, over a period of days to weeks, fully consume their bodies. The servant's devotion to their task and the anguish of their passing transforms the scarab colony and animates the funerary wrappings to carry on with the sacred duty. Most view this as a corruption of the process for creating ushabtis, reducing the time and cost of construction with blood and resulting in a weaker, uncontrollable guardian. Though a corrupted ushabti fulfills its duties to protect its dead charges, it views living creatures as meals for the scarab colony within its wrappings, regardless of that creature's identity.

> [!note] Ushabti in Midgard
> 
> In Midgard, ushabtis are common in the Southlands as funerary figures. Originally gifted to his faithful by the wise god Eshu—whether this was truly as a gift or as trickery depends on the scholar telling the tale—these constructs gained near universal usage among the priests of other faiths. In Nuria Natal, they take on many more utilitarian roles for the living, not being confined to merely serving the dead, such as by protecting travelers and offerings at roadside shrines and as bodyguards and servants for the living god‑kings and other important figures.
> 
> Of note, a corrupted ushabti is viewed with some esteem in Nuria Natal, assuming the sacrifice was willing. These ushabti are sometimes called imy-ut ushabtis.
^ushabti-in-midgard

## Statblock

```ad-statblock
title: Corrupted Ushabti
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ToB1-2023/Corrupted%20Ushabti.webp#token)
*Medium undead, Neutral Evil*

- **Armor Class** 15 (natural armor)
- **Hit Points** 97 (`15d8 + 30`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|17 (+3)|14 (+2)|15 (+2)| 6 (-2)|10 (+0)| 5 (-3)|

- **Proficiency Bonus** +3
- **Saving Throws** Wisdom +3, Charisma +0
- **Skills** ⏤
- **Senses** darkvision 60 ft., passive Perception 10
- **Damage Vulnerabilities** fire
- **Damage Resistances** bludgeoning, piercing, slashing from nonmagical attacks
- **Damage Immunities** necrotic, poison
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened), [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed), [petrified](2-Mechanics/CLI/rules/conditions.md#Petrified), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned), [stunned](2-Mechanics/CLI/rules/conditions.md#Stunned)
- **Languages** understands Common but can't speak
- **Challenge** 5

## Traits

***Necrotic Weapons.*** The ushabti's weapon attacks are magical. When the ushabti hits with any weapon, the weapon deals an extra (`dice:2d6|noform|avg` (`2d6`)) necrotic damage (included in the attack).

***Regeneration.*** The ushabti regains 5 hp at the start of its turn if it has at least 1 hp.

***Swarm Body.*** The corrupted ushabti is a spirit inhabiting a colony of scarabs around a Humanoid skeleton within funerary wrappings. It can move through any opening large enough for a Tiny scarab and Humanoid bones, and it can't regain hp or gain temporary hp, except for its Regeneration trait. In addition, a creature that hits the ushabti with a melee attack while within 5 feet of it takes `dice:1d4|noform|avg|text(2)` (`1d4`) piercing damage as a dozen Tiny scarabs skitter out and bite the attacker.

***Undead Nature.*** The ushabti doesn't require air, food, drink, or sleep.

## Actions

***Multiattack.*** The corrupted ushabti makes two Ceremonial Greatsword attacks.

***Ceremonial Greatsword.*** *Melee Weapon Attack:* `dice:1d20+6|noform|text(+6)` to hit, reach 5 ft., one creature. *Hit:* `dice:2d6+3|noform|avg|text(11)` (`2d6 + 3`) slashing damage plus `dice:2d6|noform|avg|text(7)` (`2d6`) necrotic damage.

***Vomit Swarm (Recharge 5-6).*** The corrupted ushabti exhales scarabs in a 30-foot cone. Each creature in the area must make a DC 15 Dexterity saving throw. On a failure, a creature takes `dice:10d4|noform|avg|text(25)` (`10d4`) piercing damage and is covered in scarabs. On a success, a creature takes half the damage and isn't covered in scarabs. A creature covered in scarabs takes `dice:1d4|noform|avg|text(2)` (`1d4`) piercing damage at the start of each of its turns. A creature, including the covered creature, can take its action to brush the scarabs off the covered creature by succeeding on a DC 15 Dexterity check.
```
^statblock

## Environment

desert, underdark, urban