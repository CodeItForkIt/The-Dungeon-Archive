---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/tob1-2023
- monster/cr/15
- monster/environment/urban
- monster/size/medium
- monster/type/undead
aliases: ["Pact Vampire"]
---
# Pact Vampire
*Source: Tome of Beasts 1 (2023 Edition) p. 380*  

*Blood flows up the slain man's body, defying gravity as it makes its way into the skin and fanged maw of this wild-haired vampire.*

Pact warlocks seek transformation into a vampire while blessed by a patron of blood, destruction, or undead. The pact vampire's thirst for blood is so all-consuming that it can draw the blood of others through the air to its open maw.

## Blood Line

The patron's blessing frees the warlock from some of a vampire's weaknesses, but it also secures a magical line of blood and life energy between the warlock and the patron. This drives the warlock to wantonly shed and drink blood, fueling the patron with each drop. A pact vampire must feed blood to its patron weekly by shedding the blood of other creatures and absorbing that blood into its body. A pact vampire that forgets or refuses to shed blood for its patron begins to lose vitality, steadily becoming more gaunt until it withers into a mindless, skincovered skeleton under the patron's control.

## Transformed Vampires

Not all pact vampires start as living warlocks. Some vampires choose to make a pact with a foul power to diminish some of its weaknesses and to gain more control over its own blood and the blood of others. Such vampires transform into pact vampires, giving up some of their autonomy for greater power and safety from running water and sunlight. Regardless of how it initially transformed, a pact vampire can't change its form like a standard vampire, relying on its followers and its patron's power to ensure its safe exit from dangerous situations.

## Poisonous Blood

A pact vampire's blood is tainted by its enhanced magical connection to its patron, and when introduced to living creatures, the vampire's blood causes the creature's blood to flow more freely. Pact vampires coat their claws in this blood to better subdue and sup from bleeding victims. Particularly brave alchemists have attempted to harvest pact vampire blood for use in treating diseases related to thick or sluggish blood, but few survive the attempt.

> [!note] A Pact of a Different Color
> 
> The pact vampire represented here is based on the Fiend patron. Not all patrons, especially those of good alignment, would condone their warlocks seeking transformation into an especially bloodthirsty vampire. Those patrons who are associated with blood, destruction, or undeath, however, take special glee in aiding such a transformation, reveling in the blood shed by the warlock and sending their minions to assist in the mayhem.
> 
> If you want to bring a pact vampire into play from a different patron, consider some changes. Damage resistances, immunities, and actions like Children of the Lower Planes can be changed to reflect a different pact, such as resistance to damage from weapons not made with cold iron for a pact vampire whose patron is one of the fey lords or ladies (see Tome of Beasts) or magically calling mephits and other minor elementals for a pact vampire whose patron is a genie lord.
^a-pact-of-a-different-color

## A Pact Vampire's Lair

Needing to be near civilization for ready access to the blood its patron craves, a pact vampire dwells in a city's catacombs, sewers, or other underground complex with easy access to the city's streets at night. Pact vampires often lead secret cults within the city, building its patron's followers while drinking in the blood of the victims the cult brings to it. Due to the pact vampire's more direct link to the patron than many warlocks, the lair takes on aspects of the patron and is subtly shaped by the patron's will, filling the lair with hellish heat, eldritch lights, sourceless screams, and similar effects pleasing to that particular patron.

## Statblock

