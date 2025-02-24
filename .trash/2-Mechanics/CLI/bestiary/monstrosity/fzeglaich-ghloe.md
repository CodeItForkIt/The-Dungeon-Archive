---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/ghloe
- monster/cr/7
- monster/size/medium
- monster/type/monstrosity
aliases: ["Fzeglaich"]
---
# Fzeglaich
*Source: Grim Hollow: Lairs of Etharis p. 79*  

> [!quote]  
> 
> We've been led to believe that vampires and werewolves are natural enemies. Convenient that two fearsome creatures would be so opposed to the other. Never did we imagine, nor prepare, for a time when they might unite.

## Salvage

Someone who has proficiency with alchemist's supplies can use 1 pint of blood from a fzeg and mix it with silver and other reagents worth 50 gp to create a [lycanthropy antidote](2-Mechanics/CLI/items/lycanthropy-antidote-ghloe.md) (see Appendix A of Lairs of Etharis). A slain fzeg has `dice:1d4+2|noform|avg|text(10)` (`1d4 + 2`) usable pints of blood. The blood of a fzeglaich can be used, but it takes five times as much blood and twice as long to brew. Creating the antidote takes 4 hours of work and a successful DC 15 Intelligence ([Religion](2-Mechanics/CLI/rules/skills.md#Religion)) check.

## Lore

- **DC 10 Intelligence ([Arcana](2-Mechanics/CLI/rules/skills.md#Arcana)).** A fzeg is a mix of werewolf and vampire but has fewer weaknesses. The creature is resistant to nonmagical attacks.  
- **DC 15 Intelligence ([Nature](2-Mechanics/CLI/rules/skills.md#Nature)).** With its bite, a fzeg can drain life force and curse a person with werewolf lycanthropy. Someone who dies from a fzeg's bite becomes a fzeglaich, a creature like the fzeg and loyal to it.  
- **DC 20 Intelligence ([Arcana](2-Mechanics/CLI/rules/skills.md#Arcana)).** A fzeg can transform into humanoid form. It's natural form, however, is that of a wolf-human hybrid. This vampiric monster isn't vulnerable to sunlight, but radiant damage prevents it from regenerating.  

> [!note] GM Advice
> 
> An ambitious DM could imagine a fzeg at the lead of a force including other werewolf-undead hybrids. Combined with a ghoul or ghast, the creature would paralyze, or combined with a wight, it would drain the life and lower the maximum hit points of a target. Similarly, other kinds of lycanthropes could become undead and wield hybrid powers.
^gm-advice

## Statblock

```ad-statblock
title: Fzeglaich
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/GHLoE/Fzeglaich.webp#token)
*Medium monstrosity, Chaotic Evil*

- **Armor Class** 15 (natural armor)
- **Hit Points** 90 (`12d8 + 36`)
- **Speed** 40 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|16 (+3)|16 (+3)|16 (+3)|11 (+0)|11 (+0)|12 (+1)|

- **Proficiency Bonus** +3
- **Saving Throws** Dexterity +6, Wisdom +3
- **Skills** Perception +3, Stealth +6
- **Senses** darkvision 60 ft., passive Perception 13
- **Damage Resistances** bludgeoning, piercing, slashing from nonmagical attacks
- **Languages** one language
- **Challenge** 7

## Traits

***Keen Hearing and Smell.*** The fzeglaich has advantage on Wisdom ([Perception](2-Mechanics/CLI/rules/skills.md#Perception)) checks that rely on hearing or smell.

***Rampage.*** When the fzeglaich reduces a creature to 0 hit points with a melee attack on its turn, the fzeglaich can take a bonus action to move up to half its speed and make a bite attack.

***Regeneration.*** The fzeglaich regains 10 hit points at the start of its turn if it has at least 1 hit point. If the fzeglaich takes radiant damage, this trait doesn't function at the start of the fzeglaich's next turn.

## Actions

***Multiattack.*** The fzeglaich makes two attacks, only one of which can be a bite.

***Bite.*** *Melee Weapon Attack:* `dice:1d20+6|noform|text(+6)` to hit, reach 5 ft., one creature. *Hit:* `dice:1d8+3|noform|avg|text(7)` (`1d8 + 3`) piercing damage plus `dice:2d6|noform|avg|text(7)` (`2d6`) necrotic damage, and the target must succeed on a DC 14 Constitution saving throw or be [incapacitated](2-Mechanics/CLI/rules/conditions.md#Incapacitated) until the end of its next turn. The fzeglaich regains hit points equal to the amount of necrotic damage dealt.

***Claws.*** *Melee Weapon Attack:* `dice:1d20+6|noform|text(+6)` to hit, reach 5 ft., one creature. *Hit:* `dice:2d4+3|noform|avg|text(8)` (`2d4 + 3`) slashing damage.
```
^statblock