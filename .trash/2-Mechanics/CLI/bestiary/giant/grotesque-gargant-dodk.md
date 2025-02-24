---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/dodk
- monster/cr/8
- monster/size/huge
- monster/type/giant
aliases: ["Grotesque Gargant"]
---
# Grotesque Gargant
*Source: Dungeons of Drakkenheim p. 197*  

These mutated human monstrosities have grown to tremendous size. Delerium shards are merged into their disfigured bodies, and their muscles pulse with arcane energies as they lumber forward. Furiously territorial, these creatures are occasionally sighted hauling massive delerium crystals from the crater and placing them like obelisks in the ruins.

```ad-statblock
title: Grotesque Gargant
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/DoDk/Grotesque%20Gargant.webp#token)
*Huge giant, Neutral*

- **Armor Class** 17 (natural armor)
- **Hit Points** 126 (`11d12 + 55`)
- **Speed** 40 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|23 (+6)|15 (+2)|20 (+5)|10 (+0)|12 (+1)| 9 (-1)|

- **Proficiency Bonus** +3
- **Saving Throws** Dexterity +5, Constitution +8, Wisdom +4
- **Skills** Athletics +12, Perception +4
- **Senses** darkvision 60 ft., passive Perception 14
- **Languages** Giant
- **Challenge** 8

## Traits

***Regeneration.*** A grotesque gargant regains 10 hit points at the start of its turn as long as it is within the Deep Haze. The gargant dies only if it starts its turn with 0 hit points and doesn't regenerate.

***Misty Camouflage.*** The grotesque gargant has advantage on Dexterity ([Stealth](2-Mechanics/CLI/rules/skills.md#Stealth)) checks to hide in any area obscured by mist or fog.

## Actions

***Multiattack.*** The grotesque gargant makes two greatclub attacks.

***Greatclub.*** *Melee Weapon Attack:* `dice:1d20+9|noform|text(+9)` to hit, reach 15 ft., one target. *Hit:* `dice:3d8+6|noform|avg|text(19)` (`3d8 + 6`) bludgeoning damage.

***Rock.*** *Ranged Weapon Attack:* `dice:1d20+9|noform|text(+9)` to hit, range 60/240 ft., one target. *Hit:* `dice:4d10+6|noform|avg|text(28)` (`4d10 + 6`) bludgeoning damage. If the target is a creature, it must succeed on a DC 17 Strength saving throw or be knocked [prone](2-Mechanics/CLI/rules/conditions.md#Prone).

***Contaminating Beam.*** The grotesque gargant magically forces a creature it can see within 60 feet of it to make a DC 15 Constitution saving throw. The creature takes `dice:6d8|noform|avg|text(27)` (`6d8`) necrotic damage on a failed save and gains one level of contamination.

## Reactions

***Rock Catching.*** If a rock or similar object is hurled at the grotesque gargant, the grotesque gargant can, with a successful DC 10 Dexterity saving throw, catch the missile and take no bludgeoning damage from it.
```
^statblock