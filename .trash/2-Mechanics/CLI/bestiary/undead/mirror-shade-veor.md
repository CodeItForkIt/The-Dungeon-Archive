---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/veor
- monster/cr/10
- monster/size/medium
- monster/type/undead
aliases: ["Mirror Shade"]
---
# Mirror Shade
*Source: Vecna: Eve of Ruin p. 226*  

> [!quote] A quote from Hopewell Lightfinger, Sword Coast Adventurer  
> 
> She was great at picking locks but had a terrible cruel streak. When the cloaker got her, we were glad we'd never see her again—then, to our horror, we did.

When the spirit of a malevolent trickster or callous rogue refuses to enter the afterlife, the spirit sometimes becomes a mirror shade instead. Mirror shades are incorporeal Undead that, in their true forms, look like person-shaped blobs of shining light. More often, though, mirror shades are encountered on reflective surfaces such as mirrors or panes of glass. There, they blend in seamlessly with their reflected surroundings and wait until the moment is right to strike. Mirror shades can be found throughout the multiverse but are particularly common in the Outer Planes.

```ad-statblock
title: Mirror Shade
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/VEoR/Mirror%20Shade.webp#token)
*Medium undead, typically  Chaotic Evil*

- **Armor Class** 13
- **Hit Points** 91 (`14d8 + 28`)
- **Speed** 40 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
| 8 (-1)|17 (+3)|14 (+2)|10 (+0)|13 (+1)|18 (+4)|

- **Proficiency Bonus** +4
- **Saving Throws** Dexterity +7, Wisdom +5
- **Skills** Deception +8, Stealth +7
- **Senses** darkvision 60 ft., passive Perception 11
- **Damage Resistances** acid; fire; lightning; bludgeoning, piercing, slashing from nonmagical attacks
- **Damage Immunities** poison, psychic, radiant
- **Condition Immunities** [blinded](2-Mechanics/CLI/rules/conditions.md#Blinded), [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened), [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled), [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed), [petrified](2-Mechanics/CLI/rules/conditions.md#Petrified), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned), [prone](2-Mechanics/CLI/rules/conditions.md#Prone), [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained)
- **Languages** —
- **Challenge** 10

## Traits

***False Appearance.*** If the mirror shade is within 5 feet of a reflective surface—such as a mirror, glass pane, or still water—it has advantage on its initiative roll. If a creature hasn't observed the mirror shade move or act, that creature must succeed on a DC 18 Intelligence ([Investigation](2-Mechanics/CLI/rules/skills.md#Investigation)) check to discern that the mirror shade isn't the creature's own reflection.

***Mirror Movement.*** The mirror shade can move along the surface of reflective or translucent objects, such as mirrors, without provoking opportunity attacks. It can move through translucent objects as if they were difficult terrain.

## Actions

***Multiattack.*** The mirror shade makes two Phantasmal Strike attacks and uses Reflect Fear.

***Phantasmal Strike.*** *Melee Weapon Attack:* `dice:1d20+7|noform|text(+7)` to hit, reach 5 ft., one target. *Hit:* `dice:1d8+3|noform|avg|text(7)` (`1d8 + 3`) radiant damage plus `dice:2d6|noform|avg|text(7)` (`2d6`) psychic damage.

***Reflect Fear.*** The mirror shade targets one creature it can see within 60 feet of itself and projects an illusion of that creature's greatest fear. The target must make a DC 16 Wisdom saving throw. On a failed save, the target takes `dice:8d6|noform|avg|text(28)` (`8d6`) psychic damage and has the [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened) condition until the start of the mirror shade's next turn. On a successful save, the target takes half as much damage only.

## Bonus Actions

***Mirror Stealth.*** While within 5 feet of a reflective surface, such as a mirror, the mirror shade takes the Hide action.
```
^statblock