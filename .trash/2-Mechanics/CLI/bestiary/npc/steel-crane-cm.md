---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/cm
- monster/cr/8
- monster/size/medium
- monster/type/humanoid/human
aliases: ["Steel Crane"]
---
# Steel Crane
*Source: Candlekeep Mysteries p. 164*  

Steel Crane is tall and slender. He is exceptionally handsome, with neat silver hair and deep green eyes, and carries himself with the grace of a dancer.

A strip of cloth was torn from the left sleeve of Steel Crane's white robe during the raid on Candlekeep, and Steel Crane hasn't yet bothered to mend the garment. The robe's damage is clearly visible—evidence of Steel Crane's role in the theft.

```ad-statblock
title: Steel Crane
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/CM/Steel%20Crane.webp#token)
*Medium humanoid (human), Lawful Evil*

- **Armor Class** 17 (Unarmored Defense)
- **Hit Points** 76 (`9d8 + 36`)
- **Speed** 40 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|13 (+1)|18 (+4)|18 (+4)|13 (+1)|17 (+3)|14 (+2)|

- **Proficiency Bonus** +3
- **Saving Throws** Dexterity +7, Intelligence +4
- **Skills** Acrobatics +7, Deception +5, Perception +6, Stealth +7
- **Senses** passive Perception 16
- **Damage Resistances** poison, psychic
- **Languages** Common
- **Challenge** 8

## Traits

***Unarmored Defense.*** While Steel Crane is wearing no armor and wielding no shield, his AC includes his Wisdom modifier.

## Actions

***Multiattack.*** Steel Crane makes three attacks.

***Force Strike.*** *Melee Weapon Attack:* `dice:1d20+7|noform|text(+7)` to hit, reach 5 ft., one target. *Hit:* `dice:1d8+4|noform|avg|text(8)` (`1d8 + 4`) force damage, and if the target is a creature, it must succeed on a DC 15 Constitution saving throw or be [stunned](2-Mechanics/CLI/rules/conditions.md#Stunned) until the start of Steel Crane's next turn.

***Whip.*** *Melee Weapon Attack:* `dice:1d20+7|noform|text(+7)` to hit, reach 10 ft., one target. *Hit:* `dice:1d4+4|noform|avg|text(6)` (`1d4 + 4`) slashing damage or, if the target is a creature, Steel Crane can grapple the target instead (escape DC 15). Steel Crane can't make attacks with the whip while using it to grapple a creature. Anytime on his turn, he can release a creature [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) by the whip (no action required).

***Heal Self (Recharges after a Long Rest).*** Steel Crane regains `dice:2d8+4|noform|avg` (`2d8 + 4`) hit points, and all levels of [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion) end on him.

## Reactions

***Deflect Missile.*** In response to being hit by a ranged weapon attack, Steel Crane deflects the missile. The damage he takes from the attack is reduced by `dice:1d10+10|noform|avg` (`1d10 + 10`). If the damage is reduced to 0, Steel Crane catches the missile if it's small enough to hold in one hand and Steel Crane has a hand free.

***Slow Descent (3/Day).*** When Steel Crane falls, he can slow his descent, taking no damage from the fall.
```
^statblock