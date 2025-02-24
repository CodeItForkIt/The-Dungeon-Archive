---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/toa
- monster/cr/1-2
- monster/size/medium
- monster/type/plant
aliases: ["Tri-flower Frond"]
---
# Tri-flower Frond
*Source: Tomb of Annihilation p. 234*  

When fully grown, a tri-flower frond stands 6 to 7 feet tall. It has three bright, trumpet-shaped flowers, each as large as a human head and each one a different color: intense red, vivid orange, and bright yellow. Each flower can harm a creature in a different terrible way.

```ad-statblock
title: Tri-flower Frond
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ToA/Tri-flower%20Frond.webp#token)
*Medium plant, Unaligned*

- **Armor Class** 10
- **Hit Points** 11 (`2d8 + 2`)
- **Speed** 5 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|14 (+2)|15 (+2)|12 (+1)| 9 (-1)|13 (+1)| 9 (-1)|

- **Proficiency Bonus** +2
- **Saving Throws** ⏤
- **Skills** ⏤
- **Senses** blindsight 30 ft., passive Perception 10
- **Condition Immunities** [blinded](2-Mechanics/CLI/rules/conditions.md#Blinded), [deafened](2-Mechanics/CLI/rules/conditions.md#Deafened), [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [prone](2-Mechanics/CLI/rules/conditions.md#Prone)
- **Languages** —
- **Challenge** 1/2

## Actions

***Multiattack.*** The tri-flower frond uses its orange blossom, then its yellow blossom, and then its red blossom.

***Orange Blossom.*** The tri-flower frond chooses one creature it can see within 5 feet of it. The target must succeed on a DC 11 Constitution saving throw or be [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned) for 1 hour. While [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned) in this way, the target is [unconscious](2-Mechanics/CLI/rules/conditions.md#Unconscious). At the end of each minute, the [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned) target can repeat the saving throw, ending the effect on itself on a success.

***Yellow Blossom.*** The tri-flower frond chooses one creature it can see within 5 feet of it. The target must succeed on a DC 11 Dexterity saving throw, or it is covered with corrosive sap and takes 5 acid damage at the start of each of its turns. Dousing the target with water reduces the acid damage by 1 point per pint or flask of water used.

***Red Blossom.*** *Melee Weapon Attack:* `dice:1d20+2|noform|text(+2)` to hit, reach 5 ft., one creature. *Hit:* `dice:1d4|noform|avg|text(2)` (`1d4`) piercing damage, and the target is [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) (escape DC 11). Until this grapple ends, the target takes `dice:2d4|noform|avg|text(5)` (`2d4`) poison damage at the start of each of its turns. The red blossom can grapple only one target at a time. Another creature within reach of the tri-flower frond can use its action to end the grapple on the target.
```
^statblock