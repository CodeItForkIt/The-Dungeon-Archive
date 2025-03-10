---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/erlw
- monster/cr/24
- monster/size/medium
- monster/type/aberration
aliases: ["Dyrrn"]
---
# Dyrrn
*Source: Eberron: Rising from the Last War p. 288*  

Dyrrn is known to its followers as the Corruptor, the Stealer of Thoughts, the Slithering Lord, and the Foul Labyrinth. In the lore of the Gatekeepers, it is said that Dyrrn plants thoughts in the weak minded—the seeds of terrible ideas that fester and grow. Those who are particularly brilliant often draw the attention of the Foul Labyrinth, which hungers to consume unique minds.

## Twisting Flesh and Thought

The mind flayers of Eberron know Dyrrn as the Overmind, and it serves as the cornerstone of their collective consciousness. Of all the daelkyr, the Corruptor is the most adept at twisting minds and bodies to create monsters. It was Dyrrn who turned goblinoid prisoners into the first dolgaunts and dolgrims, creating the legions that would savage the nations of Khorvaire. Dyrrn is also a prolific creator of symbionts—treasures that tempt people to bind alien entities to their flesh.

## Dyrrn's Cults

Dyrrn's lair touches the Eldeen Reaches, and the druids of the Towering Wood are always watching for Dyrrn's influence. At the start of the Last War, the dwarves of the Mror Holds discovered passages to the daelkyr's realm below their halls, and Dyrrn's cults have spread from there.

Mind flayers often work with Dyrrn's cults, many of which are obsessed with evolution—through the use of symbionts or by becoming an aberration. Those who worship the Stealer of Thoughts believe that Dyrrn will consume all sentient beings, except for its servants.

Dyrrn most often appears as a tall humanoid male with pale skin, clad in a heavy cassock of interwoven black leather that slithers unsettlingly around the daelkyr's form. Dyrrn can extend tentacles from its body, using them to extract the brains of others.

## Dyrrn's Lair

Dyrrn makes its lair in the Palace of Sinew, a horrid site shaped from the leftover flesh and bones of the daelkyr's sculpting. The walls of the palace undulate as air flows through them, as if the space were breathing.

## Madness of Dyrrn

If a creature goes mad in Dyrrn's lair or while it can see the daelkyr, it gains a form of indefinite madness. Roll on the Madness of Dyrrn table to determine the nature of this madness, which takes the form of a character flaw that lasts until cured. Chapter 8 of the "Dungeon Master's Guide" has more information on madness.

**Madness of Dyrrn**

`dice: [](dyrrn-erlw.md#^madness-of-dyrrn)`

| dice: d6 | Flaw (lasts until cured) |
|----------|--------------------------|
| 1 | "There's an illithid parasite living in my brain!" |
| 2 | "I can feel myself evolving into an aberration." |
| 3 | "Aberrations are the only natural things." |
| 4 | "A part of me has become a conscious entity." |
| 5 | "My opponents must bow down to a mind flayer!" |
| 6 | "Dyrrn and the mind flayers simply want to unite all sentient creatures in collective consciousness. And I receive messages from the group mind!" |
^madness-of-dyrrn

## Statblock

