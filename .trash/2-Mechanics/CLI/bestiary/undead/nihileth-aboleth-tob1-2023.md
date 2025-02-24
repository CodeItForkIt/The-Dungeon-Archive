---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/tob1-2023
- monster/cr/13
- monster/environment/coastal
- monster/environment/underdark
- monster/environment/underwater
- monster/size/large
- monster/type/undead
aliases: ["Nihileth Aboleth"]
---
# Nihileth Aboleth
*Source: Tome of Beasts 1 (2023 Edition) p. 9*  

*Eons ago, a group of aboleth left the Material Plane to wander through distant planes—seeing them through magical scrying was not enough, so these aboleth used astral magic and bodily travel to see far beyond normal realms*.

## A Forgotten Tribe

As ages passed, memories of those who departed slowly faded from the minds of those aboleth who remained behind. Those few aboleth who did remember that long ago some of their kin had gone plane-wandering assumed that the wanderers died in distant hells or paradises.

## Changed by Planar Wandering

The plane-wanderers hadn't died. Instead, their eons-long exposure to alien realms and the space between changed them, restructuring their life force, making them into something even more nightmarish—but better able to withstand both strange hells and golden realms of eldritch delight. They returned even more corrupt and powerful than when left, and these wandering nihileths returned to the mortal world intent on spreading the influence of the Void and the utter evil they found in the vast darkness between worlds.

## Undead Servitors

Humanoids, giants, and monstrosities that succumb to the nihileth's disease transform into servitors for the twisted aboleths. Most humanoids transform into nihilethic zombies, while the larger giants and monstrosities transform into nihilethic dominators. While the creatures retain much of the general shape they had in life, these servitors have translucent and slimy skin, and are adept swimmers, able to function in water or on land in service to their nihileth masters.

## A Nihileth's Lair

While aboleths create their lairs underwater, spending most of their time submerged, a nihileth can create a lair outside the water, often in a cave or a ruined, abandoned city. Nihileth lairs on land typically contain several pools of water and are often within at least 1 mile of a large body of water, as the nihileth's ability to fully function outside of water is limited.

## Statblock

