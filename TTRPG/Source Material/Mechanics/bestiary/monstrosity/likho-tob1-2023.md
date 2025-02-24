---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/tob1-2023
- monster/cr/5
- monster/environment/badlands
- monster/environment/hill
- monster/size/medium
- monster/type/monstrosity
statblock: inline
aliases: ["Likho"]
---
# [Likho](Mechanics\bestiary\monstrosity/likho-tob1-2023.md)
*Source: Tome of Beasts 1 (2023 Edition) p. 254*  

*This goblin-like creature bears one large, strange eye in the middle of its face. It wears dark and dirty rags, and its spindly claws and arms match its hunched torso.*

## Ferocious Attitude

Likhos are scrappy fighters. They weaken foes from afar with their magical gaze, then rush forward, shredding the victims with their claws. Once a likho has leapt onto a creature, it shreds flesh using the claws on both its hands and feet.

## Jeers and Insults

A likho uses its limited telepathy to taunt and jeer at its target from a distance during the hunt. A likho enjoys stalking intelligent humanoids and tormenting them from hiding until discovered or when it grows tired of the hunt.

## Organ Eaters

Likhos thrive when they drain away luck and aptitude. Once the likho immobilizes a creature, it gnaws at the creature's abdomen with its jagged teeth, devouring the organs of its still-living prey. A likho consumes only a humanoid's organs and leaves the rest of the body behind.

```statblock
"name": "Likho (ToB1-2023)"
"size": "Medium"
"type": "monstrosity"
"alignment": "Chaotic Evil"
"ac": !!int "15"
"ac_class": "natural armor"
"hp": !!int "105"
"hit_dice": "14d8 + 42"
"stats":
- !!int "16"
- !!int "18"
- !!int "16"
- !!int "13"
- !!int "16"
- !!int "19"
"speed": "40 ft."
"saves":
  "Charisma": !!int "7"
  "Dexterity": !!int "7"
"skillsaves":
  "Stealth": !!int "10"
  "Perception": !!int "6"
  "Acrobatics": !!int "7"
"senses": "darkvision 60 ft., passive Perception 16"
"languages": "Common, Goblin, Void Speech"
"cr": "5"
"traits":
- "desc": "The likho can magically transmit simple messages and images to any creature\
    \ within 120 feet of it that can understand a language. This form of telepathy\
    \ doesn't allow the receiving creature to telepathically respond."
  "name": "Limited Telepathy"
- "desc": "If the likho moves at least 20 feet straight toward a creature and then\
    \ hits it with a Claw attack on the same turn, that target must succeed on a DC\
    \ 15 Strength saving throw or be knocked [prone](Mechanics/Rules/conditions.md#Prone).\
    \ If the target is [prone](Mechanics/Rules/conditions.md#Prone), the likho can\
    \ make one Claw attack against it as a bonus action."
  "name": "Pounce"
- "desc": "The likho has advantage on saving throws against spells and other magical\
    \ effects."
  "name": "Magic Resistance"
"actions":
- "desc": "The likho can use its Disruptive Gaze. It then makes four Claw attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +7 to hit, reach 5 ft., one target. Hit: 8 (1d8\
    \ + 4) slashing damage."
  "name": "Claw"
- "desc": "One creature the likho can see within 60 feet of it must succeed on a DC\
    \ 15 Charisma saving throw or have disadvantage on attack rolls, ability checks,\
    \ and saving throws until the end of its next turn."
  "name": "Disruptive Gaze"
"source":
- "ToB1-2023"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ToB1-2023/Likho.webp"
```
^statblock

## Environment

badlands, hill