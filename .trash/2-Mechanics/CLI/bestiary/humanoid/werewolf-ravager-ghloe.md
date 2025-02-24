---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/ghloe
- monster/cr/7
- monster/size/medium
- monster/type/humanoid/any
- monster/type/humanoid/shapechanger
aliases: ["Werewolf Ravager"]
---
# Werewolf Ravager
*Source: Grim Hollow: Lairs of Etharis p. 83*  

> [!quote]  
> 
> During full moons, inhabitants of Etharis stay inside with the doors barred and windows tightly shut. Even then, they look at those indoors with them with a suspicious eye. One never knows.

## Salvage

Lycanthropes exist in a state of perpetual mental turmoil, and over time their memories fragment. As a result, many carry keepsakes of their past lives to strengthen the memories they do not want to lose. The pelt of a lycanthrope is prized by certain mages for the crafting of magical cloaks, particularly cloaks that allow a person to change their form such as the cloak of the bat or the cloak of the manta ray.

Weapons made from the fangs or claws of deceased lycanthropes have special properties and are known as [lycan weapons](2-Mechanics/CLI/items/lycan-weapon-ghloe.md) (see Appendix A of Lairs of Etharis). These weapons require a successful DC 15 Intelligence ([Arcana](2-Mechanics/CLI/rules/skills.md#Arcana)) check by a proficient weaponsmith, consuming 500 gp worth of components, and requiring 10 days of work.

## Lore

- **DC 10 Intelligence ([Nature](2-Mechanics/CLI/rules/skills.md#Nature)).** Lycanthropy is a common affliction in Etharis. The source is a curse that twists mind and body into that of a savage beast. Though they can change at will, the light of the full moon triggers the transformation no matter what.  
- **DC 15 Intelligence ([Nature](2-Mechanics/CLI/rules/skills.md#Nature)).** In addition to the normal transmission of the curse through the bite of a lycanthrope, certain druidic sects also perform rituals to create new lycanthropes. This ritual is known as the Lunar Sacrament, used as a tool to protect druid groves from invasion.  
- **DC 20 Intelligence ([Nature](2-Mechanics/CLI/rules/skills.md#Nature)).** While the nature of the transformation tends to override the senses with bestial fury, some can control themselves. By finding a balance between man and beast, they gain greater control over the curse, gaining the ability to turn into a full animal and retain their mental faculties.  

## Statblock

```ad-statblock
title: Werewolf Ravager
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/GHLoE/Werewolf%20Ravager.webp#token)
*Medium humanoid (any, shapechanger), Any alignment*

- **Armor Class** 13 (16 from natural armor in hybrid form)
- **Hit Points** 91 (`14d8 + 28`)
- **Speed** 30 ft. (50 ft. in hybrid form)

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|17 (+3)|16 (+3)|14 (+2)| 9 (-1)|15 (+2)|10 (+0)|

- **Proficiency Bonus** +3
- **Saving Throws** Strength +6, Dexterity +6
- **Skills** Perception +5
- **Senses** darkvision 60 ft., passive Perception 15
- **Damage Vulnerabilities** bludgeoning, piercing, slashing from nonmagical attacks that are silvered
- **Damage Immunities** bludgeoning, piercing, slashing from nonmagical attacks that aren't silvered
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened)
- **Languages** any two languages
- **Challenge** 7

## Traits

***Grappler.*** While a creature is [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) by the werewolf ravager, the werewolf has advantage on attack rolls against [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) targets, and the target takes an additional 3 `dice:1d6|noform|avg` (`1d6`) damage whenever it is hit with the werewolf's bite or claw attack.

***Shapechanger.*** The werewolf can use its action to polymorph into a wolf-humanoid hybrid or back into its true form, which is humanoid. Any armor it is wearing merges into its hybrid form. It reverts to its true form if it dies.

## Actions

***Multiattack.*** The werewolf ravager makes two melee attacks. It can only make one bite attack per turn.

***Bite (Hybrid Form Only).*** *Melee Weapon Attack:* `dice:1d20+6|noform|text(+6)` to hit, reach 5 ft., one creature. *Hit:* `dice:2d8+3|noform|avg|text(12)` (`2d8 + 3`) piercing damage. The target must succeed on a DC 14 Strength saving throw or be [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled).

Additionally, if the target is a humanoid, it must succeed on a DC 13 Constitution saving throw or be cursed with werewolf lycanthropy.

***Claw (Hybrid Form Only).*** *Melee Weapon Attack:* `dice:1d20+6|noform|text(+6)` to hit, reach 5 ft., one creature. *Hit:* `dice:2d6+3|noform|avg|text(10)` (`2d6 + 3`) slashing damage.

***Short Sword.*** *Melee Weapon Attack:* `dice:1d20+6|noform|text(+6)` to hit, reach 5 ft., one creature. *Hit:* `dice:1d6+3|noform|avg|text(6)` (`1d6 + 3`) piercing damage.
```
^statblock