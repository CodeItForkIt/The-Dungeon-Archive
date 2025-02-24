---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/dodk
- monster/cr/10
- monster/size/large
- monster/type/dragon
aliases: ["Tower Dragon"]
---
# Tower Dragon
*Source: Dungeons of Drakkenheim p. 198*  

These young bronze dragons perch upon the towers and parapets of the city and Castle Drakken. Once noble protectors of the city, they are now controlled by the will of the Haze.

```ad-statblock
title: Tower Dragon
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/DoDk/Tower%20Dragon.webp#token)
*Large dragon, Lawful Good*

- **Armor Class** 18 (natural armor)
- **Hit Points** 142 (`15d10 + 60`)
- **Speed** 40 ft., fly 80 ft., swim 40 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|21 (+5)|10 (+0)|19 (+4)|14 (+2)|13 (+1)|17 (+3)|

- **Proficiency Bonus** +4
- **Saving Throws** Dexterity +3, Constitution +7, Wisdom +4, Charisma +6
- **Skills** Insight +4, Perception +7, Stealth +3
- **Senses** blindsight 30 ft., darkvision 120 ft., truesight 120 ft., passive Perception 17
- **Damage Resistances** poison; psychic; bludgeoning, piercing, slashing from nonmagical attacks that aren't adamantine
- **Damage Immunities** lightning
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened), [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed), [petrified](2-Mechanics/CLI/rules/conditions.md#Petrified), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** Common, Draconic
- **Challenge** 10

## Traits

***Amphibious.*** The dragon can breathe air and water.

***Constructed Nature.*** The dragon doesn't require air, food, drink, or sleep.

***False Appearance.*** While the dragon remains motionless, it is indistinguishable from an inanimate bronze statue.

***Faultless Tracker.*** The creature(s) that caused the dragon to animate becomes its quarry. The dragon knows the direction and distance to its quarry as long the quarry remains within Drakkenheim or until the dragon is destroyed.

***Immutable Form.*** The dragon is immune to any spell or effect that would alter its form.

***Magic Resistance.*** The dragon has advantage on saving throws against spells and other magical effects.

***Magic Weapons.*** The dragon's weapon attacks are magical.

***Rejuvenation.*** If the tower dragon is destroyed, it regains all its hit points in 1 hour unless a [disintegrate](2-Mechanics/CLI/spells/disintegrate.md) spell is cast on its remains.

## Actions

***Multiattack.*** The dragon makes three attacks: one with its bite and two with its claws.

***Bite.*** *Melee Weapon Attack:* `dice:1d20+8|noform|text(+8)` to hit, reach 10 ft., one target. *Hit:* `dice:2d10+5|noform|avg|text(16)` (`2d10 + 5`) piercing damage.

***Claw.*** *Melee Weapon Attack:* `dice:1d20+8|noform|text(+8)` to hit, reach 5 ft., one target. *Hit:* `dice:2d6+5|noform|avg|text(12)` (`2d6 + 5`) slashing damage.

***Breath Weapons (Recharge 5-6).*** The dragon uses one of the following breath weapons.

- **Lightning Breath.** The dragon exhales lightning in a 60-foot line that is 5 feet wide. Each creature in that line must make a DC 15 Dexterity saving throw, taking `dice:10d10|noform|avg|text(55)` (`10d10`) lightning damage on a failed save, or half as much damage on a successful one.  
- **Repulsion Breath.** The dragon exhales repulsion energy in a 30-foot cone. Each creature in that area must succeed on a DC 15 Strength saving throw. On a failed save, the creature is pushed 40 feet away from the dragon.  
```
^statblock