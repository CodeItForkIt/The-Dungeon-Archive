---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/ghloe
- monster/cr/24
- monster/size/gargantuan
- monster/type/undead
aliases: ["Gegazol"]
---
# Gegazol
*Source: Grim Hollow: Lairs of Etharis p. 117*  

> [!quote]  
> 
> The Scourge of the North is an undead dragon named Gegazol. If I hear her name, I get the hell out of there. She's powerful, cunning, and treacherous. And she's rarely alone—she always has one army or another behind her.

## Salvage

Gegazol's lair holds a hoard gathered over the centuries. She has spread this loot among various vaults and chambers, and her Immortals guard these treasures. Her treasurers—a trio of compulsive vampires—keep careful records of the hoard in a library within the lair's inner vaults. Each record contains a great deal of knowledge about the fates of various objects, and sometimes the vampires track a treasure beyond its gifting and engage in occasional quests to regain a lost valuable. Each historic tome from the library is worth at least 100 gp to the right collector. Enterprising adventurers could use any of these books as a guide to searches for lost treasures.

## Lore

- **DC 10 Intelligence ([History](2-Mechanics/CLI/rules/skills.md#History)).** Gegazol, Scourge of the North, is an ancient dragon transformed into an undead horror millennia ago. Tales as old as creation tell of her infrequent but violent assaults on lands south of her lair, and all lands of Etharis are south of her lair.  
- **DC 15 Intelligence ([Religion](2-Mechanics/CLI/rules/skills.md#Religion)).** Not only possessing great physical power, defenses against magic, and an undead army at her back, Gegazol, like a lich, has a soul vessel that harbors her undead soul and can rejuvenate her body when Gegazol is destroyed. It's said that this vessel is a massive daemon skull, and that the dragon keeps it hidden in her lair.  
- **DC 20 Intelligence ([History](2-Mechanics/CLI/rules/skills.md#History)).** Gegazol calls the undead who serve her Immortals'. Among them are vampires, ghouls, and undead that are even more powerful. Given many of these undead have fallen in her wars and powerplays, the Immortal title is aspirational.  

> [!note] Daemon Skull Soul Vessel
> 
> The ancient daemon skull that serves as Gegazol's soul vessel possesses infernal power, giving it the means for mischief and self-preservation. It has AC 6, but it's immune to bludgeoning, piercing, and slashing damage from nonmagical attacks, as well as cold, fire, necrotic, and psychic damage. It's immune to all conditions, and it has a +7 bonus to all saving throws, making saves against spells and magical effects with advantage. The skull has 200 hit points.
> 
> When harmed, the skull sends out a psychic alarm. Gegazol and her Immortals can sense this alarm, provided they are on the same plane of existence. Also, when a creature deals the skull damage, that creature must succeed on a DC 21 Wisdom saving throw or take psychic damage equal to half the damage the creature dealt.
> 
> If her soul vessel is destroyed, Gegazol can't rejuvenate. When her body is destroyed again, she dies.
^daemon-skull-soul-vessel

## Gegazol's Lair

The Scourge's lair is the sinkhole cave on an island off the northernmost shores of Etharis, north of even the raging coldfire. In this cave, the daemon's skull sits. It rests at the bottom of a deep, wet cavern upon a pedestal carved into the earth. Magic wards protect the crack above the skull. Gegazol's Immortals, a brutal cadre of undead warriors the dragon created or conquered, guard the expanded catacombs around the shrine. Gegazol needs no rest, but between campaigns, she lounges within the shrine, curled around the skull's pedestal. The whole place stinks of decay, making the site nauseating. While in her lair, Gegazol's Stench radius increases to 120 feet.

## Statblock

```ad-statblock
title: Gegazol
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/GHLoE/Gegazol.webp#token)
*Gargantuan undead, Chaotic Evil*

- **Armor Class** 22 (natural armor)
- **Hit Points** 462 (`25d20 + 200`)
- **Speed** 40 ft., burrow 40 ft., fly 80 ft., swim 40 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|27 (+8)|14 (+2)|26 (+8)|16 (+3)|15 (+2)|23 (+6)|

- **Proficiency Bonus** +7
- **Saving Throws** Dexterity +9, Intelligence +10, Wisdom +9
- **Skills** Perception +9
- **Senses** blindsight 60 ft., darkvision 120 ft., passive Perception 19
- **Damage Immunities** cold, necrotic, poison
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened), [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** Draconic
- **Challenge** 24

## Traits

***Ice Walk.*** Gegazol can move across and climb icy surfaces without needing to make an ability check. Additionally, difficult terrain composed of ice or snow doesn't cost her extra movement.

***Legendary Resistance (3/Day).*** If Gegazol fails a saving throw, she can choose to succeed instead.

***Magic Resistance.*** Gegazol has advantage on saving throws against spells and other magical effects.

***Rejuvenation.*** If destroyed while her soul vessel remains intact, Gegazol's [unconscious](2-Mechanics/CLI/rules/conditions.md#Unconscious) body rejuvenates within 5 feet of the soul vessel, where she regains `dice:12d12|noform|avg|text(78)` (`12d12`) hit points each day. When she has regained half her hit points, she regains consciousness.

***Stench.*** Any creature not immune to the [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned) condition that starts its turn within 30 feet of Gegazol must succeed on a DC 23 Constitution saving throw or become [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned) until the start of that creature's next turn. On a successful saving throw, the creature is immune to Gegazol's stench for 1 hour.

***Turning Defiance.*** Gegazol and undead within 120 feet of her have advantage on saving throws against effects that turn undead.

## Actions

***Multiattack.*** Gegazol can use her frightful presence. She then makes three attacks: one with her bite and two with her claws.

***Bite.*** *Melee Weapon Attack:* `dice:1d20+15|noform|text(+15)` to hit, reach 15 ft., one target. *Hit:* `dice:2d12+8|noform|avg|text(21)` (`2d12 + 8`) piercing damage, `dice:2d8|noform|avg|text(9)` (`2d8`) cold damage and `dice:2d8|noform|avg|text(9)` (`2d8`) necrotic damage.

***Claw.*** *Melee Weapon Attack:* `dice:1d20+15|noform|text(+15)` to hit, reach 10 ft., one target. *Hit:* `dice:2d10+8|noform|avg|text(19)` (`2d10 + 8`) piercing damage.

***Tail.*** *Melee Weapon Attack:* `dice:1d20+15|noform|text(+15)` to hit, reach 20 ft., one target. *Hit:* `dice:2d10+8|noform|avg|text(19)` (`2d10 + 8`) bludgeoning damage. If the target is a creature, it must succeed on a DC 23 Strength saving throw or fall [prone](2-Mechanics/CLI/rules/conditions.md#Prone).

***Frightful Presence.*** Each creature of Gegazol's choice within 120 feet of and aware of her must succeed on a DC 21 Wisdom saving throw or become [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened) for 1 minute. A creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success. If a creature's saving throw is successful or the effect ends for it, the creature is immune to Gegazol's Frightful Presence for the next 24 hours.

***Breath of Long Night (Recharge 5-6).*** Gegazol exhales frozen material and rot in a 90-foot cone. Each creature in that area must make a DC 23 Constitution saving throw, taking `dice:10d8|noform|avg|text(45)` (`10d8`) cold damage and `dice:10d8|noform|avg|text(45)` (`10d8`) necrotic damage on a failed save, or half as much damage on a successful one. Those who fail the save also gain two levels of [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion) until the end of Gegazol's next turn, and those who fail by 5 or more are also [blinded](2-Mechanics/CLI/rules/conditions.md#Blinded) for 1 minute. A [blinded](2-Mechanics/CLI/rules/conditions.md#Blinded) creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.

## Legendary Actions

***Daemon Sight.*** Gegazol gains truesight out to 120 feet until the end of her next turn and can make a Wisdom ([Perception](2-Mechanics/CLI/rules/skills.md#Perception)) check.

***Tail.*** Gegazol makes a tail attack.

***Wings of Winter (Costs 2 Actions).*** Gegazol beats her wings. Each creature within 30 feet of her must succeed on a DC 23 Dexterity saving throw or take `dice:2d8+8|noform|avg|text(17)` (`2d8 + 8`) bludgeoning damage and `dice:2d8|noform|avg|text(9)` (`2d8`) cold damage, and then fall [prone](2-Mechanics/CLI/rules/conditions.md#Prone). Gegazol can then fly up to half her flying speed.

![Gegazol](2-Mechanics/CLI/bestiary/legendary-group/gegazol-ghloe.md)
```
^statblock