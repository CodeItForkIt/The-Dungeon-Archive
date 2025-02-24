---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/crcotn
- monster/cr/8
- monster/size/medium
- monster/type/humanoid/drow
- monster/type/humanoid/elf
- monster/type/humanoid/wizard
aliases: ["Galsariad Ardyth (Tier 3)"]
---
# Galsariad Ardyth (Tier 3)
*Source: Critical Role: Call of the Netherdeep p. 193*  

Beautiful, ethereal, deathly, shadowy—all accurately describe Galsariad Ardyth, a drow in his two-hundredth year of life. He's recently taken up the study of arcane magic, and he's pursuing the life of an adventurer in hopes of improving his reputation within the Kryn Dynasty. Loquacious, snarky, and sarcastic to a fault, he's ready with a barb for any occasion—usually to mask his own insecurities.

A city-dweller from the Kryn capital of Rosohna, Galsariad is blessed with sharp aesthetic sensibilities and an interest in ancient lore, especially history concerning the Age of Arcanum, Exandria's long-lost magical golden age. He's also the newest member of the rival party, and both Ayo and Irvan are impressed by his ethereal elegance—and have a bit of a crush on him, even if he does talk too much.

Galsariad appreciates people who share his interests and are willing to spend time studying with him, though he also likes it when people treat him with respect even if they don't care about magic. He dislikes people who keep secrets from him, and hates when people judge him for being a novice at magic even though he's centuries old.

> [!note] Battle Chatter Sample Quotes
> 
> "You have much to learn." "And here I thought you possessed some talent." "With this next incantation, I shall pluck any hope of victory from your mind."
^battle-chatter-sample-quotes

## Rival Stat Blocks

Stat blocks for the rivals can be found in appendix A. Each of the rivals has three stat blocks; like the characters, they become more powerful as the adventure progresses. The Rival Stat Blocks table shows you which stat blocks to use based on the chapter you are running.

### Rival Stat Blocks

| Chapters | Stat Blocks |
|----------|-------------|
| 1 and 2 | Galsariad Ardyth (Tier 1) |
| 3 and 4 | Galsariad Ardyth (Tier 2) |
| 5, 6, and 7 | Galsariad Ardyth (Tier 3) |
^chapters-stat-blocks

Their journey has forced the tier 3 rivals to make decisions, sometimes out of grim necessity, that they might have not made earlier. All five suffer from ruidium corruption (see "Ruidium "in the introduction). When the characters encounter them, assume that the rivals have removed all levels of exhaustion from themselves through rest or magic, but the other effects of ruidium corruption remain.

If instead you want to weaken the rivals to make them less of a physical threat or reinforce the danger of ruidium corruption, you can give one or more of the rivals `dice:1d4|noform|avg` (`1d4`) levels of exhaustion each. In this case, you'll need to keep track of each rival's exhaustion level and the condition's corresponding effects (see "Exhaustion "in the *Player's Handbook*).

#### Useful Magic

To facilitate their efforts, Galsariad has learned the water breathing spell. Additionally, all the rivals have acquired ruidium equipment to protect them from the effects of underwater pressure.

## Statblock

```ad-statblock
title: Galsariad Ardyth (Tier 3)
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/CRCotN/Galsariad%20Ardyth%20%28Tier%203%29.webp#token)
*Medium humanoid (drow, elf, wizard), Neutral*

- **Armor Class** 17 (deflection)
- **Hit Points** 90 (`20d8`)
- **Speed** 30 ft., fly 30 ft. (hover), swim 40 ft. (ring of swimming)

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
| 8 (-1)|14 (+2)|10 (+0)|20 (+5)|15 (+2)|12 (+1)|

- **Proficiency Bonus** +3
- **Saving Throws** Intelligence +8, Wisdom +5
- **Skills** Arcana +8, Investigation +8, Nature +8
- **Senses** darkvision 120 ft., passive Perception 12
- **Languages** Common, Draconic, Undercommon
- **Challenge** 8

## Traits

***Deflection.*** Galsariad warps gravity around himself to magically deflect incoming attacks. While Galsariad is wearing no armor and not [incapacitated](2-Mechanics/CLI/rules/conditions.md#Incapacitated), his AC includes his Intelligence modifier.

***Fey Ancestry.*** Galsariad has advantage on saving throws against being [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), and magic can't put him to sleep.

***Special Equipment.*** Galsariad wears a [ring of swimming](2-Mechanics/CLI/items/ring-of-swimming.md) and carries a ruidium dagger (see appendix B). If he rolls a 1 on an attack roll made with the dagger, he must succeed on a DC 20 Charisma saving throw or gain 1 level of [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion).

***Spellcasting.*** Galsariad casts one of the following spells, using Intelligence as the spellcasting ability (spell save DC 16):

**At will**: [mage hand](2-Mechanics/CLI/spells/mage-hand.md)

**1/day each**: [longstrider](2-Mechanics/CLI/spells/longstrider.md), [scrying](2-Mechanics/CLI/spells/scrying.md) (as an action), [slow](2-Mechanics/CLI/spells/slow.md), [telekinesis](2-Mechanics/CLI/spells/telekinesis.md), [water breathing](2-Mechanics/CLI/spells/water-breathing.md)

## Actions

***Multiattack.*** Galsariad makes one Drain Potential attack and one Ruidium Dagger attack.

***Drain Potential.*** *Melee or Ranged Spell Attack:* `dice:1d20+8|noform|text(+8)` to hit, reach 5 ft. or range 120 ft., one creature. *Hit:* `dice:4d10|noform|avg|text(22)` (`4d10`) necrotic damage, and Galsariad gains 10 temporary hit points.

***Ruidium Dagger.*** *Melee or Ranged Weapon Attack:* `dice:1d20+5|noform|text(+5)` to hit, reach 5 ft. or range 20/60 ft., one target. *Hit:* `dice:1d4+2|noform|avg|text(4)` (`1d4 + 2`) piercing damage plus `dice:2d6|noform|avg|text(7)` (`2d6`) psychic damage.

***Gravity Wave (Recharge 5-6).*** Galsariad causes a rippling wave of magical gravity to fill a 30-foot-radius sphere centered on a point he can see within 100 feet of himself. Each creature in that area must make a DC 16 Strength saving throw. On a failed saving throw, the creature takes `dice:12d6|noform|avg|text(42)` (`12d6`) force damage and is [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained) for 1 minute. On a successful save, the creature takes half as much damage and isn't [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained). A [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained) creature can repeat the save at the end of each of its turns, ending the effect on itself on a success.

## Bonus Actions

***Distort Gravity (1/Day).*** Galsariad targets himself or one willing creature that he can see within 60 feet of himself, magically distorting gravity around the target. Any creature within 5 feet of the target takes `dice:4d6|noform|avg|text(14)` (`4d6`) force damage. In addition, the target can use a reaction to float upward, up to 20 feet, without provoking opportunity attacks. When this effect ends at the start of Galsariad's next turn, the target floats gently down up to 20 feet.
```
^statblock