---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/tob1-2023
- monster/cr/6
- monster/environment/desert
- monster/size/medium
- monster/type/fey
aliases: ["Sand Hag"]
---
# Sand Hag
*Source: Tome of Beasts 1 (2023 Edition) p. 229*  

*This withered crone glares malevolently, her face framed by lank, gray hair. Her malicious grin is filled with shark teeth and drool trickles from her lips.*

## Hatred of Beauty

Dressed in tattered robes and skeletally thin, sand hags are terrifying crones that haunt desert ruins and forgotten oases. Their hatred for things of beauty and peace is terrible to behold. A sand hag uses her illusions and mimicry to lure travelers into an ambush.

## False Oasis

These hags delight in tricking a caravan into an illusory oasis, killing all the riding animals and pack animals so the travelers can't flee, and then terrifying and slaughtering them one by one.

## Drain Bodies

For the slaughter of animals or humanoids, a sand hag prefers to rely on her claws, which drain the moisture from her victims. They leave the mummified remnants in postures of life—tied to a saddle or atop a guard tower—to terrify others.

## Statblock

```ad-statblock
title: Sand Hag
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ToB1-2023/Sand%20Hag.webp#token)
*Medium fey, Chaotic Evil*

- **Armor Class** 17 (natural armor)
- **Hit Points** 120 (`16d8 + 48`)
- **Speed** 30 ft., burrow 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|18 (+4)|15 (+2)|16 (+3)|16 (+3)|14 (+2)|16 (+3)|

- **Proficiency Bonus** +3
- **Saving Throws** ⏤
- **Skills** Deception +6, Perception +5, Stealth +5
- **Senses** darkvision 120 ft., passive Perception 15
- **Languages** Common, Dwarvish, Giant, Gnomish
- **Challenge** 6

## Traits

***Magic Resistance.*** The sand hag has advantage on saving throws against spells and other magical effects.

***Mimicry.*** The sand hag can mimic animal sounds and Humanoid voices. A creature that hears the sounds can tell they are imitations with a successful DC 16 Wisdom ([Insight](2-Mechanics/CLI/rules/skills.md#Insight)) check.

***Scorpion Walk.*** Difficult terrain composed of sand or gravel doesn't cost the hag extra movement. In addition, while in sandy terrain, she doesn't leave tracks and has tremorsense out to a range of 30 feet.

***Spellcasting.*** The sand hag casts one of the following spells, requiring no material components and using Charisma as the spellcasting ability (spell save DC 14):

**At will**: [silent image](2-Mechanics/CLI/spells/silent-image.md)

**3/day each**: [hallucinatory terrain](2-Mechanics/CLI/spells/hallucinatory-terrain.md) (as an action), [major image](2-Mechanics/CLI/spells/major-image.md)

## Actions

***Multiattack.*** The hag makes three Claw attacks. If two Claw attacks hit one creature, the target must succeed on a DC 14 Constitution saving throw or suffer one level of [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion). A creature can't suffer more than two levels of [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion) from this effect.

***Claw.*** *Melee Weapon Attack:* `dice:1d20+7|noform|text(+7)` to hit, reach 5 ft., one target. *Hit:* `dice:2d8+4|noform|avg|text(13)` (`2d8 + 4`) slashing damage.

***Illusory Appearance.*** The sand hag covers herself and anything she is wearing or carrying with a magical illusion that makes her look like another creature of her general size and Humanoid shape. The illusion ends if the hag takes a bonus action to end it or if she dies.

The changes wrought by this effect fail to hold up to physical inspection. Otherwise, a creature must take an action to visually inspect the illusion and succeed on a DC 20 Intelligence ([Investigation](2-Mechanics/CLI/rules/skills.md#Investigation)) check to discern that the hag is disguised.

***Scouring Sirocco (Recharge 5-6).*** The sand hag generates a blast of hot wind and sand in a 30-foot cone. Each creature in the area must make a DC 14 Constitution saving throw. On a failure, a creature takes `dice:4d6|noform|avg|text(14)` (`4d6`) slashing damage and `dice:2d8|noform|avg|text(9)` (`2d8`) fire damage and is [blinded](2-Mechanics/CLI/rules/conditions.md#Blinded) for 1 minute. On a success, a creature takes half the damage and isn't [blinded](2-Mechanics/CLI/rules/conditions.md#Blinded). A [blinded](2-Mechanics/CLI/rules/conditions.md#Blinded) creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success. The area is heavily obscured by airborne sand until the start of the sand hag's next turn.
```
^statblock

## Environment

desert