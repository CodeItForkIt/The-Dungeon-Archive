---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/toa
- monster/cr/3
- monster/size/medium
- monster/type/monstrosity/shapechanger
- monster/type/monstrosity/yuan-ti
aliases: ["Yuan-ti Priest"]
---
# Yuan-ti Priest
*Source: Tomb of Annihilation p. 118*  

```ad-statblock
title: Yuan-ti Priest
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ToA/Yuan-ti%20Priest.webp#token)
*Medium monstrosity (shapechanger, yuan-ti), Neutral Evil*

- **Armor Class** 12
- **Hit Points** 66 (`12d8 + 12`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|16 (+3)|14 (+2)|13 (+1)|14 (+2)|12 (+1)|16 (+3)|

- **Proficiency Bonus** +2
- **Saving Throws** ⏤
- **Skills** Deception +5, Stealth +4
- **Senses** darkvision 60 ft., passive Perception 11
- **Damage Immunities** poison
- **Condition Immunities** [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** Abyssal, Common, Draconic
- **Challenge** 3

## Traits

***Shapechanger.*** The yuan-ti can use its action to polymorph into a Medium snake, or back into its true form. Its statistics are the same in each form. Any equipment it is wearing or carrying isn't transformed. It doesn't change form if it dies.

***Magic Resistance.*** The yuan-ti has advantage on saving throws against spells and other magical effects.

***Malison Type.*** The yuan-ti has one of the following types:

- **Type 1.** Human body with snake head  
- **Type 2.** Human head and body with snakes for arms  
- **Type 3.** Human head and upper body with a serpentine lower body instead of legs  

***Innate Spellcasting (Yuan-ti Form Only).*** The yuan-ti's innate spellcasting ability is Charisma (spell save DC 13, `dice:1d20+5|noform|text(+5)` to hit with spell attacks). The yuan-ti can innately cast the following spells, requiring no material components:

**At will**: [animal friendship](2-Mechanics/CLI/spells/animal-friendship.md) (snakes only), [eldritch blast](2-Mechanics/CLI/spells/eldritch-blast.md) (2 beams), [minor illusion](2-Mechanics/CLI/spells/minor-illusion.md), [poison spray](2-Mechanics/CLI/spells/poison-spray.md)

**3/day**: [suggestion](2-Mechanics/CLI/spells/suggestion.md)

## Actions

***Multiattack (Yuan-ti Form Only).*** The yuan-ti makes two ranged attacks or two melee attacks, but can constrict only once.

***Bite (Snake Form Only).*** *Melee Weapon Attack:* `dice:1d20+5|noform|text(+5)` to hit, reach 5 ft., one creature. *Hit:* `dice:1d4+3|noform|avg|text(5)` (`1d4 + 3`) piercing damage plus `dice:2d6|noform|avg|text(7)` (`2d6`) poison damage.

***Constrict.*** *Melee Weapon Attack:* `dice:1d20+5|noform|text(+5)` to hit, reach 5 ft., one target. *Hit:* `dice:2d6+3|noform|avg|text(10)` (`2d6 + 3`) bludgeoning damage, and the target is [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) (escape DC 13). Until this grapple ends, the target is [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained), and the yuan-ti can't constrict another target.

***Scimitar (Yuan-ti Form Only).*** *Melee Weapon Attack:* `dice:1d20+5|noform|text(+5)` to hit, reach 5 ft., one target. *Hit:* `dice:1d6+3|noform|avg|text(6)` (`1d6 + 3`) slashing damage.
```
^statblock