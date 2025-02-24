---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/mpp
- monster/cr/1
- monster/size/tiny
- monster/type/fiend
aliases: ["Vargouille Reflection"]
---
# Vargouille Reflection
*Source: Morte's Planar Parade p. 52, Sigil and the Outlands, Turn of Fortune's Wheel*  

Vargouilles are flying Fiends that resemble disembodied Humanoid heads with wings. While most vargouilles roam the planes to curse Humanoids and create more vargouilles, a variant known as the vargouille reflection resides in Undersigil. When a vargouille reflection spots a Humanoid target, it takes on that creature's visage, terrifying that creature by appearing as its own disembodied head.

```ad-statblock
title: Vargouille Reflection
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/MPP/Vargouille%20Reflection.webp#token)
*Tiny fiend, typically  Chaotic Evil*

- **Armor Class** 12
- **Hit Points** 22 (`5d4 + 10`)
- **Speed** 5 ft., fly 40 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
| 6 (-2)|15 (+2)|14 (+2)| 6 (-2)|10 (+0)| 2 (-4)|

- **Proficiency Bonus** +2
- **Saving Throws** ⏤
- **Skills** ⏤
- **Senses** darkvision 60 ft., passive Perception 10
- **Damage Resistances** cold, fire, lightning, psychic
- **Damage Immunities** poison
- **Condition Immunities** [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** understands Abyssal, Infernal, and any languages it knew before becoming a vargouille, but it can't speak
- **Challenge** 1

## Traits

***Magic Resistance.*** The vargouille has advantage on saving throws against spells and other magical effects.

## Actions

***Bite.*** *Melee Weapon Attack:* `dice:1d20+4|noform|text(+4)` to hit, reach 5 ft., one target. *Hit:* `dice:1d6+2|noform|avg|text(5)` (`1d6 + 2`) piercing damage plus `dice:3d6|noform|avg|text(10)` (`3d6`) psychic damage.

***Abyssal Curse.*** The vargouille targets one Humanoid within 5 feet of itself that has the [incapacitated](2-Mechanics/CLI/rules/conditions.md#Incapacitated) condition. The target must succeed on a DC 12 Charisma saving throw or become cursed. The cursed target's Charisma decreases by 1 after each hour, as its head takes on fiendish aspects, and its Charisma can't increase. The curse doesn't advance while the target is in sunlight or the area of a [daylight](2-Mechanics/CLI/spells/daylight.md) spell. When the cursed target's Charisma becomes 2, the target dies, and its head tears from its body and becomes a new vargouille reflection. Casting remove curse, greater restoration, or a similar spell on the target before the transformation is complete ends the curse and restores the target's Charisma.

***Horrific Reflection (Recharge 5-6).*** The vargouille's head mimics that of a Humanoid the vargouille can see within 120 feet of itself. The target must succeed on a DC 12 Wisdom saving throw or take `dice:3d6|noform|avg|text(10)` (`3d6`) psychic damage and have the [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened) condition for 1 hour or until the vargouille loses [concentration](2-Mechanics/CLI/rules/conditions.md#Concentration) (as if concentrating on a spell). If the target's saving throw is successful or if the effect ends on it, the target is immune to the Horrific Reflection of all vargouille reflections for 1 hour.
```
^statblock