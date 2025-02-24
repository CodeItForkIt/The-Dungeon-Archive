---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/tob1-2023
- monster/cr/7
- monster/environment/badlands
- monster/environment/forest
- monster/size/large
- monster/type/aberration
aliases: ["Chelicerae"]
---
# Chelicerae
*Source: Tome of Beasts 1 (2023 Edition) p. 53*  

*The massive spider stands perched on tall, stilted legs, and the disheveled body of a robed arcanist swings from its clenched mandibles.*

## Feed on Spellcasters

These massive arachnids are largely confined to great forests and occasional wastelands, although rumors persist of sightings in the dark alleys of magocratic cities, causing trepidation among the spellcasters there. Few creatures pose such a threat to spellcasters as chelicerae.

## Carry Their Prey

Walking on high, stilted legs, these creatures resemble gigantic harvesters. More often than not, they are found with the grisly bodies of humanoids dangling from their clenched mandibles.

## Cocoon Arcanists

Chelicerae stalk isolated victims, striking with a poisonous bite then pinning the victim within powerful jaws. There, the victim's helpless body can hang for days on end as the chelicerae pursues obscure and eldritch tasks. At best, victims wake up weeks later with no memory of the events, far from home, and drained of vitality and spells. Others are stored immobilized in thick cocoons in a high treetop until their body and mind recover. A few unlucky victims are slain and rise a week later as walking dead that obey and protect the chelicerae.

## Statblock

```ad-statblock
title: Chelicerae
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ToB1-2023/Chelicerae.webp#token)
*Large aberration, Neutral Evil*

- **Armor Class** 16 (natural armor)
- **Hit Points** 153 (`18d10 + 54`)
- **Speed** 40 ft., climb 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|22 (+6)|17 (+3)|17 (+3)|18 (+4)|15 (+2)|14 (+2)|

- **Proficiency Bonus** +3
- **Saving Throws** Dexterity +6, Wisdom +5, Charisma +5
- **Skills** Acrobatics +6, Athletics +9, Perception +5, Stealth +6
- **Senses** darkvision 60 ft., passive Perception 15
- **Damage Immunities** poison
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** understands Common but can't speak
- **Challenge** 7

## Traits

***Magic Resistance.*** The chelicerae has advantage on saving throws against spells and other magical effects.

***Spider Climb.*** The chelicerae can climb difficult surfaces, including upside down on ceilings, without needing to make an ability check.

***Spellcasting.*** The chelicerae casts one of the following spells, requiring no material or verbal components and using Intelligence as the spellcasting ability (spell save DC 15):

**At will**: [mage hand](2-Mechanics/CLI/spells/mage-hand.md), [minor illusion](2-Mechanics/CLI/spells/minor-illusion.md)

**1/day each**: [haste](2-Mechanics/CLI/spells/haste.md), [hold person](2-Mechanics/CLI/spells/hold-person.md), [invisibility](2-Mechanics/CLI/spells/invisibility.md), [phantasmal killer](2-Mechanics/CLI/spells/phantasmal-killer.md)

## Actions

***Multiattack.*** The chelicerae makes one Bite attack and two Claw attacks. It can replace the Bite attack with a use of Spellcasting.

***Bite.*** *Melee Weapon Attack:* `dice:1d20+9|noform|text(+9)` to hit, reach 5 ft., one target. *Hit:* `dice:2d10+6|noform|avg|text(17)` (`2d10 + 6`) piercing damage, and the target must succeed on a DC 15 Constitution saving throw or become [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned) for 1 minute. If the target is a Medium or smaller creature and the chelicerae doesn't have another creature [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled), the target is [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) (escape DC 15). A [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned) target is also [unconscious](2-Mechanics/CLI/rules/conditions.md#Unconscious) while [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned) in this way. The [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned) target can repeat the saving throw at the end of each of its turns, ending the [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned) condition on itself on a success.

***Claw.*** *Melee Weapon Attack:* `dice:1d20+9|noform|text(+9)` to hit, reach 10 ft., one target. *Hit:* `dice:2d8+6|noform|avg|text(15)` (`2d8 + 6`) slashing damage.

***Magical Discharge (Recharge Special).*** The chelicerae releases some of its stored magical energy in a burst. Each creature within 15 feet of the chelicerae must make a DC 15 Dexterity saving throw, taking `dice:8d8|noform|avg|text(36)` (`8d8`) force damage on a failed save, or half as much damage on a successful one. After using Magical Discharge, the chelicerae can't do so again until it successfully siphons magic from a creature or until it finishes a long rest.

## Bonus Actions

***Nimble Moves.*** The chelicerae takes the Dash or Disengage action.

***Siphon Magic.*** The chelicerae siphons magic from a spellcaster it is grappling. The target must succeed on a DC 15 Intelligence saving throw or lose one spell slot of the highest level it can cast. The chelicerae then regains an expended use of its Spellcasting.
```
^statblock

## Environment

badlands, forest