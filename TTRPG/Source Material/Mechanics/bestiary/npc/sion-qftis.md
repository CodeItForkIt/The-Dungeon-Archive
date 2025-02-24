---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/qftis
- monster/cr/2
- monster/size/medium
- monster/type/humanoid/human
- monster/type/humanoid/sorcerer
statblock: inline
aliases: ["Sion"]
---
# [Sion](Mechanics\bestiary\npc/sion-qftis.md)
*Source: Quests from the Infinite Staircase p. 216*  

Sion is the most trusted servant of Piyarz, a traitorous sage in the Tower of the Heavens. Originally one of the tower's stewards, Sion displayed an innate talent for magic. Piyarz encouraged Sion to develop his arcane powers in secret, and in time Sion became a skilled shadow sorcerer. He kept his umbral abilities hidden from the tower's other residents. Even so, they all noticed his fervent devotion to Piyarz and, ironically, refer to him in private as "Piyarz's shadow."

Sion's sorcery allows him to step in and out of shadows and create shadowy duplicates of himself. He can even exercise limited control over others' shadows, causing the shadows to grasp their hosts and pin them in place. Wherever Sion goes, he's accompanied by his two pets, a ferocious hound and an oversized raven that help Sion track down his enemies. Spun by Sion from pure shadow, both creatures use the shadow stat block, but the raven has a flying speed of 40 feet.

```statblock
"name": "Sion (QftIS)"
"size": "Medium"
"type": "humanoid"
"subtype": "human, sorcerer"
"alignment": "Neutral Evil"
"ac": !!int "12"
"hp": !!int "49"
"hit_dice": "9d8 + 9"
"stats":
- !!int "16"
- !!int "14"
- !!int "13"
- !!int "12"
- !!int "14"
- !!int "16"
"speed": "30 ft."
"saves":
  "Charisma": !!int "5"
  "Constitution": !!int "3"
"skillsaves":
  "Stealth": !!int "6"
  "Perception": !!int "4"
  "Arcana": !!int "3"
"senses": "darkvision 120 ft., passive Perception 14"
"languages": "Common"
"cr": "2"
"traits":
- "desc": "Sion casts one of the following spells, using Charisma as the spellcasting\
    \ ability (spell save DC 13):\n\nAt will: [Mage Hand](Mechanics/spells/mage-hand.md),\
    \ [Minor Illusion](Mechanics/spells/minor-illusion.md)\n\n1/day each: [Darkness](Mechanics/spells/darkness.md),\
    \ [Mirror Image](Mechanics/spells/mirror-image.md), [Silence](Mechanics/spells/silence.md)"
  "name": "Spellcasting"
- "desc": "Sion has advantage on saving throws against spells and other magical effects\
    \ if he is in dim light or darkness."
  "name": "Magic Resistance"
- "desc": "Magical darkness doesn't impede Sion's darkvision."
  "name": "Shadesight"
- "desc": "If Sion dies, his body melts into shadow, leaving behind only equipment\
    \ he was wearing or carrying."
  "name": "Shadowy Demise"
- "desc": "While in sunlight, Sion has disadvantage on attack rolls, ability checks,\
    \ and saving throws."
  "name": "Sunlight Weakness"
"actions":
- "desc": "Sion makes one Shadow Sword attack and uses Affix Shadow or Spellcasting."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 14\
    \ (2d10 + 3) necrotic damage."
  "name": "Shadow Sword"
- "desc": "Sion targets a creature within 60 feet of himself that he can see. That\
    \ target must make a DC 13 Charisma saving throw. On a failed save, the target\
    \ has the [grappled](Mechanics/Rules/conditions.md#Grappled) condition (escape\
    \ DC 13) as its shadow wraps around it. Once the target escapes the grapple, its\
    \ shadow returns to normal."
  "name": "Affix Shadow"
"bonus_actions":
- "desc": "While Sion is in dim light or darkness, he magically teleports up to 15\
    \ feet to an unoccupied space he can see that is also in dim light or darkness."
  "name": "Shadow Step"
"source":
- "QftIS"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/QftIS/Sion.webp"
```
^statblock