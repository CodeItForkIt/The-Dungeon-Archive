---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/veor
- monster/cr/10
- monster/size/medium
- monster/type/undead
statblock: inline
aliases: ["Mirror Shade"]
---
# [Mirror Shade](Mechanics\bestiary\undead/mirror-shade-veor.md)
*Source: Vecna: Eve of Ruin p. 226*  

> [!quote] A quote from Hopewell Lightfinger, Sword Coast Adventurer  
> 
> She was great at picking locks but had a terrible cruel streak. When the cloaker got her, we were glad we'd never see her again—then, to our horror, we did.

When the spirit of a malevolent trickster or callous rogue refuses to enter the afterlife, the spirit sometimes becomes a mirror shade instead. Mirror shades are incorporeal Undead that, in their true forms, look like person-shaped blobs of shining light. More often, though, mirror shades are encountered on reflective surfaces such as mirrors or panes of glass. There, they blend in seamlessly with their reflected surroundings and wait until the moment is right to strike. Mirror shades can be found throughout the multiverse but are particularly common in the Outer Planes.

```statblock
"name": "Mirror Shade (VEoR)"
"size": "Medium"
"type": "undead"
"alignment": "typically  Chaotic Evil"
"ac": !!int "13"
"hp": !!int "91"
"hit_dice": "14d8 + 28"
"stats":
- !!int "8"
- !!int "17"
- !!int "14"
- !!int "10"
- !!int "13"
- !!int "18"
"speed": "40 ft."
"saves":
  "Dexterity": !!int "7"
  "Wisdom": !!int "5"
"skillsaves":
  "Deception": !!int "8"
  "Stealth": !!int "7"
"damage_resistances": "acid; fire; lightning; bludgeoning, piercing, slashing from\
  \ nonmagical attacks"
"damage_immunities": "poison, psychic, radiant"
"condition_immunities": "[blinded](Mechanics/Rules/conditions.md#Blinded), [exhaustion](Mechanics/Rules/conditions.md#Exhaustion),\
  \ [frightened](Mechanics/Rules/conditions.md#Frightened), [grappled](Mechanics/Rules/conditions.md#Grappled),\
  \ [paralyzed](Mechanics/Rules/conditions.md#Paralyzed), [petrified](Mechanics/Rules/conditions.md#Petrified),\
  \ [poisoned](Mechanics/Rules/conditions.md#Poisoned), [prone](Mechanics/Rules/conditions.md#Prone),\
  \ [restrained](Mechanics/Rules/conditions.md#Restrained)"
"senses": "darkvision 60 ft., passive Perception 11"
"languages": ""
"cr": "10"
"traits":
- "desc": "If the mirror shade is within 5 feet of a reflective surface—such as a\
    \ mirror, glass pane, or still water—it has advantage on its initiative roll.\
    \ If a creature hasn't observed the mirror shade move or act, that creature must\
    \ succeed on a DC 18 Intelligence ([Investigation](Mechanics/Rules/skills.md#Investigation))\
    \ check to discern that the mirror shade isn't the creature's own reflection."
  "name": "False Appearance"
- "desc": "The mirror shade can move along the surface of reflective or translucent\
    \ objects, such as mirrors, without provoking opportunity attacks. It can move\
    \ through translucent objects as if they were difficult terrain."
  "name": "Mirror Movement"
"actions":
- "desc": "The mirror shade makes two Phantasmal Strike attacks and uses Reflect Fear."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +7 to hit, reach 5 ft., one target. Hit: 7 (1d8\
    \ + 3) radiant damage plus 7 (2d6) psychic damage."
  "name": "Phantasmal Strike"
- "desc": "The mirror shade targets one creature it can see within 60 feet of itself\
    \ and projects an illusion of that creature's greatest fear. The target must make\
    \ a DC 16 Wisdom saving throw. On a failed save, the target takes 28 (8d6) psychic\
    \ damage and has the [frightened](Mechanics/Rules/conditions.md#Frightened) condition\
    \ until the start of the mirror shade's next turn. On a successful save, the target\
    \ takes half as much damage only."
  "name": "Reflect Fear"
"bonus_actions":
- "desc": "While within 5 feet of a reflective surface, such as a mirror, the mirror\
    \ shade takes the Hide action."
  "name": "Mirror Stealth"
"source":
- "VEoR"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/VEoR/Mirror%20Shade.webp"
```
^statblock