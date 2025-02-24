---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/ghloe
- monster/cr/6
- monster/size/large
- monster/type/fiend
aliases: ["Lupilisk Elder"]
---
# Lupilisk Elder
*Source: Grim Hollow: Lairs of Etharis p. 62*  

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
title: Lupilisk Elder
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/GHLoE/Lupilisk%20Elder.webp#token)
*Large fiend, Neutral Evil*

- **Armor Class** 15 (natural armor)
- **Hit Points** 97 (`13d10 + 26`)
- **Speed** 50 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|18 (+4)|16 (+3)|15 (+2)| 6 (-2)|14 (+2)| 8 (-1)|

- **Proficiency Bonus** +3
- **Saving Throws** ⏤
- **Skills** Perception +5, Stealth +6
- **Senses** darkvision 120 ft., passive Perception 15
- **Damage Resistances** cold, fire
- **Damage Immunities** poison
- **Condition Immunities** [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** can learn languages but can't speak
- **Challenge** 6

## Traits

***Keen Hearing and Smell.*** The lupilisk elder has advantage on Wisdom ([Perception](2-Mechanics/CLI/rules/skills.md#Perception)) checks that rely on hearing or smell.

***Pack Tactics.*** The lupilisk elder has advantage on an attack roll against a creature if at least one of the lupilisk's allies is within 5 feet of the creature and the ally isn't [incapacitated](2-Mechanics/CLI/rules/conditions.md#Incapacitated).

## Actions

***Bite.*** *Melee Weapon Attack:* `dice:1d20+7|noform|text(+7)` to hit, reach 5 ft., one target. *Hit:* `dice:2d8+4|noform|avg|text(13)` (`2d8 + 4`) piercing damage and `dice:2d8|noform|avg|text(9)` (`2d8`) poison damage. If the target is a creature, it must succeed on a DC 13 Constitution saving throw or become [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned) and [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained) while [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned) in this way. The creature must repeat the saving throw at the end of its next turn. On a success, the effect ends. If the save fails again, the creature is permanently [petrified](2-Mechanics/CLI/rules/conditions.md#Petrified).

***Pack Attack (Recharge 5-6).*** One lupilisk or lupilisk whelp the lupilisk elder can see within 30 feet of it can use a reaction to move up to half its speed and make a bite attack. The target must be able to hear or see the elder. The lupilisk elder then makes one bite attack.
```
^statblock