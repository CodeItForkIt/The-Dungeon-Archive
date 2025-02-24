---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/idrotf
- monster/cr/3
- monster/size/medium
- monster/type/undead
aliases: ["Sephek Kaltro"]
---
# Sephek Kaltro
*Source: Icewind Dale: Rime of the Frostmaiden p. 23*  

Sephek Kaltro is a well-built man in his thirties. He has an olive complexion, dark hair pulled back in a ponytail, and no facial or body hair. He is dressed in a stylish vest with matching pants and boots, similar in style to those worn by mariners of the southern Sword Coast, but wears no armor or cold weather clothing and doesn't appear to be armed. His most striking feature is his eyes, which are as blue as a frozen lake.

```ad-statblock
title: Sephek Kaltro
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/IDRotF/Sephek%20Kaltro.webp#token)
*Medium undead, Neutral Evil*

- **Armor Class** 12
- **Hit Points** 75 (`10d8 + 30`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|16 (+3)|14 (+2)|16 (+3)|11 (+0)|16 (+3)|18 (+4)|

- **Proficiency Bonus** +2
- **Saving Throws** ⏤
- **Skills** Perception +5, Survival +5
- **Senses** passive Perception 15
- **Damage Immunities** cold
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened)
- **Languages** Common
- **Challenge** 3

## Traits

***Cold Regeneration.*** If the temperature around him is 0 degrees Fahrenheit or lower, Sephek regains 5 hit points at the start of his turn. If he takes fire damage, this trait doesn't function at the start of Sephek's next turn. Sephek dies only if he starts his turn with 0 hit points and doesn't regenerate.

***Innate Spellcasting.*** Sephek can innately cast [misty step](2-Mechanics/CLI/spells/misty-step.md) up to three times per day, requiring no components. His innate spellcasting ability is Charisma.

**At will**: [misty step](2-Mechanics/CLI/spells/misty-step.md)

## Actions

***Multiattack.*** Sephek attacks twice with a weapon.

***Ice Longsword.*** *Melee Weapon Attack:* `dice:1d20+5|noform|text(+5)` to hit, reach 5 ft., one target. *Hit:* `dice:1d8+3|noform|avg|text(7)` (`1d8 + 3`) slashing damage, or `dice:1d10+3|noform|avg|text(8)` (`1d10 + 3`) slashing damage if Sephek uses the weapon with two hands, plus `dice:2d4|noform|avg|text(5)` (`2d4`) cold damage.

***Ice Dagger.*** *Ranged Weapon Attack:* `dice:1d20+5|noform|text(+5)` to hit, reach 5 ft. or range 20/60 ft., one target. *Hit:* `dice:1d4+3|noform|avg|text(5)` (`1d4 + 3`) piercing damage plus `dice:2d4|noform|avg|text(5)` (`2d4`) cold damage.
```
^statblock