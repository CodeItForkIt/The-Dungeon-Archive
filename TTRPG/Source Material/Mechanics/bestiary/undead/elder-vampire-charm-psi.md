---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/psi
- monster/cr/5
- monster/size/medium
- monster/type/undead
statblock: inline
aliases: ["Elder Vampire: Charm"]
---
# [Elder Vampire: Charm](Mechanics\bestiary\undead/elder-vampire-charm-psi.md)
*Source: Plane Shift: Innistrad p. 17*  

```statblock
"name": "Elder Vampire: Charm (PSI)"
"size": "Medium"
"type": "undead"
"alignment": "Neutral Evil"
"ac": !!int "15"
"ac_class": "natural armor"
"hp": !!int "82"
"hit_dice": "11d8 + 33"
"stats":
- !!int "16"
- !!int "16"
- !!int "16"
- !!int "11"
- !!int "10"
- !!int "12"
"speed": "30 ft."
"saves":
  "Dexterity": !!int "6"
  "Wisdom": !!int "3"
"skillsaves":
  "Stealth": !!int "6"
  "Perception": !!int "3"
"damage_resistances": "necrotic; bludgeoning, piercing, slashing from nonmagical attacks\
  \ not made with living wood weapons"
"senses": "darkvision 60 ft., passive Perception 13"
"languages": "Common"
"cr": "5"
"traits":
- "desc": "The vampire regains 10 hit points at the start of its turn if it has at\
    \ least 1 hit point. If the vampire takes radiant damage or damage from holy water,\
    \ this trait doesn't function at the start of the vampire's next turn."
  "name": "Regeneration"
"actions":
- "desc": "The vampire makes two attacks, only one of which can be a bite attack."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +6 to hit, reach 5 ft., one creature. Hit: 8\
    \ (2d4 + 3) slashing damage. Instead of dealing damage, the vampire can grapple\
    \ the target (escape DC 13)."
  "name": "Claws"
- "desc": "Melee Weapon Attack: +6 to hit, reach 5 ft., one willing creature,\
    \ or a creature that is [grappled](Mechanics/Rules/conditions.md#Grappled) by\
    \ the vampire, [incapacitated](Mechanics/Rules/conditions.md#Incapacitated), or\
    \ [restrained](Mechanics/Rules/conditions.md#Restrained). Hit: 6 (1d6 + 3)\
    \ piercing damage plus 7 (2d6) necrotic damage. The target's hit point maximum\
    \ is reduced by an amount equal to the necrotic damage taken, and the vampire\
    \ regains hit points equal to that amount. The reduction lasts until the target\
    \ finishes a long rest. The target dies if this effect reduces its hit point maximum\
    \ to 0."
  "name": "Bite"
- "desc": "The vampire obscures its form with mind-affecting magic that makes others\
    \ perceive it as a beautiful human of the same size and shape. The illusion ends\
    \ if the vampire takes a bonus action to end it or if the vampire dies. A creature\
    \ that can see the vampire can take an action to visually inspect it, ending the\
    \ mental effect on itself and seeing the vampire's true form with a successful\
    \ DC 20 Wisdom ([Perception](Mechanics/Rules/skills.md#Perception)) check."
  "name": "Vampiric Glamer"
- "desc": "The vampire shrouds itself in a cloak of silence to a radius of 2 feet.\
    \ Within that radius, the effect is the same as the [silence](Mechanics/spells/silence.md)\
    \ spell."
  "name": "Aura of Silence"
- "desc": "The vampire targets one humanoid it can see within 30 feet of it. If the\
    \ target can see the vampire, the target must succeed on a DC 17 Wisdom saving\
    \ throw against this magic or be [charmed](Mechanics/Rules/conditions.md#Charmed)\
    \ by the vampire. The [charmed](Mechanics/Rules/conditions.md#Charmed) target\
    \ regards the vampire as a trusted friend to be heeded and protected. Although\
    \ the target isn't under the vampire's control, it takes the vampire's requests\
    \ or actions in the most favorable way it can, and it is a willing target for\
    \ the vampire's bite attack.\n\nEach time the vampire or the vampire's companions\
    \ do anything harmful to the target, it can repeat the saving throw, ending the\
    \ effect on itself on a success. Otherwise, the effect lasts 24 hours or until\
    \ the vampire is destroyed, is on a different plane of existence than the target,\
    \ or takes a bonus action to end the effect."
  "name": "Charm"
"source":
- "PSI"
```
^statblock