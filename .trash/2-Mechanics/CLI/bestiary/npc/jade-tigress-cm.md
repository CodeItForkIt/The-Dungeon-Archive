---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/cm
- monster/cr/8
- monster/size/medium
- monster/type/humanoid/human
aliases: ["Jade Tigress"]
---
# Jade Tigress
*Source: Candlekeep Mysteries p. 166*  

Jade Tigress is a powerfully built woman whose body has been honed by intense physical training. She is rugged in appearance, with jet-black hair, hazel eyes, and a long, thin scar running across her right cheek. She matches the description of one of the thieves who infiltrated Candlekeep.

```ad-statblock
title: Jade Tigress
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/CM/Jade%20Tigress.webp#token)
*Medium humanoid (human), Lawful Evil*

- **Armor Class** 15 (Unarmored Defense)
- **Hit Points** 71 (`11d8 + 21`)
- **Speed** 40 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|18 (+4)|14 (+2)|15 (+2)|11 (+0)|16 (+3)|11 (+0)|

- **Proficiency Bonus** +3
- **Saving Throws** Strength +7, Constitution +5
- **Skills** Athletics +7, Insight +6, Intimidation +3, Perception +6
- **Senses** passive Perception 16
- **Damage Resistances** poison
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened)
- **Languages** Common
- **Challenge** 8

## Traits

***Unarmored Defense.*** While Jade Tigress is wearing no armor and wielding no shield, her AC includes her Wisdom modifier.

## Actions

***Multiattack.*** Jade Tigress makes three attacks.

***Force Strike.*** *Melee Weapon Attack:* `dice:1d20+7|noform|text(+7)` to hit, reach 5 ft., one target. *Hit:* `dice:2d8+4|noform|avg|text(13)` (`2d8 + 4`) force damage, and if the target is a creature, it must succeed on a DC 15 Constitution saving throw or be [stunned](2-Mechanics/CLI/rules/conditions.md#Stunned) until the end of Jade Tigress's next turn.

***Poisoned Dart.*** *Ranged Weapon Attack:* `dice:1d20+5|noform|text(+5)` to hit, range 20/60 ft., one target. *Hit:* `dice:1d4+2|noform|avg|text(4)` (`1d4 + 2`) piercing damage plus `dice:3d4|noform|avg|text(7)` (`3d4`) poison damage, and the target must succeed on a DC 15 Constitution saving throw or gain 1 level of [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion).

***Heal Self (Recharges after a Long Rest).*** Jade Tigress regains `dice:2d8+2|noform|avg` (`2d8 + 2`) hit points, and all levels of [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion) end on her.

## Bonus Actions

***Nimble Escape.*** Jade Tigress takes the Disengage or Hide action.

## Reactions

***Deflect Missile.*** In response to being hit by a ranged weapon attack, Jade Tigress deflects the missile. The damage she takes from the attack is reduced by `dice:1d10+9|noform|avg` (`1d10 + 9`). If the damage is reduced to 0, Jade Tigress catches the missile if it's small enough to hold in one hand and Jade Tigress has a hand free.
```
^statblock