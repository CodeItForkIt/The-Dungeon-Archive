---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/mcv3mc
- monster/cr/1-4
- monster/size/medium
- monster/type/beast
statblock: inline
aliases: ["Wolf of the Overworld"]
---
# [Wolf of the Overworld](Mechanics\bestiary\beast/wolf-of-the-overworld-mcv3mc.md)
*Source: Monstrous Compendium Volume 3: Minecraft Creatures p. 7, Lightning Keep*  

Running through the forests of the Overworld on four legs, this gray-furred hunter is at home in the cold of the taiga.

Wolves hunt in packs, roaming their territories and chasing sheep, rabbits, and foxes. Wild wolves are typically indifferent to Humanoids, neither running from nor attacking them, but a pack of wolves becomes hostile toward any creature that hurts one of the pack's members. Wolves can be tamed by adventurers who feed and look after them. Tamed wolves follow their masters everywhere they go.

Wolves instinctively regard animated skeletons as enemies and attack them without hesitation. Even tamed wolves, which obediently hold themselves back from attacking their natural prey, freely charge at skeletons unless they are commanded to sit.

```statblock
"name": "Wolf of the Overworld (MCV3MC)"
"size": "Medium"
"type": "beast"
"alignment": "Unaligned"
"ac": !!int "13"
"ac_class": "natural armor"
"hp": !!int "11"
"hit_dice": "2d8 + 2"
"stats":
- !!int "12"
- !!int "15"
- !!int "12"
- !!int "3"
- !!int "12"
- !!int "6"
"speed": "40 ft."
"skillsaves":
  "Stealth": !!int "4"
  "Perception": !!int "5"
"senses": "passive Perception 15"
"languages": ""
"cr": "1/4"
"traits":
- "desc": "The wolf has advantage on attack rolls against a creature if at least one\
    \ of the wolf's allies is within 5 feet of the creature and the ally doesn't have\
    \ the [incapacitated](Mechanics/Rules/conditions.md#Incapacitated) condition."
  "name": "Pack Tactics"
"actions":
- "desc": "Melee Weapon Attack: +4 to hit; reach 5 ft., one target. Hit: 7 (2d4\
    \ + 2) piercing damage. If the target is a creature, it must succeed on a DC\
    \ 11 Strength saving throw or have the [prone](Mechanics/Rules/conditions.md#Prone)\
    \ condition."
  "name": "Bite"
"source":
- "MCV3MC"
- "LK"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/MCV3MC/Wolf%20of%20the%20Overworld.webp"
```
^statblock