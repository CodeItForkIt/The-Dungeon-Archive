---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/crcotn
- monster/cr/5
- monster/size/small
- monster/type/humanoid/cleric
- monster/type/humanoid/goblin
- monster/type/humanoid/goblinoid
statblock: inline
aliases: ["Dermot Wurder (Tier 2)"]
---
# [Dermot Wurder (Tier 2)](Mechanics\bestiary\npc/dermot-wurder-tier-2-crcotn.md)
*Source: Critical Role: Call of the Netherdeep p. 191*  

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

The tier 2 rivals are learning that their adventures take them into horrific places that will test their mettle, but they face these challenges with heads held high.

```statblock
"name": "Dermot Wurder (Tier 2) (CRCotN)"
"size": "Small"
"type": "humanoid"
"subtype": "cleric, goblin, goblinoid"
"alignment": "Lawful Good"
"ac": !!int "19"
"ac_class": "splint mail, [shield](Mechanics/items/shield.md)"
"hp": !!int "82"
"hit_dice": "15d6 + 30"
"stats":
- !!int "18"
- !!int "12"
- !!int "14"
- !!int "10"
- !!int "18"
- !!int "10"
"speed": "30 ft."
"saves":
  "Charisma": !!int "3"
  "Wisdom": !!int "7"
"skillsaves":
  "Medicine": !!int "7"
  "Religion": !!int "3"
  "Survival": !!int "7"
"senses": "darkvision 60 ft., passive Perception 14"
"languages": "Common, Goblin, Orc"
"cr": "5"
"traits":
- "desc": "Dermot casts one of the following spells, using Wisdom as the spellcasting\
    \ ability (spell save DC 15):\n\nAt will: [guidance](Mechanics/spells/guidance.md),\
    \ [light](Mechanics/spells/light.md), [spare the dying](Mechanics/spells/spare-the-dying.md)\n\
    \n1/day: [revivify](Mechanics/spells/revivify.md)\n\n2/day each: [bless](Mechanics/spells/bless.md)\
    \ (at 2nd level), [cure wounds](Mechanics/spells/cure-wounds.md) (at 3rd level)"
  "name": "Spellcasting"
"actions":
- "desc": "Dermot makes one Warhammer attack and one Searing Wrath attack."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +7 to hit, reach 5 ft., one target. Hit: 8 (1d8\
    \ + 4) bludgeoning damage, or 9 (1d10 + 4) bludgeoning damage when used with\
    \ two hands."
  "name": "Warhammer"
- "desc": "Ranged Spell Attack: +7 to hit, range 60 ft., one creature. Hit:\
    \ 18 (4d8) radiant damage, and the target is [blinded](Mechanics/Rules/conditions.md#Blinded)\
    \ until the end of its next turn."
  "name": "Searing Wrath"
"source":
- "CRCotN"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/CRCotN/Dermot%20Wurder%20%28Tier%202%29.webp"
```
^statblock