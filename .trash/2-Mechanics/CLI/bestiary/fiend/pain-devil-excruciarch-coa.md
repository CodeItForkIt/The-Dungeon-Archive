---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/coa
- monster/cr/12
- monster/size/medium
- monster/type/fiend/devil
aliases: ["Pain Devil (Excruciarch)"]
---
# Pain Devil (Excruciarch)
*Source: Chains of Asmodeus p. 249*  

Another type of devil devoted to torture, excruciarchs are also competent fighters and mercenaries. Due to their reputation as torturers of devils, they're often looked down upon by other devils, occasionally even beaten or killed, and as a result they frequently travel together. Their cruelty is known across the Nine Hells, and their revelry in pain gives them their name. Another defining feature of pain devils is their greed: they serve no particular master, their loyalty must be purchased.

## Masked Devils

Excruciarchs appear almost humanoid in size and shape. Their skin is usually pale shades of white or red, and hair doesn't grow anywhere on their body. To conceal their identity and lend themselves some form of protection, almost all pain devils wear masks made from various types of leather, often adorned with spikes, horns, or ridges.

## Devoted to Pain

When an excruciarch enters battle, they activate a unique ability to inflict pain upon their adversaries. Excruciarchs thrive on even their own pain and they almost always fight to the death.

## Statblock

```ad-statblock
title: Pain Devil (Excruciarch)
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/CoA/Pain%20Devil%20%28Excruciarch%29.webp#token)
*Medium fiend (devil), Lawful Evil*

- **Armor Class** 16 (natural armor)
- **Hit Points** 171 (`18d8 + 90`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|18 (+4)|15 (+2)|20 (+5)|11 (+0)|10 (+0)|13 (+1)|

- **Proficiency Bonus** +4
- **Saving Throws** Strength +8, Constitution +9
- **Skills** Deception +5, Insight +4, Intimidation +5, Perception +4
- **Senses** darkvision 120 ft., passive Perception 14
- **Damage Resistances** cold; bludgeoning, piercing, slashing from nonmagical attacks that aren't silvered
- **Damage Immunities** fire, poison
- **Condition Immunities** [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** Celestial, Common, Infernal, telepathy 120 ft.
- **Challenge** 12

## Traits

***Aura of Torment.*** Any creature hostile to the excruciarch that starts its turn within 20 feet of the excruciarch takes `dice:4d4|noform|avg|text(10)` (`4d4`) slashing damage, unless the excruciarch is [incapacitated](2-Mechanics/CLI/rules/conditions.md#Incapacitated).

***Devil's Sight.*** Magical darkness doesn't impede the excruciarch's darkvision.

***Magic Resistance.*** The excruciarch has advantage on saving throws against spells and other magical effects.

***Sadism.*** The excruciarch gains a +1 bonus to attack and damage rolls for each creature it damaged on its previous turn.

## Actions

***Multiattack.*** The excruciarch makes two Scourge attacks. It can replace one of the attacks with Storm of Steel (if available).

***Scourge.*** *Melee Weapon Attack:* `dice:1d20+8|noform|text(+8)` to hit, reach 10 ft., one target. *Hit:* `dice:2d8+4|noform|avg|text(13)` (`2d8 + 4`) bludgeoning damage plus `dice:2d8+4|noform|avg|text(13)` (`2d8 + 4`) slashing damage.

***Storm of Steel (Recharge 4-6).*** The excruciarch swings its scourge wildly around itself. All creatures within 15 feet of the excruciarch must make a DC 16 Dexterity saving throw. Targets take `dice:6d8+4|noform|avg|text(31)` (`6d8 + 4`) slashing damage on a failed save, or half as much damage on a successful one.

## Reactions

***Vulnerable Gaze.*** As a reaction to a creature resisting damage dealt by the excruciarch, it turns its gaze on that creature, negating any resistances and immunities that creature has until the start of the excruciarch's next turn.
```
^statblock