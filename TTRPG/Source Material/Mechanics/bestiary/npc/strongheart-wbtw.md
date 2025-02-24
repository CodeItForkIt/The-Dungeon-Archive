---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/wbtw
- monster/cr/4
- monster/size/medium
- monster/type/humanoid/human
- monster/type/humanoid/paladin
statblock: inline
aliases: ["Strongheart"]
---
# [Strongheart](Mechanics\bestiary\npc/strongheart-wbtw.md)
*Source: The Wild Beyond the Witchlight p. 228*  

Strongheart is a fearless seeker of justice, risking his life to ensure that good triumphs over evil. He is thoughtful, kind, and seldom rash, yet never hesitant to punish those who spit in the face of law and order.

Strongheart doesn't worship a god but devotes himself to an ideal: that the world can be spared from evil by those who have enough courage to stand against it.

```statblock
"name": "Strongheart (WBtW)"
"size": "Medium"
"type": "humanoid"
"subtype": "human, paladin"
"alignment": "Lawful Good"
"ac": !!int "20"
"ac_class": "[plate armor](Mechanics/items/plate-armor.md), [shield](Mechanics/items/shield.md)"
"hp": !!int "55"
"hit_dice": "10d8 + 10"
"stats":
- !!int "15"
- !!int "12"
- !!int "13"
- !!int "12"
- !!int "13"
- !!int "17"
"speed": "30 ft."
"saves":
  "Charisma": !!int "5"
  "Wisdom": !!int "3"
"skillsaves":
  "Insight": !!int "3"
  "Persuasion": !!int "5"
"condition_immunities": "[frightened](Mechanics/Rules/conditions.md#Frightened)"
"senses": "passive Perception 11"
"languages": "Common, Dwarvish"
"cr": "4"
"traits":
- "desc": "Strongheart casts one of the following spells, using Charisma as the spellcasting\
    \ ability (spell save DC 13):\n\n1/day each: [lesser restoration](Mechanics/spells/lesser-restoration.md),\
    \ [remove curse](Mechanics/spells/remove-curse.md), [zone of truth](Mechanics/spells/zone-of-truth.md)\n\
    \n3/day each: [command](Mechanics/spells/command.md), [detect evil and good](Mechanics/spells/detect-evil-and-good.md),\
    \ [protection from evil and good](Mechanics/spells/protection-from-evil-and-good.md)"
  "name": "Spellcasting"
- "desc": "Strongheart wields Steel, a sentient, lawful good longsword (see appendix\
    \ A)."
  "name": "Special Equipment"
"actions":
- "desc": "Strongheart makes three Steel attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +6 to hit, reach 5 ft., one target. Hit: 8 (1d8\
    \ + 4) slashing damage, or 9 (1d10 + 4) slashing damage when used with two\
    \ hands. Once on each of his turns, Strongheart can also cause the blade to gleam\
    \ with holy light. If he does so, the target is [blinded](Mechanics/Rules/conditions.md#Blinded)\
    \ until the start of Strongheart's next turn."
  "name": "Steel"
- "desc": "While holding Steel, Strongheart casts [revivify](Mechanics/spells/revivify.md)."
  "name": "Revivify (Recharges at the Next Dawn)"
"reactions":
- "desc": "When a creature Strongheart can see attacks another creature that is within\
    \ 5 feet of him, Strongheart can use his reaction to impose disadvantage on the\
    \ attack roll, provided he is carrying a shield."
  "name": "Protect Another"
"source":
- "WBtW"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/WBtW/Strongheart.webp"
```
^statblock