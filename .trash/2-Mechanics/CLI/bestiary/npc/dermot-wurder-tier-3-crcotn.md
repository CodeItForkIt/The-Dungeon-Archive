---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/crcotn
- monster/cr/8
- monster/size/small
- monster/type/humanoid/cleric
- monster/type/humanoid/goblin
- monster/type/humanoid/goblinoid
aliases: ["Dermot Wurder (Tier 3)"]
---
# Dermot Wurder (Tier 3)
*Source: Critical Role: Call of the Netherdeep p. 193*  

When you're the twelfth son of a poor goblin family in Jigow, the only way to make a name for yourself is to become a great champion—someone who can win bragging contests in the local taverns night after night. Young Dermot Wurder, however, wasn't interested in performing feats of strength or agility that would win him a boast-worthy epithet. Fame wasn't for him, nor was the aggressiveness that becoming famous required. He was more interested in cooking, planting flowers, and sewing clothes—doing the work that kept his family together while his carefree siblings dove off waterfalls and wrestled stray dogs.

Dermot and Ayo Jabe have known each other long enough that their first meeting has vanished into the haze of youthful pre-memory. Dermot accompanied Ayo whenever he could, packing herbs and medicines when they went exploring in the woods. When Ayo recently told him of her dream to form an adventuring party, he started training to wear heavy armor and threw himself into studying the faith of the Luxon so he could wield the blessings of the light to protect those he cares about.

Dermot is fiercely protective of his friends and furiously rebukes anyone who disparages or threatens them. His deepest need—one even he doesn't know he has—is to make a friend who will help him realize what he wants for himself.

> [!note] Battle Chatter Sample Quotes
> 
> "I'm here to make sure no one dies. Back off!" "The Luxon will protect me." "Ayo, Maggie, I could use a little help here!"
^battle-chatter-sample-quotes

## Rival Stat Blocks

Stat blocks for the rivals can be found in appendix A. Each of the rivals has three stat blocks; like the characters, they become more powerful as the adventure progresses. The Rival Stat Blocks table shows you which stat blocks to use based on the chapter you are running.

### Rival Stat Blocks

| Chapters | Stat Blocks |
|----------|-------------|
| 1 and 2 | Dermot Wurder (Tier 1) |
| 3 and 4 | Dermot Wurder (Tier 2) |
| 5, 6, and 7 | Dermot Wurder (Tier 3) |
^chapters-stat-blocks

Their journey has forced the tier 3 rivals to make decisions, sometimes out of grim necessity, that they might have not made earlier. All five suffer from ruidium corruption (see "Ruidium "in the introduction). When the characters encounter them, assume that the rivals have removed all levels of exhaustion from themselves through rest or magic, but the other effects of ruidium corruption remain.

If instead you want to weaken the rivals to make them less of a physical threat or reinforce the danger of ruidium corruption, you can give one or more of the rivals `dice:1d4|noform|avg` (`1d4`) levels of exhaustion each. In this case, you'll need to keep track of each rival's exhaustion level and the condition's corresponding effects (see "Exhaustion "in the *Player's Handbook*).

#### Useful Magic

To facilitate their efforts, Galsariad has learned the water breathing spell. Additionally, all the rivals have acquired ruidium equipment to protect them from the effects of underwater pressure.

## Statblock

```ad-statblock
title: Dermot Wurder (Tier 3)
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/CRCotN/Dermot%20Wurder%20%28Tier%203%29.webp#token)
*Small humanoid (cleric, goblin, goblinoid), Lawful Good*

- **Armor Class** 20 ([plate](2-Mechanics/CLI/items/plate-armor.md), [shield](2-Mechanics/CLI/items/shield.md))
- **Hit Points** 93 (`17d6 + 34`)
- **Speed** 30 ft., swim 30 ft. (mariner's armor)

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|18 (+4)|12 (+1)|14 (+2)|10 (+0)|20 (+5)|10 (+0)|

- **Proficiency Bonus** +3
- **Saving Throws** Wisdom +8, Charisma +3
- **Skills** Medicine +8, Religion +3, Survival +8
- **Senses** darkvision 60 ft., passive Perception 15
- **Languages** Common, Goblin, Orc
- **Challenge** 8

## Traits

***Special Equipment.*** Dermot wears [mariner's armor](2-Mechanics/CLI/items/mariners-armor.md) and wields a ruidium warhammer (see appendix B). If Dermot rolls a 1 on an attack roll made with the warhammer, he must succeed on a DC 20 Charisma saving throw or gain 1 level of [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion).

***Spellcasting.*** Dermot casts one of the following spells, using Wisdom as the spellcasting ability (spell save DC 16):

**At will**: [guidance](2-Mechanics/CLI/spells/guidance.md), [light](2-Mechanics/CLI/spells/light.md), [spare the dying](2-Mechanics/CLI/spells/spare-the-dying.md)

**1/day**: [revivify](2-Mechanics/CLI/spells/revivify.md)

**2/day each**: [bless](2-Mechanics/CLI/spells/bless.md) (at 3rd level), [cure wounds](2-Mechanics/CLI/spells/cure-wounds.md) (at 3rd level)

## Actions

***Multiattack.*** Dermot makes one Ruidium Warhammer attack and one Searing Wrath attack.

***Ruidium Warhammer.*** *Melee Weapon Attack:* `dice:1d20+7|noform|text(+7)` to hit, reach 5 ft., one target. *Hit:* `dice:1d8+4|noform|avg|text(8)` (`1d8 + 4`) bludgeoning damage, or `dice:1d10+4|noform|avg|text(9)` (`1d10 + 4`) bludgeoning damage when used with two hands, plus `dice:2d6|noform|avg|text(7)` (`2d6`) psychic damage.

***Searing Wrath.*** *Ranged Spell Attack:* `dice:1d20+8|noform|text(+8)` to hit, range 60 ft., one creature. *Hit:* `dice:5d8|noform|avg|text(22)` (`5d8`) radiant damage, and the target is [blinded](2-Mechanics/CLI/rules/conditions.md#Blinded) until the end of its next turn.
```
^statblock