```ad-statblock
title: Dyrrn
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ERLW/Dyrrn.webp#token)
*Medium aberration, Chaotic Evil*

- **Armor Class** 21 (natural armor)
- **Hit Points** 325 (`31d8 + 186`)
- **Speed** 40 ft., fly 40 ft. (hover)

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|26 (+8)|21 (+5)|22 (+6)|26 (+8)|23 (+6)|24 (+7)|

- **Proficiency Bonus** +7
- **Saving Throws** Intelligence +15, Wisdom +13, Charisma +14
- **Skills** Arcana +15, History +15, Insight +13, Perception +13
- **Senses** truesight 120 ft., passive Perception 23
- **Damage Resistances** poison, psychic
- **Condition Immunities** [blinded](2-Mechanics/CLI/rules/conditions.md#Blinded), [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned), [prone](2-Mechanics/CLI/rules/conditions.md#Prone)
- **Languages** Deep Speech, telepathy 120 ft.
- **Challenge** 24

## Traits

***Alien Mind.*** If a creature tries to read Dyrrn's thoughts or deals psychic damage to it, that creature must succeed on a DC 23 Intelligence saving throw or be [stunned](2-Mechanics/CLI/rules/conditions.md#Stunned) for 1 minute. The [stunned](2-Mechanics/CLI/rules/conditions.md#Stunned) creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.

***Legendary Resistance (3/Day).*** If Dyrrn fails a saving throw, it can choose to succeed instead.

***Magic Resistance.*** Dyrrn has advantage on saving throws against spells and other magical effects.

***Regeneration.*** Dyrrn regains 20 hit points at the start of its turn. If Dyrrn takes radiant damage, this trait doesn't function at the start of its next turn. Dyrrn dies only if it starts its turn with 0 hit points and doesn't regenerate.

***Teleport.*** As a bonus action, Dyrrn can teleport up to 30 feet to an unoccupied space it can see.

## Actions

***Multiattack.*** Dyrrn makes one Tentacle Whip attack and uses its Corruption once. Dyrrn can replace its Tentacle Whip attack with Extract Brain if it has a creature [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled).

***Tentacle Whip.*** *Melee Weapon Attack:* `dice:1d20+15|noform|text(+15)` to hit, reach 10 ft., one target. *Hit:* `dice:3d10+8|noform|avg|text(24)` (`3d10 + 8`) slashing damage. If the target is a Medium or smaller creature, it is [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) (escape DC 23), pulled into an unoccupied space within 5 feet of Dyrrn, and must succeed on a DC 23 Intelligence saving throw or be [stunned](2-Mechanics/CLI/rules/conditions.md#Stunned) until this grapple ends. Dyrrn can't use the same tentacle whip on another target until this grapple ends. Dyrrn has two tentacle whips.

***Corruption.*** Dyrrn targets one creature it can see within 60 feet of it. The target must succeed on a DC 23 Constitution saving throw or take `dice:4d6+8|noform|avg|text(22)` (`4d6 + 8`) necrotic damage and become corrupted for 1 minute.

A corrupted creature's flesh twists in alien ways. The creature has disadvantage on attack rolls, its speed is reduced by half, and if it tries to cast a spell, it must first succeed on a DC 15 Intelligence check or the spell fails and is wasted. The corrupted creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.

***Extract Brain.*** *Melee Weapon Attack:* `dice:1d20+15|noform|text(+15)` to hit, reach 5 ft., one [incapacitated](2-Mechanics/CLI/rules/conditions.md#Incapacitated) creature [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) by Dyrrn. *Hit:* `dice:10d10|noform|avg|text(55)` (`10d10`) piercing damage. If this damage reduces the target to 0 hit points, Dyrrn kills the target by extracting and devouring its brain.

## Legendary Actions

***Tentacle Whip.*** Dyrrn makes one attack with its Tentacle Whip.

***Spawn Aberration (Costs 2 Actions).*** Dyrrn regurgitates an intellect devourer in an unoccupied space within 5 feet of it. The intellect devourer is under Dyrrn's control and acts immediately after Dyrrn in the initiative order.

***Mind Blast (Costs 3 Actions).*** Dyrrn magically emits psychic energy in a 60-foot cone. Each creature in that area must succeed on a DC 23 Intelligence saving throw or take `dice:5d8+8|noform|avg|text(30)` (`5d8 + 8`) psychic damage and be [stunned](2-Mechanics/CLI/rules/conditions.md#Stunned) for 1 minute. A creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.

![Dyrrn](2-Mechanics/CLI/bestiary/legendary-group/dyrrn-erlw.md)
```
^statblock