---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/coa
- monster/cr/16
- monster/size/huge
- monster/type/monstrosity
statblock: inline
aliases: ["Miasmorne"]
---
# [Miasmorne](Mechanics\bestiary\monstrosity/miasmorne-coa.md)
*Source: Chains of Asmodeus p. 246*  

Avernus is a bleak wasteland of jagged mountains and metal-studded hills, but the true ugliness to a devil's eyes is in the scars of war where demonic corpses, arms, and armor pile, infecting the plane with their chaotic ichor and breeding fresh monsters to trouble the order of the Nine Hells. The miasmorne were bred to clean up after Abyssal invasion: great lumbering Monstrosities able to devour demonic flesh, armor, weapons, and ruined war engines and return the plane to its pristine starkness. The monsters prospered beyond anyone's reckoning and now drag their bellies across many layers of the Nine Hells.

## Voracious Detritovores

Miasmorne resemble bulky, wingless dragons, their broad heads flanked with great fans that they spread when challenged. While they will gorge themselves on dead flesh—or create fresh corpses with their impressive teeth and jaws—their preferred meal is mineral. Where their populations have grown, they seek out concentrations of metal. Iron and steel are their staple fare, but they will take gold, silver, adamantine or mithril if available. As infernal cities and fortresses are often constructed of iron this leads to literal holes in the Fiends' security.

## Armored in Rust

As well as sustaining the monsters, the metals they devour go towards fortifying their hides, bones, and jaws. Miasmorne are formidably heavy and strong, proof against mundane blades and as resistant to heat as most denizens of the Nine Hells. Not naturally aggressive, the dull-witted brutes are hard to dissuade once they decide to feed. Miasmorne saliva corrodes metal efficiently, and they frequently pause mid-fight to slobber down the brittle flakes of whatever they've just destroyed. Under threat, their head fans bristle with thousands of extruded metal spines which they launch in a cloud of flechettes at foes, scouring the air both with sharp-edged missiles and a great spray of their rusting spittle. When injured, those that have devoured magic weapons or defenses manifest those same effects in their hide and claws, expending their internal store of swallowed arcana to drive away those who disturb their feasting.

## Pests and War-beasts

Miasmorne are a serious problem in some regions, chewing at the walls of castles and cities, swallowing whole armories, and tearing the armaments off the hosts of the Nine Hells. Mortal intruders who can lure the creatures with meals of enchanted or high-quality metal can even use them as siege engines to get past infernal walls. In other parts of the Nine Hells, the creatures are kept as semi-domesticated guards or waste disposal monsters. In Avernus, where they were first bred, Zariel maintains a crack corps of handlers who goad the beasts into wallowing through hosts of invading demons, chewing on Abyssal mail, and eating the prized magic blades of demon princes.

```statblock
"name": "Miasmorne (CoA)"
"size": "Huge"
"type": "monstrosity"
"alignment": "Unaligned"
"ac": !!int "19"
"ac_class": "natural armor"
"hp": !!int "230"
"hit_dice": "20d12 + 100"
"stats":
- !!int "22"
- !!int "10"
- !!int "21"
- !!int "3"
- !!int "10"
- !!int "10"
"speed": "20 ft., burrow 20 ft."
"saves":
  "Strength": !!int "11"
  "Constitution": !!int "10"
"skillsaves":
  "Athletics": !!int "16"
  "Arcana": !!int "1"
  "Survival": !!int "5"
"damage_immunities": "acid; fire; bludgeoning, piercing, slashing from nonmagical\
  \ attacks"
"condition_immunities": "[petrified](Mechanics/Rules/conditions.md#Petrified)"
"senses": "tremorsense 60 ft., passive Perception 10"
"languages": ""
"cr": "16"
"traits":
- "desc": "If a creature takes acid damage from the miasmorne and that creature is\
    \ wearing nonmagical metal armor, that armor is destroyed."
  "name": "Acidic Attacks"
- "desc": "After a nonmagical metal weapon hits the miasmorne that weapon melts and\
    \ is destroyed. Likewise, nonmagical metal ammunition that hits the miasmorne\
    \ is destroyed."
  "name": "Acidic Hide"
"actions":
- "desc": "The miasmorne makes three attacks using Bite, Flechette or a combination\
    \ of the two."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +11 to hit, reach 5 ft., one target. Hit: 22\
    \ (3d10 + 6) bludgeoning damage plus 7 (2d6) acid damage. If the target is\
    \ a Large or smaller creature, it has the [grappled](Mechanics/Rules/conditions.md#Grappled)\
    \ condition (escape DC 18). The miasmorne can't make Bite attacks while a creature\
    \ is [grappled](Mechanics/Rules/conditions.md#Grappled) in this way."
  "name": "Bite"
- "desc": "Ranged Weapon Attack: +11 to hit, range 60/120 ft., one target. Hit:\
    \ 16 (3d6 + 6) acid damage."
  "name": "Flechette"
- "desc": "The miasmorne launches flechettes from its fins in a 90-foot cone in front\
    \ of it. All creatures in the cone must make a DC 19 Dexterity saving throw, taking\
    \ 21 (6d6) acid damage on a failed save, or half as much damage on a successful\
    \ one."
  "name": "Flechette Spray (Recharge 5-6)"
- "desc": "The miasmorne secretes an acidic solution, then sprays it around itself.\
    \ All creatures in a 20-foot-radius sphere, centered on the miasmorne, must make\
    \ a DC 19 Dexterity saving throw. Targets take 26 (4d12) acid damage on a failed\
    \ save, or half as much damage on a successful one. All nonmagical metals within\
    \ the radius that aren't being carried, as well as nonmagical metal items carried\
    \ or worn by creatures that failed the save, are destroyed."
  "name": "Acidic Secretion (1/Day)"
"source":
- "CoA"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/CoA/Miasmorne.webp"
```
^statblock