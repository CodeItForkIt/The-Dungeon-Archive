---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/bgdia
- monster/cr/14
- monster/size/gargantuan
- monster/type/fiend/demon
statblock: inline
aliases: ["Crokek'toeck"]
---
# [Crokek'toeck](Mechanics\bestiary\npc/crokektoeck-bgdia.md)
*Source: Baldur's Gate: Descent Into Avernus p. 231*  

Crokek'toeck is Yeenoghu's demonic pet. Resembling a giant mudskipper with the teeth, fur, ears, and laugh of a hyena, this unique demon can hold smaller demons in its gullet and disgorge them anywhere Yeenoghu wishes. Immune to the mind-shattering effects of the River Styx, Crokek'toeck is often used to transport smaller demons (and sometimes Yeenoghu himself) through the Styx's terrible waters.

```statblock
"name": "Crokek'toeck (BGDIA)"
"size": "Gargantuan"
"type": "fiend"
"subtype": "demon"
"alignment": "Chaotic Evil"
"ac": !!int "15"
"ac_class": "natural armor"
"hp": !!int "297"
"hit_dice": "17d20 + 119"
"stats":
- !!int "28"
- !!int "10"
- !!int "24"
- !!int "6"
- !!int "10"
- !!int "13"
"speed": "60 ft., swim 60 ft."
"saves":
  "Wisdom": !!int "5"
  "Constitution": !!int "12"
"damage_resistances": "cold; fire; lightning; bludgeoning, piercing, slashing from\
  \ nonmagical attacks"
"damage_immunities": "poison"
"condition_immunities": "[charmed](Mechanics/Rules/conditions.md#Charmed), [frightened](Mechanics/Rules/conditions.md#Frightened),\
  \ [poisoned](Mechanics/Rules/conditions.md#Poisoned)"
"senses": "darkvision 120 ft., passive Perception 10"
"languages": "understands Abyssal but can't speak"
"cr": "14"
"traits":
- "desc": "Crokek'toeck can breathe air and water."
  "name": "Amphibious"
- "desc": "Crokek'toeck has advantage on saving throws against spells and other magical\
    \ effects."
  "name": "Magic Resistance"
- "desc": "Crokek'toeck's weapon attacks are magical."
  "name": "Magic Weapons"
- "desc": "Crokek'toeck is immune to the waters of the River Styx as well as any effect\
    \ that would steal or modify its memories or detect or read its thoughts."
  "name": "Secure Memory"
- "desc": "Crokek'toeck's long jump is up to 60 feet and its high jump is up to 30\
    \ feet, with or without a running start."
  "name": "Standing Leap"
"actions":
- "desc": "Melee Weapon Attack: +14 to hit, reach 15 ft., one target. Hit: 44\
    \ (10d6 + 9) piercing damage."
  "name": "Bite"
- "desc": "Crokek'toeck opens its mouth and disgorges 1d4 [barlguras](Mechanics/bestiary/fiend/barlgura.md),\
    \ 3d6 [gnolls](Mechanics/bestiary/humanoid/gnoll.md) led by 1 [gnoll fang of\
    \ Yeenoghu](Mechanics/bestiary/fiend/gnoll-fang-of-yeenoghu.md), 6d6 [dretches](Mechanics/bestiary/fiend/dretch.md),\
    \ or 1d3 [vrocks](Mechanics/bestiary/fiend/vrock.md). Each creature it disgorges\
    \ appears in an unoccupied space within 30 feet of Crokek'toeck's mouth, or the\
    \ next closest unoccupied space."
  "name": "Disgorge Allies (Recharge 6)"
"source":
- "BGDIA"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/BGDIA/Crokek%27toeck.webp"
```
^statblock