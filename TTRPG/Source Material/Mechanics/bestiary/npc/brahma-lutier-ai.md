---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/ai
- monster/cr/2
- monster/size/medium
- monster/type/humanoid/elf
statblock: inline
aliases: ["Brahma Lutier"]
---
# [Brahma Lutier](Mechanics\bestiary\npc/brahma-lutier-ai.md)
*Source: Acquisitions Incorporated p. 205*  

Formally a former member of the "B" Team, Brahma Lutier is a gifted cartographer, spy, and troubadour. Tutored in at least the latter of those vocations by Audra Courtier (wife of Propha Dran and co-owner of the Dran & Courtier inn of Red Larch), Brahma's specialty is a song of domination that is legendarily difficult to resist.

Her retirement is said to be connected to a falling out with husband Oak Truestrike, and Brahma has been operating as a solo agent for some time now. Known for a personality that is murderous and cheery in equal part, she utilizes an instrument of dragonborn design in combat. Known as a war lute, this unique item comes replete with hidden storage and powerful weaponry.

```statblock
"name": "Brahma Lutier (AI)"
"size": "Medium"
"type": "humanoid"
"subtype": "elf"
"alignment": "Neutral"
"ac": !!int "12"
"hp": !!int "33"
"hit_dice": "6d8 + 6"
"stats":
- !!int "12"
- !!int "15"
- !!int "12"
- !!int "11"
- !!int "13"
- !!int "16"
"speed": "30 ft."
"skillsaves":
  "Perception": !!int "3"
  "Performance": !!int "5"
  "Persuasion": !!int "5"
"senses": "passive Perception 13"
"languages": "Common, Elvish"
"cr": "2"
"traits":
- "desc": "Brahma is a 4th-level spellcaster. Her spellcasting ability is Charisma\
    \ (spell save DC 13, +5 to hit with spell attacks). She has the following bard\
    \ spells prepared:\n\nCantrips (at will): [mage hand](Mechanics/spells/mage-hand.md),\
    \ [message](Mechanics/spells/message.md), [vicious mockery](Mechanics/spells/vicious-mockery.md)\n\
    \n1st level (4 slots): [charm person](Mechanics/spells/charm-person.md), [heroism](Mechanics/spells/heroism.md),\
    \ [illusory script](Mechanics/spells/illusory-script.md), [sleep](Mechanics/spells/sleep.md),\
    \ [unseen servant](Mechanics/spells/unseen-servant.md)\n\n2nd level (3 slots):\
    \ [cloud of daggers](Mechanics/spells/cloud-of-daggers.md), [invisibility](Mechanics/spells/invisibility.md)"
  "name": "Spellcasting"
- "desc": "Brahma has advantage on saving throws against being [charmed](Mechanics/Rules/conditions.md#Charmed),\
    \ and magic can't put her to sleep."
  "name": "Fey Ancestry"
- "desc": "Brahma can use a bonus action to target one creature she can see within\
    \ 30 feet of her. If the target can hear Brahma, it must succeed on a DC 13 Charisma\
    \ saving throw or have disadvantage on ability checks, attack rolls, and saving\
    \ throws until the start of Brahma's next turn."
  "name": "Taunt (2/Day)"
"actions":
- "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 5 (1d6\
    \ + 2) slashing damage."
  "name": "War Lute"
- "desc": "Brahma targets one creature that can see or hear her, which must succeed\
    \ on a DC 13 Wisdom saving throw or be [charmed](Mechanics/Rules/conditions.md#Charmed)\
    \ by her for 1 minute. The target can repeat the save at the end of each of its\
    \ turns, ending the effect on itself on a success. It has disadvantage on these\
    \ saves if being [charmed](Mechanics/Rules/conditions.md#Charmed) by Brahma is\
    \ something the target openly or secretly desires. For 1 hour after the charm\
    \ effect ends, the target has disadvantage on Intelligence, Wisdom, or Charisma\
    \ checks made as part of a contest with Brahma."
  "name": "Song of Domination (3/Day)"
"source":
- "AI"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/AI/Brahma%20Lutier.webp"
```
^statblock