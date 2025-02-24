---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/lr
- monster/cr/5
- monster/size/medium
- monster/type/humanoid/human
aliases: ["Whymsee"]
---
# Whymsee
*Source: Locathah Rising p. 20*  

```ad-statblock
title: Whymsee
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/LR/Whymsee.webp#token)
*Medium humanoid (human), Neutral Evil*

- **Armor Class** 17 (natural armor)
- **Hit Points** 75 (`10d8 + 30`)
- **Speed** 30 ft., swim 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|12 (+1)|10 (+0)|16 (+3)|10 (+0)|15 (+2)|14 (+2)|

- **Proficiency Bonus** +3
- **Saving Throws** ⏤
- **Skills** Perception +5
- **Senses** passive Perception 15
- **Damage Resistances** bludgeoning, piercing, slashing from nonmagical attacks
- **Languages** Common, Aquan
- **Challenge** 5

## Traits

***Amphibious.*** Whymsee can breathe air and water.

***Innate Spellcasting.*** Whymsee's spellcasting ability is Wisdom (spell save DC 13, `dice:1d20+5|noform|text(+5)` to hit with spell attacks). It can innately cast the following spells, requiring no material components:

**At will**: [command](2-Mechanics/CLI/spells/command.md), [create or destroy water](2-Mechanics/CLI/spells/create-or-destroy-water.md)

**1/day each**: [lightning bolt](2-Mechanics/CLI/spells/lightning-bolt.md), [Evard's black tentacles](2-Mechanics/CLI/spells/evards-black-tentacles.md)

**3/day each**: [control water](2-Mechanics/CLI/spells/control-water.md), [darkness](2-Mechanics/CLI/spells/darkness.md), [water breathing](2-Mechanics/CLI/spells/water-breathing.md), [water walk](2-Mechanics/CLI/spells/water-walk.md)

## Actions

***Thunderous Touch.*** *Melee Spell Attack:* `dice:1d20+5|noform|text(+5)` to hit, reach 5 ft., one creature. *Hit:* `dice:5d10|noform|avg|text(27)` (`5d10`) thunder damage.

***Ink Cloud.*** While underwater, Whymsee can expel an ink cloud in a 20-foot radius. The cloud spreads around corners, and that area is heavily obscured to creatures other than kraken priests or a kraken. Each creature other than a kraken priest or a kraken that ends its turn there must succeed on a DC 14 Constitution saving throw, taking `dice:2d8|noform|avg|text(9)` (`2d8`) poison damage on a failed save, or half as much damage on a successful one. A strong current disperses the cloud, which otherwise disappears at the end of Whymsee's next turn.

***Shell Defense.*** Whymsee withdraws into her shell. Until she emerges, she gains a +4 bonus to AC and has advantage on Strength and Constitution saving throws. While in her shell, Whymsee is [prone](2-Mechanics/CLI/rules/conditions.md#Prone), her speed is 0 and can't increase, she has disadvantage on Dexterity saving throws, it can't take reactions, and the only action she can take is a bonus action to emerge.
```
^statblock