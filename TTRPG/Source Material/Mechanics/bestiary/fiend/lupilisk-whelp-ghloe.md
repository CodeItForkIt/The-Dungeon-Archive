---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/ghloe
- monster/cr/1
- monster/size/medium
- monster/type/fiend
statblock: inline
aliases: ["Lupilisk Whelp"]
---
# [Lupilisk Whelp](Mechanics\bestiary\fiend/lupilisk-whelp-ghloe.md)
*Source: Grim Hollow: Lairs of Etharis p. 62*  

> [!quote]  
> 
> If you find a statue in the wild with its mouth open in a scream, flee. Best case, it's an artist working out their twisted ideas. Worst case, you'll be a statue soon.

## Salvage

Someone who has proficiency with alchemist's supplies can take four lupilisk venom fangs, or just the two fangs of one lupilisk elder, and treat them with reagents worth 250 gp per tooth for 3 days. A successful treatment requires the alchemist to succeed on a DC 15 Intelligence or Wisdom check. During the treatment time, somebody must also cast lesser restoration on the fangs. After a successful treatment, someone who has proficiency with jeweler's tools can fashion the fangs, now blackened, into a necklace, creating a periapt of proof against poison. If the wearer attunes to the periapt, the amulet also provides that wearer immunity to being petrified.

## Lore

- **DC 10 Intelligence ([Arcana](Mechanics/Rules/skills.md#Arcana)).** A lupilisk's bite imparts a petrifying venom to prey. This magic toxin grows more potent as the lupilisk ages.  
- **DC 15 Intelligence ([History](Mechanics/Rules/skills.md#History)).** Lupilisks live in packs with an elder couple in the lead. This couple are the parents of most other pack members.  

```statblock
"name": "Lupilisk Whelp (GHLoE)"
"size": "Medium"
"type": "fiend"
"alignment": "Neutral Evil"
"ac": !!int "12"
"hp": !!int "33"
"hit_dice": "6d8 + 6"
"stats":
- !!int "13"
- !!int "14"
- !!int "12"
- !!int "3"
- !!int "11"
- !!int "6"
"speed": "40 ft."
"skillsaves":
  "Stealth": !!int "4"
  "Perception": !!int "2"
"damage_resistances": "cold, fire"
"damage_immunities": "poison"
"condition_immunities": "[poisoned](Mechanics/Rules/conditions.md#Poisoned)"
"senses": "darkvision 120 ft., passive Perception 12"
"languages": "can learn languages but can't speak"
"cr": "1"
"traits":
- "desc": "The lupilisk whelp has advantage on Wisdom ([Perception](Mechanics/Rules/skills.md#Perception))\
    \ checks that rely on hearing or smell."
  "name": "Keen Hearing and Smell"
- "desc": "The lupilisk whelp has advantage on an attack roll against a creature if\
    \ at least one of the lupilisk's allies is within 5 feet of the creature and the\
    \ ally isn't [incapacitated](Mechanics/Rules/conditions.md#Incapacitated)."
  "name": "Pack Tactics"
"actions":
- "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 7 (2d4\
    \ + 2) piercing damage and 5 (2d4) poison damage. If the target is a creature,\
    \ it must succeed on a DC 11 Constitution saving throw or become [poisoned](Mechanics/Rules/conditions.md#Poisoned)\
    \ and [restrained](Mechanics/Rules/conditions.md#Restrained) while [poisoned](Mechanics/Rules/conditions.md#Poisoned)\
    \ in this way. The creature must repeat the saving throw at the end of its next\
    \ turn. On a success, the effect ends. If the save fails again, the creature is\
    \ [petrified](Mechanics/Rules/conditions.md#Petrified) for 24 hours."
  "name": "Bite"
"source":
- "GHLoE"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/GHLoE/Lupilisk%20Whelp.webp"
```
^statblock