---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/ftd
- monster/cr/17
- monster/size/huge
- monster/type/undead
aliases: ["Ghost Dragon"]
---
# Ghost Dragon
*Source: Fizban's Treasury of Dragons p. 203*  

A dragon's attachment to a hoard can be strong enough to bind the dragon's spirit to existence after death. Such a ghost dragon haunts the hoard, often forming an attachment to a single priceless object that becomes the focus of the ghost dragon's Undead existence.

A ghost dragon is a translucent and incorporeal version of the original dragon. Though its breath weapon resembles ghostly flames, lightning, or acid, it carries an otherworldly curse. The breath's shadowy mist can induce waking nightmares.

```ad-statblock
title: Ghost Dragon
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/FTD/Ghost%20Dragon.webp#token)
*Huge undead, Any alignment*

- **Armor Class** 10
- **Hit Points** 324 (`24d12 + 168`)
- **Speed** 40 ft., fly 80 ft. (hover)

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|20 (+5)|10 (+0)|25 (+7)|16 (+3)|15 (+2)|19 (+4)|

- **Proficiency Bonus** +6
- **Saving Throws** Constitution +13, Wisdom +8, Charisma +10
- **Skills** Perception +14, Stealth +12
- **Senses** blindsight 60 ft., darkvision 120 ft., passive Perception 24
- **Damage Resistances** bludgeoning, piercing, slashing
- **Damage Immunities** acid, cold, necrotic, poison
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened), [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled), [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed), [petrified](2-Mechanics/CLI/rules/conditions.md#Petrified), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned), [prone](2-Mechanics/CLI/rules/conditions.md#Prone), [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained)
- **Languages** Common, Draconic, telepathy 120 ft.
- **Challenge** 17

## Traits

***Incorporeal Movement.*** The ghost dragon can move through other creatures and objects as if they were difficult terrain. It takes `dice:1d10|noform|avg|text(5)` (`1d10`) force damage if it ends its turn inside an object.

***Legendary Resistance (3/Day).*** If the ghost dragon fails a saving throw, it can choose to succeed instead.

***Unusual Nature.*** The ghost dragon doesn't require air, food, drink, or sleep.

## Actions

***Multiattack.*** The ghost dragon makes one Bite attack and two Claw attacks.

***Bite.*** *Melee Weapon Attack:* `dice:1d20+11|noform|text(+11)` to hit, reach 10 ft., one target. *Hit:* `dice:6d8+5|noform|avg|text(32)` (`6d8 + 5`) cold damage, and the target's speed is halved until the start of the dragon's next turn.

***Claw.*** *Melee Weapon Attack:* `dice:1d20+11|noform|text(+11)` to hit, reach 5 ft., one target. *Hit:* `dice:2d8+5|noform|avg|text(14)` (`2d8 + 5`) necrotic damage.

***Terrifying Breath (Recharge 6).*** The ghost dragon exhales shadowy mist in a 90-foot cone. Each creature in that area must make a DC 21 Constitution saving throw. On a failed save, the creature takes `dice:9d8|noform|avg|text(40)` (`9d8`) cold damage and is [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened) of the ghost dragon for 1 minute. On a successful save, the creature takes half as much damage and isn't [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened).

While [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened) of the ghost dragon, a creature is [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed). The [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened) creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.

If a creature's saving throw is successful or the effect ends for it, the creature is immune to this ghost dragon's Terrifying Breath for the next 24 hours.
```
^statblock