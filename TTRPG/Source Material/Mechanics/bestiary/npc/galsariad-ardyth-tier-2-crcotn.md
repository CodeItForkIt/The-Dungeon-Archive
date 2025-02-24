---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/crcotn
- monster/cr/5
- monster/size/medium
- monster/type/humanoid/drow
- monster/type/humanoid/elf
- monster/type/humanoid/wizard
statblock: inline
aliases: ["Galsariad Ardyth (Tier 2)"]
---
# [Galsariad Ardyth (Tier 2)](Mechanics\bestiary\npc/galsariad-ardyth-tier-2-crcotn.md)
*Source: Critical Role: Call of the Netherdeep p. 190*  

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

The tier 2 rivals are learning that their adventures take them into horrific places that will test their mettle, but they face these challenges with heads held high.

```statblock
"name": "Galsariad Ardyth (Tier 2) (CRCotN)"
"size": "Medium"
"type": "humanoid"
"subtype": "drow, elf, wizard"
"alignment": "Neutral"
"ac": !!int "12"
"hp": !!int "67"
"hit_dice": "15d8"
"stats":
- !!int "8"
- !!int "14"
- !!int "10"
- !!int "18"
- !!int "15"
- !!int "12"
"speed": "30 ft., fly 30 ft. (hover)"
"saves":
  "Wisdom": !!int "5"
  "Intelligence": !!int "7"
"skillsaves":
  "Nature": !!int "7"
  "Investigation": !!int "7"
  "Arcana": !!int "7"
"senses": "darkvision 120 ft., passive Perception 12"
"languages": "Common, Draconic, Undercommon"
"cr": "5"
"traits":
- "desc": "Galsariad casts one of the following spells, using Intelligence as the\
    \ spellcasting ability (spell save DC 15):\n\nAt will: [mage armor](Mechanics/spells/mage-armor.md),\
    \ [mage hand](Mechanics/spells/mage-hand.md)\n\n1/day each: [longstrider](Mechanics/spells/longstrider.md),\
    \ [scrying](Mechanics/spells/scrying.md) (as an action), [slow](Mechanics/spells/slow.md)"
  "name": "Spellcasting"
- "desc": "Galsariad has advantage on saving throws against being [charmed](Mechanics/Rules/conditions.md#Charmed),\
    \ and magic can't put him to sleep."
  "name": "Fey Ancestry"
"actions":
- "desc": "Melee or Ranged Spell Attack: +7 to hit, reach 5 ft. or range 60 ft.,\
    \ one creature. Hit: 22 (4d10) necrotic damage, and Galsariad gains 5 temporary\
    \ hit points."
  "name": "Drain Potential"
- "desc": "Galsariad causes a rippling wave of magical gravity to fill a 20-foot-radius\
    \ sphere centered on a point he can see within 100 feet of himself. Each creature\
    \ in that area must make a DC 15 Strength saving throw. On a failed saving throw,\
    \ the creature takes 35 (10d6) force damage and is pulled up to 20 feet toward\
    \ the sphere's center, and is knocked [prone](Mechanics/Rules/conditions.md#Prone).\
    \ On a successful save, the creature takes half as much damage and isn't pulled\
    \ or knocked [prone](Mechanics/Rules/conditions.md#Prone)."
  "name": "Gravity Wave (Recharge 5-6)"
"bonus_actions":
- "desc": "Galsariad targets himself or one willing creature that he can see within\
    \ 60 feet of himself, magically distorting gravity around the target. Any creature\
    \ within 5 feet of the target takes 7 (2d6) force damage. In addition, the target\
    \ can use a reaction to float upward, up to 20 feet, without provoking opportunity\
    \ attacks. When this effect ends at the start of Galsariad's next turn, the target\
    \ floats gently down up to 20 feet."
  "name": "Distort Gravity (1/Day)"
"source":
- "CRCotN"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/CRCotN/Galsariad%20Ardyth%20%28Tier%202%29.webp"
```
^statblock