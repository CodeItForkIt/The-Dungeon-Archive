---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/tob1-2023
- monster/cr/6
- monster/environment/forest
- monster/size/huge
- monster/type/plant
statblock: inline
aliases: ["Weeping Treant"]
---
# [Weeping Treant](Mechanics\bestiary\plant/weeping-treant-tob1-2023.md)
*Source: Tome of Beasts 1 (2023 Edition) p. 369*  

*This twisted tree's face is made of cracked, black bark knotted into vaguely humanoid features, and thick tears of sap run down its face.*

Weeping treants clearly are related to other treants, but they are smaller than the normal variety. Their gnarled trunks are twisted, and their wood often groans when they move.

## Forest Wardens

Weeping treants are protectors of dark, shadowy forests—particularly forests in the Plane of Shadow—and they are as long-lived as the trees themselves. They act as guardians for an entire forest or for something specific within the forest, and they have no pity for those carrying axes or fire.

## Skeptical Mein

Weeping treants are terrifying and relentless when fighting in defense of their charge. They are inherently distrustful, particularly of anything not of the natural or shadow world, and they're notoriously difficult to fool or deceive.

## Enchanted Bitter Tears

Sages and scholars debate why these creatures weep, but no one has come forward with a compelling reason beyond "it's what trees do." The weeping treants themselves refuse to speak on the matter. Their tears are occasionally components in druidic spells or items.

```statblock
"name": "Weeping Treant (ToB1-2023)"
"size": "Huge"
"type": "plant"
"alignment": "Neutral"
"ac": !!int "17"
"ac_class": "natural armor"
"hp": !!int "105"
"hit_dice": "10d12 + 40"
"stats":
- !!int "21"
- !!int "8"
- !!int "18"
- !!int "12"
- !!int "16"
- !!int "11"
"speed": "30 ft."
"skillsaves":
  "Insight": !!int "6"
"damage_vulnerabilities": "fire"
"damage_resistances": "bludgeoning, piercing"
"senses": "darkvision 60 ft., passive Perception 13"
"languages": "Common, Druidic, Elvish, Sylvan, Umbral"
"cr": "6"
"traits":
- "desc": "The weeping treant deals double damage to objects and structures."
  "name": "Siege Monster"
- "desc": "The weeping treant can communicate with plants as if they shared a language."
  "name": "Speak with Plants"
- "desc": "Thick tears of dark, acidic sap stream continuously down the treant's face\
    \ and trunk. A creature that touches the weeping treant or hits it with a melee\
    \ attack while within 5 feet of it must succeed on a DC 15 Dexterity saving throw\
    \ or take 3 (1d6) acid damage."
  "name": "Weep Acid"
"actions":
- "desc": "The weeping treant makes two Slam or Rock attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +8 to hit, reach 5 ft., single target. Hit:\
    \ 15 (3d6 + 5) bludgeoning damage plus 3 (2d6) acid damage, and the target\
    \ takes 3 (1d6) acid damage at the end of its next turn unless it or another\
    \ creature takes an action to wipe off the acid."
  "name": "Slam"
- "desc": "Ranged Weapon Attack: +8 to hit, range 60/180 ft., one target. Hit:\
    \ 21 (3d10 + 5) bludgeoning damage."
  "name": "Rock"
"source":
- "ToB1-2023"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ToB1-2023/Weeping%20Treant.webp"
```
^statblock

## Environment

forest