```ad-statblock
title: Nihileth Aboleth
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ToB1-2023/Nihileth%20Aboleth.webp#token)
*Large undead, Chaotic Evil*

- **Armor Class** 17 (natural armor)
- **Hit Points** 157 (`21d10 + 42`)
- **Speed** 10 ft., fly 40 ft. (hover) in void ghost form, swim 40 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|21 (+5)| 9 (-1)|15 (+2)|18 (+4)|15 (+2)|18 (+4)|

- **Proficiency Bonus** +5
- **Saving Throws** Constitution +7, Intelligence +9, Wisdom +7
- **Skills** History +12, Perception +10
- **Senses** darkvision 120 ft., passive Perception 20
- **Damage Resistances** bludgeoning, piercing, slashing from nonmagical attacks
- **Damage Immunities** cold, necrotic, poison
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened), [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled), [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed), [petrified](2-Mechanics/CLI/rules/conditions.md#Petrified), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned), [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained)
- **Languages** telepathy 120 ft., Void Speech
- **Challenge** 13

## Traits

***Ghostly Body (Void Ghost Form Only).*** The nihileth has resistance to acid, fire, lightning, and thunder damage, it has immunity to the [prone](2-Mechanics/CLI/rules/conditions.md#Prone) condition, and it has immunity to bludgeoning, piercing, and slashing damage from nonmagical attacks. In addition, the nihileth can move through other creatures and objects as if they were difficult terrain. It takes `dice:1d10|noform|avg|text(5)` (`1d10`) force damage if it ends its turn inside an object.

***Infecting Telepathy.*** If a creature communicates telepathically with the nihileth, or deals psychic damage to it, the creature must succeed on a DC 15 Wisdom saving throw or become infected with the nihilethic rot disease.

***Nihilethic Rot.*** This disease takes 1 minute to manifest in an infected creature, during which time the disease can be removed with the [lesser restoration](2-Mechanics/CLI/spells/lesser-restoration.md) spell. After 1 minute, the creature's flesh becomes slimy and translucent, and the disease can be cured only by the [heal](2-Mechanics/CLI/spells/heal.md) spell or similar magic. Until this disease is cured, the creature can't regain hp unless it is submerged in water, and it can breathe air and water. The creature must be submerged in water at least once every 2 hours to avoid suffocating, and if it is outside a body of water, it takes `dice:2d6|noform|avg|text(7)` (`2d6`) acid damage every 10 minutes, unless moisture is applied to its skin before 10 minutes have passed. If a Humanoid dies while infected with this disease, it rises 1 minute later as a nihilethic zombie under the nihileth's control. If a Large giant or monstrosity dies while infected with this disease, it rises 1 minute later as a nihilethic dominator under the nihileth's control.

***Undead Fortitude.*** If damage reduces the nihileth to 0 hp, it must make a Constitution saving throw with a DC of 5 + the damage taken, unless the damage is radiant or from a critical hit. On a success, the nihileth drops to 1 hp instead.

***Undead Nature.*** The nihileth doesn't require air, food, drink, or sleep.

***Void Aura.*** The nihileth is surrounded by a chilling cloud. A creature that isn't a construct or undead and that starts its turn within 5 feet of the nihileth must succeed on a DC 15 Constitution saving throw or its speed is halved until the start of its next turn. In addition, a creature infected with nihilethic rot takes `dice:2d6|noform|avg|text(7)` (`2d6`) cold damage when it starts its turn within this aura.

## Actions

***Multiattack.*** The nihileth makes two Tentacle attacks and one Tail attack, or it makes three Withering Touch attacks.

***Tail (Undead Form Only).*** *Melee Weapon Attack:* `dice:1d20+10|noform|text(+10)` to hit, reach 10 ft. one target. *Hit:* `dice:3d6+5|noform|avg|text(15)` (`3d6 + 5`) bludgeoning damage.

***Tentacle (Undead Form Only).*** *Melee Weapon Attack:* `dice:1d20+10|noform|text(+10)` to hit, reach 10 ft., one target. *Hit:* `dice:2d6+5|noform|avg|text(12)` (`2d6 + 5`) bludgeoning damage, and the target must succeed on a DC 15 Constitution saving throw or contract the nihilethic rot disease (see the Nihilethic Rot trait).

***Withering Touch (Void Ghost Form Only).*** *Melee Spell Attack:* `dice:1d20+9|noform|text(+9)` to hit, reach 10 ft., one creature. *Hit:* `dice:3d6+4|noform|avg|text(14)` (`3d6 + 4`) necrotic damage.

## Bonus Actions

***Void Shape.*** The nihileth magically transforms into a dark purple, Void ghost form or back into its Undead form. Its statistics, other than its speed, resistances, and immunities, are the same in each form. Any equipment it is wearing or carrying changes with it. It reverts to its Undead form if it dies.

## Reactions

***Void Body.*** When the nihileth takes damage, it can reduce the damage to 0. Radiant damage can be reduced by only half.

## Legendary Actions

***Detect.*** The nihileth makes a Wisdom ([Perception](2-Mechanics/CLI/rules/skills.md#Perception)) check.

***Tail Swipe.*** The nihileth makes one Tail attack.

***Rotten Drain (Costs 2 Actions).*** One creature infected with the nihilethic rot disease within 30 feet of the nihileth takes `dice:3d6|noform|avg|text(10)` (`3d6`) psychic damage, and the nihileth regains hp equal to that amount.

![Nihileth Aboleth](2-Mechanics/CLI/bestiary/legendary-group/nihileth-aboleth-tob1-2023.md)
```
^statblock

## Environment

coastal, underdark, underwater