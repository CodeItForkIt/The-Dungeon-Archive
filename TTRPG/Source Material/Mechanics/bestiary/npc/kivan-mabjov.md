---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/mabjov
- monster/cr/7
- monster/size/medium
- monster/type/humanoid/elf
statblock: inline
aliases: ["Kivan"]
---
# [Kivan](Mechanics\bestiary\npc/kivan-mabjov.md)
*Source: Minsc and Boo's Journal of Villainy p. 48*  

Kivan is a highly skilled elven ranger, equally proficient in archery and melee combat. In his youth, Kivan was driven to avenge the death of his wife, Deheriana. He channeled that anger by serving the shadow druid Faldorn in various raids against towns and villages on the borders of civilization. But this anger was quelled when he met his future husband, the druid Cernd of the Emerald Enclave. He left Faldorn and joined the Emerald Enclave.

While life was good for many decades, his past eventually caught up with him. Faldorn joined the Emerald Enclave and quickly rose through the ranks to become one of the Enclave's Hierophants. She has been positioning herself to take one of the three spots in the Elder Circle—the three highest members of the Emerald Enclave.

Kivan is torn on what to do. He knows that Faldorn is secretly a shadow druid, but if he were to expose her, she would expose him as well. He would lose everything—the friends he has made, his position in the Enclave, but most of all the love of his husband, Cernd. Cernd has long battled against what he views as the corruption of the shadow druids.

Kivan is a blunt and taciturn elf who values bravery and skill in battle above all other qualities. He tirelessly hones his skills as a tracker and warrior.

## Kivan as a Contact

Kivan is the primary contact for members of the Emerald Enclave at low levels. Kivan can connect you with an animal or plant companion for a short duration. Your group can only have one of these companions at a time. Once the companion has helped you for a 24-hour period you can make an [Animal Handling](Mechanics/Rules/skills.md#Animal%20Handling), [Nature](Mechanics/Rules/skills.md#Nature) or [Persuasion](Mechanics/Rules/skills.md#Persuasion) check (depending on the creature) to convince them to stay with you for another 24 hours. Each time you make this check it increases by 1. If the companion dies while helping you, you can never gain the aid of that type of creature again. If the companion leaves your service without dying, then you can ask Kivan for another companion after one month has passed.

**Animal and Plant Companions via Kivan**

| Magical Plant and Animal Companion | Required Level | Skill Check |
|------------------------------------|----------------|-------------|
| Overly enthusiastic blink dog | 1 | DC 15 [Animal Handling](Mechanics/Rules/skills.md#Animal%20Handling) |
| Sulky needle blight | 1 | DC 15 [Nature](Mechanics/Rules/skills.md#Nature) |
| Air headed satyr | 3 | DC 15 [Persuasion](Mechanics/Rules/skills.md#Persuasion) |
| Prankster vine blight | 3 | DC 15 [Nature](Mechanics/Rules/skills.md#Nature) |
| Sarcastic dryad | 5 | DC 15 [Persuasion](Mechanics/Rules/skills.md#Persuasion) |
| Awakened tree with confusing wisdom | 7 | DC 20 [Nature](Mechanics/Rules/skills.md#Nature) |
| Doom and gloom hamadryad | 7 | DC 20 [Persuasion](Mechanics/Rules/skills.md#Persuasion) |
^animal-and-plant-companions-via-kivan

```statblock
"name": "Kivan (MaBJoV)"
"size": "Medium"
"type": "humanoid"
"subtype": "elf"
"alignment": "Chaotic Good"
"ac": !!int "16"
"ac_class": "[studded leather](Mechanics/items/studded-leather-armor.md)"
"hp": !!int "132"
"hit_dice": "24d8 + 24"
"stats":
- !!int "16"
- !!int "18"
- !!int "12"
- !!int "11"
- !!int "14"
- !!int "11"
"speed": "30 ft."
"saves":
  "Dexterity": !!int "7"
  "Wisdom": !!int "5"
"skillsaves":
  "Nature": !!int "6"
  "Stealth": !!int "10"
  "Perception": !!int "8"
  "Survival": !!int "8"
"senses": "passive Perception 18"
"languages": "Common, Elvish, Sylvan"
"cr": "7"
"traits":
- "desc": "Kivan has advantage on saving throws against being [charmed](Mechanics/Rules/conditions.md#Charmed),\
    \ and magic can't put Kivan to sleep."
  "name": "Fey Ancestry"
- "desc": "Kivan has advantage on Wisdom ([Perception](Mechanics/Rules/skills.md#Perception))\
    \ checks that rely on hearing or sight."
  "name": "Keen Hearing and Sight"
"actions":
- "desc": "Kivan makes three Longsword attacks or three Longbow attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +6 to hit, reach 5 ft., one target. Hit: 7 (1d8\
    \ + 3) slashing damage or 8 (1d10 + 3) slashing damage if wielded with two\
    \ hands."
  "name": "Longsword"
- "desc": "Ranged Weapon Attack: +7 to hit, ranged 150/600 ft., one target. Hit:\
    \ 8 (1d8 + 4) piercing damage."
  "name": "Longbow"
- "desc": "Kivan makes a Longbow attack against any number of creatures he can see\
    \ within 150 feet. He must make a separate attack roll with advantage for each\
    \ target."
  "name": "Volley (2/Day)"
"bonus_actions":
- "desc": "Kivan designates one creature he can see within 60 feet as his prey. The\
    \ first time each turn that Kivan hits his prey with a weapon attack, the prey\
    \ takes an extra 7 (2d6) damage from the weapon."
  "name": "Kivan's Mark"
"source":
- "MaBJoV"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/MaBJoV/Kivan.webp"
```
^statblock