---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/ftd
- monster/cr/30
- monster/size/gargantuan
- monster/type/dragon/chromatic
aliases: ["Aspect of Tiamat"]
---
# Aspect of Tiamat
*Source: Fizban's Treasury of Dragons p. 166*  

The five-headed progenitor of chromatic dragons, Tiamat embodies the vices of evil dragons. Since the destruction of the First World, she has dwelled in the Nine Hells—some say by choice. But others claim that she is imprisoned there to punish her for the evils she perpetrated when the gods sought to colonize the First World with their followers.

Mortals who hunger for power and wealth often swear fealty to Tiamat in pursuit of those goals. Many of her followers have attempted to break her out of Avernus—and failed—but even while she remains in the Nine Hells, Tiamat can send her aspect to manifest in the Material Plane. A follower with enough power and anger, and with a hoard worthy of ancient dragons, can sacrifice it all to unleash the wrath of the dragon queen on a world.

The aspect of Tiamat has the body of a titanic dragon with five heads, each the shape and hue of a different chromatic dragon. Each head might speak separately and have different mannerisms, but they are all Tiamat. Once unleashed, the aspect of Tiamat rampages across the world, acquiring any treasure she can find and destroying any creature that dares to cross her path.

```ad-statblock
title: Aspect of Tiamat
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/FTD/Aspect%20of%20Tiamat.webp#token)
*Gargantuan dragon (chromatic), Chaotic Evil*

- **Armor Class** 23 (natural armor)
- **Hit Points** 574 (`28d20 + 280`)
- **Speed** 60 ft., burrow 60 ft., fly 120 ft., swim 60 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|30 (+10)|14 (+2)|30 (+10)|21 (+5)|20 (+5)|26 (+8)|

- **Proficiency Bonus** +9
- **Saving Throws** Dexterity +11, Constitution +19, Wisdom +14, Charisma +17
- **Skills** Intimidation +26, Perception +23
- **Senses** truesight 120 ft., passive Perception 33
- **Damage Immunities** acid; cold; fire; lightning; poison; bludgeoning, piercing, slashing from nonmagical attacks
- **Condition Immunities** [blinded](2-Mechanics/CLI/rules/conditions.md#Blinded), [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [deafened](2-Mechanics/CLI/rules/conditions.md#Deafened), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned), [stunned](2-Mechanics/CLI/rules/conditions.md#Stunned)
- **Languages** Common, Draconic, Infernal
- **Challenge** 30

## Traits

***Chromatic Wrath (Recharges after a Short or Long Rest).*** If the aspect would be reduced to 0 hit points, her current hit point total instead resets to 500 hit points, she recharges her Chromatic Flames, and she regains any expended uses of Legendary Resistance. Additionally, the aspect can now use the options in the "Mythic Actions" section for 1 hour. Award a party an additional 155,000 XP (310,000 XP total) for defeating the aspect of Tiamat after her Chromatic Wrath activates.

***Legendary Resistance (5/Day).*** If the aspect fails a saving throw, she can choose to succeed instead.

## Actions

***Multiattack.*** The aspect makes one Bite attack, one Claw attack, and one Tail attack.

***Bite.*** *Melee Weapon Attack:* `dice:1d20+19|noform|text(+19)` to hit, reach 20 ft., one target. *Hit:* `dice:2d12+10|noform|avg|text(23)` (`2d12 + 10`) piercing damage plus `dice:3d12|noform|avg|text(19)` (`3d12`) force damage.

***Claw.*** *Melee Weapon Attack:* `dice:1d20+19|noform|text(+19)` to hit, reach 15 ft., one target. *Hit:* `dice:2d10+10|noform|avg|text(21)` (`2d10 + 10`) slashing damage. If the target is a Huge or smaller creature, it is [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) (escape DC 20) and is [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained) until this grapple ends. The aspect can have only one creature [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) this way at a time.

***Tail.*** *Melee Weapon Attack:* `dice:1d20+19|noform|text(+19)` to hit, reach 15 ft., one target. *Hit:* `dice:2d12+10|noform|avg|text(23)` (`2d12 + 10`) bludgeoning damage. If the target is a creature, it must succeed on a DC 27 Strength saving throw or be knocked [prone](2-Mechanics/CLI/rules/conditions.md#Prone).

***Chromatic Flames (Recharge 5-6).*** The aspect exhales multicolored flames in a 300-foot cone. Each creature in that area must make a DC 27 Dexterity saving throw. On a failed save, the creature takes `dice:11d12|noform|avg|text(71)` (`11d12`) damage of a type of the aspect's choosing: acid, cold, fire, lightning, or poison. On a successful save, the creature takes half as much damage.

## Legendary Actions

***Attack.*** The aspect makes one Claw or Tail attack.

***Furious Bite (Costs 2 Actions).*** The aspect makes one Bite attack. If the attack hits a creature, the target must succeed on a DC 27 Wisdom saving throw or become [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened) of the aspect until the end of its next turn.
```
^statblock