```ad-statblock
title: Pact Vampire
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ToB1-2023/Pact%20Vampire.webp#token)
*Medium undead, Any Evil alignment*

- **Armor Class** 16 (natural armor)
- **Hit Points** 178 (`17d8 + 102`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|22 (+6)|16 (+3)|22 (+6)|17 (+3)|15 (+2)|20 (+5)|

- **Proficiency Bonus** +5
- **Saving Throws** Dexterity +8, Constitution +11, Wisdom +7, Charisma +10
- **Skills** Perception +7, Persuasion +10, Stealth +8
- **Senses** darkvision 120 ft., passive Perception 17
- **Damage Resistances** necrotic; bludgeoning, piercing, slashing from nonmagical attacks
- **Damage Immunities** poison
- **Condition Immunities** [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** the languages it knew in life
- **Challenge** 15

## Traits

***Blood Sense.*** The pact vampire can pinpoint the location of creatures that aren't Constructs or Undead within 60 feet of it and can sense the general direction of such creatures within 1 mile of it.

***Legendary Resistance (3/Day).*** If the pact vampire fails a saving throw, it can choose to succeed instead.

***Poisonous Blood.*** A creature that hits the pact vampire with a melee attack while within 5 feet of it takes `dice:2d6|noform|avg|text(7)` (`2d6`) poison damage.

***Regeneration.*** The pact vampire regains 25 hp at the start of its turn if it has at least 1 hp and isn't in sunlight. If the vampire takes radiant damage or damage from holy water, this trait doesn't function at the start of the vampire's next turn.

***Undead Nature.*** The pact vampire doesn't require air.

***Vampire Weaknesses.*** The pact vampire has the following flaws:

***Stake to the Heart.*** If a piercing weapon made of wood is driven into the vampire's heart while the vampire is [incapacitated](2-Mechanics/CLI/rules/conditions.md#Incapacitated) in its resting place, the vampire is [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed) until the stake is removed.

***Sunlight Hypersensitivity.*** The vampire takes 10 radiant damage when it starts its turn in sunlight. While in sunlight, it has disadvantage on attack rolls and ability checks.

## Actions

***Multiattack.*** The pact vampire makes three Claw attacks.

***Claw.*** *Melee Weapon Attack:* `dice:1d20+11|noform|text(+11)` to hit, reach 5 ft., one target. *Hit:* `dice:2d6+6|noform|avg|text(13)` (`2d6 + 6`) slashing damage plus `dice:3d8|noform|avg|text(13)` (`3d8`) poison damage.

***Call Blood.*** The pact vampire draws the blood out of a bleeding creature's body, where it flows through the air into the vampire's mouth. One creature the vampire can see within 60 feet of it that doesn't have all its hp and isn't a Construct or Undead must succeed on a DC 18 Constitution saving throw or take `dice:4d10|noform|avg|text(22)` (`4d10`) necrotic damage, and its hp maximum is reduced by that amount. The vampire regains hp equal to half the damage dealt. This reduction lasts until the target finishes a long rest. The target dies if this effect reduces its hp maximum to 0.

***Charm.*** One Humanoid the vampire can see within 30 feet of it must succeed on a DC 18 Wisdom saving throw or be magically [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed) for 1 day. The [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed) target obeys the vampire's verbal commands. If the target suffers any harm or receives a suicidal command, it can repeat the saving throw, ending the effect on itself on a success. If the target's saving throw is successful or the effect ends for it, the target is immune to this vampire's Charm for the next 24 hours.

The vampire can have only one target [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed) at a time. If it charms another, the effect on the previous target ends.

***Children of the Lower Planes (1/Day).*** The pact vampire magically calls `dice:2d4|noform|avg` (`2d4`) dretches, `dice:1d4|noform|avg` (`1d4`) imps, or 1 bearded devil. The called Fiends arrive in `dice:1d4|noform|avg` (`1d4`) rounds, acting as allies of the vampire and obeying its spoken commands. The Fiends remain for 1 hour, until the vampire dies, or until the vampire dismisses them as a bonus action.

## Legendary Actions

***Move.*** The pact vampire moves up to its speed without provoking opportunity attacks.

***Call Blood (Costs 2 Actions).*** The pact vampire uses Call Blood.

***Spread Poison (Costs 2 Actions).*** The pact vampire's blood briefly turns into a mist around it. Each creature within 15 feet of the vampire must succeed on a DC 18 Constitution saving throw or take `dice:4d6|noform|avg|text(14)` (`4d6`) poison damage and be [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned) until the end of its next turn.

![Pact Vampire](2-Mechanics/CLI/bestiary/legendary-group/pact-vampire-tob1-2023.md)
```
^statblock

## Environment

urban