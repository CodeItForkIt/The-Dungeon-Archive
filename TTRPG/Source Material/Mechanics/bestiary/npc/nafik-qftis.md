---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/qftis
- monster/cr/6
- monster/size/medium
- monster/type/undead
statblock: inline
aliases: ["Nafik"]
---
# [Nafik](Mechanics\bestiary\npc/nafik-qftis.md)
*Source: Quests from the Infinite Staircase p. 212*  

In life, Nafik was the high priest of Amun Sa, the last pharaoh of the land of Bakar. Nafik was a loyal subject and was respected in turn by Amun Sa and the lesser priests in the pharaoh's retinue. When Amun Sa died, Nafik and a cadre of priests locked themselves in Amun Sa's tomb according to tradition. There, they performed holy rites and accepted food and offerings from the outside.

As time went on, Nafik grew envious of Amun Sa. "Why should the pharaoh get to enjoy eternal bliss in the afterlife while his priests are condemned to live out the rest of their lives imprisoned in his pyramid?" he thought. In his anger, Nafik turned to unholy grimoires, seeking forbidden rituals he hoped could teach him the secrets of everlasting life.

When the lands of Bakar dried up, the faithful stopped bringing offerings to Amun Sa's tomb. The threat of starvation loomed over Nafik and his priests. In a desperate measure, Nafik wrought a haphazard ritual on himself and his fellow priests, transforming them and himself into Undead. Heartless and corrupted by evil, Nafik now rules over the upper halls of Amun Sa's pyramid and the priests he sentenced to an exanimate eternity.

```statblock
"name": "Nafik (QftIS)"
"size": "Medium"
"type": "undead"
"alignment": "Lawful Evil"
"ac": !!int "13"
"ac_class": "natural armor"
"hp": !!int "82"
"hit_dice": "11d8 + 33"
"stats":
- !!int "18"
- !!int "10"
- !!int "16"
- !!int "10"
- !!int "16"
- !!int "14"
"speed": "20 ft."
"saves":
  "Wisdom": !!int "6"
  "Intelligence": !!int "3"
"skillsaves":
  "Religion": !!int "3"
  "History": !!int "3"
"damage_vulnerabilities": "fire"
"damage_resistances": "bludgeoning, piercing, slashing from nonmagical attacks"
"damage_immunities": "necrotic, poison"
"condition_immunities": "[charmed](Mechanics/Rules/conditions.md#Charmed), [exhaustion](Mechanics/Rules/conditions.md#Exhaustion),\
  \ [frightened](Mechanics/Rules/conditions.md#Frightened), [paralyzed](Mechanics/Rules/conditions.md#Paralyzed),\
  \ [poisoned](Mechanics/Rules/conditions.md#Poisoned)"
"senses": "darkvision 60 ft., passive Perception 13"
"languages": "Common"
"cr": "6"
"traits":
- "desc": "Nafik casts one of the following spells, using Wisdom as the spellcasting\
    \ ability (spell save DC 14):\n\nAt will: [Thaumaturgy](Mechanics/spells/thaumaturgy.md)\n\
    \n1/day: [Insect Plague](Mechanics/spells/insect-plague.md)\n\n2/day each:\
    \ [Command](Mechanics/spells/command.md), [Silence](Mechanics/spells/silence.md)"
  "name": "Spellcasting"
- "desc": "If Nafik fails a saving throw, he can choose to succeed instead."
  "name": "Legendary Resistance (2/Day)"
- "desc": "Nafik has advantage on saving throws against spells and other magical effects."
  "name": "Magic Resistance"
- "desc": "When he is destroyed, Nafik gains a new body in 24 hours if his heart is\
    \ intact, regaining all his hit points. The new body appears in an unoccupied\
    \ space within 5 feet of Nafik's heart."
  "name": "Rejuvenation"
"actions":
- "desc": "Nafik can use his Dreadful Glare and makes one Rotting Fist or Unholy Beam\
    \ attack."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +7 to hit, reach 5 ft., one target. Hit: 11\
    \ (2d6 + 4) bludgeoning damage plus 21 (6d6) necrotic damage. If the target\
    \ is a creature, it must succeed on a DC 14 Constitution saving throw or be cursed\
    \ with mummy rot. The cursed target can't regain hit points, and its hit point\
    \ maximum decreases by 10 (3d6) for every 24 hours that elapse. If the curse\
    \ reduces the target's hit point maximum to 0, the target dies and its body turns\
    \ to dust. The curse lasts until removed by the [Remove Curse](Mechanics/spells/remove-curse.md)\
    \ spell or other magic."
  "name": "Rotting Fist"
- "desc": "Ranged Spell Attack: +6 to hit, range 120 ft., one target. Hit: 28\
    \ (8d6) necrotic damage, and the next attack roll made against this target before\
    \ the end of Nafik's next turn has advantage."
  "name": "Unholy Beam"
- "desc": "Nafik targets one creature he can see within 60 feet of himself. The target\
    \ must succeed on a DC 14 Wisdom saving throw or have the [frightened](Mechanics/Rules/conditions.md#Frightened)\
    \ condition until the end of Nafik's next turn. A target that succeeds on the\
    \ saving throw is immune to Nafik's Dreadful Glare for the next 24 hours."
  "name": "Dreadful Glare"
"source":
- "QftIS"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/QftIS/Nafik.webp"
```
^statblock