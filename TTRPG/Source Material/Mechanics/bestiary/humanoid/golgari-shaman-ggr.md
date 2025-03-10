---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/ggr
- monster/cr/5
- monster/size/medium
- monster/type/humanoid/elf
statblock: inline
aliases: ["Golgari Shaman"]
---
# [Golgari Shaman](Mechanics\bestiary\humanoid/golgari-shaman-ggr.md)
*Source: Guildmasters' Guide to Ravnica p. 236*  

Golgari shamans are the spiritual leaders of the Golgari Swarm. They teach the guild's beliefs about the cycles of nature, using their necromantic magic to show how life sprouts from death.

Golgari shamans paint their faces so they appear to have extra eyes on their cheeks and chins. They sometimes use magical moodmark paint (described in chapter 5) to allow them to communicate by means of these marks. They wear clothing adorned with beetle carapaces, spiderwebs, or shelf fungus.

## Golgari Lairs

Members of the Golgari Swarm have an intimate connection to their territory. When at least six Golgari defend their territory together, they can call on the environment to aid them. The group must include Jarad Vod Savo or at least one Golgari shaman, kraul death priest, undercity medusa, or Devkarin lich. When determining the difficulty of such an encounter, consider the lair to be one additional creature of challenge rating 1.

```statblock
"name": "Golgari Shaman (GGR)"
"size": "Medium"
"type": "humanoid"
"subtype": "elf"
"alignment": "Neutral Evil"
"ac": !!int "14"
"ac_class": "[hide armor](Mechanics/items/hide-armor.md)"
"hp": !!int "88"
"hit_dice": "16d8 + 16"
"stats":
- !!int "11"
- !!int "15"
- !!int "12"
- !!int "12"
- !!int "17"
- !!int "16"
"speed": "30 ft."
"saves":
  "Wisdom": !!int "6"
  "Constitution": !!int "4"
"skillsaves":
  "Nature": !!int "4"
  "Religion": !!int "4"
  "Insight": !!int "6"
  "Arcana": !!int "4"
"senses": "darkvision 60 ft., passive Perception 13"
"languages": "Common, Elvish"
"cr": "5"
"traits":
- "desc": "The shaman is an 8th-level Golgari spellcaster. Its spellcasting ability\
    \ is Wisdom (spell save DC 14, +6 to hit with spell attacks). The shaman has\
    \ the following druid spells prepared:\n\nCantrips (at will): [poison spray](Mechanics/spells/poison-spray.md),\
    \ [shillelagh](Mechanics/spells/shillelagh.md), [thorn whip](Mechanics/spells/thorn-whip.md)\n\
    \n1st level (4 slots): [cure wounds](Mechanics/spells/cure-wounds.md), [entangle](Mechanics/spells/entangle.md),\
    \ [ray of sickness](Mechanics/spells/ray-of-sickness.md)\n\n2nd level (3 slots):\
    \ [pass without trace](Mechanics/spells/pass-without-trace.md), [ray of enfeeblement](Mechanics/spells/ray-of-enfeeblement.md),\
    \ [spike growth](Mechanics/spells/spike-growth.md)\n\n3rd level (3 slots):\
    \ [animate dead](Mechanics/spells/animate-dead.md), [dispel magic](Mechanics/spells/dispel-magic.md),\
    \ [plant growth](Mechanics/spells/plant-growth.md)\n\n4th level (2 slots):\
    \ [blight](Mechanics/spells/blight.md), [giant insect](Mechanics/spells/giant-insect.md)"
  "name": "Spellcasting"
- "desc": "The shaman has advantage on saving throws against being [charmed](Mechanics/Rules/conditions.md#Charmed),\
    \ and magic can't put it to sleep."
  "name": "Fey Ancestry"
"actions":
- "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 5 (1d6\
    \ + 2) bludgeoning damage, or 6 (1d8 + 2) bludgeoning damage if used with two\
    \ hands."
  "name": "Quarterstaff"
- "desc": "Melee Spell Attack: +6 to hit, reach 5 ft., one target. Hit: 9 (2d8)\
    \ necrotic damage, and the target must make a DC 14 Constitution saving throw,\
    \ taking 18 (4d8) poison damage on a failed save, or half as much damage on\
    \ a successful one."
  "name": "Fungal Rot"
"reactions":
- "desc": "When a creature within 30 feet of the shaman drops to 0 hit points, the\
    \ shaman gains 5 (1d10) temporary hit points."
  "name": "Feed on Death"
"source":
- "GGR"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/GGR/Golgari%20Shaman.webp"
```
^statblock