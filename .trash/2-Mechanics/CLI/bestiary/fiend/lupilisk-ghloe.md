---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/ghloe
- monster/cr/3
- monster/size/large
- monster/type/fiend
aliases: ["Lupilisk"]
---
# Lupilisk
*Source: Grim Hollow: Lairs of Etharis p. 61*  

> [!quote]  
> 
> If you find a statue in the wild with its mouth open in a scream, flee. Best case, it's an artist working out their twisted ideas. Worst case, you'll be a statue soon.

## Salvage

Someone who has proficiency with alchemist's supplies can take four lupilisk venom fangs, or just the two fangs of one lupilisk elder, and treat them with reagents worth 250 gp per tooth for 3 days. A successful treatment requires the alchemist to succeed on a DC 15 Intelligence or Wisdom check. During the treatment time, somebody must also cast lesser restoration on the fangs. After a successful treatment, someone who has proficiency with jeweler's tools can fashion the fangs, now blackened, into a necklace, creating a periapt of proof against poison. If the wearer attunes to the periapt, the amulet also provides that wearer immunity to being petrified.

## Lore

- **DC 10 Intelligence ([Arcana](2-Mechanics/CLI/rules/skills.md#Arcana)).** A lupilisk's bite imparts a petrifying venom to prey. This magic toxin grows more potent as the lupilisk ages.  
- **DC 15 Intelligence ([History](2-Mechanics/CLI/rules/skills.md#History)).** Lupilisks live in packs with an elder couple in the lead. This couple are the parents of most other pack members.  

## Statblock

```ad-statblock
title: Lupilisk
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/GHLoE/Lupilisk.webp#token)
*Large fiend, Neutral Evil*

- **Armor Class** 13
- **Hit Points** 60 (`8d10 + 16`)
- **Speed** 40 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|16 (+3)|17 (+3)|14 (+2)| 5 (-3)|13 (+1)| 7 (-2)|

- **Proficiency Bonus** +2
- **Saving Throws** ⏤
- **Skills** Perception +3, Stealth +5
- **Senses** darkvision 120 ft., passive Perception 13
- **Damage Resistances** cold, fire
- **Damage Immunities** poison
- **Condition Immunities** [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** can learn languages but can't speak
- **Challenge** 3

## Traits

***Keen Hearing and Smell.*** The lupilisk has advantage on Wisdom ([Perception](2-Mechanics/CLI/rules/skills.md#Perception)) checks that rely on hearing or smell.

***Pack Tactics.*** The lupilisk has advantage on an attack roll against a creature if at least one of the lupilisk's allies is within 5 feet of the creature and the ally isn't [incapacitated](2-Mechanics/CLI/rules/conditions.md#Incapacitated).

## Actions

***Bite.*** *Melee Weapon Attack:* `dice:1d20+5|noform|text(+5)` to hit, reach 5 ft., one target. *Hit:* `dice:2d6+3|noform|avg|text(10)` (`2d6 + 3`) piercing damage and `dice:2d6|noform|avg|text(7)` (`2d6`) poison damage. If the target is a creature, it must succeed on a DC 12 Constitution saving throw or become [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned) and [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained) while [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned) in this way. The creature must repeat the saving throw at the end of its next turn. On a success, the effect ends. If the save fails again, the creature is [petrified](2-Mechanics/CLI/rules/conditions.md#Petrified) for 24 hours. At that time, it can repeat the saving throw, becoming permanently [petrified](2-Mechanics/CLI/rules/conditions.md#Petrified) on a failure or ending the effect on a success.
```
^statblock