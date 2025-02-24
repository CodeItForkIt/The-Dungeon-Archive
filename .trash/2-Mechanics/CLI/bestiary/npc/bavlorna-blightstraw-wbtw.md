---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/wbtw
- monster/cr/7
- monster/size/medium
- monster/type/fey/hag
aliases: ["Bavlorna Blightstraw"]
---
# Bavlorna Blightstraw
*Source: The Wild Beyond the Witchlight p. 216*  

Younger than Skabatha and older than Endelyn, Bavlorna is called Slack-jawed Lorna because her wide mouth is prone to hang agape. Flies flit in and out of it. She is the hag of the present, the here and now, the moment to moment. Those desperate individuals who seek her out do so to find a remedy for a nagging problem or anxiety. Though she despises unannounced visitors, a tragic tale of woe and misery puts her in a bargaining mood. If these visitors enter into an agreement with Bavlorna, she'll use her powers to resolve their pressing problem in exchange for something of use to her.

```ad-statblock
title: Bavlorna Blightstraw
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/WBtW/Bavlorna%20Blightstraw.webp#token)
*Medium fey (hag), Neutral Evil*

- **Armor Class** 15 (natural armor)
- **Hit Points** 110 (`13d8 + 52`)
- **Speed** 30 ft., swim 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|22 (+6)|11 (+0)|18 (+4)|16 (+3)|12 (+1)|15 (+2)|

- **Proficiency Bonus** +3
- **Saving Throws** Constitution +7, Intelligence +6, Wisdom +4, Charisma +5
- **Skills** Arcana +9, Deception +5, Perception +4, Stealth +3
- **Senses** truesight 60 ft., passive Perception 14
- **Languages** Common, Elvish, Sylvan
- **Challenge** 7

## Traits

***Amphibious.*** Bavlorna can breathe air and water.

***Boon of Immortality.*** Bavlorna is immune to any effect that would age her, and she can't die from old age.

***Widdershins Allergy.*** If a creature within 10 feet of Bavlorna uses at least 10 feet of movement to run in place counterclockwise, Bavlorna is overcome by a fit of sneezing and can't cast spells until the end of her next turn. In addition, any creature Bavlorna has swallowed is immediately expelled and falls [prone](2-Mechanics/CLI/rules/conditions.md#Prone) in an unoccupied space within 5 feet of her.

***Spellcasting.*** Bavlorna casts one of the following spells, requiring no material components and using Intelligence as the spellcasting ability (spell save DC 14):

**At will**: [detect magic](2-Mechanics/CLI/spells/detect-magic.md)

**1/day**: [plane shift](2-Mechanics/CLI/spells/plane-shift.md) (self only)

**2/day each**: [create food and water](2-Mechanics/CLI/spells/create-food-and-water.md), [polymorph](2-Mechanics/CLI/spells/polymorph.md), [remove curse](2-Mechanics/CLI/spells/remove-curse.md)

## Actions

***Multiattack.*** Bavlorna makes one Bite attack and one Withering Ray attack.

***Bite.*** *Melee Weapon Attack:* `dice:1d20+9|noform|text(+9)` to hit, reach 5 ft., one target. *Hit:* `dice:2d6+6|noform|avg|text(13)` (`2d6 + 6`) piercing damage, and the target is [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) (escape DC 16) if it is a Medium or smaller creature. Until the grapple ends, the target is [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained), and Bavlorna can't use her Bite attack on another target.

***Withering Ray.*** *Ranged Spell Attack:* `dice:1d20+6|noform|text(+6)` to hit, range 60 ft., one target. *Hit:* `dice:4d6+3|noform|avg|text(17)` (`4d6 + 3`) necrotic damage.

***Create Lornlings (Recharge 5-6).*** Bavlorna creates one or two 1-foot-tall duplicates of herself, called lornlings (use the Quickling stat block in appendix C). Each lornling appears in an unoccupied space within 5 feet of Bavlorna, obeys her commands, and takes its turn immediately after hers. A lornling lasts for 1 hour, until it or Bavlorna dies, or until Bavlorna dismisses it as an action. Bavlorna can have no more than eight lornlings in existence at a time.

## Bonus Actions

***Swallow.*** Bavlorna swallows a Small or smaller creature she is grappling, ending the grapple on it. The swallowed creature is [blinded](2-Mechanics/CLI/rules/conditions.md#Blinded) and [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained), it has total cover against attacks and other effects outside Bavlorna, and it takes `dice:3d6|noform|avg|text(10)` (`3d6`) acid damage at the start of each of its turns. If the swallowed creature is one of Bavlorna's lornlings, Bavlorna gains all the lornling's memories when the acid damage reduces it to 0 hit points.

Bavlorna can have only one creature swallowed at a time. If Bavlorna dies, a swallowed creature is no longer [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained) and can escape from the corpse using 5 feet of movement, exiting [prone](2-Mechanics/CLI/rules/conditions.md#Prone).
```
^statblock