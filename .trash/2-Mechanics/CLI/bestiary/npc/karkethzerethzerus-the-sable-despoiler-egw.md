---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/egw
- monster/cr/23
- monster/size/gargantuan
- monster/type/dragon
aliases: ["Karkethzerethzerus, the Sable Despoiler"]
---
# Karkethzerethzerus, the Sable Despoiler
*Source: Explorer's Guide to Wildemount p. 158*  

```ad-statblock
title: Karkethzerethzerus, the Sable Despoiler
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/EGW/Karkethzerethzerus%2C%20the%20Sable%20Despoiler.webp#token)
*Gargantuan dragon, Lawful Good*

- **Armor Class** 22 (natural armor)
- **Hit Points** 487 (`25d20 + 225`)
- **Speed** 40 ft., fly 80 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|30 (+10)|10 (+0)|29 (+9)|18 (+4)|15 (+2)|23 (+6)|

- **Proficiency Bonus** +7
- **Saving Throws** Dexterity +7, Constitution +16, Wisdom +9, Charisma +13
- **Skills** Arcana +11, History +11, Perception +16, Stealth +7
- **Senses** blindsight 60 ft., darkvision 120 ft., passive Perception 26
- **Damage Resistances** necrotic
- **Damage Immunities** cold
- **Languages** Common, Draconic
- **Challenge** 23

## Traits

***Legendary Resistance (3/Day).*** If the dragon fails a saving throw, it can choose to succeed instead.

***Living Shadow.*** While in dim light or darkness, the dragon has resistance to damage that isn't force, psychic, or radiant.

***Shadow Stealth.*** While in dim light or darkness, the dragon can take the [Hide](2-Mechanics/CLI/rules/actions.md#Hide) action as a bonus action.

***Sunlight Sensitivity.*** While in sunlight, the dragon has disadvantage on attack rolls, as well as on Wisdom ([Perception](2-Mechanics/CLI/rules/skills.md#Perception)) checks that rely on sight.

## Actions

***Multiattack.*** The dragon can use its Frightful Presence. It then makes three attacks: one with its bite and two with its claws.

***Bite.*** *Melee Weapon Attack:* `dice:1d20+17|noform|text(+17)` to hit, reach 15 ft., one target. *Hit:* `dice:2d10+10|noform|avg|text(21)` (`2d10 + 10`) piercing damage.

***Claw.*** *Melee Weapon Attack:* `dice:1d20+17|noform|text(+17)` to hit, reach 10 ft., one target. *Hit:* `dice:2d6+10|noform|avg|text(17)` (`2d6 + 10`) slashing damage.

***Tail.*** *Melee Weapon Attack:* `dice:1d20+17|noform|text(+17)` to hit, reach 20 ft., one target. *Hit:* `dice:2d8+10|noform|avg|text(19)` (`2d8 + 10`) bludgeoning damage.

***Frightful Presence.*** Each creature of the dragon's choice that is within 120 feet of the dragon and aware of it must succeed on a DC 21 Wisdom saving throw or become [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened) for 1 minute. A creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success. If a creature's saving throw is successful or the effect ends for it, the creature is immune to the dragon's Frightful Presence for the next 24 hours.

***Breath Weapons (Recharge 5-6).*** The dragon uses one of the following breath weapons.

- **Necrotic Breath.** The dragon exhales an icy blast in a 90-foot cone. Each creature in that area must make a DC 24 Constitution saving throw, taking `dice:15d8|noform|avg|text(67)` (`15d8`) necrotic damage on a failed save, or half as much damage on a successful one.  
- **Paralyzing Breath.** The dragon exhales paralyzing gas in a 90-foot cone. Each creature in that area must succeed on a DC 24 Constitution saving throw or be [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed) for 1 minute. A creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.  

***Change Shape.*** The dragon magically polymorphs into a humanoid or beast that has a challenge rating no higher than its own, or back into its true form. It reverts to its true form if it dies. Any equipment it is wearing or carrying is absorbed or borne by the new form (the dragon's choice).

In a new form, the dragon retains its alignment, hit points, Hit Dice, ability to speak, proficiencies, Legendary Resistance, lair actions, and Intelligence, Wisdom, and Charisma scores, as well as this action. Its statistics and capabilities are otherwise replaced by those of the new form, except any class features or legendary actions of that form.

## Legendary Actions

***Detect.*** The dragon makes a Wisdom ([Perception](2-Mechanics/CLI/rules/skills.md#Perception)) check.

***Tail Attack.*** The dragon makes a tail attack.

***Wing Attack (Costs 2 Actions).*** The dragon beats its wings. Each creature within 15 feet of the dragon must succeed on a DC 25 Dexterity saving throw or take `dice:2d6+10|noform|avg|text(17)` (`2d6 + 10`) bludgeoning damage and be knocked [prone](2-Mechanics/CLI/rules/conditions.md#Prone). The dragon can then fly up to half its flying speed.
```
^statblock