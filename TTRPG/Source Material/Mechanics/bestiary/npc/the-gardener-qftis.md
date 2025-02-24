---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/qftis
- monster/cr/12
- monster/size/medium
- monster/type/fey/archfey
- monster/type/fey/druid
statblock: inline
aliases: ["The Gardener"]
---
# [The Gardener](Mechanics\bestiary\npc/the-gardener-qftis.md)
*Source: Quests from the Infinite Staircase p. 200*  

The Gardener is an archfey who adores the splendor of nature, the joy of song, and the glow of shared merriment. This ancient being once wandered the Feywild and worlds of the Material Plane until two dear friends created a wondrous garden and asked the Gardener to tend to it. The Gardener agreed to the request, then pulled the garden from the Material Plane and transformed it into a Domain of Delight—a region of the Feywild that bows to an archfey's will. This place became known as the Eternal Garden.

The Gardener abhors bloodshed and avoids killing even those who threaten the garden, preferring to entangle them in vines and pacify them with tranquilizing breaths of flowery mist.

## The Gardener's Lair

The Gardener's lair is the entirety of the Eternal Garden.

```statblock
"name": "The Gardener (QftIS)"
"size": "Medium"
"type": "fey"
"subtype": "archfey, druid"
"alignment": "Neutral Good"
"ac": !!int "17"
"ac_class": "natural armor"
"hp": !!int "209"
"hit_dice": "22d8 + 110"
"stats":
- !!int "21"
- !!int "16"
- !!int "20"
- !!int "17"
- !!int "20"
- !!int "18"
"speed": "30 ft."
"saves":
  "Charisma": !!int "8"
  "Dexterity": !!int "7"
  "Wisdom": !!int "9"
  "Constitution": !!int "9"
"skillsaves":
  "Nature": !!int "11"
  "Insight": !!int "9"
  "Perception": !!int "9"
  "Survival": !!int "13"
"damage_resistances": "cold, fire"
"damage_immunities": "poison"
"condition_immunities": "[charmed](Mechanics/Rules/conditions.md#Charmed), [frightened](Mechanics/Rules/conditions.md#Frightened),\
  \ [poisoned](Mechanics/Rules/conditions.md#Poisoned)"
"senses": "truesight 120 ft., passive Perception 19"
"languages": "Common, Druidic, Elvish, Sylvan"
"cr": "12"
"traits":
- "desc": "The Gardener casts one of the following spells, requiring no material components\
    \ and using Wisdom as the spellcasting ability (spell save DC 17):\n\nAt will:\
    \ [Druidcraft](Mechanics/spells/druidcraft.md), [Speak with Animals](Mechanics/spells/speak-with-animals.md),\
    \ [Speak with Plants](Mechanics/spells/speak-with-plants.md)\n\n1/day each:\
    \ [Heroes' Feast](Mechanics/spells/heroes-feast.md) (as an action), [Teleport](Mechanics/spells/teleport.md)\n\
    \n2/day each: [Awaken](Mechanics/spells/awaken.md) (as an action), [Goodberry](Mechanics/spells/goodberry.md),\
    \ [Plant Growth](Mechanics/spells/plant-growth.md) (as an action only)"
  "name": "Spellcasting"
- "desc": "If the Gardener dies in the Eternal Garden, they revive with all their\
    \ hit points 1d4 days later in a safe location within the garden."
  "name": "Fey Rebirth"
- "desc": "If the Gardener fails a saving throw, they can choose to succeed instead."
  "name": "Legendary Resistance (3/Day)"
- "desc": "The Gardener is unaffected by difficult terrain."
  "name": "Unfettered Steps"
"actions":
- "desc": "The Gardener makes two Vine attacks and can use Breath of Tranquility if\
    \ available."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +9 to hit, reach 10 ft., one target. Hit: 11\
    \ (1d12 + 5) bludgeoning damage plus 9 (2d8) psychic damage, and if the target\
    \ is a Large or smaller creature, the vine wraps around the target, and the target\
    \ has the [grappled](Mechanics/Rules/conditions.md#Grappled) condition (escape\
    \ DC 17). The vine vanishes when the target is no longer [grappled](Mechanics/Rules/conditions.md#Grappled),\
    \ or when the Gardener wills it to (no action required). A creature reduced to\
    \ 0 hit points by the vine has the [unconscious](Mechanics/Rules/conditions.md#Unconscious)\
    \ condition but is stable instead of dying."
  "name": "Vine"
- "desc": "The Gardener exhales soporific vapor in a 30-foot cone. Each creature in\
    \ that area must succeed on a DC 17 Constitution saving throw or have the [poisoned](Mechanics/Rules/conditions.md#Poisoned)\
    \ condition. A [poisoned](Mechanics/Rules/conditions.md#Poisoned) creature must\
    \ repeat the saving throw at the end of its next turn. On a failed save, it has\
    \ the [unconscious](Mechanics/Rules/conditions.md#Unconscious) condition, and\
    \ on a successful save, the effect ends on it. An [unconscious](Mechanics/Rules/conditions.md#Unconscious)\
    \ creature is no longer [poisoned](Mechanics/Rules/conditions.md#Poisoned) and\
    \ remains [unconscious](Mechanics/Rules/conditions.md#Unconscious) for 1 hour,\
    \ until it takes damage, or until a creature uses an action to shake it awake."
  "name": "Breath of Tranquility (Recharge 5-6)"
"reactions":
- "desc": "The Gardener can take up to three reactions per round but only one per\
    \ turn."
  "name": ""
- "desc": "When a creature within 120 feet of the Gardener damages the Gardener, that\
    \ creature takes 10 (3d6) psychic damage, and the Gardener teleports, along\
    \ with anything they are wearing or carrying, to an unoccupied space they can\
    \ see within 15 feet. A creature reduced to 0 hit points by the psychic damage\
    \ has the [unconscious](Mechanics/Rules/conditions.md#Unconscious) condition and\
    \ is stable instead of dying."
  "name": "Pacification"
- "desc": "When the Gardener or a creature within 30 feet of the Gardener takes damage\
    \ from a spell, the Gardener chooses up to 5 creatures within 30 feet of themself.\
    \ The Gardener and the chosen creatures have resistance to all damage from the\
    \ triggering spell."
  "name": "Spell Refuge"
"lair_actions":
- "desc": "On initiative count 20 (losing initiative ties), the Gardener can take\
    \ one of the following lair actions; they can't take the same lair action two\
    \ rounds in a row:"
  "name": ""
- "desc": "- Plant Walk. The Gardener moves up to their speed into the space of\
    \ a Medium or larger plant within the lair, then teleports to an unoccupied space\
    \ within 5 feet of any other Medium or larger plant within the lair.  \n- Vine\
    \ Wall. A wall of grasping vines appears on the ground within 120 feet of the\
    \ Gardener. The wall is up to 60 feet long, 10 feet high, and 5 feet thick, and\
    \ it blocks line of sight. When the wall appears, each creature in its area must\
    \ succeed on a DC 15 Dexterity saving throw or have the grappled condition (escape\
    \ DC 15). A creature must make this saving throw when it starts its turn inside\
    \ the wall or when it enters the wall for the first time on a turn. The wall's\
    \ area is difficult terrain for a creature that isn't grappled. The wall sinks\
    \ back into the ground, freeing all creatures grappled by it, when the Gardener\
    \ uses this lair action again or when the Gardener dies.  "
  "name": ""
"regional_effects":
- "desc": "The Eternal Garden has the following features:"
  "name": ""
- "desc": "- Boundary. At the border of the domain is a lightly obscuring mist,\
    \ tinged with a sweet blossom scent and the colors of sunset. No matter how far\
    \ a creature travels into the mist, the creature finds itself back where it entered\
    \ the border, returning to the garden.  \n- Eternal Summer. The climate in\
    \ the garden is a perpetual, lovely summer, but weather conditions reflect the\
    \ emotional tone of creatures in the garden. In times of danger, thunderstorms\
    \ shake the sky. During times of melancholy or mourning, chill rain patters throughout\
    \ the domain.  \n- Gardener's Vigil. The Gardener senses when anything dies\
    \ in the garden. If a creature dies in the garden, roll a d6. On a 1, the Gardener\
    \ appears on initiative count 20 of the next round (losing initiative ties) to\
    \ investigate.  \n- Lighting. The sky above the garden is a perpetual twilight\
    \ range of orange, red, pink, and yellow hues with no visible sun, moon, or stars.\
    \ During daylight hours, it emits bright light, but at night, it never reaches\
    \ full darkness, becoming dim light instead.  \n- Memory Loss. Unless otherwise\
    \ stated, a creature that leaves the domain must make a DC 10 Wisdom saving throw;\
    \ Fey creatures and creatures with the Fey Ancestry trait automatically succeed\
    \ on the saving throw. On a failed save, the creature remembers nothing of its\
    \ time in the garden or the Palace of Spires. On a successful save, the creature's\
    \ memories remain intact, but they're hazy and dreamlike. A Remove Curse or Greater\
    \ Restoration spell restores the creature's memories.  \n- Time. Time passes\
    \ slower in the Eternal Garden relative to other planes. For each day spent in\
    \ the garden, one year passes on the Material Plane.  "
  "name": ""
"source":
- "QftIS"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/QftIS/The%20Gardener.webp"
```
^statblock