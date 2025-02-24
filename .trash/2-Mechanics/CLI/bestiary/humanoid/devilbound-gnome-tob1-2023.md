---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/tob1-2023
- monster/cr/9
- monster/environment/urban
- monster/size/small
- monster/type/humanoid/gnome
aliases: ["Devilbound Gnome"]
---
# Devilbound Gnome
*Source: Tome of Beasts 1 (2023 Edition) p. 408*  

The devilbound gnome is a gnome spellcaster that has made a magical agreement with a devil for greater power. To ensure loyalty and to further the gnome's power, the devil binds an imp to the gnome's service. This binding changes the gnome, giving it fiendish protections and minor fiendish features, such as glowing eyes, a sulfurous aroma, a forked tongue, or similar. Beyond fulfilling the occasional demand, the devil cares little for what the gnome does with the power, provided the flow of souls doesn't cease.

```ad-statblock
title: Devilbound Gnome
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ToB1-2023/Devilbound%20Gnome.webp#token)
*Small humanoid (gnome), Any Evil alignment*

- **Armor Class** 17 (infernal blessing)
- **Hit Points** 104 (`19d6 + 38`)
- **Speed** 25 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|10 (+0)|14 (+2)|15 (+2)|16 (+3)|12 (+1)|21 (+5)|

- **Proficiency Bonus** +4
- **Saving Throws** Constitution +6, Intelligence +7, Charisma +9
- **Skills** Arcana +7, Deception +9, History +7, Persuasion +9
- **Senses** darkvision 60 ft., passive Perception 11
- **Damage Resistances** cold; fire; poison; bludgeoning, piercing, slashing from nonmagical attacks that aren't silvered
- **Condition Immunities** [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** Common, Gnomish, Infernal
- **Challenge** 9

## Traits

***Infernal Blessing.*** While the devilbound gnome is conscious and wearing no armor and wielding no shield, it adds its Charisma modifier to its AC (included above) and saving throws. In addition, magical darkness doesn't impede the gnome's darkvision.

***Infernal Bond.*** The devilbound gnome is magically bound to an imp. The imp acts as an ally of the gnome's, obeying its spoken commands. The gnome can perceive through the imp's senses, speak through its mouth, and communicate with it telepathically even if the two aren't on the same plane of existence.

***Magic Resistance.*** The devilbound gnome has advantage on saving throws against spells and other magical effects.

***Spellcasting.*** The devilbound gnome casts one of the following spells, requiring no material components and using Charisma as the spellcasting ability (spell save DC 17):

**At will**: [detect magic](2-Mechanics/CLI/spells/detect-magic.md), [minor illusion](2-Mechanics/CLI/spells/minor-illusion.md), [prestidigitation](2-Mechanics/CLI/spells/prestidigitation.md)

**1/day each**: [fly](2-Mechanics/CLI/spells/fly.md), [haste](2-Mechanics/CLI/spells/haste.md), [wall of fire](2-Mechanics/CLI/spells/wall-of-fire.md)

**3/day each**: [command](2-Mechanics/CLI/spells/command.md), [dimension door](2-Mechanics/CLI/spells/dimension-door.md), [invisibility](2-Mechanics/CLI/spells/invisibility.md)

## Actions

***Multiattack.*** The devilbound gnome makes three Hellish Blast attacks. It can replace one attack with a use of Spellcasting.

***Hellish Blast.*** *Melee or Ranged Spell Attack:* `dice:1d20+9|noform|text(+9)` to hit, reach 5 ft. or range 120 ft., one target. *Hit:* `dice:2d6+5|noform|avg|text(12)` (`2d6 + 5`) fire damage plus `dice:2d8|noform|avg|text(9)` (`2d8`) poison damage.

***Hell's Servitors (1/Day).*** The devilbound gnome magically calls `dice:1d4|noform|avg` (`1d4`) devils with a challenge rating of 4 or lower, or it calls 1 devil with a challenge rating of 6 or lower. The called Fiends arrive in `dice:1d4|noform|avg` (`1d4`) rounds, acting as allies of the gnome and obeying its spoken commands. The Fiends remain for 1 hour, until the gnome dies, or until the gnome dismisses them as a bonus action.

***To Hell and Back (1/Day).*** The devilbound gnome sends one creature it can see within 60 feet of it hurling through Hell. The target must make a DC 17 Wisdom saving throw. On a success, the target takes `dice:10d6|noform|avg|text(35)` (`10d6`) fire damage as Hell pulls on the creature. On a failure, the target is [incapacitated](2-Mechanics/CLI/rules/conditions.md#Incapacitated) and disappears, as it takes a quick trip through the nightmarish landscapes of Hell. At the end of the gnome's next turn, the target reappears in the space it previously occupied, or the nearest unoccupied space, and takes `dice:10d10|noform|avg|text(55)` (`10d10`) psychic damage.

## Reactions

***Fiendish Sacrifice.*** When the devilbound gnome is reduced to 0 hp, it can sacrifice a Fiend called with the Hell's Servitor's action or sacrifice its bonded imp, preventing the damage and killing the chosen Fiend. If the gnome sacrifices its bonded imp, it loses its Infernal Blessing and Infernal Bond traits until it receives a new imp from its patron devil.
```
^statblock

## Environment

urban