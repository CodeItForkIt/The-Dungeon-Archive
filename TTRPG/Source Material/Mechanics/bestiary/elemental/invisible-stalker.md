---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/mm
- monster/cr/6
- monster/environment/urban
- monster/size/medium
- monster/type/elemental
statblock: inline
aliases: ["Invisible Stalker"]
---
# [Invisible Stalker](Mechanics\bestiary\elemental/invisible-stalker.md)
*Source: Monster Manual p. 192, Curse of Strahd, Princes of the Apocalypse, Storm King's Thunder, Tomb of Annihilation, Waterdeep: Dungeon of the Mad Mage, Ghosts of Saltmarsh, Divine Contention, Dragon of Icespire Peak, Storm Lord's Wrath, Mythic Odysseys of Theros, Icewind Dale: Rime of the Frostmaiden, The Wild Beyond the Witchlight, Critical Role: Call of the Netherdeep, Keys from the Golden Vault, Phandelver and Below: The Shattered Obelisk, Dungeons of Drakkenheim, Vecna: Eve of Ruin, Quests from the Infinite Staircase. Available in the <span title='Systems Reference Document (5.1)'>SRD</span>*  

An invisible stalker is an air elemental that has been summoned from its native plane and transformed by powerful magic. Its sole purpose is to hunt down creatures and retrieve objects for its summoner. When it is defeated or the magic that binds it expires, an invisible stalker vanishes in a gust of wind.

## Directed Hunter

When an invisible stalker is created, it stays at its summoner's side until it is given a task to perform. If an assignment doesn't involve hunting down and slaying a specific creature or recovering an object, the magic that created the invisible stalker ends and the elemental is released. Otherwise, it completes the task, then returns to its summoner for more commands, forced to serve until the magic that binds it expires. If its summoner dies in the interim, the invisible stalker vanishes after completing its task.

An invisible stalker is an unwilling servant at best. It resents any undertaking assigned to it. A mission that requires significant time might drive the invisible stalker to pervert the intent of a command unless it is worded carefully.

## Unseen Threat

Invisible stalkers are composed of air and are naturally invisible. A creature might hear and feel an invisible stalker in passing, but the elemental remains invisible even when it attacks. A spell that allows someone to see the invisible reveals only the invisible stalker's vague outline.

## Elemental Nature

An invisible stalker requires no air, food, drink, or sleep.

```statblock
"name": "Invisible Stalker"
"size": "Medium"
"type": "elemental"
"alignment": "Neutral"
"ac": !!int "14"
"hp": !!int "104"
"hit_dice": "16d8 + 32"
"stats":
- !!int "16"
- !!int "19"
- !!int "14"
- !!int "10"
- !!int "15"
- !!int "11"
"speed": "50 ft., fly 50 ft. (hover)"
"skillsaves":
  "Stealth": !!int "10"
  "Perception": !!int "8"
"damage_resistances": "bludgeoning, piercing, slashing from nonmagical attacks"
"damage_immunities": "poison"
"condition_immunities": "[exhaustion](Mechanics/Rules/conditions.md#Exhaustion), [grappled](Mechanics/Rules/conditions.md#Grappled),\
  \ [paralyzed](Mechanics/Rules/conditions.md#Paralyzed), [petrified](Mechanics/Rules/conditions.md#Petrified),\
  \ [poisoned](Mechanics/Rules/conditions.md#Poisoned), [prone](Mechanics/Rules/conditions.md#Prone),\
  \ [restrained](Mechanics/Rules/conditions.md#Restrained), [unconscious](Mechanics/Rules/conditions.md#Unconscious)"
"senses": "darkvision 60 ft., passive Perception 18"
"languages": "Auran, understands Common but doesn't speak it"
"cr": "6"
"traits":
- "desc": "The stalker is [invisible](Mechanics/Rules/conditions.md#Invisible)."
  "name": "Invisibility"
- "desc": "The stalker is given a quarry by its summoner. The stalker knows the direction\
    \ and distance to its quarry as long as the two of them are on the same plane\
    \ of existence. The stalker also knows the location of its summoner."
  "name": "Faultless Tracker"
"actions":
- "desc": "The stalker makes two slam attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +6 to hit, reach 5 ft., one target. Hit: 10\
    \ (2d6 + 3) bludgeoning damage."
  "name": "Slam"
"source":
- "MM"
- "CoS"
- "PotA"
- "SKT"
- "ToA"
- "WDMM"
- "GoS"
- "DC"
- "DIP"
- "SLW"
- "MOT"
- "IDRotF"
- "WBtW"
- "CRCotN"
- "KftGV"
- "PaBTSO"
- "DoDk"
- "VEoR"
- "QftIS"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/MM/Invisible%20Stalker.webp"
```
^statblock

## Environment

urban