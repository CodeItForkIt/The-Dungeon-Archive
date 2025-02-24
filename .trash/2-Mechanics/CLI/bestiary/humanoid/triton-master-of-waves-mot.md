---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/mot
- monster/cr/8
- monster/size/medium
- monster/type/humanoid/triton
aliases: ["Triton Master of Waves"]
---
# Triton Master of Waves
*Source: Mythic Odysseys of Theros p. 245*  

Triton masters of waves sculpt storms and change the tides, bending the sea to their will. Drawing forth living currents and the icy cold of the deep, these mages make the ocean their ally, using it to defend their people or enact Thassa's wishes. While dire threats from the land might bring them to coastal shallows, most masters of waves keep to the ocean's depths.

Although many masters of waves resent land-dwellers and strike out at those who trespass upon their waters, most are devoted followers of the sea god. Those who share their faith or who bear earnest offerings to Thassa might defuse the tritons' ire—that is, if they survive the deadly winds and waves that typically herald these sea guardians' appearance.

Clever, far-ranging people of the sea, tritons live rich lives unknown to most land-dwelling individuals. While the waves separate most tritons from land-dwellers, occasionally the inhabitants of the surface and the deep come into conflict. In such cases, tritons prove skilled at sabotaging ocean-going vessels, employing water-based magic, and otherwise whipping up the fury of the sea. Few dare insult tritons in their home environment, but those who do and survive often learn that the tritons' wrath doesn't end at the shore.

```ad-statblock
title: Triton Master of Waves
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/MOT/Triton%20Master%20of%20Waves.webp#token)
*Medium humanoid (triton), Neutral*

- **Armor Class** 15 (natural armor)
- **Hit Points** 105 (`14d8 + 42`)
- **Speed** 30 ft., swim 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|16 (+3)|11 (+0)|16 (+3)|10 (+0)|12 (+1)|19 (+4)|

- **Proficiency Bonus** +3
- **Saving Throws** Dexterity +3, Intelligence +3, Charisma +7
- **Skills** Athletics +6, Nature +6, Survival +4
- **Senses** darkvision 60 ft., passive Perception 11
- **Damage Resistances** cold, fire
- **Languages** Common, Primordial
- **Challenge** 8

## Traits

***Amphibious.*** The triton can breathe air and water.

***Summon Water Weird (Recharges after a Short or Long Rest).*** As a bonus action, the triton magically summons `dice:1d4|noform|avg` (`1d4`) [water weirds](2-Mechanics/CLI/bestiary/elemental/water-weird.md). The summoned weirds appear in unoccupied spaces in water within 60 feet of the triton. The water weirds act immediately after the triton on the same initiative count and fight until they're destroyed. They disappear if the triton dies.

***Innate Spellcasting.*** The triton's spellcasting ability is Charisma (spell save DC 15, `dice:1d20+7|noform|text(+7)` to hit with spell attacks). It can innately cast the following spells, requiring no material components:

**At will**: [ray of frost](2-Mechanics/CLI/spells/ray-of-frost.md) (see "Actions" below)

**1/day each**: [fog cloud](2-Mechanics/CLI/spells/fog-cloud.md), [gust of wind](2-Mechanics/CLI/spells/gust-of-wind.md), [wind wall](2-Mechanics/CLI/spells/wind-wall.md)

**2/day**: [cone of cold](2-Mechanics/CLI/spells/cone-of-cold.md)

## Actions

***Multiattack.*** The triton makes two attacks using Wave Touch and casts [ray of frost](2-Mechanics/CLI/spells/ray-of-frost.md).

***Wave Touch.*** *Melee Spell Attack:* `dice:1d20+7|noform|text(+7)` to hit, reach 5 ft., one target. *Hit:* `dice:4d10|noform|avg|text(22)` (`4d10`) cold damage.

***Ray of Frost (Cantrip).*** *Ranged Spell Attack:* `dice:1d20+7|noform|text(+7)` to hit, range 60 ft., one creature. *Hit:* `dice:3d8|noform|avg|text(13)` (`3d8`) cold damage, and the target's speed is reduced by 10 feet until the start of the triton's next turn.

## Reactions

***Frigid Shield.*** When a creature the triton can see targets the triton with an attack, the triton gains 10 temporary hit points. If the attack hits and reduces the temporary hit points to 0, each creature within 5 feet of the triton takes `dice:2d8|noform|avg|text(9)` (`2d8`) cold damage.
```
^statblock