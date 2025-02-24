---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/mot
- monster/cr/9
- monster/size/large
- monster/type/fiend
aliases: ["Abhorrent Overlord"]
---
# Abhorrent Overlord
*Source: Mythic Odysseys of Theros p. 219*  

Abhorrent overlords are gaunt, bipedal creatures whose gray, leathery skin is in stark contrast to the gleaming jewelry made of Underworld gold that they adorn themselves with. Their appetite for pain and death is eclipsed only by their greed; these fiends delight in searching out treasure and slaughtering all who stand in their way.

```ad-statblock
title: Abhorrent Overlord
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/MOT/Abhorrent%20Overlord.webp#token)
*Large fiend, Lawful Evil*

- **Armor Class** 16 (natural armor)
- **Hit Points** 136 (`16d10 + 48`)
- **Speed** 30 ft., fly 60 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|20 (+5)|18 (+4)|16 (+3)|15 (+2)|14 (+2)|16 (+3)|

- **Proficiency Bonus** +4
- **Saving Throws** Constitution +7, Charisma +7
- **Skills** Deception +7, Intimidation +7, Persuasion +7
- **Senses** darkvision 120 ft., passive Perception 12
- **Damage Resistances** cold, necrotic
- **Damage Immunities** poison
- **Condition Immunities** [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** Abyssal, Common, Infernal
- **Challenge** 9

## Traits

***Insatiable Greed.*** The abhorrent overlord can sense the presence of gold within 1,000 feet of itself. It can determine which location has the greatest amount of gold and can sense the direction to that site. If the gold is being moved, it knows the direction of the movement. It can't locate gold if any thickness of clay or lead, even a thin sheet, blocks a direct path between it and the gold.

***Magic Resistance.*** The abhorrent overlord has advantage on saving throws against spells and other magical effects.

***Innate Spellcasting.*** The abhorrent overlord's spellcasting ability is Charisma (spell save DC 15). It can innately cast the following spells, requiring no material components:

**1/day each**: [confusion](2-Mechanics/CLI/spells/confusion.md), [crown of madness](2-Mechanics/CLI/spells/crown-of-madness.md), [suggestion](2-Mechanics/CLI/spells/suggestion.md)

## Actions

***Multiattack.*** The abhorrent overlord makes two attacks with its claws.

***Claws.*** *Melee Weapon Attack:* `dice:1d20+9|noform|text(+9)` to hit, reach 5 ft., one target. *Hit:* `dice:2d8+5|noform|avg|text(14)` (`2d8 + 5`) slashing damage plus `dice:4d6|noform|avg|text(14)` (`4d6`) necrotic damage. The abhorrent overlord regains hit points equal to half the amount of necrotic damage dealt if the target is a creature.

***Storm of Crows (Recharge 6).*** The abhorrent overlord conjures a swarm of spectral crows and harpies in a 20-foot-radius sphere centered on a point the overlord can see within 120 feet of it. The sphere remains for 1 minute or until the overlord loses [concentration](2-Mechanics/CLI/rules/conditions.md#Concentration) (as if concentrating on a spell), and its area is lightly obscured and difficult terrain.

Any creature that moves into the area for the first time on a turn or starts its turn there must make a DC 15 Constitution saving throw. A creature takes `dice:3d10|noform|avg|text(16)` (`3d10`) slashing damage plus `dice:3d10|noform|avg|text(16)` (`3d10`) psychic damage on a failed save, or half as much damage on a successful one.
```
^statblock