---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/tob1-2023
- monster/cr/6
- monster/environment/forest
- monster/environment/urban
- monster/size/medium
- monster/type/fey
aliases: ["Mirror Hag"]
---
# Mirror Hag
*Source: Tome of Beasts 1 (2023 Edition) p. 227*  

*This hunchbacked crone's sallow skin is covered with growths and lesions.*

## Hideous Hex

Until a creature can see past the hag's deformities, she curses it with the pain of a disfigured life. Some mirror hags do this for the betterment of all, but most do it because causing pain amuses them.

## Warped Features

Mirror hags are hunchbacked, with growths and lesions covering their skin. Their joints misalign, and the extremities of their bones press against their skin. However, it is their faces that inspire legends: the blackest moles sprouting long white hairs, noses resembling half-eaten carrots, and eyes mismatched in size, color, and alignment. If a creature recoils from a mirror hag's looks, she bestows her reconfiguring curse on it.

## Mirror Covens

Mirror hags can form a coven with two other hags. Generally, mirror hags only form covens with other mirror hags, but from time to time a mirror hag will join a coven of witches or green hags.

## Statblock

```ad-statblock
title: Mirror Hag
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ToB1-2023/Mirror%20Hag.webp#token)
*Medium fey, Chaotic Neutral*

- **Armor Class** 16 (natural armor)
- **Hit Points** 147 (`14d8 + 84`)
- **Speed** 30 ft., fly 10 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|15 (+2)|16 (+3)|22 (+6)|12 (+1)|14 (+2)|19 (+4)|

- **Proficiency Bonus** +3
- **Saving Throws** ⏤
- **Skills** ⏤
- **Senses** darkvision 60 ft., passive Perception 12
- **Damage Resistances** thunder
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened)
- **Languages** Common, Sylvan
- **Challenge** 6

## Traits

***Confounding Ugliness.*** Any Humanoid that starts its turn within 60 feet of the hag and can see the hag's true form must succeed on a DC 15 Wisdom saving throw or be [incapacitated](2-Mechanics/CLI/rules/conditions.md#Incapacitated) until the start of its next turn. If the Humanoid's saving throw is successful, it is immune to the hag's Confounding Ugliness for the next 24 hours.

Unless the target is surprised or the revelation of the hag's true form is sudden, the target can avert its eyes to avoid the saving throw at the start of its turn. If the Humanoid does so, it can't see the hag until the start of its next turn, when it can avert its eyes again. If the Humanoid looks at the hag in the meantime, it must immediately make the save.

***Spellcasting.*** The blood hag casts one of the following spells, requiring no material components and using Charisma as the spellcasting ability (spell save DC 15):

**At will**: [disguise self](2-Mechanics/CLI/spells/disguise-self.md), [ray of enfeeblement](2-Mechanics/CLI/spells/ray-of-enfeeblement.md)

**1/day each**: [dispel magic](2-Mechanics/CLI/spells/dispel-magic.md), [locate creature](2-Mechanics/CLI/spells/locate-creature.md)

## Actions

***Multiattack.*** The mirror hag can use her Reconfiguring Curse. She then makes one Bite attack and two Claw attacks. She can replace her Bite attack with a use of Spellcasting.

***Bite.*** *Melee Weapon Attack:* `dice:1d20+6|noform|text(+6)` to hit, reach 5 ft., one target. *Hit:* `dice:2d8+3|noform|avg|text(12)` (`2d8 + 3`) piercing damage plus `dice:2d4|noform|avg|text(5)` (`2d4`) necrotic damage.

***Claw.*** *Melee Weapon Attack:* `dice:1d20+6|noform|text(+6)` to hit, reach 5 ft., one target. *Hit:* `dice:1d6+3|noform|avg|text(6)` (`1d6 + 3`) slashing damage plus `dice:2d4|noform|avg|text(5)` (`2d4`) necrotic damage.

***Reconfiguring Curse.*** The mirror hag curses one creature she can see within 60 feet of her, corrupting its form. The target must make a DC 15 Constitution saving throw. On a success, the target is immune to the hag's Reconfiguring Curse for the next 24 hours. On a failure, the target is cursed, suffering one of the following effects of the hag's choice:

- **Disfigured.** The target's skin erupts with growths and lesions, and it has disadvantage on all Charisma checks made to influence Humanoids, except for [Intimidation](2-Mechanics/CLI/rules/skills.md#Intimidation).  
- **Sickly.** The target becomes frail and unhealthy, and it has disadvantage on Constitution saving throws. It regains only half its lost hp at the end of a long rest, and it halves the result of any Hit Dice rolled to restore hp during a short rest.  
- **Twisted.** The target's limbs and spine become bent and clumsy. It has disadvantage on all Dexterity checks and Dexterity saving throws, and its speed is reduced by 10 feet.  
- **Withered.** The target's muscles atrophy, and it has disadvantage on all Strength checks and Strength saving throws.  
```
^statblock

## Environment

forest, urban