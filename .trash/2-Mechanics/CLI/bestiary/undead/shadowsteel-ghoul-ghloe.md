---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/ghloe
- monster/cr/4
- monster/size/medium
- monster/type/undead
aliases: ["Shadowsteel Ghoul"]
---
# Shadowsteel Ghoul
*Source: Grim Hollow: Lairs of Etharis p. 84*  

> [!quote]  
> 
> Shards of dark metal pierce the skin of the foul creature. The metal pushes out from within the abomination rather than the other way.

## Salvage

Taking 1 hour to extract the shards of Shadowsteel from a Shadowsteel ghoul, someone can collect an amount worth 250 gp. A Shadowsteel ghast yields a quantity worth 500 gp.

## Lore

- **DC 15 Intelligence ([Religion](2-Mechanics/CLI/rules/skills.md#Religion)).** Those who use Shadowsteel to power curses can become Shadowsteel ghouls upon death. These undead creatures seek out more of the metal. As the creature ages, it can regain a semblance of the arcane power it had in life, empowering similar creatures and cursing nearby foes.  

## Statblock

```ad-statblock
title: Shadowsteel Ghoul
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/GHLoE/Shadowsteel%20Ghoul.webp#token)
*Medium undead, Chaotic Evil*

- **Armor Class** 15 (natural armor)
- **Hit Points** 65 (`10d8 + 20`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|16 (+3)|12 (+1)|14 (+2)| 9 (-1)|10 (+0)| 6 (-2)|

- **Proficiency Bonus** +2
- **Saving Throws** Wisdom +2
- **Skills** Perception +2
- **Senses** darkvision 120 ft., passive Perception 12
- **Damage Immunities** poison
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** one language known in life
- **Challenge** 4

## Traits

***Magic Resistance.*** The Shadowsteel ghoul has advantage on saving throws against spells and other magical effects.

***Shadowsteel Coat.*** The Shadowsteel ghoul is coated in metal armor made of Shadowsteel.

***Shadowsteel Hunger.*** The Shadowsteel ghoul has advantage on attack rolls against creatures carrying or wearing Shadowsteel.

## Actions

***Multiattack.*** The Shadowsteel ghoul makes two claw attacks.

***Claw.*** *Melee Weapon Attack:* `dice:1d20+5|noform|text(+5)` to hit, reach 5 ft., one target. *Hit:* `dice:2d6+3|noform|avg|text(10)` (`2d6 + 3`) slashing damage and `dice:2d4|noform|avg|text(5)` (`2d4`) necrotic damage. A cursed target must make an escalation check. If a target drops to 0 hit points due to this damage and isn't already cursed, roll `dice:1d4|noform|avg` (`1d4`), and the target is afflicted with a curse based on the result: 1-2 Curse of Damned Aging, 3-4 Curse of Foul Blight. (See Grim Hollow Campaign Guide for information on curses and escalation.)
```
^statblock